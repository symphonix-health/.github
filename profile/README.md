<div align="center">
  <br/>
  <h1>Symphonix Health</h1>
  <strong>Intelligent Healthcare Infrastructure</strong>
  <br/><br/>

  [![Website](https://img.shields.io/badge/Website-symphonix--health.com-6366F1?style=for-the-badge)](https://symphonix-health.com)
  [![License](https://img.shields.io/badge/License-Apache_2.0-orange?style=for-the-badge)](https://opensource.org/licenses/Apache-2.0)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Symphonix_Health-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/company/symphonix-health)

  <br/>
</div>

---

We build the foundation layer for AI-powered healthcare — the infrastructure that lets clinical AI agents discover each other, communicate securely, and operate under full governance.

Three products. One platform. Zero patient data in the registry.

---

### 🚄 BulletTrain — Health Information Exchange

160+ microservice orchestration platform. Speaks FHIR R4, HL7v2, CDA, X12, DICOM natively. Maps SNOMED CT, ICD-10, ICD-11, LOINC, CPT, RxNorm, and dm+d in real time. Not an integration engine — a governed orchestration platform where clinical workflows, AI agents, and health data converge through a single HIE layer.

### 🌐 GHARRA — Global Agent Registry & Routing Authority

Federated, zero-trust registry for healthcare AI agents. The DNS for clinical AI — agents register capabilities, callers discover them across organisational and national boundaries. Zero patient data by design. Emergency care is never blocked. 9-rule ABAC policy engine with three-tier federation (Root → Sovereign → Organisational).

### 🔗 Nexus A2A — Agent-to-Agent Protocol

Open protocol for clinical AI agents to delegate tasks securely. JSON-RPC 2.0 with 13-point route admission validation. 25 reference agents across 5 clinical workflow domains. 7,000+ test scenarios with 100% pass rate. Every interaction is governed, audited, and consent-verified.

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
| **Open where it matters** | Discovery and communication protocols are Apache 2.0. The connectivity layer should be a public good. |
| **13-point admission control** | Every agent-to-agent request passes identity, trust, consent, jurisdiction, and governance checks. |
| **Built on OpenHIE** | WHO-endorsed Health Information Exchange architecture, extended for AI agent orchestration. |

---

## Who this is for

- **Health system CIOs/CTOs** evaluating AI-native infrastructure
- **Enterprise architects** designing interoperability for clinical AI
- **AI engineers** building healthcare agents that need governed communication
- **Digital health startups** looking for open standards to build on
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
