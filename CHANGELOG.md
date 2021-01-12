#Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]
### Added
- Option to pass ssh key as parameter + dependencies

### Changed
- Replaced centos6 with centos8

## [2.1.1] - 2020-06-25
### Changed
- Change frozen_string_literal to false in the check

## [2.1.0] - 2020-05-15
### Added
- Bonsai asset support, missed .bonsai.yml before

### Changed
- Updated net-sftp dependency to '3.0.0'

## [2.0.0] - 2020-05-15
### Breaking Changes
- Update minimum required ruby version to 2.3. Drop unsupported ruby versions.
- Bump `sensu-plugin` dependency to `~> 4.0`

### Added
- Bonsai asset support
### Changed
- Updated bundler dependancy to '~> 2.1'
- Updated rubocop dependency to '~> 0.81.0'
- Remediated rubocop issues
- Updated rake dependency to '~> 13.0'
- Updated net-sftp dependency to '2.1.2'

## [1.0.1] - 2017-09-20
### Fixed
- Corrected Auth Method in Net::SFTP.start (@makaveli0129)

### Added
- Ruby 2.4.1 testing

## [1.0.0] - 2016-09-25
### Removed
- Ruby 1.9.3 support

### Added
- Ruby 2.3.0 support

### Fixed
- uninitialized constant CheckSftp::Timeout error (@nickptrvc)

### Changed
- Update to rubocop 0.40 and cleanup

## [0.0.2] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## 0.0.1 - 2015-07-04
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-sftp/compare/2.1.1...HEAD
[2.1.1]: https://github.com/sensu-plugins/sensu-plugins-sftp/compare/2.1.0...2.1.1
[2.1.0]: https://github.com/sensu-plugins/sensu-plugins-sftp/compare/2.0.0...2.1.0
[2.0.0]: https://github.com/sensu-plugins/sensu-plugins-sftp/compare/1.0.1...2.0.0
[1.0.1]: https://github.com/sensu-plugins/sensu-plugins-sftp/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-sftp/compare/0.0.2...1.0.0
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-sftp/compare/0.0.1...0.0.2
