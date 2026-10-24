# Aodı Akdıro Data OS — Data Production Playbook

**The operator's handbook for real data work — one zero-dependency app, six audited modules, Arabic + English.**

Data teams don't fail at tooling; they fail at primitives: sources without owners, transforms nobody can re-run, dashboards built from guesses, and governance that lives in someone's head. Data OS packages the primitives: **75 audited records** across **6 OS modules** in a single HTML file that runs offline.

- **License:** MIT © 2026 Baran Avisat (see LICENSE)
- **Price:** $14 — lifetime license, free updates for 1 year
- **Support:** baranavisat@gmail.com · WhatsApp +90 531 326 37 22 (wa.me/905313263722)
- **Product line:** Aodı Akdıro Suite — github.com/aoodiakdiro0001-ops

## What's inside (6 modules)

| Module | Records | What you get |
|---|---|---|
| 🗃️ **Tool Map** | 12 | Selection criteria for document stores, columnar warehouses, distributed engines, reviewed-as-code transforms, BI clouds, in-memory engines, local SQL, catalogs and access control |
| ⚙️ **Data Pipelines** | 10 | Complete loops: nightly ingestion with row-count gates, CDC sync, re-runnable cleaning, 3-layer modeling, star schemas, fast dashboards, scheduled reports, quality gates, slow-query triage, archiving |
| 📜 **Data Contracts** | 8 | SQL-with-assumptions, schema documentation, slow-query diagnosis, dashboard specs, metric dictionaries, quality test plans, pipeline docs, incident reports |
| 🗓️ **21-Day Plan** | 21 | Inventory → foundation → quality gates → scale → lock-in, one day = one move with a KPI |
| 🧮 **Data Cost Calculator** | 6 fields | Storage + scan + seats → monthly/yearly burn with the biggest cost driver named |
| 🛡️ **Governance Policy** | 18 | PII separation, masking, encryption, least-privilege, query logs, consent, backups + restore tests, spend caps, quarterly access reviews |

**75 records, all checked by the automated auditor** (contract counts, empty-field scan, encoding hygiene) before shipping.

## Why this is different

1. **Decisions, not definitions.** Every card is a choice you can make this week — with pointers and execution bullets.
2. **Anti-hype stance.** The app itself warns: vendor docs win, and no dataset ships without quality gates.
3. **One file. No dependencies.** `app/index.html` runs offline from any browser.
4. **Bilingual.** Arabic + English toggle, RTL-aware.
5. **Your data stays yours.** localStorage persistence (`aos_aoddataos_*`), JSON export, per-module CSV.

## Quick start

1. Open `app/index.html` in any modern browser.
2. Start with **21-Day Plan** → day 1 (write your source+owner inventory).
3. Copy any **Data Contract** and fill the `{{variables}}`.

## What's in the package

```
app/          index.html — the full app (single file, offline)
export/       aoddataos.json + one CSV per module (UTF-8)
library/      one Markdown reference sheet per module
docs/         screenshots
README.md, START_HERE.md, POLICY.md, CHANGELOG.md, LICENSE
content.py, contract.json (source of truth) · build.py, check.py (auditor)
```

## Honest disclosure

- The calculator is an **estimate** — plug your vendor's real prices.
- The governance policy is a strong draft; make it official after your own review.
- The Tool Map helps you **compare faster**; it does not replace vendor docs.

© 2026 Baran Avisat · MIT License · Bitcoin `bc1q8dhtdrndxsl70e97t8grydfe6pjue37zrhzf6c` · USDT-TRC20 `TLWdTjqqogkXNEXGiPWsGdjFP6ioycxeWW`
