# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).



## [0.7.1](https://github.com/rokucommunity/bslint/compare/v0.7.0...v0.7.1) - 2022-05-09
### Fixed
 - error variable from `catch` statement should be available within the `catch` block ([#64](https://github.com/rokucommunity/bslint/pull/64))
 - Prevent "unused var" in `goto` loop ([#65](https://github.com/rokucommunity/bslint/pull/65))



## [0.7.0](https://github.com/rokucommunity/bslint/compare/v0.6.1...v0.7.0) - 2022-04-13
### Added
 - `no-todo` code style rule ([#56](https://github.com/rokucommunity/bslint/pull/56))
 - `no-stop` rule ([#57](https://github.com/rokucommunity/bslint/pull/57))
 - `newline-last` rule ([#58](https://github.com/rokucommunity/bslint/pull/58))
### Changed
 - upgrade to brighterscript@0.48.0
### Fixed
 - do not consider enums as unused variables ([#59](https://github.com/rokucommunity/bslint/pull/59))



## [0.6.0](https://github.com/rokucommunity/bslint/compare/v0.6.0...v0.6.1) - 2022-03-24
### Changed
 - upgrade to brighterscript@0.45.3
### Fixed
 - npm audit issues



## [0.6.0](https://github.com/rokucommunity/bslint/compare/v0.5.0...v0.6.0) - 2021-10-27
### Added
 - associative array comma linting and fixing ([#40](https://github.com/rokucommunity/bslint/pull/40))
 - automatic code fix for removing `as void` when changing a function to sub ([#42](https://github.com/rokucommunity/bslint/pull/40))



## [0.5.0](https://github.com/rokucommunity/bslint/compare/v0.4.0...v0.5.0) - 2021-07-07
### Added
 - check scripts/components usage (behind `--checkUsage` flag). ([#35](https://github.com/rokucommunity/bslint/pull/35))


## [0.4.0](https://github.com/rokucommunity/bslint/compare/v0.3.0...v0.4.0) - 2021-05-25
### Added
 - automatic code fixes ([#28](https://github.com/rokucommunity/bslint/pull/28))
    - function/sub style
    - `then` style
    - if condition grouping with/without parenthesis



## [0.3.0](https://github.com/rokucommunity/bslint/compare/v0.2.0...v0.3.0) - 2021-05-19
### Added
 - Add ignores and globals ([#27](https://github.com/rokucommunity/bslint/pull/27))
### Fixed
 - invoking classes fix ([#26](https://github.com/rokucommunity/bslint/pull/26))



## [0.2.0](https://github.com/rokucommunity/bslint/compare/v0.1.0...v0.2.0) - 2021-05-13
### Added
 - no-print-rule ([#19](https://github.com/rokucommunity/bslint/pull/19))
 - Add namespaces and super ([#24](https://github.com/rokucommunity/bslint/pull/24))



## [0.1.0](https://github.com/rokucommunity/bslint/compare/213c530d29ff49771da2860cf4cae79c5341e8cb...v0.1.0) - 2021-02-22
### Added
Initial release