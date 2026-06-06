# CyroPay GRC Portfolio
### Oluwagbemiga Samuel Ibijura · GRC Analyst · Cybersecurity Professional

[![ISO 27001](https://img.shields.io/badge/ISO%2027001%3A2022-Aligned-0D9E8D?style=flat-square)](https://www.iso.org/standard/27001)
[![UK GDPR](https://img.shields.io/badge/UK%20GDPR-Compliant-7C3AED?style=flat-square)](https://ico.org.uk)
[![DORA](https://img.shields.io/badge/DORA-Aligned-EA580C?style=flat-square)](https://www.eba.europa.eu)
[![FCA](https://img.shields.io/badge/FCA-Regulated%20Sector-0891B2?style=flat-square)](https://www.fca.org.uk)
[![PCI DSS](https://img.shields.io/badge/PCI%20DSS-Referenced-F59E0B?style=flat-square)](https://www.pcisecuritystandards.org)

---

## About This Portfolio

This repository contains five end-to-end GRC and cybersecurity projects built for **CyroPay Ltd** — a fictional UK-regulated digital payment platform created entirely for portfolio purposes. No real client data, personal data, or proprietary information was used.

Each project mirrors the deliverables a **GRC Analyst**, **Information Security Analyst**, or **Compliance Analyst** would produce in a regulated financial services organisation. All work is aligned to **ISO/IEC 27001:2022**, **UK GDPR**, **FCA operational resilience requirements**, and **DORA**.

> **Disclaimer:** CyroPay Ltd is a fictional organisation. All scenarios, individuals, and data are entirely fictitious.

---

## Portfolio Overview

| Project | Title | Frameworks | Key Output |
|---|---|---|---|
| [Project 1](#project-1) | ISO 27001 Gap Assessment | ISO 27001:2022 · FCA | 93-control audit · Risk register |
| [Project 2](#project-2) | Information Security Policy Suite | ISO 27001:2022 · UK GDPR | 10 policies · Annex A mapped |
| [Project 3](#project-3) | Vendor Risk Assessment | ISO 27001:2022 · DORA | 3 vendors scored · Heat map |
| [Project 4](#project-4) | GDPR DPIA | UK GDPR Art. 35 · ICO | DPIA · Data flow diagram |
| [Project 5](#project-5) | Executive Risk Dashboard | ISO 27001 · FCA SYSC 6 | CISO briefing · Dashboard |

---

## Project 1
## ISO/IEC 27001:2022 Gap Assessment

**Objective:** Conduct a full ISO 27001:2022 gap assessment for CyroPay Ltd — a UK-based digital payment platform — and establish the ISMS foundation.

**Context:** CyroPay processes merchant payments using a Stripe-hosted payment page, operates on AWS eu-west-2, and is subject to FCA authorisation and UK GDPR obligations. The assessment established the ISMS boundary and scored compliance across all ISO 27001 clauses and Annex A controls.

### Results Summary

| Control Domain | Controls | Compliant | Non-Compliant | Partial | Compliance % |
|---|---|---|---|---|---|
| A.5 Organisational | 37 | 4 | 15 | 18 | 10.8% |
| A.6 People | 8 | 4 | 2 | 2 | 50.0% |
| A.7 Physical | 14 | 9 | 1 | 4 | 64.3% |
| A.8 Technological | 34 | 8 | 9 | 17 | 23.5% |
| **TOTAL** | **93** | **25** | **27** | **41** | **26.9%** |

**Overall posture:** 21.1% Compliant · 64.2% Partially Compliant · 14.6% Non-Compliant

### Deliverables
- 📄 [ISMS Scope Statement](Documents/ISMS_Scope_Statement_v1.0_CyroPay.pdf)
- 📄 [GRC Gap Assessment Report](Documents/CyroPay_GRC_Report_v1.0.pdf)
- 📊 [GRC Master Spreadsheet — Risk Register & Gap Tracker](Documents/CyroPay_GRC_Master.xlsx)
- 🗺️ [ISMS Scope Diagram — draw.io](Documents/CyroPay_ISMS_Diagram.drawio)
- 🖼️ [ISMS Scope Diagram — PNG](Documents/cyropay_isms_scope_diagram.png)

### Screenshots — CISO Assistant Pro
| Screenshot | Description |
|---|---|
| [01 Audit Overview](Screenshots/01_Audit_Overview.png) | Audit set up against ISO/IEC 27001:2022 framework |
| [02 Gap Findings](Screenshots/02_Audit_Gap_Findings.png) | Clause-level gap findings with compliance ratings |
| [03 100% Progress](Screenshots/03_Audit_Progress_100pct.png) | Full audit completed at 100% |
| [04 Annex A Controls](Screenshots/04_Annex_A_Controls.png) | All 93 Annex A controls mapped |
| [05 Policies Active](Screenshots/05_Policies_Active.png) | Policies active and mapped to Annex A |
| [06 Evidences Approved](Screenshots/06_Evidences_Approved.png) | Evidence formally approved with timestamps |
| [07 Compliance Donut](Screenshots/07_Audit_Compliance_Donut.png) | Visual compliance score overview |
| [08 Overall Summary](Screenshots/08_Overall_Compliance_Summary.png) | CyroPay overall compliance posture |
| [09 Clause Detail](Screenshots/09_Gap_Assessment_Clause_Detail.png) | Clause-level gap detail — A.5 controls |

**Tool used:** CISO Assistant Pro · **Frameworks:** ISO/IEC 27001:2022 Clauses 4–10 · Annex A · FCA

---

## Project 2
## Information Security Policy Suite

**Objective:** Develop a complete, ISO 27001-aligned policy library for CyroPay from scratch — version controlled, Annex A mapped, and written to a professional standard ready for board approval.

### Policies Delivered

| Policy ID | Policy Name | Annex A | Status |
|---|---|---|---|
| POL-001 | Information Security Policy | A.5.1 | ✅ Active |
| POL-002 | Acceptable Use Policy | A.5.10 | ✅ Active |
| POL-003 | Access Control Policy | A.5.15 | ✅ Active |
| POL-004 | Password & Authentication Policy | A.5.17 | ✅ Active |
| POL-005 | Incident Response Policy | A.5.24 | ✅ Active |
| POL-006 | Data Classification & Handling Policy | A.5.12 | ✅ Active |
| POL-007 | Business Continuity Policy | A.5.29 | ✅ Active |
| POL-008 | Third-Party Security Policy | A.5.19 | ✅ Active |
| POL-009 | Remote Working Policy | A.6.7 | ✅ Active |
| POL-010 | Clear Desk & Clear Screen Policy | A.7.7 | ✅ Active |

Each policy includes: purpose · scope · definitions · roles & responsibilities · policy requirements · compliance & monitoring · exceptions · related documents · ISO 27001 Annex A mapping · document control

**Frameworks:** ISO/IEC 27001:2022 Annex A · UK GDPR · FCA · DORA

---

## Project 3
## Third-Party Vendor Risk Assessment

**Objective:** Assess CyroPay's three critical suppliers against a 25-question security questionnaire aligned to ISO 27001 and DORA. Produce a formal vendor risk report with scored findings and a remediation roadmap.

### Vendor Scores

| Vendor | Service | Score | Rating | Gaps |
|---|---|---|---|---|
| Amazon Web Services | Cloud Infrastructure (IaaS/PaaS) | 47/50 (94%) | 🟢 Low | 3 |
| Stripe | Payment Processing (PCI DSS L1 SP) | 45/50 (90%) | 🟢 Low | 5 |
| Salesforce | CRM Platform | 36/50 (72%) | 🟡 Medium | 13 |

**Key finding:** Salesforce's 13 gaps are primarily CyroPay's own tenant-side governance failures — not Salesforce platform deficiencies. Access reviews, data classification configuration, and exit planning are all missing at the tenant level.

### Deliverables
- 📋 [25-Question Vendor Risk Questionnaire](Documents/VRA-Q001_Vendor_Risk_Questionnaire.docx)
- 📊 [Scored Vendor Assessments — AWS, Stripe, Salesforce](Documents/VRA-SCR-001_Vendor_Scored_Assessments.docx)
- 📄 [Vendor Risk Assessment Report](Documents/VRA-RPT-001_Vendor_Risk_Assessment_Report.docx)
- 📊 [GRC Master — Vendor Sheet & Heat Map](Documents/CyroPay_GRC_Master_v2.xlsx)

**Frameworks:** ISO/IEC 27001:2022 A.5.19–A.5.23 · DORA Articles 5, 9, 11, 17, 19, 28, 30

---

## Project 4
## GDPR Data Protection Impact Assessment (DPIA)

**Objective:** Complete an ICO-structured DPIA for CyroPay's biometric authentication feature — a mandatory DPIA trigger under UK GDPR Article 35 due to biometric special category data processing under Article 9(1).

**Feature assessed:** FIDO2/WebAuthn on-device biometric authentication (fingerprint and facial recognition) for the Merchant Portal.

**Privacy by design decision:** On-device processing via the device's hardware security enclave means CyroPay **never receives or stores raw biometric data** — only a cryptographic public key is transmitted to AWS. This eliminated the highest-risk processing scenario and meant ICO prior consultation (Article 36) was not required.

### DPIA Structure (ICO Template — 9 Steps)

| Step | Content |
|---|---|
| Step 1 | Processing description — data types, legal basis (Art. 9(2)(a) consent + Art. 6(1)(b)), recipients, data flows |
| Step 2 | Necessity & proportionality — FIDO2 on-device selected over server-side storage and SaaS biometrics |
| Step 3 | Risk identification — 10 risks scored on 3×3 likelihood/severity matrix |
| Step 4 | Risk treatment — mitigation measures for all 10 risks with owners and targets |
| Step 5 | DPO sign-off — ICO Art. 36 prior consultation not required |
| Step 6 | UK GDPR compliance checklist — 14 requirements tracked |
| Step 7 | Data flow summary — 5-stage lifecycle from device enrolment to de-enrolment |

### Deliverables
- 📄 [DPIA — ICO Template (9 Steps)](Documents/DPIA-001_Biometric_Authentication_CyroPay.docx)
- 🗺️ [Biometric Data Flow Diagram — PNG](Documents/DPIA-001-DFD_Biometric_Data_Flow_CyroPay.png)
- 🗺️ [Biometric Data Flow Diagram — SVG](Documents/DPIA-001-DFD_Biometric_Data_Flow_CyroPay.svg)

**Frameworks:** UK GDPR Articles 5, 6, 9, 13, 15–22, 25, 28, 30, 35, 36, 44–49 · ICO DPIA guidance

---

## Project 5
## Executive Risk Dashboard

**Objective:** Translate GRC findings into board-level executive reporting — a CISO briefing and risk dashboard presenting CyroPay's security posture, top risks, and remediation roadmap in language suitable for senior leadership.

**Key outputs:**
- Overall ISO 27001 compliance posture: 27% compliant · 44% partial · 29% non-compliant
- 1 Critical risk · 4 High risks identified and prioritised
- ISO 27001:2022 certification readiness target: Q2 2027
- FCA SYSC 6 obligations mapped to incident response remediation actions

### Deliverables
- 📄 [CISO Briefing — May 2026](Documents/CyroPay_CISO_Briefing_May2026.pdf)
- 📊 [Executive Risk Dashboard — Excel](Documents/CyroPay_GRC_Master_Final.xlsx)

**Frameworks:** ISO/IEC 27001:2022 · FCA SYSC 6 · DORA

---

## Skills Demonstrated

| Skill Area | Evidence |
|---|---|
| ISO 27001 Gap Assessment | Project 1 — 93 controls assessed end-to-end in CISO Assistant Pro |
| Policy Writing | Project 2 — 10 professional policies with full document control |
| Vendor Risk Management | Project 3 — scored questionnaire, heat map, DORA-aligned report |
| UK GDPR / DPIA | Project 4 — full ICO DPIA with privacy by design applied |
| Executive Reporting | Project 5 — CISO briefing and board-level risk dashboard |
| Risk Register Management | All projects — likelihood/impact scoring, treatment plans |
| Data Flow Diagramming | Project 4 — draw.io diagram exported as SVG and PNG |
| SIEM / Log Analysis | Bincom Global work experience · SOC internship · Splunk simulation |
| IAM | Tata simulation · Bincom Global access control administration |
| Phishing Analysis | Mastercard simulation · SOC internship |

---

## About the Author

**Oluwagbemiga Samuel Ibijura**
GRC Analyst · Cybersecurity Analyst · MSc Cybersecurity Candidate

- 🎓 MSc Cybersecurity (in progress)
- 🏅 Cisco Certified CyberOps Associate
- 📝 PECB ISO/IEC 27001 Lead Implementer (preparing)
- 💼 Former IT Security Analyst — Bincom Global, Lagos
- 🔐 SOC Internship — Hybrid Security Consults (2026)

📧 ibijuragbenga@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/your-linkedin)
🌐 [Notion Portfolio](https://your-notion-link)

---

*Portfolio created: May–June 2026 · All work is original and fictional · No real data used*
