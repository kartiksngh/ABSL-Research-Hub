# ABSL Research Hub

Central repository for recurring ABSLAMC active-equity fund and AMC/CIO analytics.

## Structure
- `AMC_CIO/` — AMC-wide CIO reports and master analytics
- `funds/` — one directory per fund
- `methodology/` — fund analytics framework, data architecture, reconciliation rules
- `automation/` — recurring refresh specification

Each report family uses `latest/` for current files and `archive/YYYY-MM-DD/` for dated snapshots.

## Data architecture
- Vistas Terminal: portfolio, attribution, ownership/flow, revisions, benchmark and market-regime analytics
- MF Peerset Comparison: preferred peer-performance and risk layer when available
- Web: material-fact cross-verification

## Important
This repository is public. Only publish material approved for public distribution.
