# MES Bake-Off Demo

**An independent demonstration of challenge-based procurement for Medicaid Enterprise Systems**

> **Note:** This is not an official government project. Created by Nick Aretakis, inspired by Minnesota DHS's presentation at HIT Connect 2026.

---

## What Is This?

A working GitHub Organization that demonstrates what transparent, GitHub-powered procurement could look like. Instead of 18-36 month RFP cycles:

- Publish a backlog of outcomes (not requirements)
- Run rapid evaluations in days/weeks
- Let multiple vendors compete on the same slice
- Evaluate on delivered value, not proposals

## The Backlog

GitHub Issues serve as the transparent backlog. Anyone can see what's being worked on:

| Issue | Type | Status |
|-------|------|--------|
| [#1 MSP Auto-Enrollment](https://github.com/mes-bakeoff-demo/mes-modernization/issues/1) | Slice | In Progress |
| [#2 Eligibility Verification](https://github.com/mes-bakeoff-demo/mes-modernization/issues/2) | Slice | Available |
| [#3 Identity Management](https://github.com/mes-bakeoff-demo/mes-modernization/issues/3) | Layer | Available |

## Repository Structure

| Repo | Purpose |
|------|---------|
| [mes-modernization](https://github.com/mes-bakeoff-demo/mes-modernization) | Hub — strategy, backlog, templates |
| [rfp-msp-auto-enrollment](https://github.com/mes-bakeoff-demo/rfp-msp-auto-enrollment) | RFP — Definition of Done for MSP slice |
| [msp-solution-alpha](https://github.com/mes-bakeoff-demo/msp-solution-alpha) | Vendor Alpha — Rules-based | [Demo](https://mes-bakeoff-demo.github.io/msp-solution-alpha) |
| [msp-solution-beta](https://github.com/mes-bakeoff-demo/msp-solution-beta) | Vendor Beta — Decision tree | [Demo](https://mes-bakeoff-demo.github.io/msp-solution-beta) |
| [msp-solution-gamma](https://github.com/mes-bakeoff-demo/msp-solution-gamma) | Vendor Gamma — Form wizard | [Demo](https://mes-bakeoff-demo.github.io/msp-solution-gamma) |

## The Demo Slice: MSP Auto-Enrollment

Three vendors built working prototypes for the same problem — Medicare Savings Program eligibility — each with a different approach:

| Vendor | Approach | Tech | Demo |
|--------|----------|------|------|
| Alpha | Rules-based engine | HTML/JS | [Try it](https://mes-bakeoff-demo.github.io/msp-solution-alpha) |
| Beta | Decision tree | React | [Try it](https://mes-bakeoff-demo.github.io/msp-solution-beta) |
| Gamma | Form wizard | Vue | [Try it](https://mes-bakeoff-demo.github.io/msp-solution-gamma) |

## Why GitHub?

| Need | GitHub Feature |
|------|----------------|
| Transparent backlog | Issues |
| Vendor Q&A | Discussions |
| Progress tracking | Projects |
| Code review | Pull Requests |
| Deployment | Actions + Pages |

## Credits

- Nick Aretakis — Demo
- Minnesota DHS — Original presentation (HIT Connect 2026)
- Alaska DHSS — GitHub-based procurement pioneer
- SI Delivery — Challenge-Based RFP templates
- 18F — Agile BPA

---

*Independent demonstration. Not an official government project.*
