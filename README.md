# bazzite-custom &nbsp; [![bluebuild build badge](https://github.com/omegasquad82/bazzite-custom/actions/workflows/build.yml/badge.svg)](https://github.com/omegasquad82/bazzite-custom/actions/workflows/build.yml)

See the [BlueBuild docs](https://blue-build.org/how-to/setup/) for quick setup instructions for setting up your own repository based on this template.

This custom image derives from [Bazzite](https://bazzite.gg/ "Bazzite - The next generation of Linux gaming") and is intended for everyday usage.

## Customizations

- Hardening for the OpenSSH daemon to only allow public key authentication and users in group `wheel`.
- Tweaks to the virtual memory management subsystem to allow more aggressive swapping out of pages.
- A zram swap configuration with up to 16 GiB size using `LZ4` and recompression with `Zstd`.
- A Network Time Security configuration for chrony to use a selection of European servers.
- A selection of few packages is installed during image build for convenience.
- Most Flatpaks I'm using are marked for installation during runtime.
- An [adapted](https://gist.github.com/OmegaSquad82/8dbea960956b03bb86f2f773527daf31) login script for German Rail Intercity (Express) trains.

## Installation

> [!WARNING] [This is an experimental feature](https://www.fedoraproject.org/wiki/Changes/OstreeNativeContainerStable), try at your own discretion.

To rebase an existing atomic Fedora installation to the latest build:

- First rebase to the unsigned image, to get the proper signing keys and policies installed:
  ```
  sudo bootc switch ghcr.io/omegasquad82/bazzite-stable-customized
  ```
- Reboot to complete the rebase:
  ```
  systemctl reboot
  ```
- Then rebase to the signed image, like so:
  ```
  sudo bootc switch --enforce-container-sigpolicy ghcr.io/omegasquad82/bazzite-stable-customized
  ```
- Reboot again to complete the installation
  ```
  systemctl reboot
  ```
- Henceforth use [bootc](https://github.com/bootc-dev/bootc) to update it
  ```
  sudo bootc update
  ```

The `latest` tag will automatically point to the latest build. That build will still always use the Fedora version specified in `recipe.yml`, so you won't get accidentally updated to the next major version.

## ISO

If build on Fedora Atomic, you can generate an offline ISO with the instructions available [here](https://blue-build.org/learn/universal-blue/#fresh-install-from-an-iso). These ISOs cannot unfortunately be distributed on GitHub for free due to large sizes, so for public projects something else has to be used for hosting.

## Verification

These images are signed with [Sigstore](https://www.sigstore.dev/)'s [cosign](https://github.com/sigstore/cosign). You can verify the signature by downloading the `cosign.pub` file from this repo and running the following command and if you want it to be pretty printed, use [jq](https://github.com/jqlang/jq):

```bash
cosign verify --key cosign.pub ghcr.io/omegasquad82/bazzite-stable-customized | jq .
```
