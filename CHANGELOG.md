# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
And the commit guidelines from [Conventional Commits](https://conventionalcommits.org) are being used.

## [1.1.7] - 2022-01-21

### Changed

- One of the subdependencies (`pass-stream`) of this package was referencing to the dependency `readable-stream` from github.com directly within its earlier versions. This might lead to problems in contexts that expect pure npm dependencies, so updating the related `digest-stream` leads to a "fix" for that.
