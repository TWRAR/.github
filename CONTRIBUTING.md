<p align="center">
  <img src="https://raw.githubusercontent.com/TWRAR/Engine/main/assets/logo.png" width="300" alt="TWRAR — The Website Recorder And Replayer">
</p>

# Contributing to TWRAR

TWRAR is split across two repos, each with its own `CONTRIBUTING.md`:

- **[Engine](https://github.com/TWRAR/Engine)** - the recorder/replayer engine and GUI
- **[Website](https://github.com/TWRAR/Website)** - source for twrar.stuxie.dev

Open your issue or PR on whichever of those the change actually belongs to.
This `.github` repo itself holds only the org profile
(`profile/README.md`) and org-wide defaults - contributions here are
typically fixes to those, or to files that fall back to this repo when a
target repo doesn't have its own (see GitHub's
[community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file-for-your-organization)).

## Versioning

Bump [`VERSION.md`](VERSION.md) and add a matching entry to
[`CHANGELOG.md`](CHANGELOG.md) in the same PR, following
[Semantic Versioning](https://semver.org/) (`MAJOR.MINOR.PATCH`),
independent of the other repos' own versions.
