# kapa.ai (kapa-ai)

kapa.ai is an AI assistant and answer platform that turns technical documentation, GitHub content, forums, and developer products into a retrieval-augmented chat experience. The kapa.ai Query API lets teams ask questions, run threaded conversations with streaming answers, perform semantic retrieval and search, and pull analytics over projects and threads via a REST interface authenticated with an X-API-KEY header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kapa-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kapa-ai/refs/heads/main/apis.yml)

## Tags

- AI
- Answer Engine
- RAG
- Documentation
- Developer Tools

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### kapa.ai Query Chat API

Ask a project's kapa.ai instance a question and receive a retrieval-augmented answer with relevant sources. Each chat call creates a new Thread; both standard and Server-Sent-Event style streamed variants are available, plus a custom-chat endpoint for supplying your own context.

- **Human URL:** [https://docs.kapa.ai/api/reference/query-v-1-projects-chat](https://docs.kapa.ai/api/reference/query-v-1-projects-chat)
- **Base URL:** `https://api.kapa.ai/query/v1`

#### Tags

- Chat
- Query
- RAG
- Streaming

#### Properties

- [Documentation](https://docs.kapa.ai/api/quickstart)
- [API Reference](https://docs.kapa.ai/api/reference/query-v-1-projects-chat)
- [OpenAPI](openapi/kapa-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kapa-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kapa-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### kapa.ai Threads Conversations API

List and retrieve Thread objects and continue a multi-turn conversation by chatting in an existing thread, with standard and streamed follow-up variants and a feedback endpoint for upserting reactions on a question/answer.

- **Human URL:** [https://docs.kapa.ai/api/reference](https://docs.kapa.ai/api/reference)
- **Base URL:** `https://api.kapa.ai/query/v1`

#### Tags

- Threads
- Conversations
- Follow Up

#### Properties

- [Documentation](https://docs.kapa.ai/analytics/conversations)
- [API Reference](https://docs.kapa.ai/api/reference)
- [OpenAPI](openapi/kapa-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kapa-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kapa-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### kapa.ai Search and Retrieval API

Semantic retrieval that returns the most relevant chunks from a project's ingested knowledge sources without LLM generation, intended to supply context to external LLMs and agents, alongside a deprecated keyword search endpoint.

- **Human URL:** [https://docs.kapa.ai/api/reference/query-v-1-projects-retrieval](https://docs.kapa.ai/api/reference/query-v-1-projects-retrieval)
- **Base URL:** `https://api.kapa.ai/query/v1`

#### Tags

- Search
- Retrieval
- Semantic

#### Properties

- [Documentation](https://docs.kapa.ai/api/reference/query-v-1-projects-retrieval)
- [OpenAPI](openapi/kapa-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kapa-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kapa-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### kapa.ai Projects API

Retrieve a project and enumerate the integrations and ingested sources configured for it, scoping every other Query API call to a project_id.

- **Human URL:** [https://docs.kapa.ai/api/overview](https://docs.kapa.ai/api/overview)
- **Base URL:** `https://api.kapa.ai`

#### Tags

- Projects
- Integrations
- Sources

#### Properties

- [Documentation](https://docs.kapa.ai/api/overview)
- [OpenAPI](openapi/kapa-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kapa-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kapa-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### kapa.ai Analytics API

Read usage and quality analytics for a project - activity, question/answers, end users, coverage-gap periods, and top-question periods - to understand how the AI assistant is performing against the knowledge base.

- **Human URL:** [https://docs.kapa.ai/api/reference](https://docs.kapa.ai/api/reference)
- **Base URL:** `https://api.kapa.ai/query/v1`

#### Tags

- Analytics
- Coverage Gaps
- Top Questions

#### Properties

- [Documentation](https://docs.kapa.ai/api/reference)
- [OpenAPI](openapi/kapa-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kapa-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kapa-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/kapa-ai)
- [LinkedIn](https://www.linkedin.com/company/kapa-ai)
- [Website](https://www.kapa.ai)
- [Documentation](https://docs.kapa.ai)
- [Plans](plans/kapa-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/kapa-ai-rate-limits.yml)
- [Fin Ops](finops/kapa-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
