# Compliance Dashboard

> Automated CMMI L3-L5 maturity assessment + ISO 27001 audit evidence generator. Scans repos for CI/CD, testing, security, documentation compliance.

[![Python](https://img.shields.io/badge/python-3.10+-blue)]()
[![GitHub API](https://img.shields.io/badge/GitHub-API-black)]()
[![CMMI](https://img.shields.io/badge/CMMI-L3--L5-green)]()

## Maturity Model

| Level | Name | Criteria | Auto-Check |
|-------|------|----------|------------|
| L1 | Initial | Code exists in git | ✅ |
| L2 | Managed | README, .gitignore, branches | ✅ |
| L3 | Defined | CI/CD, tests, CONTRIBUTING, ADRs | ✅ |
| L4 | Quantitatively Managed | Coverage >60%, security scan, metrics | ✅ |
| L5 | Optimizing | Automated retraining, drift detection, SLA monitoring | ✅ |

## Dashboard Output

```
┌────────────────────────────────────────────────────────────┐
│              COMPLIANCE SCORE — 2026-02-10                  │
├──────────────────────┬───────┬────┬────┬────┬────┬─────────┤
│ Repository           │ CI/CD │Test│ Sec│Docs│ ADR│ Score   │
├──────────────────────┼───────┼────┼────┼────┼────┼─────────┤
│ ollama-local         │  ⚠️   │ ❌ │ ✅ │ ✅ │ ✅ │ L3 72%  │
│ kanban-pmo           │  ❌   │ ❌ │ ⚠️  │ ✅ │ ❌ │ L2 45%  │
│ devops-pipeline      │  ⚠️   │ ❌ │ ✅ │ ✅ │ ✅ │ L3 68%  │
│ ai-gateway           │  ❌   │ ❌ │ ❌ │ ✅ │ ✅ │ L2 40%  │
│ contract-engine      │  ❌   │ ❌ │ ❌ │ ✅ │ ✅ │ L2 40%  │
└──────────────────────┴───────┴────┴────┴────┴────┴─────────┘
```

## Revenue

Compliance consulting **R8,000-15,000/engagement** + **R3,000/month** automated monitoring. Target: companies preparing for ISO 27001 or CMMI certification.

---
*MIT License*
