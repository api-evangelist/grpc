---
title: "Blog: gRPC on HTTP/2 Engineering a Robust, High-performance Protocol"
url: "https://grpc.io/blog/grpc-on-http2/"
date: "Mon, 20 Aug 2018 00:00:00 +0000"
author: ""
feed_url: "https://grpc.io/blog/index.xml"
---
In a previous article , we explored how HTTP/2 dramatically increases network efficiency and enables real-time communication by providing a framework for long-lived connections. In this article, we’ll look at how gRPC builds on HTTP/2’s long-lived connections to create a performant, robust platform for inter-service communication. We will explore the relationship between gRPC and HTTP/2, how gRPC manages HTTP/2 connections, and how gRPC uses HTTP/2 to keep connections alive, healthy, and utilized. gRPC Semantics To begin, let’s dive into how gRPC concepts relate to HTTP/2 concepts. gRPC…
