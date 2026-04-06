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

<br/>

<table>
<tr>
<td width="33%" valign="top">

### 🚄 BulletTrain
**Health Information Exchange**

160+ microservice orchestration platform. Speaks FHIR R4, HL7v2, CDA, X12, DICOM natively. Maps SNOMED CT, ICD-10, ICD-11, LOINC, CPT, RxNorm, and dm+d in real time.

Not an integration engine. A governed orchestration platform where clinical workflows, AI agents, and health data converge.

`Enterprise`

</td>
<td width="33%" valign="top">

### 🌐 [GHARRA](https://github.com/Symphonix-Health/global-agent-registry)
**Global Agent Registry**

Federated, zero-trust registry for healthcare AI agents. The DNS for clinical AI — agents register capabilities, callers discover them across organisational and national boundaries.

Zero patient data by design. Emergency care is never blocked.

`Apache 2.0` · `Python`

</td>
<td width="33%" valign="top">

### 🔗 [Nexus A2A](https://github.com/Symphonix-Health/nexus-a2a-protocol)
**Agent-to-Agent Protocol**

Open protocol for clinical AI agents to delegate tasks securely. JSON-RPC 2.0 with 13-point route admission validation. 25 reference agents. 7,000+ test scenarios. 100% pass rate.

Every interaction is governed, audited, and consent-verified.

`Apache 2.0` · `Python`

</td>
</tr>
</table>

<br/>

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

<br/>

## Quick start

```bash
# GHARRA — Agent Discovery
git clone https://github.com/Symphonix-Health/global-agent-registry.git
cd global-agent-registry && pip install -e ".[dev]"
python -m gharra.api.main
curl http://localhost:8400/v1/discover?capability=triage

# Nexus A2A — Agent Communication
git clone https://github.com/Symphonix-Health/nexus-a2a-protocol.git
cd nexus-a2a-protocol && pip install -e ".[dev]"
python tools/launch_all_agents.py --with-gateway
python tools/helixcare_scenarios.py --run chest_pain_cardiac
```

<br/>

## Design principles

| Principle | What it means |
|---|---|
| **Zero patient data in the registry** | GHARRA never stores or proxies PHI. Three-layer detection blocks it at the gateway. |
| **Emergency care is never blocked** | Break-glass override bypasses all gates except authentication. Not by policy. Not by billing. |
| **Open where it matters** | Discovery (GHARRA) and communication (Nexus) are Apache 2.0. The connectivity layer should be a public good. |
| **13-point admission control** | Every agent-to-agent request passes identity, trust, consent, jurisdiction, and governance checks. |
| **Built on OpenHIE** | WHO-endorsed Health Information Exchange architecture, extended for AI agent orchestration. |

<br/>

## Who this is for

- **Health system CIOs/CTOs** evaluating AI-native infrastructure
- **Enterprise architects** designing interoperability for clinical AI
- **AI engineers** building healthcare agents that need governed communication
- **Digital health startups** looking for open standards to build on
- **National health programmes** deploying AI-native infrastructure at scale

<br/>

<div align="center">
  <sub>Dublin, Ireland · <a href="https://symphonix-health.com">symphonix-health.com</a> · <a href="mailto:info@symphonix-health.com">info@symphonix-health.com</a></sub>
  <br/>
  <sub>Named for Aneurin Bevan, founder of the NHS. Healthcare infrastructure should be available to all.</sub>
</div>
