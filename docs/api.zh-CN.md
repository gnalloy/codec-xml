# API 参考

[English](api.md) | [文档索引](README.zh-CN.md)

本清单由本仓库 package 的 `go doc -short` 生成，用于快速查看公共面。精确语义以源码和测试为准。

## 包

### `gnalloy.org/codec-xml`

包名：`xml`

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
