# Porter (porter)

A package manager for Kubernetes that uses Cloud Native Application Bundles (CNAB) to package and deploy applications along with their dependencies and configuration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/porter/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/porter/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Cloud Native
- CNAB
- DevOps
- Kubernetes
- Package Manager

## Timestamps

- **Created:** 2025
- **Modified:** 2026-05-19

## APIs

### Porter Bundle API

Core API for authoring, building, distributing, and installing Cloud Native Application Bundles (CNAB) using Porter. Bundles package application artifacts, client tools, configuration, and deployment logic into a single distributable installer that can be run with a single command.

- **Human URL:** [https://porter.sh/docs/](https://porter.sh/docs/)
- **Base URL:** `https://porter.sh`

#### Tags

- Cloud Native
- CNAB
- DevOps
- Kubernetes
- Package Manager

#### Properties

- [Documentation](https://porter.sh/docs/)
- [Getting Started](https://porter.sh/docs/learn/)
- [OpenAPI](openapi/porter-bundle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/porter-bundle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/porter-bundle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/porter-manifest-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Porter Mixins API

Extension interface for building and using mixins, which are the building blocks for authoring Porter bundles. Mixins provide pre-built integrations for interacting with tools and services such as Kubernetes, Helm, Terraform, and Docker Compose from within a bundle action.

- **Human URL:** [https://porter.sh/mixins/](https://porter.sh/mixins/)
- **Base URL:** `https://porter.sh`

#### Tags

- CNAB
- DevOps
- Extensions
- Mixins
- Plugins

#### Properties

- [Documentation](https://porter.sh/mixins/)
- [Reference](https://porter.sh/docs/development/dev-a-mixin/)
- [Postman Collection](collections/porter-bundle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/porter-bundle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Porter Plugins API

Plugin interface that allows extending Porter's core functionality, such as storing installation data, credential sets, and parameter sets in external systems like cloud storage instead of the local filesystem. Plugins reimplement Porter's default behavior to integrate with enterprise or cloud infrastructure.

- **Human URL:** [https://porter.sh/docs/introduction/concepts-and-components/mixins-vs-plugins/](https://porter.sh/docs/introduction/concepts-and-components/mixins-vs-plugins/)
- **Base URL:** `https://porter.sh`

#### Tags

- Cloud Native
- CNAB
- DevOps
- Extensions
- Plugins

#### Properties

- [Documentation](https://porter.sh/docs/introduction/concepts-and-components/mixins-vs-plugins/)
- [Postman Collection](collections/porter-bundle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/porter-bundle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/porterrun)
- [Website](https://porter.sh/)
- [JSON-LD](json-ld/porter-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/porter-manifest-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Documentation](https://porter.sh/docs/)
- [Getting Started](https://porter.sh/docs/learn/)
- [GitHub Organization](https://github.com/getporter)
- [GitHub Repository](https://github.com/getporter/porter)
- [Community](https://porter.sh/community/)
- [Integrations](https://porter.sh/docs/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
