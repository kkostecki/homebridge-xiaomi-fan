# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]


## [0.9.5] - 2020-06-29
### Changed
- Reset fan status after connection loss. When the fan was turned off manually then the Home fan status got stuck on the last reported state by the fan.

## [0.9.4] - 2020-06-28
### Changed
- Changed default preferences directory

### Removed
- Removed unused dependency

## [0.9.3] - 2020-06-28
### Added
- Added missing dmaker.fan.p5 properties

### Changed
- Optimized code

## [0.9.2] - 2020-06-25
### Added
- Initial dmaker fan support

### Changed
- Fixed some typos
- Optimized error handling


## [0.9.1] - 2020-06-19
### Fixed
- Fixed a bug which might have caused a crash in some cases


## [0.9.0] - 2020-06-14
### Added
- Better device status retrieval. Requesting the device status should not longer make other accessories unresponsive.

### Changed
- Fixed a bug which might have caused a crash when setting the speed level


## [0.8.1] - 2019-08-13
### Fixed
- Fixed a bug where optional switches could not be disabled


## [0.8.0] - 2019-08-04
### Initial release
