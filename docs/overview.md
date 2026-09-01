# Overview

[简体中文](overview.zh-CN.md) | [Docs Index](README.md)

## Purpose

Streaming XML token codecs for Gnalloy ByteBuf and pipeline integration.

This module sits above transports and below application handlers. It translates bytes or Gnalloy messages into protocol objects, and translates outbound protocol objects back to bytes. It does not open sockets or own EventLoops.

## Repository Identity

- Module path: `gnalloy.org/codec-xml`
- GitHub repository: `github.com/gnalloy/codec-xml`
- Default branch: `dev`
- License: Apache-2.0

## Package Map
- `gnalloy.org/codec-xml` (`xml`)

## Direct Gnalloy Dependencies
- `gnalloy.org/gnalloy`

## Direct Dependents in the Current Module Plan
- No repository in the current module plan depends on this module directly.

## Architecture Position

Gnalloy keeps the core small and dependency-light. This repository is a replaceable module around one responsibility, connected through explicit Go packages instead of runtime discovery.

## Compatibility

The public import path is `gnalloy.org/codec-xml`. Until the first stable tag is published, use `@dev` or an explicit pseudo-version selected by your dependency policy.
