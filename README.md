# RESTful Services

Representational State Transfer (REST) services are web services built using the REST architectural style defined by Roy Fielding in 2000. RESTful services use stateless HTTP communication and standard HTTP methods (GET, POST, PUT, DELETE, PATCH) to expose resources. REST is the dominant pattern for modern public APIs and microservices.

## References

| Type | URL |
|------|-----|
| Roy Fielding Dissertation | https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm |
| REST API Standards | https://standards.rest/ |
| RESTful API Best Practices | https://restfulapi.net/ |
| W3C REST Reference | https://www.w3.org/2001/sw/wiki/REST |

## Notable APIs and Services

| Name | Description | URL |
|------|-------------|-----|
| Standards.REST | Curated REST standards and conventions | https://standards.rest/ |
| Zalando REST Guidelines | Widely-adopted REST design guidelines | https://opensource.zalando.com/restful-api-guidelines/ |
| Azure REST API Guidelines | Microsoft REST design guidelines | https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design |
| AWS API Gateway | Amazon managed REST API service | https://aws.amazon.com/api-gateway/ |
| Google Apigee | Google Cloud API management | https://cloud.google.com/apigee |

## Artifacts

### JSON Schemas

| File | Description |
|------|-------------|
| [json-schema/restful-services-resource-schema.json](json-schema/restful-services-resource-schema.json) | Abstract REST resource schema with hypermedia links |
| [json-schema/restful-services-error-schema.json](json-schema/restful-services-error-schema.json) | RFC 7807 Problem Details error response schema |

### JSON Structures

| File | Description |
|------|-------------|
| [json-structure/restful-services-resource-structure.json](json-structure/restful-services-resource-structure.json) | REST resource field reference |

### JSON-LD Context

| File | Description |
|------|-------------|
| [json-ld/restful-services-context.jsonld](json-ld/restful-services-context.jsonld) | JSON-LD context using Hydra, Dublin Core, and schema.org |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/restful-services-vocabulary.yml](vocabulary/restful-services-vocabulary.yml) | Core REST architectural vocabulary |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
