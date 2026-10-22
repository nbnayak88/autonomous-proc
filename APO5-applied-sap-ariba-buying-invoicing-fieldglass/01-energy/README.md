# Energy — Implementing SAP Ariba Procurement

**Status:** Official course mapping published; applied exercises proposed  
**Sector:** GICS01 Energy · **Case:** OmniVerse Energy Ltd. (fictional)  
**Verified course inventory:** 18 SAP courses · Reviewed 22 October 2026

[Official SAP learning journey](https://learning.sap.com/learning-journeys/implementing-sap-ariba-procurement) · [APO5 series](../README.md) · [Procurement repository](../../README.md)

## Course ownership

Keep **17 courses in APO5 Buying & Invoicing** and **AR820 in AIG2 Procurement Integration**. This is a course map within the application repository; it does not migrate or duplicate Township sprint content, or finalize the complete Township taxonomy.

Although the existing APO5 series also covers Fieldglass, this particular 18-course journey concerns SAP Ariba Procurement. Do not infer Fieldglass configuration coverage from the series title.

## All 18 official courses in SAP journey order

| Order | SAP code | Official SAP course | Primary learning record | Time |
|---|---|---|---|---|
| 1 | ARP010 | [SAP Ariba Procurement overview](https://learning.sap.com/courses/sap-ariba-procurement-overview) | [APO5 · Orientation](official-courses/arp010-sap-ariba-procurement-overview.md) | 1h 06m |
| 2 | ARP100 | [Creating Requisitions in SAP Ariba Buying and Invoicing](https://learning.sap.com/courses/creating-requisitions-in-sap-ariba-buying-and-invoicing) | [APO5 · Requisitioning](official-courses/arp100-creating-requisitions-in-sap-ariba-buying-and-invoicing.md) | 1h 23m* |
| 3 | ARP101 | [Receiving Purchase Orders in SAP Ariba Buying and Invoicing](https://learning.sap.com/courses/receiving-purchase-orders-in-sap-ariba-buying-and-invoicing) | [APO5 · Receiving](official-courses/arp101-receiving-purchase-orders-in-sap-ariba-buying-and-invoicing.md) | 2h 05m* |
| 4 | ARP102 | [Managing Purchase Orders in SAP Ariba Buying and Invoicing](https://learning.sap.com/courses/managing-purchase-orders-in-sap-ariba-buying-and-invoicing) | [APO5 · Purchase order management](official-courses/arp102-managing-purchase-orders-in-sap-ariba-buying-and-invoicing.md) | 3h 10m |
| 5 | ARP104 | [SAP Ariba Procurement Reports](https://learning.sap.com/courses/sap-ariba-procurement-reports) | [APO5 · Operational reporting](official-courses/arp104-sap-ariba-procurement-reports.md) | 0h 20m |
| 6 | ARP200 | [Invoice Creation](https://learning.sap.com/courses/invoice-creation) | [APO5 · Invoicing](official-courses/arp200-invoice-creation.md) | 0h 59m |
| 7 | ARP201 | [Invoice Reconciliation](https://learning.sap.com/courses/invoice-reconciliation) | [APO5 · Invoice reconciliation](official-courses/arp201-invoice-reconciliation.md) | 0h 46m |
| 8 | ARP203 | [Advanced Purchasing](https://learning.sap.com/courses/advanced-purchasing) | [APO5 · Advanced buying](official-courses/arp203-advanced-purchasing.md) | 2h 24m |
| 9 | ARP204 | [Loading Catalogs](https://learning.sap.com/courses/loading-catalogs) | [APO5 · Catalog administration](official-courses/arp204-loading-catalogs.md) | 4h 00m |
| 10 | ARP300 | [Contract Compliance Release](https://learning.sap.com/courses/contract-compliance-release) | [APO5 · Operational contract compliance](official-courses/arp300-contract-compliance-release.md) | 2h 33m |
| 11 | ARP301 | [Contract Compliance No Release](https://learning.sap.com/courses/contract-compliance-no-release) | [APO5 · Operational contract compliance](official-courses/arp301-contract-compliance-no-release.md) | 3h 40m |
| 12 | ARP340 | [Managing Catalog Items and Attributes](https://learning.sap.com/courses/managing-catalog-items-and-attributes) | [APO5 · Catalog administration](official-courses/arp340-managing-catalog-items-and-attributes.md) | 4h 10m* |
| 13 | ARP341 | [SAP Ariba Guided Buying Configuration](https://learning.sap.com/courses/sap-ariba-guided-buying-configuration) | [APO5 · Guided Buying configuration](official-courses/arp341-sap-ariba-guided-buying-configuration.md) | 1h 53m* |
| 14 | ARP342 | [SAP Ariba Procurement: Configuring Receiving](https://learning.sap.com/courses/sap-ariba-procurement-configuring-receiving) | [APO5 · Receiving configuration](official-courses/arp342-sap-ariba-procurement-configuring-receiving.md) | 3h 40m |
| 15 | ARP343 | [SAP Ariba Procurement: Configuring Approval Rules](https://learning.sap.com/courses/sap-ariba-procurement-configuring-approval-rules) | [APO5 · Approval configuration](official-courses/arp343-sap-ariba-procurement-configuring-approval-rules.md) | 4h 10m* |
| 16 | ARP344 | [Configuring a New Realm](https://learning.sap.com/courses/configuring-a-new-realm) | [APO5 · Realm administration](official-courses/arp344-configuring-a-new-realm.md) | 4h 21m* |
| 17 | TAR73 | [SAP Ariba Procurement: Implementation Consulting and Configuration](https://learning.sap.com/courses/sap-ariba-procurement-implementation-consulting-and-configuration) | [APO5 · Implementation practice](official-courses/tar73-sap-ariba-procurement-implementation-consulting-and-configuration.md) | 1h 12m |
| 18 | AR820 | [SAP Ariba Integration: SAP Ariba Integration Points](https://learning.sap.com/courses/sap-ariba-integration-sap-ariba-integration-points) | [AIG2 · Integration](../../AIG2-applied-sap-integration-suite-procurement/01-energy/official-courses/ar820-sap-ariba-integration-sap-ariba-integration-points.md) | 1h 47m* |

**Time note:** Asterisks mark calculated sums of displayed SAP unit durations where the course header has no total. The combined planning estimate is **43h 39m**. Displayed times are learning-content estimates, not implementation effort or a claim of mastery. Recheck SAP for updates before delivery.

## Capability distribution and cross-links

| Area | Primary courses | Secondary references |
|---|---|---|
| Orientation | ARP010 | Shared procurement foundation; recommended after customer cloud onboarding |
| Requisition, order and receipt execution | ARP100, ARP101, ARP102 | Procurement process, Business Network, logistics/receiving boundary |
| Native procurement reporting | ARP104 | ASP8 spend analytics and AAN0 analytics; no duplicate course record |
| Invoice processing | ARP200, ARP201 | Finance/AP handoff and network invoicing; this is not an FI configuration course |
| Advanced purchasing | ARP203 | Tactical sourcing and category strategy references as applicable |
| Catalogs and Guided Buying | ARP204, ARP340, ARP341 | ASU4 Business Network, supplier-management, policy and user-experience learning |
| Operational contract compliance | ARP300, ARP301 | ASN3 Contracts; execution compliance is distinct from legal contract/workspace authoring |
| Administration and implementation | ARP342, ARP343, ARP344, TAR73 | Access, controls, governance and integration; customer cloud onboarding remains a separate shared course |
| Integration | AR820, maintained under AIG2 | APO5, APS1, ASN3 and ASU4 use links to this record |

## Recommended learning sequence

The table preserves SAP journey order. The following is an original SuccessLabs practice sequence, not an additional SAP prerequisite list:

1. Use the [shared customer cloud-onboarding course](https://learning.sap.com/courses/cloud-onboarding-for-sap-ariba-sap-fieldglass-and-sap-business-network-for-procurement) as a readiness recommendation, then ARP010.
2. Follow the business transaction: ARP100 requisition → ARP102 order → ARP101 receipt → ARP200 invoice → ARP201 reconciliation.
3. Add ARP104 operational reporting and ARP203 advanced purchasing.
4. Explore catalogs and contracts: ARP204, ARP340, ARP300, ARP301.
5. Prepare configuration decisions with TAR73; use AR820 and ARP344 to understand interfaces and realm setup, then configure relevant buying, approval and receiving behavior with ARP341, ARP343 and ARP342.
6. Verify an end-to-end Energy scenario and revisit gaps.

Several official pages list no prerequisites; ARP200 and AR820 do not show a prerequisite section in the reviewed rendering. Do not present the recommended sequence as a mandatory SAP dependency chain.

## Proposed Energy case and evidence

Use the [canonical OmniVerse Energy case](https://github.com/nbnayak88/successlabs-case-studies/tree/main/01-energy/omniverse-energy-ltd). Apply the courses to a maintenance-material request through compliant purchasing, receiving and invoice reconciliation.

- Operations defines the requirement, technical acceptance and needed date.
- Procurement defines the buying channel and commercial controls.
- Data owners validate material/service, supplier, accounting and organizational data.
- Receivers distinguish physical arrival from acceptance and record discrepancies.
- Invoice reviewers resolve matching exceptions and document accountability.
- Integration owners demonstrate identity mapping, delivery, reconciliation and recovery.
- Learners capture requirements, configuration decisions, role separation, positive/negative tests and outcome evidence.

These are illustrative experiments, not established OmniVerse procurement events, completed configurations or real savings. Energy safety authorization remains a separate operational decision.

Use TOGAF, BIZBOK, BABOK, DAMA-DMBOK, applicable ISO/IEC guidance and COBIT where relevant. Alignment to a learning framework does not establish formal compliance.

## Source and maintenance policy

Official SAP titles, identifiers, sequence and unit counts were checked against the journey's published course records. Course outlines were reviewed on their official SAP Learning pages. Full lessons and videos remain on SAP Learning.

Maintain one record per course. The source URLs are authoritative for current SAP content; Energy experiments and suggested SuccessLabs levels are our learning-design proposals. No new six-level sprint curriculum or certification-readiness claim is created here.

## Explore together

Curious how these procurement decisions work in an energy enterprise? [Join a SuccessLabs Academy webinar](https://hub.successlabsacademy.com/web/checkout/694af8798dd872a219700dd3).
