# gRPC

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

gRPC is a high-performance, open-source universal RPC framework that uses HTTP/2 for transport, Protocol Buffers as the interface description language, and provides features such as authentication, bidirectional streaming and flow control, blocking or nonblocking bindings, and cancellation and timeouts. Originally developed at Google, it is now a CNCF project.

**Areas:** CNCF · HTTP/2 · Microservices · Protocol Buffers · RPC

## gRPC on APIs.io

Everything profiled for gRPC is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/grpc/](https://apis.io/providers/grpc/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [gRPC Core Framework](https://apis.io/apis/grpc/grpc-core/) — The gRPC core framework defines the RPC protocol, service definition format using Protocol Buffers, and the fundamental call lifecycle including unary,…
- [Protocol Buffers Service Definition Schema](https://apis.io/apis/grpc/protobuf-service-definition/) — JSON Schema for Protocol Buffers service definition format (.proto files). Describes the structure of gRPC service declarations, RPC methods, message types,…
- [gRPC Health Checking Service](https://apis.io/apis/grpc/grpc-health-checking/) — The gRPC Health Checking Protocol defines a standard service that gRPC servers implement to expose health status information to clients and load balancers.…
- [gRPC Server Reflection](https://apis.io/apis/grpc/grpc-server-reflection/) — The gRPC Server Reflection Protocol allows gRPC servers to declare the protobuf-defined APIs they export over a standardized RPC service, including all…
- [gRPC Channelz API](https://apis.io/apis/grpc/grpc-channelz-api/) — Channelz service for runtime introspection of gRPC channels, subchannels, servers, and sockets.
- [gRPC Health Checking API](https://apis.io/apis/grpc/grpc-health-checking-api/) — gRPC Health Checking Protocol endpoints for monitoring service availability and readiness.
- [gRPC Reflection API](https://apis.io/apis/grpc/grpc-reflection-api/) — Server Reflection service for runtime discovery of available gRPC services and their definitions.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Collections (3)

Postman and Open Collection request collections.

- [gRPC-Web Proxy Channelz API](https://apis.io/collections/grpc/open-grpc-channelz-api/)
- [gRPC-Web Proxy Health Checking API](https://apis.io/collections/grpc/open-grpc-health-checking-api/)
- [gRPC-Web Proxy Reflection API](https://apis.io/collections/grpc/open-grpc-reflection-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [gRPC — jsonschema rules](https://apis.io/rules/grpc/grpc-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Grpc Domain Security](https://apis.io/security/grpc/grpc-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Grpc Plans Pricing](https://apis.io/plans/grpc/grpc-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Grpc Rate Limits](https://apis.io/rate-limits/grpc/grpc-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Grpc Finops](https://apis.io/finops/grpc/grpc-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://grpc.io/)
- [Documentation](https://grpc.io/docs/)
- [Getting started](https://grpc.io/docs/languages/)
- [Changelog](https://github.com/grpc/grpc/releases)
- [Blog](https://grpc.io/blog/)
- [GitHub](https://github.com/grpc)

## API Evangelist rating

**Kin Score 42.6** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 55.3 |
| Contract governance | 9.8 |
| Operational transparency | 36.8 |
| Developer ergonomics | 52.4 |
| Access clarity | 7.9 |

**Agent readiness 21.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/grpc/](https://apis.io/providers/grpc/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for gRPC: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/grpc/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
