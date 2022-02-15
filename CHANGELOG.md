## v0.6.0 (Released 2022-02-04)

BREAKING CHANGES

- feat: our File type no longer implements the fs.File interface

IMPROVEMENTS

- fix: only log on client startup, not connection init
- feat: add enhanced debugging statements
- fix: close file descriptor after list

## v0.5.2 (Released 2022-01-31)

BUG FIXES

- client: allow multiple authentication methods

BUILD

- Update golang.org/x/crypto commit hash to 198e437
- Update module github.com/prometheus/client_golang to v1.12.1

## v0.5.1 (Released 2022-01-27)

BUG FIXES

- fix: bugfix for Read

## v0.5.0 (Released 2022-01-27)

ADDITIONS

- feat: make our File type fs.File compatible

BUILD

- Update golang.org/x/crypto commit hash to aa10faf

## v0.4.0 (Released 2022-01-25)

IMPROVEMENTS

- client: support reading private keys with passphrases

## v0.3.0 (Released 2022-01-21)

- feat: export MockClient
- refactor: use testing.T's TempDir instead of ioutil

## v0.2.0 (Released 2022-01-19)

- Added GitHub actions workflow
- Added new Prometheus metrics

## v0.1.2 (Released 2022-01-12)

- Updated filepaths in mock client to match the actual SFTP client

## v0.1.1 (Released 2022-01-6)

- Configured renovate bot for dependency updates

## v0.1.0 (Released 2022-01-6)

- Initial release