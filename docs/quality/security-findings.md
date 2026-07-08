# Security Findings Log

Central registry of all security audit findings. Every finding is recorded here with its status (`TODO` or `DONE`) to preserve history.

**Owner**: Security Auditor
**Consumers**: Technical Lead, Project Manager, Backend Developer, Frontend Developer, DevOps Engineer

## How To Use This File

- The Security Auditor appends new findings after each audit.
- Each finding gets a unique ID (sequential, never reused).
- Status transitions: `TODO` → `DONE` (never delete entries).
- High-severity items are delegated immediately; see the Delegations section.
- Filter by status to see outstanding work.

## Findings

| ID | Date | Severity | Category | File | Line(s) | Description | Status | Delegated To | Resolved Date |
|----|------|----------|----------|------|----------|-------------|--------|--------------|---------------|
| — | — | — | — | — | — | _No findings yet_ | — | — | — |

## Categories

- **VULN** — Vulnerabilities & Security Flaws
- **QUAL** — Code Quality & Technical Debt
- **OPT** — Optimization Opportunities

## Severity Scale

| Rating | Meaning | Action |
|--------|---------|--------|
| High | Exploitable vulnerability, critical flaw, or severe risk | Delegate immediately to responsible developer/DevOps |
| Medium | Notable concern, not immediately exploitable but should be addressed | Schedule for next task/sprint |
| Low | Minor improvement, best-practice suggestion | Address opportunistically |

## Delegations

Track active delegations for High-severity findings here:

| Finding ID | Delegated To | Handoff Date | Resolution Date | Notes |
|------------|--------------|--------------|-----------------|-------|
| — | — | — | — | _No delegations yet_ |
