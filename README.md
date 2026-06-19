# GMU-PhD

The strategical path to a GMU Public Policy PhD (Schar School, Fall 2027) — a single-page application control center for **Hui Ding (丁惠)**.

Research direction: **Trade · Institutions · Firm Behavior** — *How do policy shocks in institutionally unstable environments affect firm survival, resource allocation, and supply chain restructuring?*

## Dashboards

| Version | Page | Focus |
| --- | --- | --- |
| v2 | [`index.html`](index.html) | Full application dashboard: research positioning, materials, timeline, kanban, risk control |
| v3 | [`v3.html`](v3.html) | Professor CRM + Research Idea evolution track |
| v4 | [`v4.html`](v4.html) | **Control center** — live deadline countdown, an interactive checklist that persists in your browser, plus a unified CRM / research / materials view |

All pages share a top navigation bar so you can move between versions. Open any `.html` file directly in a browser, or serve the folder:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000/v4.html
```

## Notes

- The v4 checklist saves progress to the browser's `localStorage`, so it does not sync across devices.
- Target submission window: **Dec 2026**; intake: **Fall 2027**.
