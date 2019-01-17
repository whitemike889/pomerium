<img  height="175" src="./docs/.vuepress/public/logo.svg" alt="logo" align="right" >

# Pomerium

[![Travis CI](https://travis-ci.org/pomerium/pomerium.svg?branch=master)](https://travis-ci.org/pomerium/pomerium)
[![Go Report Card](https://goreportcard.com/badge/github.com/pomerium/pomerium)](https://goreportcard.com/report/github.com/pomerium/pomerium)
[![LICENSE](https://img.shields.io/github/license/pomerium/pomerium.svg)](https://github.com/pomerium/pomerium/blob/master/LICENSE)
[![Docker Automated build](https://img.shields.io/docker/automated/pomerium/pomerium.svg)](https://hub.docker.com/r/pomerium/pomerium/)

Pomerium is a tool for managing secure access to internal applications and resources.

Use Pomerium to:

- provide a unified gateway to internal corporate applications.
- enforce dynamic access policies based on context, identity, and device state.
- deploy mutual authenticated encryption (mTLS).
- aggregate logging and telemetry data.

To learn more about some problems Pomerium attempts to address, check out this repository of [resources] covering zero-trust and BeyondCorp.

## Get started

For instructions on getting started using Pomerium, see our [quick start guide].

## Start developing

Assuming you have a working [Go environment].

```sh
$ go get -d github.com/pomerium/pomerium
$ cd $GOPATH/src/github.com/pomerium/pomerium
$ make
$ source ./env # see env.example
$ ./bin/pomerium -debug
```

[resources]: https://github.com/pomerium/awesome-zero-trust
[go environment]: https://golang.org/doc/install
[quick start guide]: https://www.pomerium.io/guide/
