[![Go Report Card](https://goreportcard.com/badge/github.com/nokia/ntt?style=flat-square)](https://goreportcard.com/report/github.com/nokia/ntt)
[![Go Doc](https://img.shields.io/badge/godoc-reference-blue.svg?style=flat-square)](http://godoc.org/github.com/nokia/ntt/ttcn3/syntax)
[![Release](https://img.shields.io/github/release/golang-standards/project-layout.svg?style=flat-square)](https://github.com/nokia/ntt/releases/latest)

# A tool for managing TTCN-3 source code and tests

[TTCN-3](http://www.ttcn-3.org/) (Testing and Test Control Notation Version 3)
is a standardized test specification language that applies to a variety of
application domains and types of testing. It has been used since 2000 in
standardization as well as in industry, research, international projects and
academia.

Unfortunately tool support for TTCN-3 is quite antiquated, which makes
maintaining big TTCN-3 code bases difficult and developing new TTCN-3 tools
expensive.

This project aims to provide maintainable tools and libraries, helping testers
and developers not to reinvent the TTCN-3 wheel:

  * Modern CLI for configuration-management, monitoring, ...
  * Formatting and refactoring tools
  * Wide range IDE support, using [Language Server Protocol](https://microsoft.github.io/language-server-protocol/)
  * Analytics and visualization (cyclomatic complexity, coverage, ...)
  * Code generators (go, erlang, llvm, titan, ...)
  * Support for other IDLs (ASN.1, Protobuf, IDL, ...)

Please note, NTT is still much work in progress. The TTCN-3 parser has been done
and initial CLI interface is beeing implemented. Functionality (and
documentation) will grow over time. If you are interested in contributing, just
create a pull-request. Help is very much appreciated. A contribution guide will
be provided soon.


# Getting Started

If you want to dive into TTCN-3 right now, have a look at [Titan](https://github.com/eclipse/titan.core/),
which already has a lot of features and a huge set of adapters to choose from.

I am currently developing the CLI (k3), so there isn't that much to see, yet.
Assuming you have Go installed you can install k3 using `go get` method:

        go get -u github.com/nokia/ntt/cmd/...


