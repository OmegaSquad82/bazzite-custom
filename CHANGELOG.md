# Changelog

## [1.7.2](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.7.1...v1.7.2) (2026-02-27)


### Bug Fixes

* Add global recompression parameter for huge pages ([e6f4ddc](https://github.com/OmegaSquad82/bazzite-custom/commit/e6f4ddc5c9c750d1a69d7c62a51f9fccbfd67376))

## [1.7.1](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.7.0...v1.7.1) (2025-12-22)


### Bug Fixes

* issue installing Flatpaks when rebasing to custom Bazzite ([056224d](https://github.com/OmegaSquad82/bazzite-custom/commit/056224d667eaaf23ce0f951d3fc8dc1d215b6bb1))
* issue installing Flatpaks when rebasing to custom Bazzite ([9a25368](https://github.com/OmegaSquad82/bazzite-custom/commit/9a2536869b504416e330ffcfcf6f5db1f2ca2f8f))

## [1.7.0](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.6.2...v1.7.0) (2025-11-30)


### Features

* use rpm-ostree compose build_chunked_oci ([f96d8ed](https://github.com/OmegaSquad82/bazzite-custom/commit/f96d8eda575f18e9979976e7af0abb621fc27b76))
* use rpm-ostree compose build_chunked_oci ([a1b5f88](https://github.com/OmegaSquad82/bazzite-custom/commit/a1b5f882fa8660675e4a4323c2b3d157ece65a9d))


### Bug Fixes

* return to hdd-dev/rechunk algorithm ([ce8498a](https://github.com/OmegaSquad82/bazzite-custom/commit/ce8498a4ca57130faca9b426e0f337f7069e4659))

## [1.6.2](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.6.1...v1.6.2) (2025-11-05)


### Bug Fixes

* let only a single zstd level remain for recompression ([68ddf9f](https://github.com/OmegaSquad82/bazzite-custom/commit/68ddf9f658a1616fd3360b517fc413828d9a7476))
* let only a single zstd level remain for recompression ([2215c26](https://github.com/OmegaSquad82/bazzite-custom/commit/2215c2634c51e91ca5901ff0f641b9d59d8fccb3))

## [1.6.1](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.6.0...v1.6.1) (2025-11-05)


### Bug Fixes

* drop incremental zstd levels for zram in favor of lz4hc and all default levels ([58ab6c2](https://github.com/OmegaSquad82/bazzite-custom/commit/58ab6c205231bc10451718a6edb8f6c69e36e4d0))
* duplicate runtimes for user and system flatpaks ([ede874d](https://github.com/OmegaSquad82/bazzite-custom/commit/ede874d4b4376df41beb9c335becbd23c5d834a7))
* duplicate runtimes for user and system flatpaks ([320c0cf](https://github.com/OmegaSquad82/bazzite-custom/commit/320c0cfc82a9eaa90a135e22a7395bfbda343399))

## [1.6.0](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.5.3...v1.6.0) (2025-11-04)


### Features

* Migrate to Bazzite 43 ([6111c79](https://github.com/OmegaSquad82/bazzite-custom/commit/6111c793da638024961c4525acff8835bb69a1f5))


### Bug Fixes

* it builds without Libation ([e1f7649](https://github.com/OmegaSquad82/bazzite-custom/commit/e1f7649fa6c4e7d9f8eda8d7a4e6fcc591138738))
* Libation setup ([dd98606](https://github.com/OmegaSquad82/bazzite-custom/commit/dd98606536ae5349087f1e64f8ed45b3d4e23eb8))

## [1.5.3](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.5.2...v1.5.3) (2025-11-01)


### Bug Fixes

* fix Renovate config for Libation, it now successfully upgrades it by itself...

## [1.5.2](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.5.1...v1.5.2) (2025-10-31)


### Bug Fixes

* adding virtualization kargs so you don't have to ([8165c8b](https://github.com/OmegaSquad82/bazzite-custom/commit/8165c8beb9337b51f0ef90d39df65b61ddebfd37))
* allow applications to ask for ssh passphrases ([581d17c](https://github.com/OmegaSquad82/bazzite-custom/commit/581d17cab08fc555f196a746548b2febc4e21e80))
* drop VS Codium flatpak in favor of homebrew cask ([28466b3](https://github.com/OmegaSquad82/bazzite-custom/commit/28466b3e6944f67e4b6a6b8e445d798b4cc57104))

## [1.5.1](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.5.0...v1.5.1) (2025-10-29)


### Bug Fixes

* hint why login to WIFIonICE failed ([7a4694e](https://github.com/OmegaSquad82/bazzite-custom/commit/7a4694e83f5899b40d775033f3ffd45fa477845c))

## [1.5.0](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.4.0...v1.5.0) (2025-10-24)


### Features

* add Bottles Flatpak from Flatpak Verified to System installation ([01c6138](https://github.com/OmegaSquad82/bazzite-custom/commit/01c613853ad730a83e4ab097d609ecbcdb06e844))
* add nts config for chrony ([975d0b8](https://github.com/OmegaSquad82/bazzite-custom/commit/975d0b8a7102d23ec63c2545a14804deec22eda2))
* update sshd hardening ([d2e99e5](https://github.com/OmegaSquad82/bazzite-custom/commit/d2e99e524929720de45b8a688a661cb0ebb4c699))


### Bug Fixes

* add more recompression levels ([be9c7fb](https://github.com/OmegaSquad82/bazzite-custom/commit/be9c7fb0df58576cabe88fe6dc1ed815e6710f7a))
* Arch wiki says no. ([a67ed88](https://github.com/OmegaSquad82/bazzite-custom/commit/a67ed886c337bd523b8e980773ee6aab97af4600))

## [1.4.0](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.3.6...v1.4.0) (2025-10-16)


### Features

* add Nextcloud and Thunderbird ([ab9eb4f](https://github.com/OmegaSquad82/bazzite-custom/commit/ab9eb4ff82e6b268be6aa55a3476df8241ca29c4))


### Bug Fixes

* update vm settings to value between arch wiki and maxperfwiz ([106adf1](https://github.com/OmegaSquad82/bazzite-custom/commit/106adf1eab2977a8535de3b4a009eb5c116677b5))

## [1.3.6](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.3.5...v1.3.6) (2025-10-16)


### Bug Fixes

* Fedora 42 ([a97372e](https://github.com/OmegaSquad82/bazzite-custom/commit/a97372e959330930c2016533d24338fd5d881ca3))

## [1.3.5](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.3.4...v1.3.5) (2025-10-14)


### Bug Fixes

* add ddrescue to the flock ([ccca7d2](https://github.com/OmegaSquad82/bazzite-custom/commit/ccca7d29084da4089ee64d1b0c3921318e1c08b7))
* add lziprecover to the flock ([5620d4b](https://github.com/OmegaSquad82/bazzite-custom/commit/5620d4bae2af3ba4d4f5ca5f20b8f08e87813305))

## [1.3.4](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.3.3...v1.3.4) (2025-10-13)


### Bug Fixes

* no build on pr when only docs or pre commit config changed ([bb7a06e](https://github.com/OmegaSquad82/bazzite-custom/commit/bb7a06e6ecf37f8eaf241dd3f40057cd1702b850))
* OpenRGB should be able to read its rules ([0571e10](https://github.com/OmegaSquad82/bazzite-custom/commit/0571e10c9c679de05b62fd5861f759b2d6b06696))
* ship with OpenRGB ([6da3e68](https://github.com/OmegaSquad82/bazzite-custom/commit/6da3e680ab9467d426fe35ac94e7348dd63edd74))

## [1.3.3](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.3.2...v1.3.3) (2025-10-13)


### Bug Fixes

* do not rebuild the image on pre commit config changes ([ed7c7cf](https://github.com/OmegaSquad82/bazzite-custom/commit/ed7c7cf50688758f6ffe79fbecd5e68c39dced1e))

## [1.3.2](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.3.1...v1.3.2) (2025-10-13)


### Bug Fixes

* add some apps ([01152b0](https://github.com/OmegaSquad82/bazzite-custom/commit/01152b0dcc498dd8a3fc2b8433b85519ec621009))
* add some apps ([8134819](https://github.com/OmegaSquad82/bazzite-custom/commit/813481978223015efe76f0cc233a527c0adb81cc))

## [1.3.1](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.3.0...v1.3.1) (2025-10-12)


### Bug Fixes

* really remove rocm but keep git ([cf30644](https://github.com/OmegaSquad82/bazzite-custom/commit/cf3064452efb4ccc2e0f78ee585c8717c8db6ac8))
* remove unused rocm packages ([5f8f3e3](https://github.com/OmegaSquad82/bazzite-custom/commit/5f8f3e3c4d268036b5eb0ac0410bba9d602ad06a))

## [1.3.0](https://github.com/OmegaSquad82/bazzite-custom/compare/v1.2.0...v1.3.0) (2025-10-11)


### Features

* add more flatpaks ([e7ba319](https://github.com/OmegaSquad82/bazzite-custom/commit/e7ba319807d8bca8012202afa001063da04a6bdb))
* add more flatpaks ([0f3c17c](https://github.com/OmegaSquad82/bazzite-custom/commit/0f3c17cbd4300d97a2aaa78a9d13aeba97279ccd))
* clean up dependencies to reduce image size ([477abbe](https://github.com/OmegaSquad82/bazzite-custom/commit/477abbe1ff5f58e571991711ee73e483452e00f8))
* more and more flatpaks ([8da42f7](https://github.com/OmegaSquad82/bazzite-custom/commit/8da42f76ae31f3aa0dcc1892fd3bdb921797a191))
* re-chuck when on main branch ([2bebb14](https://github.com/OmegaSquad82/bazzite-custom/commit/2bebb14f818ec94638cd7deddcbd96591c43a333))
* switch to forked easimon/maximize-build-space ([a33f92a](https://github.com/OmegaSquad82/bazzite-custom/commit/a33f92a67eea71df3974149476e9d91d68c1b89f))
* switch to forked easimon/maximize-build-space ([f69be9f](https://github.com/OmegaSquad82/bazzite-custom/commit/f69be9fabfe66f8e9f57331b8f8ab235c9424507))


### Bug Fixes

* ProtonPlus is where second DistroShelf was ([9f5f937](https://github.com/OmegaSquad82/bazzite-custom/commit/9f5f937d8bae26cecb245eb1e360ea8f0d36110f))

## [1.2.0](https://github.com/OmegaSquad82/custom-ublue-os/compare/v1.1.1...v1.2.0) (2025-10-08)


### Features

* use easier ruleset for Libation ([3bd6009](https://github.com/OmegaSquad82/custom-ublue-os/commit/3bd600913f674af7e16f5c4682c8c62dbb104067))

## [1.1.1](https://github.com/OmegaSquad82/custom-ublue-os/compare/v1.1.0...v1.1.1) (2025-10-08)


### Bug Fixes

* get rid of GNOME dependencies ([5846c59](https://github.com/OmegaSquad82/custom-ublue-os/commit/5846c59315b671d8e8073ac8f05cb0995be1d9a6))

## [1.1.0](https://github.com/OmegaSquad82/custom-ublue-os/compare/v1.0.1...v1.1.0) (2025-10-07)


### Features

* adding default-flatpaks ([00d0c86](https://github.com/OmegaSquad82/custom-ublue-os/commit/00d0c8652cf5f7e16bea9d25802c8c340c6f9dc7))
* adding default-flatpaks ([1167ce2](https://github.com/OmegaSquad82/custom-ublue-os/commit/1167ce232c80075da247ea48552a46cd76661a94))
* created pre-commit config ([9480415](https://github.com/OmegaSquad82/custom-ublue-os/commit/9480415862ed73be27144e1119fb969ffbc56334))
* created pre-commit config ([1522769](https://github.com/OmegaSquad82/custom-ublue-os/commit/15227692ce2172ba6fdb0df0996d3d85e82a3878))


### Bug Fixes

* let only minor+patch be updated for Libation ([578c949](https://github.com/OmegaSquad82/custom-ublue-os/commit/578c9499b3b3ae31d9115c769dc117c3d04ca760))
* make matchStrings for Libation more specific ([bc69da4](https://github.com/OmegaSquad82/custom-ublue-os/commit/bc69da44d577d94021a75ac00f4579be8725b5a8))
* try adding replace tamplate ([ff948f1](https://github.com/OmegaSquad82/custom-ublue-os/commit/ff948f1f81bb17bf020aa2a85e9cf0a177d18901))
* try adding replace tamplate ([20001e9](https://github.com/OmegaSquad82/custom-ublue-os/commit/20001e95d802b39deb902002d485c6abbeeaf16b))
* updated renovate.json ([1522769](https://github.com/OmegaSquad82/custom-ublue-os/commit/15227692ce2172ba6fdb0df0996d3d85e82a3878))

## [1.0.1](https://github.com/OmegaSquad82/custom-ublue-os/compare/v1.0.0...v1.0.1) (2025-10-05)


### Bug Fixes

* renovate config (1/n) ([07ac55d](https://github.com/OmegaSquad82/custom-ublue-os/commit/07ac55dd6e25a97263df75aae91b74673d4c4133))
* renovate config (1/n) ([e9c6fda](https://github.com/OmegaSquad82/custom-ublue-os/commit/e9c6fdacf0051db02ebbe48d11546084c2a13c6b))

## 1.0.0 (2025-10-05)


### Features

* add rmcrackan/Libation to the flock ([d688f45](https://github.com/OmegaSquad82/custom-ublue-os/commit/d688f454e4c0ca8ec71edf918461e61d70200acd))
* customized bazzite ([cdebdb4](https://github.com/OmegaSquad82/custom-ublue-os/commit/cdebdb44b80621450a318998836b2f469a55b41c))
* customized bazzite ([852c6c0](https://github.com/OmegaSquad82/custom-ublue-os/commit/852c6c0dd03bbeb44795e7dd2711c4d2d1bb4779))
* Update CODEOWNERS ([d7838f8](https://github.com/OmegaSquad82/custom-ublue-os/commit/d7838f8887d15ab3497a1fdad9ecd91bd35049bb))


### Bug Fixes

* Token and Bazzite naming ([e10ef52](https://github.com/OmegaSquad82/custom-ublue-os/commit/e10ef52518c26dbb56dd3b7086661f555a90f39c))
* Token and Bazzite naming ([087df1b](https://github.com/OmegaSquad82/custom-ublue-os/commit/087df1b09ce105edfc49e06f072319ebe0d7d47e))
* use patched v1.9.1 ([b50e133](https://github.com/OmegaSquad82/custom-ublue-os/commit/b50e13386f182a359e095ea011f9e2c8a3898f13))
