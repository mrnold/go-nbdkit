# go-nbdkit
Importable Golang bindings for nbdkit, extracted from official libguestfs.org releases.

This repository includes all the auto-generated golang files from the official libguestfs.org releases of nbdkit, so that the bindings can be imported with `go.mod` or `go get`. This is intended as a temporary measure to allow [CDI](https://github.com/kubevirt/containerized-data-importer) to make use of nbdkit plugins for functional tests.

Requires a minimum of nbdkit version 1.20.
