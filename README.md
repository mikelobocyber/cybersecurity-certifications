# cybersecurity-certifications

Documenting my certification progress along the DoD 8140 track toward cleared contractor work in defense tech.

Roadmap one-sheet: [`_roadmap/DoD_Cert_OneSheet.pdf`](./_roadmap/DoD_Cert_OneSheet.pdf) · Homelab: [lobo-homelab](https://github.com/mikelobocyber/lobo-homelab)

---

## Table of Contents

- [Roadmap Overview](#roadmap-overview)
- [Phase 1 — Baseline Compliance](#phase-1--baseline-compliance)
- [Phase 2 — Intermediate](#phase-2--intermediate)
- [Phase 3 — Senior / Contractor Level](#phase-3--senior--contractor-level)
- [DoD 8140 Work Role Reference](#dod-8140-work-role-reference)
- [Timeline](#timeline)
- [Civilian Market Supplement](#civilian-market-supplement)
- [Repository Structure](#repository-structure)
- [Learning Philosophy](#learning-philosophy)

---

## Roadmap Overview

| Phase | Window | Focus |
|---|---|---|
| Phase 1 | Now → 12 mo | DoD compliance baseline — CC, Security+, CySA+ |
| Phase 2 | 12–24 mo | Offensive fundamentals — CEH, PNPT, PENTEST+ |
| Phase 3 | 3–5 yr | Senior contractor level — OSCP, CISSP, CISM |

---

## Phase 1 — Baseline Compliance

> Security+ is mandatory before any privileged DoD role. Get the Army COOL voucher before paying out of pocket.

| Certification | Exam | DoD 8140 Role | Prep Time | Status | Funding |
|---|---|---|---|---|---|
| ISC2 Certified in Cybersecurity (CC) | CC | Entry baseline | 1–2 mo | 🟡 In Progress | Free |
| CompTIA Security+ | SY0-701 | IAT/IAM Level II | 3–4 mo | 🔲 Up Next | Army COOL ✓ |
| CompTIA CySA+ | CS0-003 | IAT II / CSSP Analyst | 2–3 mo | 🔲 Planned | Army COOL ✓ |

### Phase 1 Notes

- **CC** — ISC2's free entry cert. Covers the same domains as Security+ at a high level — good warmup, no cost, worth doing now. Notes in [`ISC2-CC/`](./ISC2-CC/).
- **Security+** — Non-negotiable first milestone. Required for all DoD privileged access roles under 8140/8570. Apply for COOL voucher through unit S6/G6 or [cool.army.mil](https://cool.army.mil).
- **CySA+** — Defensive follow-on. Satisfies IAT Level II and CSSP Analyst roles. Take immediately after Security+. Pairs directly with the Wazuh SIEM work in [lobo-homelab](https://github.com/mikelobocyber/lobo-homelab).

---

## Phase 2 — Intermediate

> Target window: 12–18 months post-Security+. Defensive first, then offensive.

| Certification | Exam | DoD 8140 Role | Prep Time | Status | Funding |
|---|---|---|---|---|---|
| CEH | 312-50 | CSSP Analyst / IR | 2–3 mo | 🔲 Planned | Army COOL / EC-Council |
| PNPT | Practical | Pen Tester / Red Team | 2–3 mo | 🔲 Planned | TCM ~$399 |
| CompTIA PENTEST+ | PT0-002 | CSSP / Pen Tester | 2 mo | 🔲 Planned | Army COOL ✓ |
| GIAC GPEN | GPEN | CSSP / Pen Tester | 3 mo | 🔲 Planned | SANS ~$2,500+ |

### Phase 2 Notes

- **CEH** — DoD 8140-listed, COOL-eligible. Multiple-choice only — not a substitute for hands-on offensive creds in civilian markets. Pursue for compliance coverage, not as the primary offensive cert.
- **PNPT** — Best value practical offensive cert. TCM Security's exam requires compromising a real machine and writing a professional pentest report. Highly respected for contractor and civilian roles.
- **PENTEST+** — DoD-listed, COOL-eligible. Pairs with PNPT for dual coverage across both markets.
- **GPEN** — Pursue via Army SANS allocation if assigned to a cyber unit. Not worth the out-of-pocket cost otherwise.

---

## Phase 3 — Senior / Contractor Level

> Target window: 3–5 year horizon. These unlock IAM III and senior cleared contractor positions.

| Certification | Exam | DoD 8140 Role | Prep Time | Status | Funding |
|---|---|---|---|---|---|
| OSCP | Practical | Red Team / Pen Tester | 3–6 mo | 🔲 Planned | OffSec ~$1,499 |
| CISSP | CAT | IAM Level III / CSSP Mgr | 6–12 mo | 🔲 Planned | Army COOL ✓ (5yr exp req) |
| CISM | CISM | IAM Level III | 4–6 mo | 🔲 Planned | Army COOL ✓ |
| CCSP | CCSP | Cloud / IAM | 4–6 mo | 🔲 Planned | ISC2 / COOL |

### Phase 3 Notes

- **OSCP** — Gold standard for offensive contractor and civilian roles. Requires 3–6 months of dedicated lab time. Budget accordingly. The GOAD Active Directory lab in [lobo-homelab](https://github.com/mikelobocyber/lobo-homelab) is direct prep.
- **CISSP** — Requires 5 years of paid security experience. Can sit early as an Associate of ISC2. Note: as of April 2026, ISC2 removed OSCP, CEH, CISA, and CRISC from the experience waiver list.
- **CISM** — Management-focused. Aligns with 17A officer track and ISSM/cyber officer billets. Valuable for both DoD and civilian leadership roles.
- **CCSP** — Cloud security. Increasingly required for cleared and civilian contractor positions in cloud-adjacent work.

---

## DoD 8140 Work Role Reference

| Category | Role | Required Cert(s) |
|---|---|---|
| IAT I | Helpdesk / basic IT | A+, Network+, CCNA-Sec |
| IAT II | Sysadmin, network ops | Security+, CySA+ |
| IAT III | Sr. engineer / security architect | CISA, GCIH, CISSP |
| IAM I | ISSO | Security+, CAP |
| IAM II | ISSM, cyber officer | CISM, CISSP, CAP |
| IAM III | CISO, senior cyber officer | CISM, GSLC, CISSP |
| CSSP Analyst | SOC analyst, threat hunter | CEH, CySA+, CFR |
| CSSP IR | Incident response, forensics | CEH, GCIH, CHFI |
| CSSP Mgr | SOC lead, team chief | CEH, CISM, CISSP |

---

## Timeline

| Window | Target | Notes |
|---|---|---|
| Now → 6 mo | ISC2 CC + Security+ | CC first for warmup. COOL voucher before paying. 1 hr/day minimum. |
| 6 → 12 mo | CySA+ → CEH / PNPT | Defensive then offensive. CEH via COOL. |
| Year 2 | PENTEST+ / GPEN | SANS via Army if cyber-assigned. |
| Year 3–4 | OSCP | Budget 6 mo + dedicated lab time. |
| Year 5+ | CISSP | Needs 5 yrs exp. Unlocks IAM III and senior cleared roles. |

---

## Civilian Market Supplement

The DoD 8140 track covers compliance. The civilian market runs on a different filter — hands-on evidence over cert lists. These fill the gap.

### Practice Platforms

| Platform | Purpose | Priority |
|---|---|---|
| [Hack The Box](https://hackthebox.com) | Unguided machine exploitation — what civilian pen test interviewers ask about | High |
| [TryHackMe](https://tryhackme.com) | Guided rooms, good for Security+ / CySA+ concept reinforcement | High |
| [LetsDefend](https://letsdefend.io) | Blue team / SOC analyst simulation — useful if targeting analyst roles | Medium |
| [VulnHub](https://vulnhub.com) | Offline vulnerable VMs — runs directly in the Proxmox homelab | Medium |

### Homelab as Portfolio Evidence

The [lobo-homelab](https://github.com/mikelobocyber/lobo-homelab) stack (Proxmox, Wazuh, GOAD, Kali, WireGuard, LUKS, PiHole) is a significant portfolio asset for civilian SOC and IR roles. What converts it from a setup into evidence:

- Wazuh detection rules and alert walkthroughs documented in `docs/`
- GOAD Active Directory attack chains written up end-to-end
- Network topology diagram showing segmentation decisions
- Screenshots of real alerts, not just dashboards

### CTF Writeups

HTB and THM box writeups belong in this repo under `ctf-writeups/` — structured as recon → foothold → privesc → takeaway. One writeup a week compounds fast. After three months it's a body of work. After six months it's something to walk through in an interview.

### Civilian-Relevant Additions

| Certification | Why | When |
|---|---|---|
| AWS Cloud Practitioner | Cloud baseline — many civilian postings list it as a filter | After Security+ |
| AWS Security Specialty | High salary premium, pairs with CCSP prep | Year 2–3 |

---

## Repository Structure

```
cybersecurity-certifications/
├── _roadmap/
│   └── DoD_Cert_OneSheet.pdf
├── ISC2-CC/
│   ├── notes.md
│   └── resources.md
├── CompTIA/
│   ├── Security+/
│   └── CySA+/
├── EC-Council/
│   └── CEH/
├── ctf-writeups/
│   └── README.md
└── README.md
```

Cert folders contain notes written during study, key concepts in own words, resources actually used, and proof of completion. CTF writeups are structured methodology walkthroughs, not just solutions.

---

## Status Key

| Symbol | Meaning |
|---|---|
| 🟢 | Complete |
| 🟡 | In Progress |
| 🔲 | Planned |
| ⏸ | On Hold |

---

## Learning Philosophy

- Certs open doors. Hands-on work proves you can walk through them.
- Document everything — writeups compound over time.
- Build consistency through daily reps, not bursts.
- Learn actively, not passively.

---

*Sources: DoD 8140.03M · DoD 8570.01-M · Army COOL · NICE Framework · ISC2 Workforce Study 2024*  
*Funding: [cool.army.mil](https://cool.army.mil)*
