# Changelog

All notable changes to this project will be documented in this file.

## [1.3.0] - 2025-05-28

### Role - windows

- Added step to remove AppX packages that prevent sysprep.
- Changed references to **community.windows.win_user_profile** to **ansible.windows.win_user_profile**.

## [1.2.1] - 2025-05-16

### Role - debian

- Removed `bullseye` from versions in metadata.

### Role - rhel

- Reordered versions in metadata.

### Role - ubuntu

- Reordered versions in metadata.

### Role - windows

- Changed versions to `all` in metadata.

## [1.2.0] - 2025-01-28

### Role - windows

- Added tasks to disable mouse acceleration.

## [1.1.2] - 2025-01-08

### Collection

- Added Changelog
- Updated collection README documentation.

## [1.1.1] - 2024-12-05

### Role - windows

- Moved OpenSSH tasks to the end of the role to prevent connection issues.

## [1.1.0] - 2024-12-03

### Role - windows

- Added the `win_use_bleachbit` variable (enabled by default) to enable/disable running Bleachbit on the system.

## [1.0.11] - 2024-11-25

### Role - bleachbit

- Fixed task name for removing Bleachbit.

## [1.0.10] - 2024-11-21

### Role - bleachbit

- Added task to remove Bleachbit after it has been run.

## [1.0.9] - 2024-09-18

### Role - rhel

- Changed cloud-init tasks to only happen on EL 8.

## [1.0.8] - 2024-09-10

### Role - ubuntu

- Fixed role argument spec documentation formatting for the `ubuntu_ssh_trusted_ca_cert_path` variable.

## [1.0.7] - 2024-08-14

### Role - debian

- Moved hostname change task to the end of the playbook.

### Role - rhel

- Moved hostname change task to the end of the playbook.

### Role - ubuntu

- Moved hostname change task to the end of the playbook.

## [1.0.6] - 2024-08-14

### Role - debian

- Reverted changes from 1.0.5.

## [1.0.5] - 2024-08-14

### Role - debian

- Added handler to restart `systemd-resolved.service` when the hostname changes.

## [1.0.4] - 2024-08-09

### Collection

- Minimum Ansible version changed from `2.14` to `2.15` due to EOL status.

## [1.0.3] - 2024-07-12

### Role - bleachbit

- Added default options for Microsoft Edge and backup files.

## [1.0.2] - 2024-07-08

### Collection

- Updated manifest file to ensure that molecule tests are not included in releases.

## [1.0.1] - 2024-06-20

### Role - bleachbit

- Updated documentation and role metadata for readability.

### Role - debian

- Updated documentation and role metadata for readability.

### Role - rhel

- Updated documentation and role metadata for readability.

### Role - ubuntu

- Updated documentation and role metadata for readability.

### Role - windows

- Updated documentation and role metadata for readability.

## [1.0.0] - 2024-06-11

### Collection

- Initial release.
- *bleachbit* role added.
- *debian* role added.
- *rhel* role added.
- *ubuntu* role added.
- *windows* role added.
