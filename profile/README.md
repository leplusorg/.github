# Welcome to [Leplus.org](https://www.leplus.org) OSS Repositories

<p align="center">
  <img src="https://github.com/leplusorg/.github/blob/main/profile/open_source_bg_github.jpg?raw=true" alt="Banner"/>
</p>

You can find here my [open source projects](https://github.com/leplusorg?tab=repositories).

Our projects follow the certain guidelines and best practices as described below.

## Code of Conduct

We want our community to be a place to share constructively. Personal viewpoints are welcome to foster out-of-the-box ideas and innovative contributions. But harassment is NOT welcome and will not be tolerated. Harassment includes deliberate intimidation and targeting individuals in a manner that makes them feel uncomfortable, unwelcome, or afraid to participate.

See the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) for details.

## Open Source Software (OSS)

We believe in the power of open source software as defined by the Open Source Initiative (OSI) [definition](https://opensource.org/osd). We aim to exchange knowledge freely in order to achieve the best possible software and to grow our community and its knowledge along with the way.

## Quality & Security

- All repos are continuously scanned for known vulnerabilities (CVE).
- All commits go through a code review before being merged.
- All commit messages use [Conventional Commits](https://www.conventionalcommits.org).
- All published releases and artifacts are versioned using [Semantic Versioning](https://semver.org/).
- All the merged commits and the resulting published artifacts are digitally signed:
  - Git commits are signed using [GitHub's verified signature](https://docs.github.com/github/authenticating-to-github/displaying-verification-statuses-for-all-of-your-commits).
  - Docker Hub artifacts are signed using [Sigstore](https://www.sigstore.dev).
  - Maven Central artifacts are signed using public key [4C155617](https://pgp.mit.edu/pks/lookup?op=get&search=0x6B1B9BE54C155617) which you can verity using this [Docker image](https://hub.docker.com/r/leplusorg/pgp-verify-jar) for example.

All the third-party (open source) dependencies are linked to a specific version to keep builds [reproducible](https://reproducible-builds.org) and to prevent supply chain attacks (cryptographic hashes are used instead or on top of numerical versions wherever possible in order to pin mutable versions, e.g. for Docker containers or GitHub Actions).
[Software Bill of Materials (SBOM)](https://en.wikipedia.org/wiki/Software_supply_chain) are also produced along the artifacts to provide to visibility necessary to ensure supply chain security and transparency.

Memory-safe programming languages are used whenever possible.

[![Repos status dashboard](https://img.shields.io/badge/Repos-Dashboard-blue)](https://github.com/leplusorg/actions-dashboard/blob/main/dashboard.md)

More [miscellaneous projects](https://github.com/thomasleplus?tab=repositories) of Thomas Leplus.
