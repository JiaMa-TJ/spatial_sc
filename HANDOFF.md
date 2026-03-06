# HANDOFF

## Last Updated
- Date: 2026-03-07
- Owner: Codex

## Current State
- Parent repo `codex_proj` has been initialized and pushed to GitHub.
- Submodules are configured and committed:
  - `celllens`
  - `SpatialEx`
- Root safety policy is present in `AGENTS.md`.
- Persistent memory file is present in `MEMORY.md`.

## Completed Tasks
1. Cloned CellLENS and SpatialEx repositories.
2. Built `spatialex-repro` conda environment and installed required dependencies.
3. Added and validated SpatialEx smoke script:
   - `SpatialEx/scripts/run_smoke_repro.py`
4. Pushed parent repository to:
   - `https://github.com/JiaMa-TJ/spatial_sc.git`

## Known Notes / Risks
- SpatialEx full paper-level reproduction requires external datasets (Google Drive/Zenodo links from upstream docs).
- Some sandboxed environments can fail on OpenMP shared-memory; non-sandbox execution may be required.

## Next Recommended Steps
1. Add a server bootstrap script (`scripts/bootstrap_server.sh`) to install conda envs and init submodules.
2. Export and commit env lock files for reproducibility.
3. Start paper-level SpatialEx reproduction with real datasets and metric comparison.

## Resume Command (new session)
- Ask Codex to run:
  - "Read `AGENTS.md`, `MEMORY.md`, `HANDOFF.md`, then continue from Next Recommended Steps."
