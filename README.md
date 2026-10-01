# homebrew-tap

Homebrew formulae for service-dept tools.

## Install

```bash
brew install service-dept/tap/op-img
```

| Formula | Description |
|---|---|
| [`op-img`](Formula/op-img.rb) | Composable image manipulation CLI ([source](https://github.com/service-dept/op-img)) |

## Updating a formula

`op-img`'s formula is kept and tested in the op-img repository first, at
`Formula/op-img.rb`. After a release, update it there, then copy the same URL
and checksum here. The `Tests` workflow installs and tests every change on
macOS and Linux, and again every Monday.
