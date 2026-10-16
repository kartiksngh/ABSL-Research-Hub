# 15-Day Refresh Specification

Run one reconciled AMC research refresh every 15 days.

## Sequence
1. Resolve latest complete holdings month.
2. Refresh MF Peerset performance layer if available.
3. Refresh Vistas portfolio, benchmark, ownership/flow, revisions, allocator/regime and crowding/liquidity.
4. Cross-check material facts on the web.
5. Build one common data cube.
6. Generate every scheme deep dive.
7. Generate workable Excel for every scheme.
8. Generate separate AMC/CIO presentation and master Excel.
9. Compare against previous refresh and highlight material changes.
10. Write current files to latest/.
11. Preserve dated copies under archive/YYYY-MM-DD/.

## Required outputs per fund
- latest/ABSL_<Fund>_Deep_Dive_LATEST.pptx
- latest/ABSL_<Fund>_Analytics_LATEST.xlsx
- dated archive copies

## Required AMC outputs
- AMC_CIO/latest/ABSL_AMC_CIO_Review_LATEST.pptx
- AMC_CIO/latest/ABSL_AMC_Master_Analytics_LATEST.xlsx
- dated archive copies

## Output quality
Charts/tables > prose; conclusion-led titles; numerical reconciliation; precise labels; source/as-of on every exhibit; no silent source substitution; no one-slide fund summaries in place of deep dives.
