# APO5 — Level 3: Essentials

**Series:** Applied SAP Ariba Buying & Invoicing + Extended Workforce Management by SAP Fieldglass  
**Industry:** GICS03 Industrials  
**Case study:** OmniWorks Industrial Systems Ltd.  
**Learning Lab:** Industry Immersion Lab (IIL) — Build  
**Duration:** 20 hours · 10 sessions × 2 hours  
**Level:** 3 of 5  
**Target persona:** Applied functional consultant

## Sprint outcome

Translate OmniWorks requirements into configuration, integration, exception handling, and test designs.

## OmniWorks case-study mission

Three industrial sites engage 150 contractors through five staffing suppliers and two services SOWs.

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
| 01 | Requirements and fit-gap | Classify business requirements, standard capabilities, gaps, and acceptance criteria | Requirements traceability matrix |
| 02 | Organizational and master data | Model plants, cost centers, users, supplier records, and ownership | Master data/configuration workbook |
| 03 | Buying, posting, and rate design | Specify Ariba purchasing controls and Fieldglass worker templates and rates | Requisition/posting/rate specification |
| 04 | Supplier selection and work orders | Design supplier distribution, candidate evaluation, assignment changes | Engagement functional design |
| 05 | Advanced SOW design | Compare fixed-fee deliverable and time-and-materials engineering SOWs | SOW functional design |
| 06 | Time and invoice exceptions | Resolve overtime, rejected timesheets, invoice mismatches, and reconciliation | Exception register |
| 07 | Approval and compliance workflows | Design spending thresholds, HSE gates, identity and access approvals | Approval and compliance matrix |
| 08 | Integration specifications | Define Ariba/Fieldglass/ERP/HR/IAM ownership and interface requirements | Interface inventory and mapping |
| 09 | Testing and defect resolution | Develop positive, negative, boundary, and integration test scenarios | UAT pack and defect log |
| 10 | Functional design capstone | Defend complete procurement and extended workforce process design | Functional Solution Design Document |

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

- Recommended passing score: **80/100**.
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

Previous: [Level 2 — Foundation](../02-foundation/README.md).  
Next: [Level 4 — Advanced](../04-advanced/README.md).
