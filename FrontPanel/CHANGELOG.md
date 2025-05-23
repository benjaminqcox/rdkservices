# Changelog

All notable changes to this RDK Service will be documented in this file.

* Each RDK Service has a CHANGELOG file that contains all changes done so far. When version is updated, add a entry in the CHANGELOG.md at the top with user friendly information on what was changed with the new version. Please don't mention JIRA tickets in CHANGELOG. 

* Please Add entry in the CHANGELOG for each version change and indicate the type of change with these labels:
    * **Added** for new features.
    * **Changed** for changes in existing functionality.
    * **Deprecated** for soon-to-be removed features.
    * **Removed** for now removed features.
    * **Fixed** for any bug fixes.
    * **Security** in case of vulnerabilities.

* Changes in CHANGELOG should be updated when commits are added to the main or release branches. There should be one CHANGELOG entry per JIRA Ticket. This is not enforced on sprint branches since there could be multiple changes for the same JIRA ticket during development. 

* For more details, refer to [versioning](https://github.com/rdkcentral/rdkservices#versioning) section under Main README.

## [1.0.10] - 2025-03-17
### Added
- Fixed frontpanel helper to not set fpState during init 

## [1.0.9] - 2024-11-29
### Added
- Fixed sharp FP issue

## [1.0.8] - 2024-09-30
### Added
- Fixed getFrontPanelIndicatorInfo API

## [1.0.7] - 2024-05-25
### Added
- Make plugin autostart configurable from recipe

## [1.0.6] - 2024-03-29
### Security
- Resolved security vulnerabilities

## [1.0.5] - 2023-10-04
### Added
- Implement Thunder Plugin Configuration for Kirkstone builds(CMake-3.20 & above)

## [1.0.4] - 2023-09-28
### Fixed
- Add PLUGIN_FRONTPANEL option to build FrontPanel

## [1.0.3] - 2023-04-12
### Fixed
- Fixed IARM_Bus_UnRegisterEventHandler  call to IARM_Bus_RemoveEventHandler

## [1.0.2] - 2023-04-11
### Fixed
- Updated Logging, and initialize function to be more verbose for testing purposes

## [1.0.1]
### Fixed
- Optimize include

## [1.0.0] - 2022-05-11
### Added
- Add CHANGELOG

### Change
- Reset API version to 1.0.0
- Change README to inform how to update changelog and API version
