# scoop

[![Tests](https://github.com/bruyeres/scoop/actions/workflows/ci.yml/badge.svg)](https://github.com/bruyeres/scoop/actions/workflows/ci.yml) [![Excavator](https://github.com/bruyeres/scoop/actions/workflows/excavator.yml/badge.svg)](https://github.com/bruyeres/scoop/actions/workflows/excavator.yml)

Personal [Scoop](https://scoop.sh) bucket.

## Manifests

| Manifest | Description |
| --- | --- |
| [foobar2000](bucket/foobar2000.json) | Advanced freeware audio player (portable mode) |
| [mkbrr](bucket/mkbrr.json) | Fast CLI tool to create, modify and inspect torrent files |
| [mkbrr-gui](bucket/mkbrr-gui.json) | Desktop GUI for mkbrr |

## How do I install these manifests?

```pwsh
scoop bucket add bruyeres https://github.com/bruyeres/scoop
scoop install bruyeres/<manifestname>
```
