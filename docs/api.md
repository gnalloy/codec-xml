# API Reference

[简体中文](api.zh-CN.md) | [Docs Index](README.md)

This inventory is generated from `go doc -short` for the packages in this repository. It is a quick public-surface map; source files and tests remain the authority for exact semantics.

## Packages

### `gnalloy.org/codec-xml`

Package name: `xml`

```text
var ErrInvalidXML = errors.New("gnalloy/codec/xml: invalid xml")
type Attr struct{ ... }
type CharData struct{ ... }
type Comment struct{ ... }
type Directive struct{ ... }
type EndElement struct{ ... }
type FrameDecoder struct{ ... }
    func NewFrameDecoder(maxFrameLength int) (*FrameDecoder, error)
type ProcInst struct{ ... }
type StartElement struct{ ... }
type TokenDecoder struct{ ... }
    func NewTokenDecoder() *TokenDecoder
```
