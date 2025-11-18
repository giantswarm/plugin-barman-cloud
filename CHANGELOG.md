# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Fixed

- Fix cilium network policy `endpointSelector`'s `matchLabels` field.

## [0.2.0] - 2025-11-18

### Changed

- Upgrade chart from 0.2.0 to 0.3.1.

## [0.1.0] - 2025-11-18

### Added

- Push app to collections.
- Add cilium network policy template in helm.
- Add custom service account to allow for IRSA usage until upstream PR is merged.

## [0.0.3] - 2025-10-14

### Changed

- Update images names in values.

## [0.0.2] - 2025-10-13

### Added

- Push app to control-plane-catalog.

## [0.0.1] - 2025-10-09

### Added

- Initial repo setup.

[Unreleased]: https://github.com/giantswarm/plugin-barman-cloud/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/giantswarm/plugin-barman-cloud/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/giantswarm/plugin-barman-cloud/compare/v0.0.3...v0.1.0
[0.0.3]: https://github.com/giantswarm/plugin-barman-cloud/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/giantswarm/plugin-barman-cloud/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/giantswarm/plugin-barman-cloud/releases/tag/v0.0.1
