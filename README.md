# RoninRxISK

Activism and advocacy: psychiatric medication harm and post-SSRI sexual dysfunction (PSSD) research. Tracks what is known, who is researching it, RoninSec research tools, and how patients can report harms.

Independent project, not affiliated with RxISK.org.

A [RoninSec](https://r0n1n9.github.io/roninsec/) brand. Live at https://r0n1n9.github.io/roninrxisk/

Single static `index.html`, no build step. `.nojekyll` tells GitHub Pages to serve it as-is.

## Pages

| Path | Page |
|---|---|
| `index.html` | RoninRxISK: PSSD overview, recognition timeline, research efforts, tools, how to report harms |
| `atlas/index.html` | Snapshot of the PSSD Atlas evidence map |

To refresh the Atlas, run `python -m pssd_atlas update` in the `pssd` repo, copy `docs/index.html` to `atlas/index.html`, and re-add the RoninRxISK bar after `<body>`.
