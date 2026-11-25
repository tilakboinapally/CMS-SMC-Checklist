# CMS Streamlined Modular Certification (SMC) Checklists

An interactive reference to the CMS-required outcomes for every Medicaid Enterprise System (MES) module under CMS's Streamlined Modular Certification (SMC) framework — 169 items across 16 sections.

**Live site:** https://tilakboinapally.github.io/CMS-SMC-Checklist/

## How to use it

No install, no account, no setup — it's a single web page.

1. **Open the live site** above (or download `index.html` from this repo and open it in any browser — it works offline too).
2. **Pick a module** from the menu on the left — for example Provider Management, Claims Processing, or Pharmacy Benefit Management.
3. **Click any checklist item** to expand it. Each item shows:
   - the verbatim CMS outcome wording
   - its default metric (what gets measured)
   - the federal regulation behind it
   - **how a state proves it** — a live system demo, a metric report, a document, screenshots, a third-party security assessment, or an attestation
   - a plain-language "what it looks like in practice" note
   - state examples where one exists
4. **Use the Conditions for Enhanced Funding section** (shared across all modules) to see what gates the 90% federal match for building a system and the 75% match for running it.
5. **Prior authorization** isn't a standalone CMS module — find it inside Claims Processing (CP3, medical services) and Pharmacy Benefit Management (PBM6, pharmacy: 24-hour response, 72-hour emergency fill), with cross-links between them.

## Who this is for

- **State Medicaid agency staff** preparing for a readiness review or certification review
- **Vendors and system integrators** building or replacing an MES module
- **Consultants and certification reviewers** who need the outcomes, metrics, and evidence expectations in one place
- **Students and new joiners** learning how Medicaid enterprise systems get certified

## Modules covered

| Section | Items |
|---|---|
| Provider Management | 21 |
| Claims Processing | 6 |
| Pharmacy Benefit Management | 9 |
| Eligibility and Enrollment | 27 |
| Financial Management | 9 |
| Decision Support / Data Warehouse | 2 |
| Encounter Processing | 5 |
| Long-term Services and Supports | 11 |
| Member Management | 11 |
| Prescription Drug Monitoring Program | 6 |
| Third-party Liability | 13 |
| Program Integrity | 18 |
| Health Information Exchange | 0 — CMS publishes no required outcomes for this module |
| Electronic Visit Verification | 9 |
| Asset Verification System | 0 — no CMS outcomes published; the requirement lives inside Eligibility and Enrollment |
| Conditions for Enhanced Funding | 22 (shared across all modules) |
| **Total** | **169** |

## How certification works (the short version)

- **Readiness review** — before go-live, after most user testing. The state shows the system working in a pre-production environment.
- **Certification review** — after at least six months in production, with real metric data. Evidence is due two weeks before each review.
- If certified, the **75% federal match for operations is retroactive** to the first day of the quarter after go-live.
- The **90% match for building** the system and the **75% match for running it** depend on meeting the Conditions for Enhanced Funding in this site's shared section.

## Sources

All outcome wording, metrics, and regulations are taken verbatim from CMS primary sources:

- [MES Certification Repository](https://cmsgov.github.io/CMCS-DSG-DSS-Certification/) (CMS GitHub — the outcomes spreadsheets live here)
- [SMC Guidance v2.0, October 2025](https://cmsgov.github.io/CMCS-DSG-DSS-Certification/SMC%20Guidance.pdf)
- [SMD Letter #22-001](https://www.hhs.gov/guidance/sites/default/files/hhs-guidance-documents/AID/smd22001.pdf) (April 14, 2022 — the letter that introduced SMC and retired the old MECT/MEET toolkits)

## Honest caveats

- CMS publishes **no pass/fail thresholds** for any metric, and no state has published its actual metric values. This site shows metric definitions only — never invented sample values.
- A few CMS source quirks are reproduced verbatim and flagged on the page (e.g. typos in the Program Integrity list, mismatched metrics in Member Management).
- Module lists with no CMS titles (Pharmacy, Financial Management) use descriptive labels derived from the outcome wording, marked as such.
- CMS updates the repository over time — if an outcome changes, the live CMS repo is the authority, not this page.

## About

Built as a free study and reference utility for Medicaid provider management and MES certification work. CMS content is U.S. government material; the presentation, proof guidance, and practice notes are original. Free to use and share — if it helps your team, pass it on.
