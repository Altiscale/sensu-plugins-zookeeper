# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format listed at [Keep A Changelog](http://keepachangelog.com/)

## [Unreleased]

## [1.0.0] - 2017-03-21
### Added
- check-zookeeper-reqs (@grem11n)
- check-zookeeper-latency (@grem11n)
- check-zookeeper-file-descriptors (@grem11n)
- support for Ruby 2.3.0 (@eheydrick)
- `metrics-zookeeper.rb`: Switch to using the `mntr` command to gather metrics and add additional metrics (@jasiek191)

### Removed
- support for Ruby 1.9.3 (@eheydrick)

## [0.1.0] - 2016-03-05
### Added
- check-zookeeper-ruok

## [0.0.4] - 2015-12-10
### Added
- check-znode
- metrics-zookeeper

## [0.0.3] - 2015-07-14
### Changed
- updated sensu-plugin gem to 1.2.0

## [0.0.2] - 2015-06-03
### Fixed
- added binstubs

### Changed
- removed cruft from /lib

## 0.0.1 - 2015-04-30
### Added
- initial release

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-zookeeper/compare/1.0.0...HEAD
[1.0.0]: https://github.com/sensu-plugins/sensu-plugins-zookeeper/compare/0.1.0...1.0.0
[0.1.0]: https://github.com/sensu-plugins/sensu-plugins-zookeeper/compare/0.0.4...0.1.0
[0.0.4]: https://github.com/sensu-plugins/sensu-plugins-zookeeper/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/sensu-plugins/sensu-plugins-zookeeper/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/sensu-plugins/sensu-plugins-zookeeper/compare/0.0.1...0.0.2
