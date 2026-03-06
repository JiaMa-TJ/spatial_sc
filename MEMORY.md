# MEMORY

## Project Identity
- Repo: `spatial_sc`
- Root: `/Users/jiama/Desktop/compileFIle/codex_proj`
- Main branch: `main`
- Remote: `https://github.com/JiaMa-TJ/spatial_sc.git`

## Structure
- `celllens` is a git submodule  
  Source: `https://github.com/sggao/celllens.git`
- `SpatialEx` is a git submodule  
  Source: `https://github.com/KEAML-JLU/SpatialEx.git`

## Persistent Operating Rules
- Follow root `AGENTS.md` safety policy.
- Network access is allowed.
- High-risk destructive operations still require explicit confirmation.

## Environments
- `celllens-repro` (conda): used for CellLENS smoke/quick run.
- `spatialex-repro` (conda): used for SpatialEx smoke reproduction.

## Verified Repro Facts
- SpatialEx smoke script exists:
  - `SpatialEx/scripts/run_smoke_repro.py`
- Smoke run success marker:
  - `spatialex_smoke_repro_ok=1`

## Collaboration Preference
- Prefer reproducible scripts over notebook-only steps.
- Record handoff status in `HANDOFF.md` at end of each session.
