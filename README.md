# Golang Build Tooling

This project contains `go.mod` with pinned dependencies for various Golang tools.
These tools are used to build projects like Jaeger. 

The `go.mod` is used by [Cachito](https://github.com/release-engineering/cachito) to
fetch all dependencies needed to compile and install the tools from the source.
