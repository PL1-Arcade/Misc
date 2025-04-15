# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Updated ssf.txt.

## [2.2.0] - 2025-04-10

### Changed

- Updated ssf.txt.

## [2.1.0] - 2025-01-16

### Changed

- Updated Readme to reflect vsync limitations.

- Updated ssf.txt.

### Fixed 

- Fixed false options always reverting to default values on startup.

- Fixed LUA pattern matching for underscores.

## [2.0.0] - 2024-12-15

### Added

- Added optional format to support soft reset frame numbers.

- Added ssf_custom.txt for saving/customizing frame numbers.

### Changed

- Updated Plugin Options Menu.

- Massive code refactoring, split into modular files.

- Updated ssf.txt.

### Fixed 

- Fixed debug and debug slow motion toggling.

## [1.3.0] - 2024-11-20

### Added

- Added Plugin Option Menu item to adjust frames for current game.

- Added Plugin Options Menu Close when ESCAPE is pressed.

- Set ssf.txt to save when exiting a game or exiting MAME.

- Added preservation of frame target for current game when restarting a game. (F3)

- Ensure that frameTarget is always set to zero for non-existent or negative pre-existing values.

### Changed

- Updated ssf.txt.

### Fixed

- Fixed alphabetical sort of ssf.txt.

## [1.2.0] - 2024-11-20

### Changed

- Updated ssf.txt.

## [1.1.0] - 2024-11-13

### Changed

- Improved screen blackout to apply to all screens for multi-screen games.

### Fixed

- Fixed issue with wrong screen device tag causing a crash.

## [1.0.0] - 2024-11-12

### Added

- First release.

<!-- Start comment 

Types of changes:
- Added for new features.
- Changed for changes in existing functionality.
- Deprecated for soon-to-be removed features.
- Removed for now removed features.
- Fixed for any bug fixes.
- Security in case of vulnerabilities. 


Code examples:

Link - [SemVer](https://semver.org)

Reference issues and pull requests - Bring up a list of suggested issues and pull requests within the repository by typing #.
Type the issue or pull request number or title to filter the list, and then press either tab or enter to complete the highlighted result.

Ignore Markdown formatting - Put a \ before the markdown character.

End comment -->


[unreleased]: https://github.com/Jakobud/skipstartupframes/compare/v2.2.0...HEAD
[2.2.0]: https://github.com/Jakobud/skipstartupframes/compare/v2.1.0...v2.2.0
[2.1.0]: https://github.com/Jakobud/skipstartupframes/compare/v2.0.0...v2.1.0
[2.0.0]: https://github.com/Jakobud/skipstartupframes/compare/v1.3.0...v2.0.0
[1.3.0]: https://github.com/Jakobud/skipstartupframes/compare/v1.2.0...v1.3.0
[1.2.0]: https://github.com/Jakobud/skipstartupframes/compare/v1.1.0...v1.2.0
[1.1.0]: https://github.com/Jakobud/skipstartupframes/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/Jakobud/skipstartupframes/releases/tag/v1.0.0
