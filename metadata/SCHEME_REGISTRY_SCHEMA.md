# Scheme Registry & Report Tagging

Every fund report must be indexed against a canonical metadata registry before the report is marked complete.

Required fields:
- scheme_uid
- canonical_scheme_name
- report_slug
- mf_peerset_category
- mf_peerset_sleeve
- sebi_category
- benchmark
- primary_fund_manager
- co_fund_managers
- latest_equity_book_cr
- holdings_as_of
- performance_as_of
- category_sleeve_source
- fund_manager_source
- mapping_status
- last_verified_at

## Report tags
PowerPoint cover and slide footer: Scheme | MF Peerset Category | MF Peerset Sleeve | Fund Manager(s) | As-of

Excel 00_Control: full registry row.

Research note front matter: scheme_uid, scheme, category, sleeve, benchmark, fund_managers, report_date, holdings_as_of, performance_as_of.

## Filter indexes
Create link-only indexes, without duplicating binary files:
- by-fund-manager/<manager-slug>/README.md
- by-category/<category-slug>/README.md
- by-sleeve/<sleeve-slug>/README.md
- metadata/manager_scheme_matrix.csv

A manager index must link all schemes handled by that manager to the latest PPTX, XLSX and illustrated research note.

## Source discipline
Use Vistas scheme_uid/identity and benchmark as the base. MF Peerset category and sleeve must come from the actual MF Peerset Comparison mapping when available; never infer sleeve from the fund name. Fund-manager mapping should be sourced from Vistas when exposed, otherwise from current official ABSLAMC scheme/factsheet data with the effective date recorded.
