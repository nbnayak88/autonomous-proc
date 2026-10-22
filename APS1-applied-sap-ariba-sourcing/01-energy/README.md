# GICS01 — Energy | Applied SAP Ariba Sourcing

**Program:** APS1 · Autonomous Procurement · SuccessLabs Academy  
**Status:** Origin Story Sprint published · The Origin Story → Pre-Foundation  
**Case:** OmniVerse Energy Ltd. — fictional educational enterprise

[All sectors](../README.md)

## Sprint files

| Order | Skill level | Markdown file |
|---|---|---|
| 00 | The Origin Story → Pre-Foundation | [Origin Story Sprint — Super Sprint 20™](00-the-origin-story-super-sprint-20.md) |

The Origin Story file preserves the supplied Markdown content unchanged. Further skill-level files will be added here as they are supplied.

## Business context

OmniVerse combines upstream oil and gas, refining, retail, power generation, and renewables. The canonical case stipulates 42 countries, 68,000 employees, and eight refineries. These are fictional case baselines; SAP Ariba is a learning solution option, not a confirmed deployed platform.

- [Canonical enterprise case](https://github.com/nbnayak88/successlabs-case-studies/tree/main/01-energy/omniverse-energy-ltd)
- [Procurement scope blueprint](https://github.com/nbnayak88/successlabs-case-studies/blob/main/01-energy/omniverse-energy-ltd/derived-streams/04-procurement.md)
- [Notion knowledge-management view](https://app.notion.com/p/377ce6de608980daae89e74da8236287)
- [Source and assumptions register](https://github.com/nbnayak88/successlabs-case-studies/blob/main/01-energy/omniverse-energy-ltd/references/source-and-assumptions.md)

Preserve canonical enterprise facts and existing source IDs. New supplier details, quantities, costs, scores, dates and sourcing incidents must be labelled illustrative assumptions. Do not treat transformation targets as achieved outcomes.

## Starting learning challenge

**Proposed exercise:** How should OmniVerse select a maintenance-service supplier for a planned refinery shutdown while protecting safety, schedule, and whole-life value?

This is a proposed learning extension, not an established procurement event in the canonical case.

Explore:
- What service scope and acceptance criteria do operations and engineering require?
- Which supplier qualifications are mandatory before commercial evaluation?
- When is an RFI, RFP, or auction appropriate?
- How should technical, delivery, commercial, sustainability, and risk evidence inform an award?
- Who approves the decision and receives the contract handoff?
- How will negotiated value be distinguished from realized value?

## Official SAP starting course

[SAP Ariba Sourcing Overview](https://learning.sap.com/courses/sap-ariba-sourcing-overview) — beginner; no prerequisites; 3 units, 9 lessons, 97 minutes. Course structure checked 22 October 2026.

| Official unit | SAP learning time | Proposed Energy practice |
|---|---:|---|
| Introducing SAP Ariba Sourcing Solutions | 31 minutes | Explain terminology, application responsibilities, and spend classification for the shutdown scenario |
| Recognizing the Benefits and Capabilities of SAP Ariba Sourcing | 34 minutes | Connect capabilities to sourcing problems and define evaluation evidence |
| Exploring SAP Ariba Sourcing Processes | 32 minutes | Walk through project and event creation, response evaluation, award, and downstream handoff |

The listed durations are SAP course times, not the duration of the applied sprint. Completion establishes overview knowledge; tenant practice and implementation study are separate activities.

[Broader official learning journey: Implementing SAP Ariba Sourcing](https://learning.sap.com/learning-journeys/implementing-sap-ariba-sourcing).

## Evidence to build during the sprint

| Learning experiment | Reviewable evidence |
|---|---|
| Discover the business need | Scope brief and stakeholder questions |
| Define the sourcing decision | Capability/value-stream view and requirements |
| Prepare supplier participation | Qualification checklist and draft event content |
| Compare fictional offers | Bid comparison with assumptions and agreed evaluation criteria |
| Defend the award | Decision rationale, approvals, risks, and contract handoff |
| Evaluate the outcome | Baselines, measures, owners, and evidence needed to validate benefits |

These are planned learner outputs, not completed artifacts or verified system configuration.

## Architecture and control boundaries

- **Business architecture:** Link sourcing to asset reliability and accountable business capabilities; distinguish value streams, processes, and application functions.
- **Requirements:** Trace stakeholder needs to event content, acceptance criteria, and award evidence.
- **Data:** Assign owners for supplier identity, service specifications, bid versions, currencies, units, and evaluation records.
- **Applications:** Keep sourcing-event responsibilities distinct from supplier lifecycle management, contract management, operational purchasing, and payment.
- **Integration:** Define required handoffs and reconciliation separately; no working integration is claimed.
- **Governance and security:** Review access, bid confidentiality, conflicts of interest, approvals, and audit evidence.
- **Energy domain:** Technical and safety qualification require accountable specialist review. A sourcing award does not authorize hazardous work.
- **Sector boundary:** Energy covers oil, gas, refining and related energy businesses here. Regulated electricity, gas and water utility scenarios have a separate [Utilities home](../10-utilities/README.md); classify diversified enterprises by the case scope.

Use TOGAF, BIZBOK, BABOK, DAMA-DMBOK, applicable ISO/IEC standards, and COBIT as relevant reference frameworks. This educational alignment is not a claim of certification or formal compliance.

## Next exploration

After the first service-sourcing exercise, consider critical spare parts and renewable-project procurement. Classify each category from its business use; operational importance alone does not make a purchase direct spend.

## Explore together

Curious how these sourcing decisions connect to enterprise architecture? [Join a SuccessLabs Academy webinar](https://hub.successlabsacademy.com/web/checkout/694af8798dd872a219700dd3).
