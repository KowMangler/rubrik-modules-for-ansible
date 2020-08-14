# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## Types of changes

- **Added** for new features.
- **Changed** for changes in existing functionality.
- **Deprecated** for soon-to-be removed features.
- **Removed** for now removed features.
- **Fixed** for any bug fixes.
- **Security** in case of vulnerabilities.

## v1.0.7

### Added

- `rubrik_sla` to provide alignment to change-management type of modules. `rubrik_sla` allows create, update of Rubrik SLAs
- `rubrik_replication_private`

### Changed

- `rubrik_login_banner` enabled ansible check-mode support
- `rubrik_create_sla` support to add a replication target
- `rubrik_create_sla` support to add a backup window

## v1.0.6

### Added

- `rubrik_add_organization_protectable_object_mssql_server_host`
- `rubrik_add_organization_protectable_object_sql_server_availability_group`
- `rubrik_add_organization_protectable_object_sql_server_db`

## v1.0.5

### Added

- `rubrik_vsphere_instant_recovery`
