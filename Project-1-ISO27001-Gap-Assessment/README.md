# ISO 27001:2022 Gap Assessment — CyroPay Ltd

**Project type:** GRC Portfolio · ISO 27001 Implementation  
**Organisation:** CyroPay Ltd (fictional UK payment fintech)  
**Prepared by:** Samuel O. Ibijura · MSc Cybersecurity  
**Date:** May 2026  
**Tools:** CISO Assistant · Microsoft Excel · draw.io

---

## Overview

A full ISO/IEC 27001:2022 gap assessment conducted against all 93 Annex A controls for CyroPay Ltd — a fictional FCA-authorised UK payment fintech processing cardholder data and merchant information.

The assessment establishes CyroPay's current information security posture as a baseline, identifies gaps across all four control categories, prioritises the top 10 risks by business impact, and produces a remediation roadmap aligned to ISO 27001 certification requirements.

**Overall compliance result: 25.8% fully compliant against 93 Annex A controls.**

---

## CyroPay — Organisation Context

| Field | Detail |
|---|---|
| Sector | UK Payment Fintech — FCA Authorised Payment Institution |
| Key systems | AWS cloud infrastructure, Stripe (payments), Salesforce (CRM), Microsoft 365 |
| Regulatory obligations | FCA SYSC, UK GDPR, PCI DSS Level 1 |
| Employees | 45 (one London office, full remote working) |
| ISMS scope | Payment platform, cloud infrastructure, customer/merchant data, London office, remote working |

---

## Methodology

1. Defined the ISMS scope and documented interested parties
2. Applied ISO/IEC 27001:2022 Annex A requirements across all 93 controls
3. Assessed each control using a four-point scale: Compliant / Partially Compliant / Non-Compliant / Not Applicable
4. Added a comment (assessment reasoning) and observation (specific finding) for every control
5. Conducted assessment inside CISO Assistant — an enterprise GRC platform
6. Identified the top 10 risks from gap findings using likelihood × impact scoring
7. Produced a 6-page audit-ready gap assessment report with remediation roadmap

---

## Results by Control Category

| Category | Total | Compliant | Non-Compliant | Partial | % Compliant |
|---|---|---|---|---|---|
| A.5 Organisational | 37 | 4 | 15 | 18 | 10.8% |
| A.6 People | 8 | 4 | 2 | 2 | 50.0% |
| A.7 Physical | 14 | 8 | 1 | 5 | 64.3% |
| A.8 Technological | 34 | 8 | 7 | 19 | 23.5% |
| **Total** | **93** | **24** | **25** | **44** | **25.8%** |

---

## Top 10 Risks Identified

| Risk ID | Description | Score | Rating |
|---|---|---|---|
| R001 | No privileged access management | 20 | 🔴 Critical |
| R002 | No vulnerability scanning or patch SLA | 16 | 🟠 Critical |
| R007 | MFA not enforced across all systems | 16 | 🟠 Critical |
| R003 | No supplier security assessments | 15 | 🟠 High |
| R004 | Live production data in test environments | 15 | 🟠 High |
| R005 | No formal incident response plan | 15 | 🟠 High |
| R006 | No data classification scheme | 12 | 🟡 Medium |
| R008 | No security awareness training programme | 12 | 🟡 Medium |
| R009 | Unencrypted remote laptops | 12 | 🟡 Medium |
| R010 | No formal change management process | 12 | 🟡 Medium |

---

## Deliverables

- `CyroPay_GRC_Master_Final.xlsx` — Risk register (10 risks), Annex A assessment (93 controls), risk heat map, compliance summary
- `CyroPay_ISO27001_GapAssessment_Report.pdf` — 6-page audit-ready gap assessment report
- `CyroPay_ISMS_Scope_Diagram.png` — ISMS scope diagram (draw.io)
- CISO Assistant screenshots — live GRC platform showing compliance dashboard and control assessments

---

## Key Findings

**Strongest area:** Physical controls (A.7) at 64.3% — the London office has strong perimeter security, CCTV, and access controls. AWS provides compliant backup and redundancy infrastructure.

**Biggest gap:** Organisational controls (A.5) at 10.8% — governance documentation is largely absent. No formal incident response plan, no supplier security programme, no threat intelligence process.

**Highest risk:** Technological controls (A.8) at 23.5% — no PAM, no vulnerability scanning, live production data in test environments without masking. These represent direct risk to payment infrastructure and customer data.
