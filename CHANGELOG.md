# Changelog

All notable changes to this repo are documented here. Versioning follows
[Semantic Versioning](https://semver.org/) (`MAJOR.MINOR.PATCH`), independent
of the other TWRAR repos' own versions.

Since v26.10.23 this project uses [Date Versioning](https://datevers.ing) (`YY.MM.DD`, the UTC release date, with `-1`, `-2`… for later releases the same day); earlier releases used Semantic Versioning.

## v26.10.23

### Added

- `tests/version.sh`, which checks that `VERSION.md` is a valid Date Version, a real calendar date not in the future, and the same as the newest entry in this changelog

### Changed

- Switched from Semantic Versioning to [Date Versioning](https://datevers.ing): releases are numbered by their UTC release date as `YY.MM.DD`, with `-1`, `-2`… for later releases the same day. This release follows v1.0.4
- `commit.sh` and `commit.bat` refuse a `VERSION.md` that isn't a valid Date Version or is dated in the future (UTC), and warn when it's dated before today
- `README.md` and `CONTRIBUTING.md` describe Date Versioning and the release steps

## [1.0.4] - 2026-09-22

### Added
- `generateMetrics.yml` workflow, matching the Stux.Group family's `.github` repos — generates `stats.svg` on the `metrics` branch daily and on push.
- An "Our Activity" `stats.svg` embed in `profile/README.md`.

## [1.0.3] - 2026-09-16

### Added
- Bluesky and LinkedIn badges (`bsky.app/profile/stuxie.dev`, `linkedin.com/company/stuxiedev`) in a new "Connect with Us!" section in `profile/README.md`, alongside a GitHub followers badge.

## [1.0.2] - 2026-09-15

### Fixed
- `README.md` and `profile/README.md`'s footer credit now uses the hosted `https://global.media.stuxie.dev/icon.png` StuxieDev icon instead of the live GitHub avatar shorthand

## [1.0.1] - 2026-09-10

### Changed
- Footer now reads "Written & Maintained by StuxieDev" followed by
  "A StuxieDev Project" (previously "Built & Maintained by", reversed
  order).

## [1.0.0] - 2026-09-10

### Added
- Initial org profile (`profile/README.md`) and health files for the
  `TWRAR` GitHub organisation.
