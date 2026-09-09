<div align="center">
  <img src="https://raw.githubusercontent.com/symphonix-health/.github/master/profile/assets/symphonix-health-logo-dark.svg" alt="Symphonix Health" width="420" />
  <br />
  <strong>Governed connectivity for healthcare AI.</strong>
  <br />
  Move clinical and AI data safely, reliably, and at national scale.
  <br /><br />
  <a href="https://github.com/symphonix-health/symphonix-health.github.io/blob/main/docs/system-catalogue.md"><img alt="System catalogue" src="https://img.shields.io/badge/catalogue-64_repos-14919B?style=flat-square" /></a>
  <img alt="Evidence rule" src="https://img.shields.io/badge/evidence-repo_local_proof_required-14B8A6?style=flat-square" />
</div>

<p align="center">
  <a href="https://github.com/symphonix-health/symphonix-health.github.io/blob/main/docs/system-catalogue.md">
    <img src="https://raw.githubusercontent.com/symphonix-health/.github/master/profile/assets/github-org-atlas.svg" alt="Symphonix Health GitHub system atlas" width="100%" />
  </a>
</p>

## Platform

**HelixCare Digital Hospital Ecosystem**

Symphonix Health develops and operates HelixCare — a governed digital hospital ecosystem connecting interoperability infrastructure, clinical applications, and AI safety assurance into one delivery model.

The repositories in this organisation represent the HelixCare stack end-to-end:

- Core interoperability and agent orchestration (for secure exchange, protocol translation, routing, and trust)
- Clinical and operational systems (from access, diagnostics, prescribing, and emergency workflows to specialty and population-health services)
- Safety, assurance, and AI engineering (clinical safety case workflows, requirements governance, verification, and agent SDLC automation)
- Documentation, implementation, and operations support (public docs, implementation assets, tooling, and organisational infrastructure)
For the current repository inventory, refer to the live system catalogue and organisation repository list.

The catalogue was verified from `Symphonix-Health` on 2026-08-24. It is an orientation index, not a readiness verdict. Use repo-local tests, CAID artefacts, seeded data, and runbooks for delivery, safety, or compliance claims.

`FHIR R4` | `HL7 v2` | `CDA` | `X12` | `DICOM` | `SNOMED CT` | `ICD-10/11` | `OpenHIE` | `GHARRA` | `Nexus A2A`

### Platform spine

