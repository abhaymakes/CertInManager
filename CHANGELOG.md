# Changelog

All notable changes to this project will be documented in this file.

The format is based on Keep a Changelog and this project adheres to Semantic Versioning.

## [Unreleased]

### Added

### Changed

### Fixed

---

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
