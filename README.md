# Stainless (stainless-api)

Stainless is a New York-based developer-tools company that turns an OpenAPI specification into a portfolio of high-quality, idiomatic SDKs, reference documentation, MCP servers, CLIs, and Terraform providers. The platform was founded by veterans of Stripe, Heroku, and Twilio with the explicit goal of bringing Stripe-quality developer experience to any API, and is used by AI-platform and infrastructure companies including OpenAI, Anthropic, Google DeepMind, Cloudflare, Modern Treasury, Perplexity, Replicate, LangChain, Beeper, and Runway. Stainless supports nine target languages today (TypeScript, Python, Go, Java, Kotlin, Ruby, PHP, C#, plus a CLI) and publishes generated code under the Apache 2.0 license into customer-owned GitHub repositories. The company exposes its own platform as a REST API at api.stainless.com (v0), with endpoints for managing organizations, projects, branches, builds, and the current user, plus a build-compare endpoint and matching client libraries. Stainless also ships the Stainless Studio (web-based config UI), the Stainless CLI, a Language Server, GitHub member sync, breaking-change detection, SSO, audit logs, and integrations with documentation hosts (Bump.sh, GitBook, Mintlify, ReadMe).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/stainless-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/stainless-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- SDK Generation
- OpenAPI
- API Tooling
- Developer Experience
- MCP
- Model Context Protocol
- Documentation
- Code Generation
- Terraform Provider
- API Reference
- DevTools
- API First

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Stainless Platform API

The Stainless Platform API is a REST API for programmatically managing Stainless projects, branches, and SDK builds. It exposes the same primitives that power the Stainless Studio web UI and CLI, allowing customers to create and update projects, manage branches that track different OpenAPI versions, trigger and inspect builds across the nine supported languages, compare two builds, and read organization and current-user information. The API is served from api.stainless.com under the v0 namespace and is consumed via official Stainless client libraries in TypeScript, Python, Go, Java, Kotlin, Ruby, PHP, and C#, plus the Stainless CLI.

- **Human URL:** [https://www.stainless.com/docs/api-reference](https://www.stainless.com/docs/api-reference)
- **Base URL:** `https://api.stainless.com/v0`

#### Tags

- SDK Generation
- OpenAPI
- Builds
- Projects
- Branches
- Developer Platform

#### Properties

- [Documentation](https://www.stainless.com/docs)
- [API Reference](https://www.stainless.com/docs/api-reference)
- [Getting Started](https://www.stainless.com/docs/get-started)
- [GitHub Organization](https://github.com/stainless-api)
- [Type Script S D K](https://github.com/stainless-api/stainless-node)
- [Python S D K](https://github.com/stainless-api/stainless-python)
- [Go S D K](https://github.com/stainless-api/stainless-go)
- [Java S D K](https://github.com/stainless-api/stainless-java)
- [Kotlin S D K](https://github.com/stainless-api/stainless-kotlin)
- [Ruby S D K](https://github.com/stainless-api/stainless-ruby)
- [C L I](https://github.com/stainless-api/stainless-cli)
- [M C P Front](https://github.com/stainless-api/mcp-front)
- [Postman Collection](collections/stainless-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/stainless-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.stainless.com)
- [Documentation](https://www.stainless.com/docs)
- [API Reference](https://www.stainless.com/docs/api-reference)
- [Pricing](https://www.stainless.com/pricing)
- [Customers](https://www.stainless.com/customers)
- [Blog](https://www.stainless.com/blog)
- [Changelog](https://www.stainless.com/changelog)
- [Careers](https://www.stainless.com/careers)
- [Contact](https://www.stainless.com/contact)
- [Studio](https://app.stainless.com)
- [GitHub Organization](https://github.com/stainless-api)
- [Type Script S D K](https://github.com/stainless-api/stainless-node)
- [Python S D K](https://github.com/stainless-api/stainless-python)
- [C L I](https://github.com/stainless-api/stainless-cli)
- [M C P Front](https://github.com/stainless-api/mcp-front)
- [S T L A P I](https://github.com/stainless-api/stl-api)
- [Email](mailto:support@stainless.com)
- [LinkedIn](https://www.linkedin.com/company/stainless-api)
- [Twitter](https://twitter.com/StainlessAPI)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
