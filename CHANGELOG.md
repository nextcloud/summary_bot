<!--
  - SPDX-FileCopyrightText: 2024 Nextcloud GmbH and Nextcloud contributors
  - SPDX-License-Identifier: AGPL-3.0-or-later
-->
# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [1.1.6] – 2025-11-27

### Fixed
- do not reload on code change (#43) @kyteinsky
- add user_id to taskproc OCS calls to avoid 401 resp (#43) @kyteinsky
- use "admin" as fallback if no user is found (#43) @kyteinsky
- disallow anon users to request summaries (#43) @kyteinsky

### Changed
- improve LLM taskproc error message (#43) @kyteinsky
- upgrade to python3.13 and nc_py_api to 0.23.0 (#43) @kyteinsky
- bump max supported NC to 33 (#43) @kyteinsky


## [1.1.5] – 2025-07-24

### Fixed
- Fix scheduled summary jobs #40 @lukasdotcom
- Enable dependabot and other maintenance tasks #37 @kyteinsky
- Add Github actions for reuse #36 @AndyScherzinger


## [1.1.4] – 2024-10-01

### Fixed
- Enable appstore-build-publish on nextcloud-releases


## [1.1.3] – 2024-10-01

### Fixed
- Add files required for nc release


## [1.1.2] – 2024-09-30

### Fixed
- Preserve pip cache on code change


## [1.1.1] – 2024-09-30

### Fixed
- Timezone handling
- Docker build container repo url
- Docker runs-only-on github runners
- Minor fixes


## [1.1.0] – 2024-09-18

### Changed
- Use TaskProcessing instead of TextProcessing

### Added
- Add on-demand execution command


## [1.0.0] – 2024-08-02

### Added
- The app
