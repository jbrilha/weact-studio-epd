# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
- Add `WeActStudio420TriColorDriver` and `Display420TriColor` for the 4.2 inch B/W/R (GDEY042Z98, SSD1683) display
- Add `fast_full_refresh`, `fast_full_update_from_buffer`, and `fast_full_update` for the 4.2 inch B/W/R display, based on GxEPD2's `_use_fast_update` for the GDEY042Z98

### Fixed
- Stop bypassing red RAM during full refresh on tri-color displays

## [0.1.2](https://github.com/avsaase/weact-studio-epd/compare/v0.1.1...v0.1.2) - 2024-09-04

### Added
- Add sleep and wakeup support (with esp32c6 sample) ([#14](https://github.com/avsaase/weact-studio-epd/pull/14))
- Add additional color conversions for tinybmp support ([#16](https://github.com/avsaase/weact-studio-epd/pull/16))

### Fixed
- pass display by reference not by value for tricolor displays ([#15](https://github.com/avsaase/weact-studio-epd/pull/15))

### Other
- build esp32c6 examples ([#19](https://github.com/avsaase/weact-studio-epd/pull/19))
- rustfmt

## [0.1.1](https://github.com/avsaase/weact-studio-epd/releases/tag/v0.1.1) - 2024-08-01

### Added
- First release
