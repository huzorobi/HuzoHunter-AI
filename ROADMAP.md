# HuzoHunter AI — Roadmap

> This roadmap is indicative and will shift as research progresses. Dates are intentionally
> omitted during the R&D phase.

## Phase 0 — Foundations ✅ (current)

- [x] Define vision, principles, and target market
- [x] Select core technology stack (Wazuh, OpenSearch, Grafana, local LLMs)
- [x] Document high-level architecture
- [ ] Stand up a local lab environment

## Phase 1 — Data Pipeline

- [ ] Deploy Wazuh and onboard endpoint agents
- [ ] Stream events into OpenSearch with normalised schema
- [ ] Ingest Active Directory authentication telemetry
- [ ] Ingest Microsoft 365 security signals
- [ ] Baseline Grafana dashboards for visibility

## Phase 2 — Local AI Layer

- [ ] Integrate a local LLM with GPU acceleration
- [ ] Natural-language query interface over OpenSearch data
- [ ] Explainable investigation output (evidence + reasoning)
- [ ] Prompt/result safety guardrails

## Phase 3 — Detection & Automation

- [ ] Security event correlation across sources
- [ ] Threat-intelligence enrichment pipeline
- [ ] Automated threat-hunting playbooks
- [ ] Alerting with actionable context

## Phase 4 — Hardening & Pilot

- [ ] Role-based access control and audit logging
- [ ] Deployment/packaging for SMB and air-gapped environments
- [ ] Pilot deployment with early partners
- [ ] Feedback loop and iteration

## Future Ideas

- Vulnerability management module
- Operator-in-the-loop response automation
- Multi-tenant deployment for MSSPs

---

*Have a suggestion? Open an Issue or start a Discussion.*
