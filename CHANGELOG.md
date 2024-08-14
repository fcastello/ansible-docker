# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).


## [0.1.1] - 2024-08-1
### Fixed
- Fixed linting errors from ansible-lint, replaced shell with command

## [0.1.0] - 2024-08-14
### Added
- templated config file for disabling iptables and a few other options
### Fixed
- Ansible version to 2.17
- Fixed linting errors from ansible-lint
- Fixed apt keyrings to support trusted.gpg.d from deprecated apt-key

## [0.0.5] - 2021-09-03
### Removed
- installation of python-pip and python-docker

## [0.0.4] - 2020-04-19
### Changed
- Formating after yamllint

## [0.0.3] - 2020-04-19
### Changed
- Formating after yamllint

## [0.0.2] - 2020-04-19
### Changed
- Formating after ansible lint

## [0.0.1] - 2020-04-19 -  Initial commit
### Added
- Basic installation of docker (tested in ubuntu 18.04 arm64 and amd64)
