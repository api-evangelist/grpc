---
title: "Blog: Announcing out-of-the-box support for gRPC in the Flatbuffers serialization library"
url: "https://grpc.io/blog/grpc-flatbuffers/"
date: "Thu, 17 Aug 2017 00:00:00 +0000"
author: ""
feed_url: "https://grpc.io/blog/index.xml"
---
The recent release of Flatbuffers version 1.7 introduced truly zero-copy support for gRPC out of the box. Flatbuffers is a serialization library that allows you to access serialized data without first unpacking it or allocating any additional data structures. It was originally designed for games and other resource constrained applications, but is now finding more general use, both by teams within Google and in other companies such as Netflix and Facebook.
