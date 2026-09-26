# Portfolio — Sudhansh Arora

**Role-specific portfolio sites for Sudhansh Arora, Senior Consultant at Xebia (Jaipur).**

This repo holds the landing hub and two secondary sites — one for AI Governance consulting and one for Business Analysis. Each site surfaces the work and certifications that matter for that role, with the CV one click away.

---

## Sites

### `index.html` — Hub
Landing page that routes recruiters to the right role site. Three cards: AI QA, AI Governance, Business Analyst.

### `ai-governance/` — Model Card
An AI governance portfolio styled as a "Model Card" — the format AI teams use to document a model's intended use, risks, and evaluation results, applied to a consultant's profile instead.

Covers: governance frameworks, risk assessment, regulatory mapping (EU AI Act, NIST RMF), certifications, and a live project list.

### `business-analyst/` — Requirements Board
A BA portfolio styled as a sticky-note requirements board — columns map to the consulting lifecycle (Discovery → Analysis → Delivery → Outcomes).

Covers: Power Platform (Sales 360), Appian fintech, stakeholder management, and tools (JIRA, Confluence, Figma).

---

## Features

- Consistent design system across all three sites (Archivo + Instrument Sans, shared CSS tokens)
- Full `prefers-color-scheme` dark mode on all pages
- `prefers-reduced-motion` support
- Responsive — mobile, tablet, desktop
- No build step; each site is a self-contained HTML file

---

## Assets

```
assets/
├── favicon.svg          # SVG favicon shared across all sites
└── sudhansh-arora.jpg   # Profile photo
```

---

## Structure

```
portfolio-web/
├── index.html              # Role-picker hub
├── ai-governance/
│   └── index.html          # Model Card portfolio
├── business-analyst/
│   └── index.html          # Requirements Board portfolio
├── assets/
│   ├── favicon.svg
│   └── sudhansh-arora.jpg
└── README.md
```

---

## Local preview

```bash
npx serve .
# or
python -m http.server 8080
```

Open `http://localhost:8080` for the hub, then navigate to each role site.

> [!NOTE]
> The AI QA site (SudhanshOS) lives in a separate repo: [github.com/Sudhansh3110/SudhanshOS](https://github.com/Sudhansh3110/SudhanshOS). The hub links to its GitHub Pages URL.
