# SAC Templates Hub

**Free, ready-to-use templates for SAP Analytics Cloud (SAC) and SAC Planning — plus tested accelerators for the parts that have to be right.**

🔗 **Website: [sactemplateshub.com](https://sactemplateshub.com)**

SAC Templates Hub is an independent project that gives SAP Analytics Cloud consultants and finance teams a head start: **64 ready-made templates** with KPIs, dimensions and realistic sample data, so you build a Story or Planning model in minutes instead of days. No account required, no sign-up — download as `.xlsx`, `.csv` or SAC `.package` and import.

> Independent project, not affiliated with SAP. SAP and SAP Analytics Cloud are trademarks of SAP SE.

---

## What's inside

### Templates & Generator
- **64 free templates** across **16 industries** — finance, banking, insurance, retail, supply chain, ESG, HR, pharma, telecom and more.
- **A rule-based template generator** — describe a use case, get a structured starting model with KPIs and dimensions.
- **Interactive KPI previews** — see the dimensions, measures and sample charts before you download.
- **Three download formats** per template: `.xlsx` (multi-sheet workbook), `.csv` (flat table) and `.package` (SAC model bundle with model.json + data + README).

### Tested accelerators (paid)
Not just a CSV — each ships a tested model, a step-by-step import guide, and a validation passport recording what was actually verified, including that it imports and displays in a live SAC tenant.
- **Rolling Forecast** — an Actual / Budget / Forecast planning model, proven end-to-end in a live tenant.
- **Solvency II** — SCR, MCR, own funds, solvency ratio with EIOPA thresholds (ratios allowed to exceed 100%, not silently capped).
- **Basel III** — CET1, LCR, NSFR with BIS/BCBS bounds.
- **IFRS 17** — CSM roll-forward, risk adjustment, BBA/VFA/PAA model structures.
- **CSRD / ESRS** — ESRS datapoints, double materiality, Scopes 1/2/3 (updated for the 2026 Omnibus reform).

### Blog — 55 technical articles
Practical guides, not marketing — written at a level SAC consultants and finance teams actually use.

**SAC releases (2026 QRC cycle):**
- SAC Quarterly Release 2026 — the full-year index
- QRC1 2026: story versioning, Pareto charts, live Snowflake
- QRC2 2026: asymmetric reporting, decoupled Data Panel
- QRC3 2026: rolled out mid-August · QRC4 2026: due mid-November
- The full SAC release tracker at [/releases](https://sactemplateshub.com/releases)

**Comparisons:**
- SAC vs Power BI · SAC vs Anaplan · SAC vs Tableau · SAC vs Qlik Sense · SAC vs Looker · SAC vs OneStream

**Regulatory & ESG:**
- Basel III in SAC (CET1, LCR, NSFR) · Solvency II (SCR, MCR)
- IFRS 17 CSM roll-forward · IFRS 9 ECL staging (PD × LGD × EAD)
- BCBS 239 risk data aggregation · Pillar 3 disclosures
- CSRD/ESG Scopes 1/2/3 · Double materiality (ESRS)
- SAP Analytics Cloud for ESG reporting · CSRD dashboard examples

**Tutorials:**
- How to import a model into SAC (end-to-end, with the tenant pitfalls)
- Import CSV into SAC Modeler · Multi-sheet Excel import
- SUM / AVERAGE / LAST / COUNT aggregation guide · Exception aggregation over time
- The Version dimension (Actual / Budget / Forecast)
- Data Actions: copy, allocate, spread in SAC Planning
- Workforce planning · Retail store performance · Supply chain stock model
- Annual budget and rolling forecast

All articles include **original SVG diagrams** (CSM waterfall, LAST vs SUM, Scopes value chain, double materiality matrix, Basel III capital stack, Solvency II ladder, IFRS 9 three-stage model, BCBS 239 aggregation flow, aggregation decision tree).

---

## Tech stack

- **Node.js** (single server.js, zero framework) — server-rendered HTML, no client-side SPA.
- **Pure CSS** — custom design tokens, no Tailwind/Bootstrap.
- **SVG charts and previews** — drawn in JS, no images, no external dependencies.
- **100% browser-side data processing** — uploaded CSV/Excel files never leave the user's machine (GDPR by design).
- **IndexNow** — automatic Bing/Yandex notification on every deploy.
- **JSON-LD** — Organization, WebSite, SoftwareApplication, Product, FAQPage, BreadcrumbList, Article schemas.

---

## Privacy

No tracking, no cookies, no analytics. CSV/Excel files uploaded to the generator are processed entirely in the browser and never sent to any server. See the [privacy policy](https://sactemplateshub.com/privacy).

---

## License

The community templates are provided free to use under the MIT license. The tested accelerators (Rolling Forecast and the regulatory kits) are paid products. Built from official public sources (EIOPA, BIS/BCBS, EFRAG) where regulatory frameworks are involved — you remain the validator of your own models.

---

Built and maintained by an independent developer. Feedback and template suggestions welcome via the [contact page](https://sactemplateshub.com/contact).
