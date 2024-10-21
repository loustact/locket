> [!IMPORTANT]
> To anyone who used the repo beforehand, I stupidly deleted the original as I became deranged troubleshooting Zen Browser's auto-update (finally fixed :D). Please re-add the repo if you wish to still use it. Uninstalling and reinstalling manifests shouldn't affect your browser profiles.

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
