# SmartRecruiters

SmartRecruiters is a talent acquisition platform providing a comprehensive suite of REST APIs for recruiting, hiring, and workforce management. The platform enables organizations to manage job postings, candidate applications, assessments, interviews, and offers through a unified API ecosystem.

## APIs

| API | Description |
|-----|-------------|
| [Posting API](openapi/smartrecruiters-posting-openapi.yml) | Public job postings for career sites and application submission |
| [Job API](openapi/smartrecruiters-jobs-openapi.yml) | Internal job lifecycle management from creation through hire |
| [Candidate API](openapi/smartrecruiters-candidates-openapi.yml) | Candidate profile management, import, and tracking |

## Artifacts

### OpenAPI Specifications
- [smartrecruiters-posting-openapi.yml](openapi/smartrecruiters-posting-openapi.yml) — Posting API (career sites, applications)
- [smartrecruiters-jobs-openapi.yml](openapi/smartrecruiters-jobs-openapi.yml) — Job API (job lifecycle management)
- [smartrecruiters-candidates-openapi.yml](openapi/smartrecruiters-candidates-openapi.yml) — Candidate API (profile management)

### Capabilities
- [talent-acquisition.yaml](capabilities/talent-acquisition.yaml) — Unified talent acquisition workflow (jobs + candidates + postings)

#### Shared Definitions
- [capabilities/shared/posting-api.yaml](capabilities/shared/posting-api.yaml) — Posting API capability
- [capabilities/shared/jobs-api.yaml](capabilities/shared/jobs-api.yaml) — Job API capability
- [capabilities/shared/candidates-api.yaml](capabilities/shared/candidates-api.yaml) — Candidate API capability

### Rules
- [smartrecruiters-rules.yml](rules/smartrecruiters-rules.yml) — Spectral ruleset for SmartRecruiters API conventions

### JSON Schema
- [smartrecruiters-job-schema.json](json-schema/smartrecruiters-job-schema.json) — Job entity schema
- [smartrecruiters-candidate-schema.json](json-schema/smartrecruiters-candidate-schema.json) — Candidate entity schema

### JSON Structure
- [smartrecruiters-job-structure.json](json-structure/smartrecruiters-job-structure.json) — Job object structure documentation

### JSON-LD
- [smartrecruiters-context.jsonld](json-ld/smartrecruiters-context.jsonld) — Linked data context mapping to schema.org

### Examples
- [smartrecruiters-list-postings-example.json](examples/smartrecruiters-list-postings-example.json) — List job postings request/response
- [smartrecruiters-submit-application-example.json](examples/smartrecruiters-submit-application-example.json) — Submit application request/response

### Vocabulary
- [smartrecruiters-vocabulary.yml](vocabulary/smartrecruiters-vocabulary.yml) — Domain vocabulary, statuses, and conventions

## Authentication

- **API Key** — `X-SmartToken` header for single-org integrations
- **OAuth 2.0** — Authorization Code and Client Credentials for multi-tenant Marketplace apps

## Developer Resources

- [Developer Portal](https://developers.smartrecruiters.com/)
- [API Platform Overview](https://developers.smartrecruiters.com/docs/the-smartrecruiters-platform)
- [GitHub Organization](https://github.com/smartrecruiters)
- [Marketplace](https://www.smartrecruiters.com/marketplace/)
