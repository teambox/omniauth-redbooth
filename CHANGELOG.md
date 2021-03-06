# Change Log

## [Unreleased]

### Added
### Changed
### Deprecated
### Removed
### Deprecated
### Fixed
### Security

## [1.0.2] - 2017-04-03

### Added

- Workaround on `#callback_url` for omniauth-oauth2 1.4.0

### Changed

- CI test will only run on ruby > 2.2.x

### Deprecated

- Ruby 1.9.3
- Ruby 2.1

### Removed

- Restriction on omniauth-oauth2 `< 1.4.0`

### Deprecated
### Fixed
### Security

## [1.0.1] - 2015-11-26

### Added
- Test on ruby 2.1 and 2.2 too.

### Changed
- cleaned up the code a bit.
- cleaned up specs a bit and updated to RSpec 3.
- Use debugger gem on ruby 1.9.x or less and byebug on 2.x

### Fixed
- changed omniauth-oauth2 dependency to 1.x up to 1.3.1 since [this change][1]
  in omniauth-oauth2 1.4 breaks the strategy.
- Stop dealing with SCRIPT_NAME since it was breaking stuff

## [1.0.0] - 2015-11-18

### Changed
- omniauth-oauth2 dependency to ~> 1.2

## Previous changes
Undocumented. Please review git commits history.

[Unreleased]: https://github.com/redbooth/omniauth-redbooth/compare/1.0.2...HEAD
[1.0.2]: https://github.com/redbooth/omniauth-redbooth/compare/1.0.1...1.0.2
[1.0.1]: https://github.com/redbooth/omniauth-redbooth/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/redbooth/omniauth-redbooth/compare/0.0.4...1.0.0

[1]: https://github.com/intridea/omniauth-oauth2/issues/81
