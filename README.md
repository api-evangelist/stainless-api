# Stainless (stainless-api)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
