# Changelog


## [1.6.0](https://github.com/supercharge/redis-github-action/compare/v1.5.0...v1.6.0) - 2023-07-27

### Added
- add `redis-remove-container` option adding the `--rm` flag to the resulting `docker run … --rm` command which starts the Redis container

### Updated
- update versions in README


## [1.5.0](https://github.com/supercharge/redis-github-action/compare/v1.4.0...v1.5.0) - 2023-02-14

### Added
- use a custom Redis image: useful if you need to run an alternative Redis image like Redis Stack
  - uses `redis` as the default Docker image


## [1.4.0](https://github.com/supercharge/redis-github-action/compare/v1.3.0...v1.4.0) - 2021-12-28

### Added
- use a custom name for the Redis container: this is helpful when starting multiple Redis instances


## [1.3.0](https://github.com/supercharge/redis-github-action/compare/v1.2.0...v1.3.0) - 2021-12-27

### Added
- start Redis instance on a custom port


## [1.2.0](https://github.com/supercharge/redis-github-action/compare/v1.1.0...v1.2.0) - 2021-01-08

### Added
- version check before starting the Redis container: fall back to `latest` when no Redis version is defined for the workflow
- run tests on pull requests

### Updated
- refined wording in Readme


## [1.1.0](https://github.com/supercharge/redis-github-action/compare/v1.0.0...v1.1.0) - 2019-12-18

### Updated
- switched from a Node.js workflow to a Docker-based workflow
  - reduces noise in the repo by removing the Node.js dependencies and only relying on a shell script


## 1.0.0 - 2019-12-17

### Added
- `1.0.0` release 🚀 🎉
