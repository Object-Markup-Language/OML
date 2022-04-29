# Version Formatting
Oml uses a simplified version of [Semantic Versioning](https://semver.org/). Instead of three numbers (MAJOR.MINOR.PATCH), it simply uses two (MAJOR.MINOR):
* MAJOR denotes a version which is likely to cause breaking incompatabilities with existing parsers.
* MINOR denotes a version which adds features or rewords parts of the spec in ways that is not likely to break existing parsers.

## Release Candidates
Oml additionally uses a system for pre-release versions which are still published to acquire feedback on a version before pushing it. A version will have `-rc#` appended to it if it is a release candidate, where `#` is release candidates number, beginning at 1 for each version.