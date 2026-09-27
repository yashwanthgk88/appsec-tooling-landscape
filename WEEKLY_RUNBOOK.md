# Runbook

## Weekly (Monday 08:00 IST): new entrants and AI changes
1. Clone the repo. Read README.md and one JSON file to learn the schema.
2. For each of the 7 categories, sweep for tools launched, forked, or first funded in the last 14 days: funding announcements, OWASP new project listings, Product Hunt and Hacker News security launches, GitHub trending in security, RSAC / Black Hat / BSides startup lists, Gartner Cool Vendors, vendor blogs. Only credible tools with a product page; skip vapourware.
3. For EVERY tool in the JSON (240+), scan the vendor's release notes, changelog, blog and news for the last 14 days: feature launches, GA announcements, new integrations, acquisitions, rebrands, pricing changes, major releases, shutdowns. Record each as a dated entry in that tool's recent_updates list (keep the latest 10) and, where the change affects a data column (key_features, ai_capabilities, ai_maturity, integrations, deployment, pricing_model, indicative_cost_usd, cons_known_gaps), update that column too with a fresh last_verified. Work in parallel with one subagent per category. Prioritise the incumbents and Leaders (Checkmarx, Veracode, OpenText Fortify, HCL AppScan, Black Duck, Snyk, GitHub, GitLab, Sonar, Semgrep, Sonatype, JFrog, Mend, GitGuardian, Cycode, ArmorCode, Apiiro, Wiz, Endor Labs, Aikido, IriusRisk/ThreatModeler, SD Elements) check release notes and blogs for AI features that changed maturity (announced, GA, retired) in the last 14 days. Update ai_capabilities, ai_maturity, ai_verified_source and last_verified on the affected row only.
4. Append new rows with is_new_entrant true and every field filled; write "not publicly disclosed" or "unverified" rather than guessing.
5. Run build_workbook.py, recalculate, confirm zero formula errors.
6. Add a dated CHANGELOG.md entry: new tools (name, category, link), AI changes (tool, what changed), anything checked with no change.
7. Commit and push. Notify with the changelog entry and attach the xlsx.

## Monthly (first Monday 08:00 IST): full re-verification
1. Same setup. For every row older than 30 days in last_verified, re-check product_url (dead links, rebrands, acquisitions), ai_maturity, pricing_model and indicative_cost_usd, analyst_position (new Gartner MQ or Forrester Wave), deployment.
2. Refresh OWASP project versions and the Market Notes.
3. Rebuild, changelog, commit, push, notify with a summary of rows changed.

## Rules
- JSON is the source of truth. Never hand-edit the xlsx.
- Never delete a tool row; mark acquisitions or shutdowns in cons_known_gaps and keep the row.
- No internal quotes in pricing. Public list prices only.
