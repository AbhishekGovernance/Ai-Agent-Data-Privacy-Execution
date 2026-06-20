# AI Agent — Data & Privacy Execution

**Using AI Agents in Privacy Operations with Governance Guardrails — Powered by MCP Protocol**

Prepared by **Abhishek Sinha** — Data Governance, Privacy & AI Convergence

---

## Two Projects. One Theme.

This repository contains two distinct proof of concepts — both demonstrating AI agents operating in privacy and data governance contexts.

---

## Project 2 — AI-Native Privacy Management Platform (11-layer POC)

**What it is:** A working prototype of an AI-native privacy management platform — built and operated by AI agents, with humans governing from above. Architecturally distinct from OneTrust, DataGrail, and BigID, which are human-operated with AI assistance. This inverts the model.

**Positioning:** AI agents operate. Humans govern.

### Live Demo
👉 **[Open the platform](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/)** — no login required, works on any device

| Layer | What the AI agent does |
|---|---|
| [Layer 1 — Data Discovery](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer1-data-discovery.html) | Scans 4 systems · finds health data in CRM · 2 critical findings |
| [Layer 2 — Classification](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer2-classification.html) | 39 items · 22 personal · 13 sensitive · 4 special category |
| [Layer 3 — Consent](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer3-consent.html) | Marketing campaign enforced · 6 allowed · 4 blocked |
| [Layer 4 — Cookie & Tracking](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer4-cookie-tracking.html) | 14 technologies · 3 violations blocked |
| [Layer 5 — Privacy Notice](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer5-privacy-notice.html) | v4 drafted same day · 4 jurisdictions |
| [Layer 6 — DSR Management](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer6-dsr.html) | 5 requests · 1 critical overdue · 2 auto-fulfilled |
| [Layer 7 — Retention](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer7-retention.html) | 2 overdue disposals · legal hold · RoPA live |
| [Layer 8 — Risk](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer8-risk.html) | Risk score 58 · 2 critical · AU 62% · GDPR 58% |
| [Layer 9 — Breach](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer9-breach.html) | Notifiable breach · OAIC + ICO overdue · 6 drafts ready |
| [Layer 10 — Assessments](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer10-assessments.html) | DPIA drafted in 0 days · 3 PIAs triggered |
| [Layer 11 — Governance](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/platform-layer11-governance.html) | 6 DPO decisions · tap to approve · audit trail |

### Stakeholder Deck
📥 Download `platform-poc-presentation.pptx` above

---

## Project 1 — AI Agent Executing E2E Privacy Workflows via MCP

**What it is:** A working demonstration of an AI agent — connected to an already-implemented governance/privacy platform via MCP — continuously monitoring, detecting, analysing, and escalating data and privacy operations with full governance guardrails.

**Positioning:** AI agent as operator of an existing platform.

### Live Demo
👉 **[Open Project 1 demo](https://abhishekgovernance.github.io/Ai-Agent-Data-Privacy-Execution/agent-poc-live-demo.html)**

### What is demonstrated
Four scenarios — one governed AI agent — zero autonomous irreversible actions:

- **Scenario 1 — Personal Data Discovery** — Agent scanned 3 source systems, classified 32 personal data fields, detected health data (special category) in a CRM where it should not be. Flagged for DPO review — not deleted autonomously.
- **Scenario 2 — DSR Management** — Agent identified 3 overdue data subject requests — one 26 days past deadline.