| Repository | Role |
|---|---|
| [BulletTrain](https://github.com/symphonix-health/BulletTrain) | FHIR R4-native health information exchange and orchestration fabric. |
| [global-agent-registry](https://github.com/symphonix-health/global-agent-registry) | GHARRA registry for healthcare agent discovery, trust, routing, and federation. |
| [nexus-a2a-protocol](https://github.com/symphonix-health/nexus-a2a-protocol) | JSON-RPC 2.0 agent-to-agent protocol and command-centre reference implementation. |
| [symphonix-bridge-sdk](https://github.com/symphonix-health/symphonix-bridge-sdk) | Protocol translation SDK using FHIR R4 as the canonical clinical pivot. |
| [prompt-engine](https://github.com/symphonix-health/prompt-engine) | YAML-driven prompt assembly, policy clauses, and multi-agent optimisation. |

### Clinical sibling systems

| Repository | Role |
|---|---|
| [ambulance-ems](https://github.com/symphonix-health/ambulance-ems) | Ambulance and EMS computer-aided dispatch, ePRF, and A&E handover. |
| [analytics-bi](https://github.com/symphonix-health/analytics-bi) | Healthcare analytics and BI platform with OLAP cubes, materialised-view SLAs, dashboard embedding, and k-anonymity. |
| [appointment-system](https://github.com/symphonix-health/appointment-system) | FHIR R4 appointment, slot, and scheduling workflows. |
| [blood-transfusion](https://github.com/symphonix-health/blood-transfusion) | Blood transfusion and blood-bank workflow surface. |
| [cancer-pathway-tracker](https://github.com/symphonix-health/cancer-pathway-tracker) | Cancer pathway tracking, MDT coordination, staging, and treatment planning. |
| [citizen-portal](https://github.com/symphonix-health/citizen-portal) | National patient health portal for record access, consent management, proxy and carer grants, and break-glass notifications. |
| [clinical-pathways](https://github.com/symphonix-health/clinical-pathways) | NICE and WHO pathway personalisation and execution over Bridge SDK routes. |
| [clinical-trial-system](https://github.com/symphonix-health/clinical-trial-system) | Clinical trial management for protocol lifecycle, sites, subjects, IP accountability, and adverse events. |
| [community-nursing](https://github.com/symphonix-health/community-nursing) | District nursing visit coordination, wound care, and palliative workflows. |
| [epaccs](https://github.com/symphonix-health/epaccs) | Electronic palliative care coordination with ReSPECT, ADRT, DNACPR, and proxy consent. |
| [eps](https://github.com/symphonix-health/eps) | Electronic Prescription Service clinical workflow simulator. |
| [erp](https://github.com/symphonix-health/erp) | Healthcare enterprise ERP for GL, AP, AR, procurement, inventory, HR, and payroll. |
| [etps](https://github.com/symphonix-health/etps) | Electronic Transfer of Prescriptions transport simulator. |
| [genomics-interpretation](https://github.com/symphonix-health/genomics-interpretation) | Genomic variant interpretation and clinical reporting. |
| [gp-system](https://github.com/symphonix-health/gp-system) | England primary-care workflows, prescribing, referrals, results, and GP Connect. |
| [hear-the-risk](https://github.com/symphonix-health/hear-the-risk) | Patient-facing risk communication that renders clinical risk scores as sound and plain language. |
| [helixcare-diagnostic-access-network](https://github.com/symphonix-health/helixcare-diagnostic-access-network) | Early-stage federated diagnostics access gateway: contracts, CAID artefacts, seed data, journeys, and safety evidence. |
| [HMIS](https://github.com/symphonix-health/HMIS) | Aggregate facility reporting, disease surveillance, indicators, and DHIS2-style flows. |
| [insurance-eclaims](https://github.com/symphonix-health/insurance-eclaims) | EDI X12 claims, eligibility, prior authorisation, adjudication, and denial management. |
| [lis](https://github.com/symphonix-health/lis) | Laboratory information system with HL7 v2 MLLP, FHIR R4 results, QC, and critical values. |
| [maternity-system](https://github.com/symphonix-health/maternity-system) | Booking-to-discharge maternity record, CTG-linked escalation, and PMRT package creation. |
| [mha-administration](https://github.com/symphonix-health/mha-administration) | Mental Health Act administration, detention workflows, tribunal management, and section tracking. |
| [mortuary-and-me](https://github.com/symphonix-health/mortuary-and-me) | Medical Examiner death certification, coroner referral, mortuary custody, and donation workflows. |
| [nursing-station](https://github.com/symphonix-health/nursing-station) | Inpatient ward workflow: observations, tasks, care plans, medicines, and handover. |
| [pacs-ris](https://github.com/symphonix-health/pacs-ris) | Radiology information system and DICOM archive with DICOMweb viewer, reporting workflow, and critical-finding paging. |
| [patient360-assistant](https://github.com/symphonix-health/patient360-assistant) | Governed Patient360 assistant federating healthcare systems through the BulletTrain MCP Gateway. |
| [pharmacy-system](https://github.com/symphonix-health/pharmacy-system) | Community and hospital dispensing with BCMA five-rights checks and a controlled-drug register. |
| [picis-system](https://github.com/symphonix-health/picis-system) | Acute clinical information system for theatres, anaesthesia, and critical care. |
| [provider-portal](https://github.com/symphonix-health/provider-portal) | Clinician and receptionist workspace with FHIR R4 write-path, staged MFA login, and signed prescriptions. |
| [rehabilitation](https://github.com/symphonix-health/rehabilitation) | Therapy plans, exercise programmes, and recovery tracking. |
| [scheduling-gateway](https://github.com/symphonix-health/scheduling-gateway) | Referral modality router between appointment, telemedicine, and asynchronous workflows. |
| [screening-recall](https://github.com/symphonix-health/screening-recall) | Population screening recall and invitation management. |
| [supply-chain-erp](https://github.com/symphonix-health/supply-chain-erp) | Inventory, purchasing, logistics, cold-chain breach handling, and UDI movement tracking. |
| [symphonix-eps-ig](https://github.com/symphonix-health/symphonix-eps-ig) | FHIR R4 implementation guide for electronic prescription workflows. |
| [symphonix-health-counterpoint](https://github.com/symphonix-health/symphonix-health-counterpoint) | Split-identity architecture: patient PII in an encrypted on-device vault, pseudonymised clinical data server-side. |
| [triage-api](https://github.com/symphonix-health/triage-api) | Clinical risk triage API with traditional and AI-specific observability signals. |
| [vr-therapy](https://github.com/symphonix-health/vr-therapy) | Clinician console for immersive VR therapy sessions with live status, abort, and distress monitoring. |

### Agent, assurance, and engineering systems

| Repository | Role |
|---|---|
| [caid-agent](https://github.com/symphonix-health/caid-agent) | Full-SDLC AI agent system for requirements, generation, review, and traceability. |
| [csaa](https://github.com/symphonix-health/csaa) | Clinical safety assurance, hazard seeding, and DCB0129/DCB0160 artefact drafting. |
| [REA-Agent-mcp](https://github.com/symphonix-health/REA-Agent-mcp) | Requirements Engineering Agent MCP server and requirements-quality tools. |
| [signalbox-mcp](https://github.com/symphonix-health/signalbox-mcp) | Browser, GUI, accessibility, and scenario verification driver. |
| [agent-skills](https://github.com/symphonix-health/agent-skills) | Shared agent skills and operating guidance. |
| [health-agent-workspace](https://github.com/symphonix-health/health-agent-workspace) | Cross-agent workspace harness and health-agent integration context. |
| [healthcare-pain-points-plan](https://github.com/symphonix-health/healthcare-pain-points-plan) | Healthcare pain-point planning, requirements, and traceability inputs. |
| [ormdet-governance-console](https://github.com/symphonix-health/ormdet-governance-console) | Governance console for ormdet regulatory, risk, and audit reporting with policy decisions and evidence. |
| [second-brain-kb](https://github.com/symphonix-health/second-brain-kb) | Durable cross-agent knowledge base and repository map. |
| [symphonix-assurance](https://github.com/symphonix-health/symphonix-assurance) | Estate-wide UAT programme, V-model gates, test catalogue, and assurance reporting. |
| [symphonix-emulator-kit](https://github.com/symphonix-health/symphonix-emulator-kit) | Runtime framework for per-workspace external-system emulators with fixture and LLM backends. |
| [symphonix-health-research-to-caid-agent](https://github.com/symphonix-health/symphonix-health-research-to-caid-agent) | Published-paper mining that turns research findings into CAID prompts, evidence bundles, and gated implementation handoffs. |
| [symphonix-national-health-metadata-library](https://github.com/symphonix-health/symphonix-national-health-metadata-library) | Source-aware metadata, validation, and provenance library for synthetic health-data assurance. |
| [workspace-tooling](https://github.com/symphonix-health/workspace-tooling) | Workspace-wide port registry, inventory reports, and enforcement hooks. |

### Public, design, and operational support

| Repository | Role |
|---|---|
| [.github](https://github.com/symphonix-health/.github) | Organisation profile README, the GitHub system atlas, and public GitHub landing content. |
| [design-system](https://github.com/symphonix-health/design-system) | Design tokens, brand assets, UI kits, and the Symphonix launchpad prototype. |
| [kenya-uhc-implementation](https://github.com/symphonix-health/kenya-uhc-implementation) | Kenya SHA/SHIF UHC implementation planning and pilot evidence. |
| [symphonix-demo-tunnel](https://github.com/symphonix-health/symphonix-demo-tunnel) | Governed, short-lived Cloudflare demo tunnel control plane for the estate. |
| [symphonix-email-action-worker](https://github.com/symphonix-health/symphonix-email-action-worker) | Cloudflare inbound email worker for structured agent actions. |
| [symphonix-health.github.io](https://github.com/symphonix-health/symphonix-health.github.io) | Documentation site for platform, protocol, architecture, and catalogue content. |
| [symphonix-public](https://github.com/symphonix-health/symphonix-public) | Public website, blog, launch material, and marketing site assets. |
| [tool-library](https://github.com/symphonix-health/tool-library) | Non-healthcare civic-domain CAID pipeline stress-test target. |


## Documentation

- [System catalogue](https://symphonix-health.github.io/docs/system-catalogue)
- [Nexus A2A protocol](https://github.com/symphonix-health/nexus-a2a-protocol)
- [GHARRA global agent registry](https://github.com/symphonix-health/global-agent-registry)
- [Documentation site](https://symphonix-health.github.io)
