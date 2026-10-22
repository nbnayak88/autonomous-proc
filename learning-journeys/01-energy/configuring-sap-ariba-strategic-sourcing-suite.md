# Energy — Configuring SAP Ariba Strategic Sourcing Suite

**Official SAP journey:** [Open on SAP Learning](https://learning.sap.com/learning-journeys/configuring-sap-ariba-strategic-sourcing-suite)  
**Inventory:** 3 courses · **Reviewed:** 22 October 2026  
**Case context:** GICS01 Energy · OmniVerse Energy Ltd. — fictional educational enterprise

[Shared Energy implementation and administration](../../shared-foundations/01-energy/README.md) · [Procurement repository](../../README.md)

## Mapping decision

Maintain all three primary records in the **existing shared-foundations / Energy** area, covering suite implementation. Reference them from Sourcing, Contracts and Supplier Management rather than duplicating them in each application series. Folder naming and Township optimization remain deferred.

| Order | SAP code | Official SAP course | Primary Energy record | Time | Suggested level | Primary lab |
|---|---|---|---|---|---|---|
| 1 | ARQ300 | [Planning End to End Deployment of SAP Ariba Strategic Sourcing Suite](https://learning.sap.com/courses/planning-end-to-end-deployment-of-sap-ariba-strategic-sourcing-suite) | [Shared suite implementation](../../shared-foundations/01-energy/official-courses/arq300-planning-end-to-end-deployment-of-sap-ariba-strategic-sourcing-suite.md) | 1h 40m* | Advanced | 05 Build / IIL |
| 2 | ARQ302 | [Performing Advanced Field Configurations in the SAP Ariba Strategic Sourcing Suite Test Site](https://learning.sap.com/courses/performing-advanced-field-configurations-in-the-sap-ariba-strategic-sourcing-suite-test-site) | [Shared suite implementation](../../shared-foundations/01-energy/official-courses/arq302-performing-advanced-field-configurations-in-the-sap-ariba-strategic-sourcing-suite-test-site.md) | 4h 32m | Advanced | 05 Build / IIL |
| 3 | ARQ303 | [Migrating SAP Ariba Strategic Sourcing Suite Configuration to the Production Site](https://learning.sap.com/courses/migrating-sap-ariba-strategic-sourcing-suite-configuration-to-the-production-site) | [Shared suite implementation](../../shared-foundations/01-energy/official-courses/arq303-migrating-sap-ariba-strategic-sourcing-suite-configuration-to-the-production-site.md) | 5h 31m | Advanced | 06 Move / MEL |

**Planning total: 11h 43m.** ARQ300's 1h 40m is calculated from its five displayed unit times: 20 + 50 + 10 + 10 + 10 minutes. Other times are SAP's course totals. Allow additional time for experiments, review and verification. Levels and labs are SuccessLabs recommendations.

## What is different from previous courses?

| Existing topic | Responsibility |
|---|---|
| ARX280 — project templates | Shared day-to-day project-template administration |
| ARX290 — Strategic Sourcing realm | Shared realm administration such as data imports, users and site settings |
| ARS280 — sourcing/event templates | Sourcing-specific templates and event behavior |
| ARS644 — contract-workspace templates | Contract-specific workspace behavior |
| ARQ300 / ARQ302 / ARQ303 | Suite deployment planning, advanced test-site customization and configuration migration |

These new records complement existing courses; they do not replace them. This journey concerns suite configuration deployment rather than ERP integration implementation or legacy contract-content migration. ARQ303 configuration migration is distinct from ARS642 legacy contract upload.

## Entry requirements

The parent SAP journey lists:
- Hands-on SAP Ariba project experience.
- Knowledge of SAP Activate.
- At least one of its listed SAP certifications in Procurement, Sourcing, Supplier Management or Contracts.

SAP currently uses older “Application Associate” certification labels in that prerequisite text. Preserve the source wording when needed, but verify current eligibility and certification names rather than asserting equivalence.

ARQ300 repeats the parent requirements. ARQ302 and ARQ303 individually list none; parent requirements still apply. Do not place the journey at Pre-Foundation simply because a course page has no prerequisite list.

## Proposed Energy progression

| Stage | Course | Reviewable learning evidence |
|---|---|---|
| Plan | ARQ300 | Deployment scope, landscape responsibilities, dependencies and readiness gates |
| Configure and verify in test | ARQ302 | Requirement-to-field decision, object/data implications and positive/negative test evidence |
| Rehearse migration | ARQ303 | Migration approach, configuration inventory, sequencing, reconciliation, approvals and recovery criteria |

For OmniVerse, begin with one justified sourcing-suite extension, such as a project attribute representing an equipment-criticality classification. First assess whether a standard field meets the requirement; do not create custom fields solely for demonstration. Treat the field and migration scenario as illustrative proposals, not canonical enterprise facts.

Use [the canonical OmniVerse case](https://github.com/nbnayak88/successlabs-case-studies/tree/main/01-energy/omniverse-energy-ltd). Connect the exercise to business requirements, accountable roles, data ownership, application responsibilities, access, release governance and validation. Apply TOGAF, BABOK, DAMA-DMBOK, relevant ISO/IEC guidance and COBIT as useful references, without claiming formal compliance.

No live configuration migration, production release or real tenant change is performed by publishing this learning map.

## Related learning maps

- [Implementing SAP Ariba Sourcing — 12 courses](implementing-sap-ariba-sourcing.md).
- [Sourcing and Contract Management discovery — 15 courses](discovering-procurement-sourcing-contract-management.md).
- [Buying & Invoicing implementation — 18 courses](../../APO5-applied-sap-ariba-buying-invoicing-fieldglass/01-energy/README.md).

## Sources and maintenance

The official SAP journey and its three course pages supplied the inventory, scope, units, times and prerequisites. Full instructional content remains on SAP Learning; Energy experiments, ownership mapping and lab suggestions are original SuccessLabs learning design. Review SAP's current tenant/release documentation before hands-on work.

## Explore together

Curious how these procurement decisions work in an energy enterprise? [Join a SuccessLabs Academy webinar](https://hub.successlabsacademy.com/web/checkout/694af8798dd872a219700dd3).
