# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

Types of changes:
- **Added**; for new features.
- **Changed**; for changes in existing functionality.
- **Deprecated**; for soon-to-be removed features.
- **Removed**; for now removed features.
- **Fixed**; for any bug fixes.
- **Security**; in case of vulnerabilities.

---

## Unreleased [0.0.0]

---

## [v0.3.0] - 2020-09-05

### Changed

- Color pallette has been changed back to meet around 5.0 contrast ratio. More contrast gives less color.

- Syntax variables have their colors shuffled.

- HTML; Syntax highlighting looks final like.

### Removed

- Highlighting based on meta scopes. This proofed to be unreliable.
---

## [v0.2.0] - 2020-09-02

### Changed

- Set both `@syntax-color-renamed` and `@syntax-color-modified` to `@syntax-color-info`
- Make all foreground colors meet around contrast level 6.
- Other syntax color changes; reducing blue's.

---

## [v0.1.0] - 2020-09-01

### Added

- Basic architecture for adding new syntax highlighting.
- A Base syntax stylesheet adhering Textmate's Syntax Language naming conventions making this theme a perfect match with Textmate ported languages!
- Initial language syntax files which should be specificly supported by this Developers Day syntax theme.
