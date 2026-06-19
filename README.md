# GMU-PhD

The strategical path to a GMU Public Policy PhD (Schar School, Fall 2027) — a single-page application control center for **Hui Ding (丁惠)**.

Research direction: **Trade · Institutions · Firm Behavior** — *How do policy shocks in institutionally unstable environments affect firm survival, resource allocation, and supply chain restructuring?*

## Dashboards

| Version | Page | Focus |
| --- | --- | --- |
| v2 | [`index.html`](index.html) | Full application dashboard: research positioning, materials, timeline, kanban, risk control |
| v3 | [`v3.html`](v3.html) | Professor CRM + Research Idea evolution track |
| v4 | [`v4.html`](v4.html) | **Control center** — live deadline countdown, an interactive checklist that persists in your browser, plus a unified CRM / research / materials view |
| v5 | [`v5.html`](v5.html) | **Project plan** — milestone-driven roadmap (M1→M10) toward admission, a verified GMU requirements/process section, and a built-in weekly information-verification panel |

All pages share a top navigation bar so you can move between versions.

## GMU requirements (last verified 2026-06-19)

`v5.html` tracks the official Schar School Public Policy PhD requirements. Snapshot — **re-verify weekly against the official site** (items that change per cycle are flagged):

- **Term:** Fall only. Fall 2027 applications expected to open **~Sept 2026**.
- **Deadline:** *To be confirmed for Fall 2027.* Historically priority ≈ Dec 15 / final ≈ Mar 1. Plan targets a **Dec 2026** submission with buffer.
- **GRE:** Required (ETS code 5827, within 5 years) — *verify each cycle.*
- **Recommendation letters:** 3 (≥1 from academia recommended).
- **Goals statement:** 750–1,000 words.
- **Writing sample:** ~10–25 pages.
- **Resume/CV, transcripts** (unofficial at application).
- **English (international):** TOEFL ≥88 (≥20/section) or IELTS ≥6.5; waived if highest degree is from a waiver-eligible country.
- **Application fee:** $75 domestic / $80 international.
- **Funding:** GRA for full-time students — indicate interest on the application.

Sources: [PhD Admissions](https://schar.gmu.edu/admissions/phd-admissions) · [How to Apply (Public Policy Doctoral)](https://schar.gmu.edu/programs/phd-programs/phd-public-policy/how-apply-public-policy-doctoral-program) · [Catalog](https://catalog.gmu.edu/colleges-schools/policy-government/public-policy-phd/) · contact scharGR@gmu.edu / 703-993-8099. Open any `.html` file directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000/v4.html
```

## Notes

- The v4 checklist saves progress to the browser's `localStorage`, so it does not sync across devices.
- Target submission window: **Dec 2026**; intake: **Fall 2027**.
