# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
- Add `addInfo` endpoint to `io.edgehog.devicemanager.apps.DeploymentEvent` interface


## [0.10.0] - 2025-12-09
### Added
- added `io.edgehog.devicemanager.apps.AvailableContainers` interface
- added `io.edgehog.devicemanager.apps.AvailableDeployments` interface
- added `io.edgehog.devicemanager.apps.AvailableDeviceMappings` interface
- added `io.edgehog.devicemanager.apps.AvailableImages` interface
- added `io.edgehog.devicemanager.apps.AvailableNetworks` interface
- added `io.edgehog.devicemanager.apps.AvailableVolumes` interface
- added `io.edgehog.devicemanager.apps.CreateContainerRequest` interface
- added `io.edgehog.devicemanager.apps.CreateDeploymentRequest` interface
- added `io.edgehog.devicemanager.apps.CreateDeviceMappingRequest` interface
- added `io.edgehog.devicemanager.apps.CreateImageRequest` interface
- added `io.edgehog.devicemanager.apps.CreateNetworkRequest` interface
- added `io.edgehog.devicemanager.apps.CreateVolumeRequest` interface
- added `io.edgehog.devicemanager.apps.DeploymentCommand` interface
- added `io.edgehog.devicemanager.apps.DeploymentEvent` interface
- added `io.edgehog.devicemanager.apps.DeploymentUpdate` interface
- added `io.edgehog.devicemanager.apps.stats.ContainerBlkio` interface
- added `io.edgehog.devicemanager.apps.stats.ContainerCpu` interface
- added `io.edgehog.devicemanager.apps.stats.ContainerMemoryStats` interface
- added `io.edgehog.devicemanager.apps.stats.ContainerMemory` interface
- added `io.edgehog.devicemanager.apps.stats.ContainerNetworks` interface
- added `io.edgehog.devicemanager.apps.stats.ContainerProcesses` interface
- added `io.edgehog.devicemanager.apps.stats.VolumeUsage` interface

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
