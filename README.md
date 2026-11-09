# From Signal to System: Intelligence OPD

A three-module, case-study-based officer professional development (OPD) program for the intelligence warfighting function. It covers fusing traditional analysis, data-driven methods, and AI. One scenario, **Exercise NORTH WATCH** (indications and warning on grey-zone threats to Baltic undersea infrastructure), runs through all three modules and ends with each cell hosting its own tool on GitHub.

**Live site:** https://prestondihle.github.io/12th-CAB-Intel-OPD/

## What it does
A static companion site for students and facilitators. It holds the learning outcomes, readings, discussion questions, practical exercises, an annotated tools list, guardrails, and reusable templates. Students can tick off readings and exercises as they go; progress is saved only in their own browser.

## What it does NOT do
- It is not the facilitator's guide, and it does not replace command oversight or SJA review.
- It collects no data. There are no accounts, no analytics, and no third-party scripts or fonts.
- Progress tracking lives only in `localStorage` on each device. It is not shared or backed up.

## Contents
| Path | What it is |
| --- | --- |
| `index.html` | The student site: HTML, CSS, and JS in one file |
| `facilitator.html` | Facilitator's guide: coordination, schedule options, module notes, answer keys, grading, AAR |
| `fonts/` | Self-hosted IBM Plex and Saira Condensed fonts (SIL OFL 1.1; licenses included) |
| `templates/` | Downloadable collection log and ACH matrix (CSV), fused product, and capstone README (Markdown) |
| `.github/workflows/links.yml` | Weekly link check, since tools and articles move |

## How to run / view
Open the live site, or open `index.html` locally in any browser. There is no build step. To publish changes, push to `main`; GitHub Pages serves from the repo root.

## OPSEC and data-rights statement
- Unclassified, open sources only. No classified or CUI content belongs in this repo.
- No API keys, credentials, or sensitive data are stored here.
- Third-party sources are linked and attributed, never re-hosted. Each tool's terms of use apply.

## AI use
Parts of this site were drafted and revised with AI assistance. The course author is responsible for reviewing its content, doctrine references, and links.

## License
Course content is licensed under [CC BY 4.0](LICENSE). Fonts are under the SIL Open Font License 1.1 (see `fonts/`). Linked third-party material belongs to its owners.
