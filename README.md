# Porter ()
A package manager for Kubernetes that uses Cloud Native Application Bundles (CNAB) to package and deploy applications along with their dependencies and configuration.

**URL:** [Visit APIs.json URL](https://porter.sh/)

## Tags:

 - Kubernetes, Package Manager, CNAB, DevOps, Cloud Native

## Timestamps

- **Created:** 2025 
- **Modified:** 2026-03-18 

## APIs

### Porter Bundle API
Core API for authoring, building, distributing, and installing Cloud Native Application Bundles (CNAB) using Porter. Bundles package application artifacts, client tools, configuration, and deployment logic into a single distributable installer that can be run with a single command.

**Human URL:** [https://porter.sh/docs/](https://porter.sh/docs/)


#### Tags:

 - CNAB, Kubernetes, Package Manager, Cloud Native, DevOps

#### Properties

- [Documentation](https://porter.sh/docs/)
- [Getting Started](https://porter.sh/docs/learn/)
- [OpenAPI](openapi/porter-bundle-openapi.yml)
- [JSONSchema](json-schema/porter-manifest-schema.json)

### Porter Mixins API
Extension interface for building and using mixins, which are the building blocks for authoring Porter bundles. Mixins provide pre-built integrations for interacting with tools and services such as Kubernetes, Helm, Terraform, and Docker Compose from within a bundle action.

**Human URL:** [https://porter.sh/mixins/](https://porter.sh/mixins/)


#### Tags:

 - CNAB, Mixins, Plugins, Extensions, DevOps

#### Properties

- [Documentation](https://porter.sh/mixins/)
- [Reference](https://porter.sh/docs/development/dev-a-mixin/)

### Porter Plugins API
Plugin interface that allows extending Porter's core functionality, such as storing installation data, credential sets, and parameter sets in external systems like cloud storage instead of the local filesystem. Plugins reimplement Porter's default behavior to integrate with enterprise or cloud infrastructure.

**Human URL:** [https://porter.sh/docs/introduction/concepts-and-components/mixins-vs-plugins/](https://porter.sh/docs/introduction/concepts-and-components/mixins-vs-plugins/)


#### Tags:

 - CNAB, Plugins, Extensions, Cloud Native, DevOps

#### Properties

- [Documentation](https://porter.sh/docs/introduction/concepts-and-components/mixins-vs-plugins/)

## Common Properties

- [Website](https://porter.sh/)
- [JSON-LD](json-ld/porter-context.jsonld)
- [JSONSchema](json-schema/porter-manifest-schema.json)
- [Documentation](https://porter.sh/docs/)
- [Getting Started](https://porter.sh/docs/learn/)
- [GitHub Organization](https://github.com/getporter)
- [GitHubRepository](https://github.com/getporter/porter)
- [Community](https://porter.sh/community/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
