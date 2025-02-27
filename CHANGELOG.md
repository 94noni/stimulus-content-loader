# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [4.0.1] - 2022-04-03

### Chore

- Upgrading dependencies
- Setting Stimulus as external dependency reducing bundle size from `2.20 KiB` to `0.70 KiB`.

## [4.0.0] - 2021-09-27

### Chore

- **Breaking** Upgrading Stimulus to `3.x` and change namespace from `stimulus` to `@hotwired/stimulus`.
- Upgrading dependencies
- Upgrading Node to `14.18.0`

## [3.0.0] - 2021-05-18

### Chore

- Moving from [Snowpack](https://www.snowpack.dev/) to [Vite](https://github.com/vitejs/vite)
- Upgrading Node to 14.16.1
- Moving to TypeScript

### Added

- Adding option to load inline scripts

## [2.0.0] - 2020-12-05

### Added

- Support for Stimulus 2.0
- Prevent error if the url is empty.

### Changed

- **Breaking** Using the new `values` static property

```diff
- <div data-controller="content-loader" data-content-loader-url="/message.html"></div>
+ <div data-controller="content-loader" data-content-loader-url-value="/message.html"></div>
```

## [1.0.0] - 2020-10-15

### Added

- Adding controller
