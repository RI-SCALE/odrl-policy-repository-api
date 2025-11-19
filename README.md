# ODRL Policy Repository API

This repository contains the OpenAPI specification for an ODRL-based Policy
Repository API. The API provides a standard interface for creating, managing,
validating, and retrieving access policies expressed in **ODRL (W3C Open Digital
Rights Language)**.

The specification is designed to be deployment-agnostic and can be integrated as:

- an extension to an existing IAM system, or
- a standalone microservice within an Authorisation Framework.

The work originates from the **RI-SCALE WP4 Authorisation Framework** activities
and contributes to the definition of interoperable, policy-based authorisation
mechanisms.

## Contents

- `odrl-policy-repository-api.yaml` — OpenAPI 3.1 specification for the API
- Additional documentation or examples may be added as the API evolves

## Key Features

- Management of ODRL policies in JSON-LD format
- Policy lifecycle (draft, published, deprecated)
- Optional versioning
- Query and filtering capabilities
- Server-side validation of ODRL documents
- OAuth2-based access control (scope/role-based)

## Status

The specification is an initial public draft and will evolve through feedback
from RI-SCALE WP4 partners and the wider AAI/Authorisation community.

## License

Apache 2.0
