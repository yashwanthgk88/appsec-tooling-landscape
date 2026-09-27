# AppSec Tooling Landscape

Repository: https://github.com/yashwanthgk88/appsec-tooling-landscape

Master data and build script for the internal AppSec tool analysis workbook.

- `research/*.json` : one file per category. Each has `category`, `tools[]`, `owasp`, `category_notes`. This is the system of record; edit here, never in the xlsx.
- `build_workbook.py` : regenerates `AppSec_Tooling_Landscape_2026.xlsx` from the JSON. Run `python3 build_workbook.py` then recalculate with LibreOffice (or open in Excel).
- `CHANGELOG.md` : one entry per update run.
- `WEEKLY_RUNBOOK.md` : what the scheduled task does each week and month.

Tool row schema (all string fields; pipe-separated lists): tool, vendor, product_url, is_new_entrant (bool), type, deployment, languages_coverage, key_features, ai_capabilities, ai_maturity (GA | Beta or Preview | Marketing claim | None), ai_verified_source, integrations, sectors_reference_customers, analyst_position, cons_known_gaps, pricing_model, indicative_cost_usd, pricing_confidence (High | Medium | Low | None), best_fit_for, last_verified (YYYY-MM-DD), sources.

Optional per-tool field `recent_updates`: list of `{date: YYYY-MM-DD, type: Feature launch | Feature GA | Acquisition | Pricing change | Release | New entrant | Rebrand | Shutdown, summary, source}`. Rendered in the "Recent updates" column and the "Feature Updates" sheet. Keep the latest 10 per tool.
