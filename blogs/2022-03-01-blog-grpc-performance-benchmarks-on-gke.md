---
title: "Blog: gRPC performance benchmarks on GKE"
url: "https://grpc.io/blog/performance-benchmarks-gke/"
date: "2022-03-01"
author: ""
feed_url: "https://grpc.io/blog/index.xml"
---
gRPC performance benchmarks have now been transitioned to run on GKE, with similar results but much increased flexibility. Background gRPC performance testing requires a test driver and workers (one or more clients and a server), as described in gRPC performance benchmarks. Each test may have a different configuration, or scenario, that is passed to the driver and specified as a JSON file. Previously, the driver was run by the continuous integration process, and the workers were run on long-lived GCE VMs.
