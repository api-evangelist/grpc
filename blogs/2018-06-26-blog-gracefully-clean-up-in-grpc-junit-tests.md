---
title: "Blog: Gracefully clean up in gRPC JUnit tests"
url: "https://grpc.io/blog/graceful-cleanup-junit-tests/"
date: "Tue, 26 Jun 2018 00:00:00 +0000"
author: ""
feed_url: "https://grpc.io/blog/index.xml"
---
It is best practice to always clean up gRPC resources such as client channels, servers, and previously attached Contexts whenever they are no longer needed. This is even true for JUnit tests, because otherwise leaked resources may not only linger in your machine forever, but also interfere with subsequent tests. A not-so-bad case is that subsequent tests can’t pass because of a leaked resource from the previous test.
