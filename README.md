# Factor XI Inhibitors — Internal Medicine Resident Journal Club

A 45-minute evidence-based journal club presentation on the FXI inhibitor drug class, built for Internal Medicine residents at the PGY-1 through PGY-3 level.

**Live site:** `https://<your-username>.github.io/fxi-journal-club/`

---

## Overview

This presentation uses a three-act narrative arc structured around the two landmark 2024 Phase 3 trials — OCEANIC-AF (asundexian, stopped for inferiority) and LILAC-TIMI 76 (abelacimab, stopped for overwhelming safety benefit) — to teach both the clinical content and critical appraisal methodology simultaneously.

### Session Structure (45 minutes)

| Section | Topic | Time |
|---------|-------|------|
| 01 | Opening clinical case — AF + GI bleed + ESRD | 5 min |
| 02 | Why current anticoagulation is incomplete | 4 min |
| 03 | FXI physiology — hemostasis vs. thrombosis distinction | 8 min |
| 04 | Agents in development — FXI vs. FXIa mechanistic distinction | 5 min |
| 05 | Trial narrative arc — Phase 2 → OCEANIC-AF failure → LILAC breakthrough | 14 min |
| 06 | No reversal agents — critical inpatient gap | 5 min |
| 07 | Hospital medicine implications & inpatient populations | 5 min |
| 08 | Structured debate | 4 min |
| 09 | Take-home points & close | 3 min |

---

## Learning Objectives

1. Explain why FXI is a mechanistically superior anticoagulation target using the hemostasis/thrombosis distinction
2. Distinguish FXI inhibition from FXIa inhibition and how this difference predicted divergent trial outcomes
3. Critically appraise LILAC-TIMI 76 and OCEANIC-AF — design, endpoints, early stopping, non-inferiority framing
4. Articulate the class-wide absence of reversal agents and its clinical implications
5. Identify inpatient patient populations most compelling for FXI inhibitor candidacy

---

## Key Evidence Base

- **LILAC-TIMI 76** — Bhatt DL, et al. *NEJM* 2024. Abelacimab vs. rivaroxaban in AF. Stopped early: 67% RRR major bleeding.
- **OCEANIC-AF** — OCEANIC-AF Investigators. *NEJM/Circulation* 2024. Asundexian vs. apixaban. Stopped early: inferior stroke prevention.
- **Salomon O, et al.** *Blood* 2008. Reduced ischemic stroke in severe FXI deficiency — mechanistic foundation.
- **Weitz JI, et al.** *Circulation* 2024. FXI inhibitors review.
- **Buller HR, et al.** *NEJM* 2015. FXI-LRx antisense oligonucleotide VTE prevention — original landmark ASO study.

---

## Deployment

### GitHub Pages (recommended)

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch`
4. Select `main` branch, `/ (root)` folder
5. Click **Save**
6. Your site will be live at `https://<your-username>.github.io/fxi-journal-club/` within ~60 seconds

GitHub Actions CI is included (`.github/workflows/deploy.yml`) and will auto-deploy on every push to `main`.

### Local preview

```bash
git clone https://github.com/<your-username>/fxi-journal-club.git
cd fxi-journal-club
open index.html   # macOS
# or
xdg-open index.html   # Linux
```

No build step, no dependencies — pure HTML/CSS/JS.

---

## Presenter Notes

Presenter guidance is embedded throughout the document in purple annotation boxes. Key facilitation points:

- **Section 03** — Stop and ask residents to articulate why FXI deficiency doesn't cause spontaneous bleeding before showing the physiology comparison. This ensures active engagement rather than passive receipt.
- **Section 05** — Present OCEANIC-AF first. The failure makes LILAC's success meaningful and teaches that mechanism alone doesn't guarantee efficacy.
- **Section 05 critique** — The trial-stopped-early discussion is the single most important methodological teaching point in the session. Press residents on winner's curse / inflated effect size.
- **Section 08** — Specific debate motion recommended: *"This institution should prioritize enrollment of high-risk AF patients into FXI inhibitor trials NOW."*

---

## Pre-Reading Assignment

Assign residents **one week before** the session:

1. LILAC-TIMI 76 full paper (NEJM 2024) — primary
2. OCEANIC-AF results — counterpoint

---

## File Structure

```
fxi-journal-club/
├── index.html              # Full presentation (self-contained)
├── README.md               # This file
└── .github/
    └── workflows/
        └── deploy.yml      # GitHub Actions auto-deploy to Pages
```

All styling, fonts (Google Fonts CDN), and interactivity are self-contained within `index.html`. No external dependencies beyond Google Fonts.

---

## Clinical Disclaimer

This presentation is intended for educational use in residency training. All clinical decisions should be made in accordance with current institutional protocols, evidence-based guidelines (ACC/AHA, ISTH, CHEST), and individualized patient evaluation. None of the FXI inhibitor agents discussed have received FDA approval as of the date of this publication.

---

*Developed for Internal Medicine residency education. Evidence base: NEJM, Circulation, Blood. Last updated February 2026.*
