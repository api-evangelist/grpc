---
title: "Blog: Visualizing gRPC Language Stacks"
url: "https://grpc.io/blog/grpc-stacks/"
date: "2018-12-11"
author: ""
feed_url: "https://grpc.io/blog/index.xml"
---
Here is a high level overview of the gRPC Stacks. Each of the 10 default languages supported by gRPC has multiple layers, allowing you to customize what pieces you want in your application. There are three main stacks in gRPC: C-core, Go, and Java. Most of the languages are thin wrappers on top of the C-based gRPC core library: Wrapped Languages: For example, a Python application calls into the generated Python stubs. These calls pass through interceptors, and into the wrapping library where the calls are translated into C calls.
