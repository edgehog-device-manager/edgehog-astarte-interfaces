# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.8.0] - 2024-04-19
### Added
- Add `io.edgehog.devicemanager.ForwarderSessionRequest` and
  `io.edgehog.devicemanager.ForwarderSessionState` interfaces

## [0.7.0] - 2023-06-21
### Added
- Add `operation` endpoint to `io.edgehog.devicemanager.OTARequest` interface
  ([#52](https://github.com/edgehog-device-manager/edgehog-astarte-interfaces/issues/52)).
- Add `io.edgehog.devicemanager.OTAEvent` interface
  ([#54](https://github.com/edgehog-device-manager/edgehog-astarte-interfaces/issues/54),
  [#55](https://github.com/edgehog-device-manager/edgehog-astarte-interfaces/issues/55)).

### Changed
- Bump `io.edgehog.devicemanager.OTARequest` to 1.0 changing endpoints reliability to `unreliable`
  ([#51](https://github.com/edgehog-device-manager/edgehog-astarte-interfaces/issues/51)).

### Removed
- Remove `io.edgehog.devicemanager.OTAResponse` interface
  ([#56](https://github.com/edgehog-device-manager/edgehog-astarte-interfaces/issues/56)).


## [0.5.2] - 2022-06-22

## [0.5.1] - 2022-06-01
### Added
- Add `connected` boolean endpoint to `WiFiScanResults` interface.
- Increase `io.edgehog.devicemanager.WiFiScanResults` version number to `v0.2`.

## [0.5.0] - 2022-03-22
### Added
- Initial Edgehog release
