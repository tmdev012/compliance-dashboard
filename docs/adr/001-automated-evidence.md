# ADR-001: Automated Evidence Collection

## Status: Accepted | Date: 2026-02-10

## Decision
Automate compliance evidence gathering via GitHub API rather than manual audits.

## Why
- Manual audits are expensive, slow, and point-in-time
- Automated scans run continuously (every push)
- Evidence is timestamped and reproducible
- Scales to any number of repos without additional cost
