# gRPC (grpc)
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
