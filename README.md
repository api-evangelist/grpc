# gRPC (grpc)

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

gRPC is a high-performance, open-source universal RPC framework that uses HTTP/2 for transport, Protocol Buffers as the interface description language, and provides features such as authentication, bidirectional streaming and flow control, blocking or nonblocking bindings, and cancellation and timeouts. Originally developed at Google, it is now a CNCF project.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/grpc/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - RPC, Protocol Buffers, HTTP/2, Microservices, CNCF

## Timestamps

- **Created:** 2025 
- **Modified:** 2026-03-18 

## APIs

### gRPC-Web Proxy API
OpenAPI specification for gRPC-Web proxy endpoints covering health checking, server reflection, and channelz introspection services exposed over HTTP for browser-based and REST clients.

**Human URL:** [https://grpc.io/docs/platforms/web/](https://grpc.io/docs/platforms/web/)


#### Tags:

 - Health Checking, Reflection, Channelz, gRPC-Web

#### Properties

- [OpenAPI](openapi.yml)
- [Documentation](https://grpc.io/docs/platforms/web/)
- [Reference](https://grpc.io/docs/platforms/web/basics/)
- [JSONSchema](json-schema.yml)

### gRPC Core Framework
The gRPC core framework defines the RPC protocol, service definition format using Protocol Buffers, and the fundamental call lifecycle including unary, server-streaming, client-streaming, and bidirectional streaming patterns over HTTP/2. It is the foundational specification implemented by all language-specific gRPC SDKs.

**Human URL:** [https://grpc.io/docs/what-is-grpc/introduction/](https://grpc.io/docs/what-is-grpc/introduction/)


#### Tags:

 - RPC, Protocol Buffers, HTTP/2, Streaming

#### Properties

- [Documentation](https://grpc.io/docs/what-is-grpc/introduction/)
- [Reference](https://grpc.io/docs/what-is-grpc/core-concepts/)
- [Authentication](https://grpc.io/docs/guides/auth/)
- [GitHubRepository](https://github.com/grpc/grpc)
- [JSONSchema](service-config-schema.json)
- [JSONSchema](json-schema.yml)
- [JSON-LD](context.jsonld)

### gRPC Health Checking Service
The gRPC Health Checking Protocol defines a standard service that gRPC servers implement to expose health status information to clients and load balancers. Servers implement the Health service proto to report per-service readiness, and clients can configure automatic health-check-based connection management.

**Human URL:** [https://grpc.io/docs/guides/health-checking/](https://grpc.io/docs/guides/health-checking/)


#### Tags:

 - Health Checking, Observability, Load Balancing

#### Properties

- [Documentation](https://grpc.io/docs/guides/health-checking/)
- [Reference](https://github.com/grpc/grpc-proto/blob/master/grpc/health/v1/health.proto)
- [GitHubRepository](https://github.com/grpc/grpc-proto)
- [AsyncAPI](asyncapi.yml)

### gRPC Server Reflection
The gRPC Server Reflection Protocol allows gRPC servers to declare the protobuf-defined APIs they export over a standardized RPC service, including all types referenced by request and response messages. This enables command-line debugging tools and clients to dynamically discover and invoke gRPC services without pre-compiled stubs.

**Human URL:** [https://grpc.io/docs/guides/reflection/](https://grpc.io/docs/guides/reflection/)


#### Tags:

 - Reflection, Service Discovery, Debugging

#### Properties

- [Documentation](https://grpc.io/docs/guides/reflection/)
- [Reference](https://github.com/grpc/grpc/blob/master/doc/server-reflection.md)
- [AsyncAPI](asyncapi.yml)

## Common Properties

- [Website](https://grpc.io/)
- [Documentation](https://grpc.io/docs/)
- [Getting Started](https://grpc.io/docs/languages/)
- [GitHub Organization](https://github.com/grpc)
- [Blog](https://grpc.io/blog/)
- [Community](https://grpc.io/community/)
- [FAQ](https://grpc.io/docs/what-is-grpc/faq/)
- [SDKs](https://grpc.io/docs/languages/)
- [Change Log](https://github.com/grpc/grpc/releases)
- [JSONSchema](json-schema.yml)
- [JSONSchema](service-config-schema.json)
- [AsyncAPI](asyncapi.yml)
- [JSON-LD](context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
