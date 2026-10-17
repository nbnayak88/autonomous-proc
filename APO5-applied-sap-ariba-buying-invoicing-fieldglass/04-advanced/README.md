# APO5 — Level 4: Advanced

**Series:** Applied SAP Ariba Buying & Invoicing + Extended Workforce Management by SAP Fieldglass  
**Industry:** GICS03 Industrials  
**Case study:** OmniWorks Industrial Systems Ltd.  
**Learning Lab:** Industry Immersion Lab (IIL) — Build  
**Duration:** 20 hours · 10 sessions × 2 hours  
**Level:** 4 of 5  
**Target persona:** Solution architect

## Sprint outcome

Design scalable multi-country application, integration, data, security, and deployment architecture.

## OmniWorks case-study mission

Illustrative pilot: 12 sites, six countries, 2,500 external workers, 120 suppliers; scope includes Buying, Invoicing, Fieldglass contingent labor and SOW.

**Case-study distinction:** The OmniWorks reference enterprise operates in 36 countries, with 74,000 employees and 61 plants/engineering/assembly facilities. Workforce engagement counts, pilot sizes, budgets, and scenarios in this sprint are illustrative learning assumptions unless otherwise stated.

## Business scope and system boundaries

- **SAP Ariba Buying & Invoicing:** Requisitioning, buying and invoice-related processes within the configured procurement landscape.
- **SAP Fieldglass:** Contingent workforce and services procurement engagement processes, including worker assignments and SOWs.
- **SAP S/4HANA / ERP:** Relevant purchasing, financial accounting, cost objects, and payment processes according to the implementation design.
- **SAP SuccessFactors / HR:** Internal employee HR data and applicable organizational reference information.
- **IAM and integration services:** Identity/access lifecycle and governed cross-system connectivity.

Do not assume Ariba and Fieldglass share identical objects or that a particular integration is available out of the box. Validate supported interfaces, licensing, and tenant capabilities.

## 20-hour learning sprint

| Session (2h) | Focus | Interactive OmniWorks mission | Required deliverable |
|---|---|---|---|
| 01 | Architecture vision and capability gaps | Assess current procurement and workforce landscape and target capabilities | Architecture Vision and gap assessment |
| 02 | Global operating model | Design global core processes, local legal variations, plants, and approval authorities | Operating model and localization matrix |
| 03 | Cross-functional process architecture | Model requisition-to-order-to-invoice and posting-to-work-order/SOW-to-settlement | BPMN process architecture |
| 04 | Application responsibility architecture | Separate Ariba Buying/Invoicing, Fieldglass, ERP, HR, IAM responsibilities | Application architecture and catalog |
| 05 | Enterprise integration architecture | Specify API, event, batch, mapping, retry, idempotency, and reconciliation patterns | Integration contracts and diagrams |
| 06 | Canonical data and governance | Assign ownership to supplier, worker, cost center, SOW, PO, invoice, and identity data | Canonical model and ownership matrix |
| 07 | Security and industrial compliance | Address least privilege, segregation of duties, safety induction, and privacy | Security and compliance architecture |
| 08 | NFRs and resilience | Define availability, latency, monitoring, recovery, capacity, and auditability | NFR and operations design |
| 09 | Deployment and cutover | Plan migration, pilot, test waves, change, cutover, and hypercare | Transition architecture and roadmap |
| 10 | Architecture Review Board | Defend end-to-end target architecture and trade-offs | Enterprise Solution Architecture Blueprint |

### Standard session rhythm

1. **20 minutes — Concept:** business purpose, terms, architecture principles.
2. **25 minutes — Guided demonstration:** process walkthrough or configuration concept.
3. **50 minutes — Applied mission:** role-play, system practice where access is available, or structured simulation.
4. **20 minutes — Deliverable:** complete the named artifact and trace it to requirements.
5. **5 minutes — Rapid review:** explain the decision, risk, and next step in plain language.

## Interactive learning activities

- **Role-play:** learner alternates among Procurement, plant manager, supplier, Finance, HR, and solution architect roles.
- **Decision challenge:** select a standard process, justified configuration, integration, or controlled exception and explain the trade-off.
- **Feynman review:** teach the workflow in simple words; identify missing steps and misconceptions.
- **Scenario quiz:** one applied question per session, plus a final 10-question review.
- **Evidence:** retain completed artifacts, review comments, assumptions, and scenario outcomes.

## Assessment and exit criteria

- Recommended passing score: **85/100**.
- Complete all ten session deliverables and demonstrate the end-to-end OmniWorks scenario.
- Show business-process traceability, data/application responsibilities, safety/security controls, and appropriate exception handling for this level.
- Score is a training rubric, **not** an SAP certification or proof of production implementation experience.

## Standards and architecture alignment

- **TOGAF:** business/application architecture and governance appropriate to this level.
- **BIZBOK:** procurement capabilities, value streams, and outcomes.
- **BABOK:** requirements, stakeholders, fit-gap, and solution evaluation.
- **DAMA-DMBOK:** supplier, workforce, organizational, and transaction data stewardship.
- **ISO/IEC 27001, ISO 45001, COBIT:** security, contractor safety, accountability, and control design.

## Progression

Previous: [Level 3 — Essentials](../03-essentials/README.md).  
Next: [Level 5 — Ultimate](../05-ultimate/README.md).
