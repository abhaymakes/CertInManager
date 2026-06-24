# Changelog

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog and this project adheres to Semantic Versioning.

## [Unreleased]

### Added

### Changed

### Fixed

---

## [1.1.0] - 2026-06-24

### Added

* Automatic conversion of URLs into clickable hyperlinks in generated DOCX reports.
* Automatic conversion of email addresses into clickable hyperlinks in generated DOCX reports.
* Employee suggestions/autocomplete support for selected form fields.
* Placeholder text across various form inputs to improve usability.
* Textarea support for Executive Summary asset entries.

### Changed

* Replaced single-line text inputs with textareas where multiline content is expected.
* Updated CertIn DOCX templates to better align generated table widths with template formatting.
* Improved handling of multiline content throughout report generation workflows.

### Fixed

* Fixed Executive Summary textarea content not being included in generated reports.
* Fixed date formatting inconsistencies across form inputs and generated documents.
* Fixed affected assets not being displayed in vulnerability tables due to an incorrect variable reference.
* Fixed positioning of the Add Vulnerability button to reduce unnecessary scrolling during report creation.
* Removed redundant server-side image border processing, preventing duplicate borders in generated DOCX reports.
* Fixed table width formatting inconsistencies in CertIn report templates.


## [1.0.0]

### Added

* Flask-based web interface for VAPT report management.
* Project creation, modification, and deletion functionality.
* Local SQLite data storage using SQLAlchemy.
* User authentication and session management.
* Supabase-backed user account support.
* Vulnerability management workflow.
* Appendix management workflow.
* Proof-of-concept image upload and storage.
* DOCX report generation using DOCX templates.
* Dynamic report content generation.
* Vulnerability indexing and report organization.
* OWASP category mapping support.
* Support for vulnerability proof-of-concept screenshots.
* Administrative user management capabilities.

### Security

* Source code obfuscation using PyArmor for distributed builds.
* Secure session cookie configuration.
* Password hashing and verification mechanisms.
* Restricted image upload validation.

### Fixed

* Various stability and reliability improvements identified during initial development and testing.
