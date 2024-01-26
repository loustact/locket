# Locket

[![Tests](https://github.com/loustact/loucket/actions/workflows/ci.yml/badge.svg)](https://github.com/loustact/loucket/actions/workflows/ci.yml) [![Excavator](https://github.com/loustact/locket/actions/workflows/excavator.yml/badge.svg)](https://github.com/loustact/locket/actions/workflows/excavator.yml)

Personal bucket for [Scoop](https://scoop.sh) when I need programs unavailable at official buckets.

## Usage

```powershell
To install: scoop bucket add locket https://github.com/loustact/locket/

To add/remove manifests: scoop install/uninstall locket/<manifest>

To uninstall: scoop bucket rm locket
```

If manifest name does not conflict with other buckets being used, you can also do `scoop install/uninstall <manifest>`

<details>
<summary><h2>Credits</h2></summary>

- [RU-School](https://github.com/alealexpro100/ru-school-scoop)
	- License: `Unlicense`
	- Manifests:
		- Thorium
		- Thorium-AVX2

- [Dank-Scoop](https://github.com/brian6932/dank-scoop)
	- License: `Unlicense`
	- Manifests:
		- Mercury
		- Mercury-AVX (Based off of the other manifest)

- [Extras](https://github.com/ScoopInstaller/Extras)
    - License: `Unlicense`
	- Manifests (Took install parameters):
		- Thorium
		- Thorium-AVX2

</details>