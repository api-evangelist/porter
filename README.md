# Porter (porter)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
