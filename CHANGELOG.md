# Changelog

All notable changes to this project will be documented in this file.

## [0.7.0](https://github.com/Racer159/uds-core/compare/v0.6.2...v0.7.0) (2024-02-13)


### Features

* Add istio and preliminary ci ([#3](https://github.com/Racer159/uds-core/issues/3)) ([fbd7453](https://github.com/Racer159/uds-core/commit/fbd745392340dbc978b27f0d321f3375882c1c40))
* add metrics-server ([#35](https://github.com/Racer159/uds-core/issues/35)) ([8216ab9](https://github.com/Racer159/uds-core/commit/8216ab982be79dc393a2e0db359370b32e660150))
* add monitoring and logging ([#33](https://github.com/Racer159/uds-core/issues/33)) ([c6d9aec](https://github.com/Racer159/uds-core/commit/c6d9aece4984421e1ccbf476cd0d40fb701e4e50))
* add pepr capability for istio + jobs ([#12](https://github.com/Racer159/uds-core/issues/12)) ([c32a703](https://github.com/Racer159/uds-core/commit/c32a70390f443c90796978ad4c42bbb4b17eb226))
* add prometheus-stack (monitoring) capability ([#2](https://github.com/Racer159/uds-core/issues/2)) ([e438ab6](https://github.com/Racer159/uds-core/commit/e438ab6089bc9d8c6640fa002285d38ddc3022df))
* embed tls certs in istio package ([#32](https://github.com/Racer159/uds-core/issues/32)) ([fb04fee](https://github.com/Racer159/uds-core/commit/fb04feec9657f449366389a0e0a474a8cdeecb2c))
* expose tls certs as UDS bundle variables ([#48](https://github.com/Racer159/uds-core/issues/48)) ([c1f8286](https://github.com/Racer159/uds-core/commit/c1f828650ef2c53a3fd9ed477950046020c5d375))
* introduce Pepr common policies ([#50](https://github.com/Racer159/uds-core/issues/50)) ([54182b4](https://github.com/Racer159/uds-core/commit/54182b4db691d86ce80379be272d924d105b0d07))
* release-please integration ([#25](https://github.com/Racer159/uds-core/issues/25)) ([bf3c53b](https://github.com/Racer159/uds-core/commit/bf3c53b2ddac4e02e31aa3429029dd9f1c9595e3))


### Bug Fixes

* complete incomplete deploy task ([#21](https://github.com/Racer159/uds-core/issues/21)) ([45ff5e5](https://github.com/Racer159/uds-core/commit/45ff5e5d7b6a50cdfcfabb174349ab539a8accd9))
* metrics-server mTLS fix ([#44](https://github.com/Racer159/uds-core/issues/44)) ([4853522](https://github.com/Racer159/uds-core/commit/4853522c9504c87dcbd8319d689ecb0a1cb42c0b))
* resolve istio job termination container status logic issue ([#55](https://github.com/Racer159/uds-core/issues/55)) ([c0142c2](https://github.com/Racer159/uds-core/commit/c0142c213446a37185cdf9dec5ae60aaae8ba194))


### Miscellaneous

* add commit lint workflow ([#19](https://github.com/Racer159/uds-core/issues/19)) ([776a632](https://github.com/Racer159/uds-core/commit/776a6325821329b2cbd97da2f40a30447cd48efc))
* add minio deploy time bundle variable override definitions ([#58](https://github.com/Racer159/uds-core/issues/58)) ([ca28e7b](https://github.com/Racer159/uds-core/commit/ca28e7b4c4a42769934cc8ad69361ff29a348cc5))
* bump zarf & uds-k3d deps ([#30](https://github.com/Racer159/uds-core/issues/30)) ([dd28ab3](https://github.com/Racer159/uds-core/commit/dd28ab3acd163aaccdfb76fbf9726c02a2ff0050))
* conform to latest uds bundle schema ([#52](https://github.com/Racer159/uds-core/issues/52)) ([14dad38](https://github.com/Racer159/uds-core/commit/14dad3819187d4f8e13f7bbc191dca74a29b9c98))
* dep updates for UDS CLI & Pepr ([#46](https://github.com/Racer159/uds-core/issues/46)) ([1037634](https://github.com/Racer159/uds-core/commit/10376349e350bd32f3bf32577d8f8089c09ac6cc))
* fix missing deps in tag and release workflow ([#28](https://github.com/Racer159/uds-core/issues/28)) ([1e1af76](https://github.com/Racer159/uds-core/commit/1e1af762e8eb1dd331cbd681e48ecc95ec3184d2))
* initial renovate config ([#67](https://github.com/Racer159/uds-core/issues/67)) ([2cd19d8](https://github.com/Racer159/uds-core/commit/2cd19d871a95491950d43fea8e8fd2e8c290cd55))
* **main:** release 0.1.1 ([#27](https://github.com/Racer159/uds-core/issues/27)) ([3776e91](https://github.com/Racer159/uds-core/commit/3776e91670aa73907cb9c48a05419d106ecedd67))
* **main:** release 0.1.2 ([#29](https://github.com/Racer159/uds-core/issues/29)) ([af7b0be](https://github.com/Racer159/uds-core/commit/af7b0beaf409627c87b47e4d908b0a8a0d8cff63))
* **main:** release 0.1.3 ([#31](https://github.com/Racer159/uds-core/issues/31)) ([28ad8a7](https://github.com/Racer159/uds-core/commit/28ad8a78b023f160714ecb90d748ee65403cf500))
* **main:** release 0.2.0 ([#34](https://github.com/Racer159/uds-core/issues/34)) ([5185a8f](https://github.com/Racer159/uds-core/commit/5185a8f98c90578eabd9f1494f55e43922bb7a92))
* **main:** release 0.3.0 ([#39](https://github.com/Racer159/uds-core/issues/39)) ([4d2b05d](https://github.com/Racer159/uds-core/commit/4d2b05de9d155dc91b799bde5156c5980bc348cb))
* **main:** release 0.4.0 ([#43](https://github.com/Racer159/uds-core/issues/43)) ([d2b61c3](https://github.com/Racer159/uds-core/commit/d2b61c373b91d4f405e27ce930e4f8bec52ddd21))
* **main:** release 0.4.1 ([#45](https://github.com/Racer159/uds-core/issues/45)) ([d66eafe](https://github.com/Racer159/uds-core/commit/d66eafea0ec9ccd412f5af3ed5ab12f3f8275a33))
* **main:** release 0.5.0 ([#49](https://github.com/Racer159/uds-core/issues/49)) ([f9c4269](https://github.com/Racer159/uds-core/commit/f9c426998f2bc4fc21c32b3492f25b8608f50282))
* **main:** release 0.6.0 ([#53](https://github.com/Racer159/uds-core/issues/53)) ([9b3ad64](https://github.com/Racer159/uds-core/commit/9b3ad64a6e3870ce364cad77abd367cc8d493042))
* **main:** release 0.6.1 ([#56](https://github.com/Racer159/uds-core/issues/56)) ([4a5a42c](https://github.com/Racer159/uds-core/commit/4a5a42c8fa9ee17656e462cb9df08562d9c85b96))
* **main:** release 0.6.2 ([#59](https://github.com/Racer159/uds-core/issues/59)) ([b1c49ac](https://github.com/Racer159/uds-core/commit/b1c49ac70e8a293936dea8a516c32b7bb7e6fc4c))
* refactor validate.yaml file name and task name ([#62](https://github.com/Racer159/uds-core/issues/62)) ([92a04ea](https://github.com/Racer159/uds-core/commit/92a04ea1096448995ccc0dd9d77a32a5061e06f0))
* remove version from neuvector zarf.yaml ([#11](https://github.com/Racer159/uds-core/issues/11)) ([fbc8d51](https://github.com/Racer159/uds-core/commit/fbc8d51e2b4146d394184d7596cd9a54219dc001))
* update release please extra-files to be explicit ([#26](https://github.com/Racer159/uds-core/issues/26)) ([23f4999](https://github.com/Racer159/uds-core/commit/23f49995771fb05cd18e7a077bf90e86ca5b7471))

## [0.6.2](https://github.com/defenseunicorns/uds-core/compare/v0.6.1...v0.6.2) (2023-12-11)


### Miscellaneous

* add minio deploy time bundle variable override definitions ([#58](https://github.com/defenseunicorns/uds-core/issues/58)) ([ca28e7b](https://github.com/defenseunicorns/uds-core/commit/ca28e7b4c4a42769934cc8ad69361ff29a348cc5))
* refactor validate.yaml file name and task name ([#62](https://github.com/defenseunicorns/uds-core/issues/62)) ([92a04ea](https://github.com/defenseunicorns/uds-core/commit/92a04ea1096448995ccc0dd9d77a32a5061e06f0))

## [0.6.1](https://github.com/defenseunicorns/uds-core/compare/v0.6.0...v0.6.1) (2023-12-07)


### Bug Fixes

* resolve istio job termination container status logic issue ([#55](https://github.com/defenseunicorns/uds-core/issues/55)) ([c0142c2](https://github.com/defenseunicorns/uds-core/commit/c0142c213446a37185cdf9dec5ae60aaae8ba194))

## [0.6.0](https://github.com/defenseunicorns/uds-core/compare/v0.5.0...v0.6.0) (2023-12-05)


### Features

* introduce Pepr common policies ([#50](https://github.com/defenseunicorns/uds-core/issues/50)) ([54182b4](https://github.com/defenseunicorns/uds-core/commit/54182b4db691d86ce80379be272d924d105b0d07))


### Miscellaneous

* conform to latest uds bundle schema ([#52](https://github.com/defenseunicorns/uds-core/issues/52)) ([14dad38](https://github.com/defenseunicorns/uds-core/commit/14dad3819187d4f8e13f7bbc191dca74a29b9c98))

## [0.5.0](https://github.com/defenseunicorns/uds-core/compare/v0.4.1...v0.5.0) (2023-11-19)


### Features

* expose tls certs as UDS bundle variables ([#48](https://github.com/defenseunicorns/uds-core/issues/48)) ([c1f8286](https://github.com/defenseunicorns/uds-core/commit/c1f828650ef2c53a3fd9ed477950046020c5d375))

## [0.4.1](https://github.com/defenseunicorns/uds-core/compare/v0.4.0...v0.4.1) (2023-11-17)


### Bug Fixes

* metrics-server mTLS fix ([#44](https://github.com/defenseunicorns/uds-core/issues/44)) ([4853522](https://github.com/defenseunicorns/uds-core/commit/4853522c9504c87dcbd8319d689ecb0a1cb42c0b))


### Miscellaneous

* dep updates for UDS CLI & Pepr ([#46](https://github.com/defenseunicorns/uds-core/issues/46)) ([1037634](https://github.com/defenseunicorns/uds-core/commit/10376349e350bd32f3bf32577d8f8089c09ac6cc))

## [0.4.0](https://github.com/defenseunicorns/uds-core/compare/v0.3.0...v0.4.0) (2023-11-16)


### Features

* add monitoring and logging ([#33](https://github.com/defenseunicorns/uds-core/issues/33)) ([c6d9aec](https://github.com/defenseunicorns/uds-core/commit/c6d9aece4984421e1ccbf476cd0d40fb701e4e50))

## [0.3.0](https://github.com/defenseunicorns/uds-core/compare/v0.2.0...v0.3.0) (2023-11-15)


### Features

* add metrics-server ([#35](https://github.com/defenseunicorns/uds-core/issues/35)) ([8216ab9](https://github.com/defenseunicorns/uds-core/commit/8216ab982be79dc393a2e0db359370b32e660150))

## [0.2.0](https://github.com/defenseunicorns/uds-core/compare/v0.1.3...v0.2.0) (2023-11-13)


### Features

* add pepr capability for istio + jobs ([#12](https://github.com/defenseunicorns/uds-core/issues/12)) ([c32a703](https://github.com/defenseunicorns/uds-core/commit/c32a70390f443c90796978ad4c42bbb4b17eb226))
* embed tls certs in istio package ([#32](https://github.com/defenseunicorns/uds-core/issues/32)) ([fb04fee](https://github.com/defenseunicorns/uds-core/commit/fb04feec9657f449366389a0e0a474a8cdeecb2c))

## [0.1.3](https://github.com/defenseunicorns/uds-core/compare/v0.1.2...v0.1.3) (2023-11-10)


### Miscellaneous

* bump zarf & uds-k3d deps ([#30](https://github.com/defenseunicorns/uds-core/issues/30)) ([dd28ab3](https://github.com/defenseunicorns/uds-core/commit/dd28ab3acd163aaccdfb76fbf9726c02a2ff0050))

## [0.1.2](https://github.com/defenseunicorns/uds-core/compare/v0.1.1...v0.1.2) (2023-11-09)


### Miscellaneous

* fix missing deps in tag and release workflow ([#28](https://github.com/defenseunicorns/uds-core/issues/28)) ([1e1af76](https://github.com/defenseunicorns/uds-core/commit/1e1af762e8eb1dd331cbd681e48ecc95ec3184d2))

## [0.1.1](https://github.com/defenseunicorns/uds-core/compare/v0.1.0...v0.1.1) (2023-11-09)


### Features

* Add istio and preliminary ci ([#3](https://github.com/defenseunicorns/uds-core/issues/3)) ([fbd7453](https://github.com/defenseunicorns/uds-core/commit/fbd745392340dbc978b27f0d321f3375882c1c40))
* add prometheus-stack (monitoring) capability ([#2](https://github.com/defenseunicorns/uds-core/issues/2)) ([e438ab6](https://github.com/defenseunicorns/uds-core/commit/e438ab6089bc9d8c6640fa002285d38ddc3022df))
* release-please integration ([#25](https://github.com/defenseunicorns/uds-core/issues/25)) ([bf3c53b](https://github.com/defenseunicorns/uds-core/commit/bf3c53b2ddac4e02e31aa3429029dd9f1c9595e3))


### Bug Fixes

* complete incomplete deploy task ([#21](https://github.com/defenseunicorns/uds-core/issues/21)) ([45ff5e5](https://github.com/defenseunicorns/uds-core/commit/45ff5e5d7b6a50cdfcfabb174349ab539a8accd9))


### Miscellaneous

* add commit lint workflow ([#19](https://github.com/defenseunicorns/uds-core/issues/19)) ([776a632](https://github.com/defenseunicorns/uds-core/commit/776a6325821329b2cbd97da2f40a30447cd48efc))
* remove version from neuvector zarf.yaml ([#11](https://github.com/defenseunicorns/uds-core/issues/11)) ([fbc8d51](https://github.com/defenseunicorns/uds-core/commit/fbc8d51e2b4146d394184d7596cd9a54219dc001))
* update release please extra-files to be explicit ([#26](https://github.com/defenseunicorns/uds-core/issues/26)) ([23f4999](https://github.com/defenseunicorns/uds-core/commit/23f49995771fb05cd18e7a077bf90e86ca5b7471))

## [0.0.0] - YYYY-MM-DD
PRE RELEASE

### Added
- Initial CHANGELOG.md
- CODEOWNERS
- CONTRIBUTING.md
- DEVELOPMENT_MAINTENANCE.md
- LICENSE
- READEME.md
- zarf.yaml
