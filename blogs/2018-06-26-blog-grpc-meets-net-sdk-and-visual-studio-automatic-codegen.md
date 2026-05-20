---
title: "Blog: gRPC Meets .NET SDK And Visual Studio: Automatic Codegen On Build"
url: "https://grpc.io/blog/grpc-dotnet-build/"
date: "Tue, 26 Jun 2018 00:00:00 +0000"
author: ""
feed_url: "https://grpc.io/blog/index.xml"
---
As part of Microsoft’s move towards its cross-platform .NET offering, they have greatly simplified the project file format, and allowed a tight integration of third-party code generators with .NET projects. We are listening, and now proud to introduce integrated compilation of Protocol Buffer and gRPC service .proto files in .NET C# projects starting with the version 1.17 of the Grpc.Tools NuGet package, now available from Nuget.org. You no longer need to use hand-written scripts to generate code from .proto files: The .NET build magic handles this for you.
