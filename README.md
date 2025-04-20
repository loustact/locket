# Locket

[![Tests](https://github.com/loustact/locket/actions/workflows/ci.yml/badge.svg)](https://github.com/loustact/locket/actions/workflows/ci.yml) [![Excavator](https://github.com/loustact/locket/actions/workflows/excavator.yml/badge.svg)](https://github.com/loustact/locket/actions/workflows/excavator.yml)

> [!WARNING]
> I don't use this anymore, making it unmaintained. I moved on to [EndeavourOS](https://endeavouros.com/). The bucket won't be archived until everything just breaks. I might only rarely check the bucket, making quick fixes and PRs to be quite hard to merge. At that point, just switch or fork the repo.

Personal bucket full off frankenstein'd manifests from other buckets for [Scoop](https://scoop.sh) when I need programs unavailable at official buckets.

## Usage

```powershell
To install: scoop bucket add locket https://github.com/loustact/locket/

To add/remove manifests: scoop install/uninstall locket/<manifest>

To uninstall: scoop bucket rm locket
```

If manifest name does not conflict with other buckets being used, you can also do `scoop install/uninstall <manifest>`

## Credits

This bucket takes manifests fully or partially from other buckets. The maintainer ensures to check if the provided licenses allow for such. In order to check credits for these buckets, please see the dedicated [file](./CREDITS.md).
