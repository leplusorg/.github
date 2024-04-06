# Welcome to [Leplus.org](https://www.leplus.org) OSS Repositories 👋

You can find my open source projects [here](https://github.com/leplusorg?tab=repositories).

All the projects are continuously scanned for known vulnerabilities (CVE). Releases uses [semantic versioning](https://semver.org). All commits go through a code review before being merged. All the merged commits and the resulting published artifacts are digitally signed:
- GitHub commits are signed using [GitHub's verified signature](https://docs.github.com/github/authenticating-to-github/displaying-verification-statuses-for-all-of-your-commits).
- Maven Central are signed using public key [4C155617](https://pgp.mit.edu/pks/lookup?op=get&search=0x6B1B9BE54C155617) which you can verity using this [docker image](https://hub.docker.com/r/leplusorg/pgp-verify-jar) for example.

All the third-party (open source) dependencies are linked to a specific version to keep build reproducible and to prevent supply chain attacks (cryptographic checksums are used instead of version numbers are used wherever possible to [pin the version](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions#using-third-party-actions)).

[Repos status dashboard](https://github.com/leplusorg/actions-dashboard/blob/main/dashboard.md)

I also have other incubating projects [here](https://github.com/thomasleplus?tab=repositories).
