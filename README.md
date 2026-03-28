# SOC Analyst AI — Threat Intelligence Platform

> An AI-powered Security Operations Center dashboard simulating real analyst workflows — built for learning, portfolio demonstration, and cybersecurity interview preparation.

![Platform](https://img.shields.io/badge/Platform-Web-blue)
![MITRE](https://img.shields.io/badge/MITRE%20ATT%26CK-v14-red)
![AI](https://img.shields.io/badge/AI-GPT--4o%20Powered-purple)
![Status](https://img.shields.io/badge/Status-Active-green)

---

## Live Demo

🔗 [Launch SOC Analyst AI](https://xavianab.github.io/SOC-Analyst-AI)

> Sign up with any email and password to access the dashboard. No real credentials required.

---

## What Is This?

SOC Analyst AI is a fully functional threat intelligence dashboard that replicates the core workflow of a real Security Operations Center. Built from scratch using vanilla JavaScript, HTML, and CSS — no frameworks — to demonstrate deep understanding of SOC operations, MITRE ATT&CK, and AI-assisted threat analysis.

---

## Core Features

### Three-Tier Analyst System
- **T1 — Triage:** Fast surface-level assessment. Real or noise?
- **T2 — Investigation:** Deep dive into attack chain and containment.
- **T3 — Threat Hunt:** Hypothesis-driven hunting beyond the alerts.

### AI-Powered Verdict Engine
- TRUE POSITIVE / FALSE POSITIVE / NEEDS INVESTIGATION
- Confidence score 0–100% per alert
- Structured JSON verdict with justification

### Dynamic Risk Scoring
- Severity + event count + MITRE technique danger weighting
- Score displayed as colored badge on every alert

### Attack Chain Visualizer
```
[Recon] → [Initial Access] → [Execution] → [C2 ◀ HERE] → [Exfil]
```

### Additional Features
- MITRE ATT&CK v14 full tactic mapping
- Live alert simulation (new alerts every 30 seconds)
- Incident report generator (one-click HTML export)
- Analyst leaderboard (TP/FP accuracy tracking)
- 7-day threat timeline, radar chart, heatmap
- Dark / Light mode toggle

---

## Technology Stack

| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Charts | Chart.js |
| AI Engine | GPT-4o via GitHub Models API |
| Framework | MITRE ATT&CK v14 |
| Hosting | GitHub Pages |

---

## SOC Concepts Demonstrated

- Alert triage methodology
- True Positive / False Positive / False Negative classification
- MITRE ATT&CK framework — full kill chain mapping
- Threat hunting mindset
- Incident Response lifecycle
- Dwell time awareness
- Living off the Land (LotL) detection

---

## Roadmap

- [ ] Live threat intel feed (OTX AlienVault, abuse.ch)
- [ ] Switch to Anthropic Claude API
- [ ] Node.js backend for persistent accounts
- [ ] Real-time WebSocket alert streaming

---

## About The Builder

Built by **Xavian B** — cybersecurity professional, Seattle WA.

- BS Cybersecurity 
- CompTIA A+, Network+, Security+
- Microsoft Azure AI Engineer Associate
- Microsoft Internship

> Built to go beyond certifications — to demonstrate I don't just know the theory, I can build the tools.

---

## Connect

- GitHub: [@xavianab](https://github.com/xavianab)
- LinkedIn: [Xavian B](https://linkedin.com/in/xaviannoor)

---

> *"Absence of alerts ≠ absence of attackers."*
> Built for the analysts who know the difference.
