# Changelog

## [0.7.2] - 2023-02-23

### Changed

- Updated the minimum versions of the following dependencies:
  - http-cache [0.9.2]

## [0.7.1] - 2023-02-17

### Changed

- Updated the minimum versions of the following dependencies:
  - http-cache [0.9.1]
  - http [0.2.9]

## [0.7.0] - 2023-02-16

### Changed

- MSRV is now 1.62.1

- Updated the minimum versions of the following dependencies:
  - http-cache [0.9.0]

## [0.6.0] - 2023-02-07

- MSRV is now 1.60.0

### Changed

- Updated the minimum versions of the following dependencies:
  - http-cache [0.8.0]
  - anyhow [1.0.69]
  - async-trait [0.1.64]
  - serde [1.0.152]

## [0.5.2] - 2022-11-16

### Changed

- Updated the minimum versions of the following dependencies:
  - http-cache [0.7.2]

## [0.5.1] - 2022-11-06

### Changed

- Updated the minimum versions of the following dependencies:
  - http-cache [0.7.1]
  - anyhow [1.0.66]
  - async-trait [0.1.58]
  - serde [1.0.147]
  - url [2.3.1]
  - async-std [1.12.0]

## [0.5.0] - 2022-06-17

### Changed

- The `CacheManager` trait is now implemented directly against the `MokaManager` struct rather than `Arc<MokaManager>`. The Arc is now internal to the `MokaManager` struct as part of the `cache` field.

- Updated the minimum versions of the following dependencies:
  - http-cache [0.7.0]
  - async-trait [0.1.56]
  - http [0.2.8]
  - serde [1.0.137]

## [0.4.6] - 2022-04-30

### Changed

- Updated the minimum versions of the following dependencies:
  - http-cache [0.6.5]
  - http [0.2.7]

## [0.4.5] - 2022-04-26

### Fixed

- Updated version of http-cache to 0.6.4. I apparently have forgotten to do this the last couple of updates!

## [0.4.4] - 2022-04-26

### Added

- This changelog to keep a record of notable changes to the project.
