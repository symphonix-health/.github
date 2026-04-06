<div align="center">

# Symphonix Health
**Intelligent Healthcare Infrastructure**

[![Website](https://img.shields.io/badge/Website-symphonix--health.com-6366F1?style=for-the-badge)](https://symphonix-health.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Symphonix_Health-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/company/symphonix-health)

</div>

---

We build the foundation layer for AI-powered healthcare — the infrastructure that lets clinical AI agents discover each other, communicate securely, and operate under full governance.

Three products. One platform. Zero patient data in the registry.

---

### 🚄 BulletTrain — Health Information Exchange

160+ microservice orchestration platform. Speaks FHIR R4, HL7v2, CDA, X12, DICOM natively. Maps SNOMED CT, ICD-10, ICD-11, LOINC, CPT, RxNorm, and dm+d in real time. Not an integration engine — a governed orchestration platform where clinical workflows, AI agents, and health data converge through a single HIE layer. Free to install and deploy on your own infrastructure — like Linux for healthcare interoperability. `Free · Self-hosted`

### 🌐 GHARRA — Global Agent Registry & Routing Authority

Federated, zero-trust registry for healthcare AI agents. The DNS for clinical AI — agents register capabilities, callers discover them across organisational and national boundaries. Zero patient data by design. Emergency care is never blocked. 9-rule ABAC policy engine with three-tier federation (Root → Sovereign → Organisational). Hosted and operated by Symphonix Health — subscribers register agents and consume discovery through the managed platform. `Hosted · Pay-per-use`

### 🔗 Nexus A2A — Agent-to-Agent Protocol

Secure protocol for clinical AI agents to delegate tasks to each other. JSON-RPC 2.0 with 13-point route admission validation. 25 reference agents across 5 clinical workflow domains. 7,000+ test scenarios with 100% pass rate. Every interaction is governed, audited, and consent-verified. `Protocol`

---

## How they work together

```
                 ┌─────────────────────────────────────────┐
                 │            BulletTrain (HIE)             │
                 │   Orchestration · Routing · Terminology  │
                 └──────────┬──────────────┬───────────────┘
                            │              │
                 ┌──────────▼──────┐  ┌────▼──────────────┐
                 │     GHARRA      │  │    Nexus A2A       │
                 │  Discovery +    │  │  Secure agent-to-  │
                 │  Trust Bundles  │  │  agent transport   │
                 └──────────┬──────┘  └────┬──────────────┘
                            │              │
           ┌────────────────┼──────────────┼────────────────┐
           │                │              │                │
      ┌────▼────┐   ┌──────▼──┐   ┌───────▼──┐   ┌────────▼──┐
      │ Triage  │   │ Imaging │   │ Pharmacy │   │ Discharge │
      │  Agent  │   │  Agent  │   │  Agent   │   │   Agent   │
      └─────────┘   └─────────┘   └──────────┘   └───────────┘
```

**BulletTrain** decides which agent to call. **GHARRA** resolves agents and provides trust bundles. **Nexus A2A** validates trust and delivers the call. Each step is governed, consent-gated, and audit-trailed.

---

## Design principles

| Principle | What it means |
|---|---|
| **Zero patient data in the registry** | GHARRA never stores or proxies PHI. Three-layer detection blocks it at the gateway. |
| **Emergency care is never blocked** | Break-glass override bypasses all gates except authentication. Not by policy. Not by billing. |
| **Governed by design** | Every agent interaction passes 13-point admission control — identity, trust, consent, jurisdiction, and compliance. |
| **Built on OpenHIE** | WHO-endorsed Health Information Exchange architecture, extended for AI agent orchestration. |
| **BulletTrain is free to deploy** | Install on your own infrastructure at no cost — like Linux for healthcare interoperability. |
| **GHARRA is a managed service** | Agent discovery and trust are hosted by Symphonix Health. Subscribers register agents and consume routing — we handle federation and governance. |

---

## Who this is for

- **Health system CIOs/CTOs** evaluating AI-native infrastructure
- **Enterprise architects** designing interoperability for clinical AI
- **AI engineers** building healthcare agents that need governed communication
- **Digital health startups** looking for standards-based agent discovery and routing
- **National health programmes** deploying AI-native infrastructure at scale

---

## Get started

Visit **[symphonix-health.com](https://symphonix-health.com)** to explore the platform, read technical documentation, and book a walkthrough.

- 📖 [Documentation](https://symphonix-health.com/pages/developers.html) — Technical specs, API reference, architecture guides
- 🏥 [Clinical Governance](https://symphonix-health.com/pages/clinical-governance.html) — How we govern AI in clinical settings
- 🔒 [Trust & Governance](https://symphonix-health.com/pages/trust-governance.html) — Security architecture and compliance
- 📅 [Book a Walkthrough](https://symphonix-health.com/pages/schedule-demo.html) — See the platform in action

---

<div align="center">
  <sub>Dublin, Ireland · <a href="https://symphonix-health.com">symphonix-health.com</a> · <a href="mailto:info@symphonix-health.com">info@symphonix-health.com</a></sub>
  <br/>
  <sub>Named for Aneurin Bevan, founder of the NHS. Healthcare infrastructure should be available to all.</sub>
</div>
