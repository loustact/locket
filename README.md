# Locket

[![Tests](https://github.com/loustact/locket/actions/workflows/ci.yml/badge.svg)](https://github.com/loustact/locket/actions/workflows/ci.yml) [![Excavator](https://github.com/loustact/locket/actions/workflows/excavator.yml/badge.svg)](https://github.com/loustact/locket/actions/workflows/excavator.yml)

Personal bucket full off frankenstein'd manifests for [Scoop](https://scoop.sh) when I need programs unavailable at official buckets.

## Usage

```powershell
To install: scoop bucket add locket https://github.com/loustact/locket/

To add/remove manifests: scoop install/uninstall locket/<manifest>

To uninstall: scoop bucket rm locket
```

If manifest name does not conflict with other buckets being used, you can also do `scoop install/uninstall <manifest>`

## Credits

For credits for manifests taken from other buckets, please see the dedicated [file](./CREDITS.md).
