# CHANGELOG

> Change management per Phase 2 §50–51. Every change records: Date / URL / Change / Reason / Old / New / SEO risk / Rollback.

| Date | URL | Change | Reason | Old | New | SEO risk | Rollback |
|---|---|---|---|---|---|---|---|
| 2026-09-17 | — | Initialized CHANGELOG (no site changes this batch) | Phase 2 Week 1, §50 | — | — | — | — |
| 2026-09-17 | market.worldbatteryhub.com/* (25 reports) | Added Method + Confidence rows to every "Market snapshot" table | P0 §3 Market 数字溯源 — every figure carries Source/Period/Unit/Method/Confidence (§15-16) | Snapshot tables had Source/Unit/Year but no Method/Confidence | Added Method (primary-first, conflict-flagged) + per-report Confidence | Low — additive table rows, no number/text/URL change | `git revert` this commit |
| 2026-09-17 | market.worldbatteryhub.com/{battery-price-forecast,china-battery-production,battery-materials-price-index,regional-demand,india-battery-market,south-korea-battery-market,japan-battery-market}/ | Added "Data provenance" block (Method + Confidence) before Sources on 7 reports without snapshot tables | P0 §3 Market 数字溯源 — close the Method/Confidence gap on reports with inline snapshot text | These 7 pages carried figures with source/period but no explicit Method/Confidence | Added provenance table (Method + Confidence), no number change | Low — additive only | `git revert` this commit |
