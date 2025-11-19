# Changelog
All notable changes to this project will be documented in this file.

The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and this project adheres
to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.0.1] - 2025-11-19
### Added
- Initial draft of the ODRL Policy Repository API specification.
- OpenAPI 3.1 definition (`odrl-policy-repository-api.yaml`).
- Policy CRUD endpoints (`/policies`, `/policies/{id}`).
- Policy validation endpoint (`/policies/{id}/validate`).
- RFC 7807-compliant error model for problem responses.
- OAuth2-based access control model (read/write/admin scopes).
- Initial repository documentation (`README.md`).
- Base project structure and recommended `.gitignore` and `.gitattributes`.

[0.0.1]: https://github.com/RI-SCALE/odrl-policy-repository-api/releases/tag/v0.0.1
