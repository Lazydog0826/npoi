# SeventyTwo.NPOI

**SeventyTwo.NPOI** is an *unofficial fork* of [NPOI](https://github.com/nissl-lab/npoi) — the .NET port of Apache POI — compiled and published by SeventyTwo.

- **License**: Apache License 2.0. Original code © Nissl Lab, Tony Qu and NPOI contributors. This package is distributed under the same Apache-2.0 license; no additional EULA is attached to these binaries.
- **No affiliation**: this package is not affiliated with, endorsed by, or connected to the original NPOI authors.
- **Source**: built from the NPOI master branch (post `2.8.1-rc2`).

## Why this fork exists

Official NPOI binary releases and NuGet packages (2.8.0+) ship with an [Open Source Maintenance Fee](https://opensourcemaintenancefee.org/consumers/) EULA requiring revenue-generating organizations to pay a fee. This package is compiled directly from the Apache-2.0 licensed source code, so that EULA does not apply here. If your organization benefits from NPOI, please consider [sponsoring the original author](https://github.com/sponsors/tonyqus).

## Usage

The assemblies are binary-compatible with the official NPOI packages (same assembly names and `NPOI.*` namespaces). Replace the package reference with `SeventyTwo.NPOI` and rebuild your project.

Target frameworks: `net472`, `netstandard2.0`, `netstandard2.1`, `net8.0`, `net10.0`.

## Attribution

- Original project: https://github.com/nissl-lab/npoi (Apache-2.0)
- The full Apache License 2.0 text is included at the package root (`LICENSE`).
- Code modifications in this build: none (package identity/metadata only). Any future code changes will be noted in release notes.
