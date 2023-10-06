<div align=center> <h1>Software Versioning</h1> </div>
<br />
<br />

## #1 Application Development Versioning - for End User (Computer software, Web app and Mobile Application).
<br />

**Semantic Versioning Template:**

The version number consists of three segments: `MAJOR.MINOR.PATCH`. Here's what each segment represents:

1. **MAJOR**: Increment this version number when you make incompatible changes to your app. This typically involves breaking changes that require users to update their app or modify their code.

3. **MINOR**: Increment this version number when you add new features or functionalities to the app in a backward-compatible manner. Users can update their app without worrying about breaking existing functionality.

4. **PATCH**: Increment this version number for backward-compatible bug fixes and minor improvements that do not introduce new features. These updates should not disrupt the existing functionality of the app.

In addition to these segments, you can also include optional labels or metadata:

- **Pre-release version**: If you have a version of your app that's still in development or testing, you can include a pre-release version label, such as `alpha`, `beta`, or `rc` (release candidate). For example, `1.0.0-alpha.1`.

- **Build metadata**: You can add build information or other metadata to the version number. This is typically separated by a plus sign (`+`). For example, `1.0.0+20231006`.

**Example Usage:**

- Initial Release: `1.0.0`
- Adding a New Feature: `1.1.0`
- Bug Fix: `1.1.1`
- Major UI Overhaul: `2.0.0`
- Pre-release Version: `2.0.0-alpha.1`

-----
<br />

## #2 Templates for versioning systems commonly used in web application development:
<br />

**Date-Based Versioning:**
- Format: `YYYY.MM.DD`
- Example: `2023.10.06`

**API Versioning:**
- URL Path Format: `/v{version}/resource`
- HTTP Header Format: `Accept: application/vnd.myapp.v{version}+json`
- Example: `/v1/resource`, `Accept: application/vnd.myapp.v2+json`

**Build Numbers:**
- Format: Numeric or alphanumeric build identifier
- Example: `12345`, `1.2.3-alpha-45`

**Content Management Systems (CMS):**
- CMS platforms often have their versioning templates, such as:
  - WordPress: `X.Y.Z` (e.g., `5.0.3`)
  - Joomla: `X.Y.Z` (e.g., `3.9.5`)

**Front-End and Back-End Separation:**
- Separate versioning for front-end and back-end components is typically done using Semantic Versioning (SemVer) or another suitable versioning system.
- Example (Front-End): `1.0.0`
- Example (Back-End): `2.0.0`

-----
