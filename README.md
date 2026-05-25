# Tamp.OsvScanner.V2

> Tamp wrapper for Google's osv-scanner (2.x) — cross-ecosystem SCA scanning (npm / PyPI / Cargo / Go / Maven / NuGet / Packagist / Pub) with SARIF or CycloneDX 1.5 output for the Tamp security pipeline.

| Package | Status |
|---|---|
| `Tamp.OsvScanner.V2` | 1.11.2 (post-migration from main `tamp`) |

## Install

```bash
dotnet add package Tamp.OsvScanner.V2
```

Multi-targets net8 / net9 / net10.

## Why a satellite repo

This package previously shipped from the main `tamp` repo (up to 1.11.1). It moved to its own satellite at 1.11.2 (TAM-254) so:

- Tool releases don't gate Tamp.Core releases (and vice versa).
- Adopters can pin the wrapper independently of Tamp.Core minors.
- The wrapper's release cadence tracks the wrapped tool instead of the whole framework.

Package ID, namespace, public API, and version line are unchanged — adopters see no break.

## License

MIT — see [LICENSE](LICENSE).
