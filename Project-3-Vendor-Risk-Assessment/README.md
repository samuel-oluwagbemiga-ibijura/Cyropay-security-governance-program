# Third-Party Vendor Risk Assessment — CyroPay Ltd

**Project type:** GRC Portfolio · Vendor Risk Management  
**Organisation:** CyroPay Ltd (fictional UK payment fintech)  
**Prepared by:** Samuel O. Ibijura · MSc Cybersecurity  
**Date:** May 2026  
**Regulatory alignment:** DORA Article 28 · ISO 27001 A.5.19–A.5.22

---

## Overview

A structured third-party vendor risk assessment for CyroPay Ltd's three critical ICT service providers, conducted using a 25-question vendor risk questionnaire aligned to DORA third-party risk management obligations.

All assessments were completed using publicly available vendor trust portal documentation.

---

## Vendors Assessed

| Vendor | Service | Score | Risk Rating |
|---|---|---|---|
| Amazon Web Services | Cloud Infrastructure (IaaS/PaaS) | 47/50 | 🟢 Low |
| Stripe | Payment Processing | 45/50 | 🟢 Low |
| Salesforce | CRM Platform | 36/50 | 🟡 Medium |

---

## Questionnaire Domains

The 25-question questionnaire covered:
- Data handling and encryption standards
- Access controls and authentication
- Incident response and notification procedures
- Business continuity and disaster recovery
- Subprocessor management and supply chain risk
- Regulatory certifications (ISO 27001, SOC 2, PCI DSS)
- Audit rights and contractual security obligations

---

## Key Findings

**AWS** — Highest scoring vendor. ISO 27001 certified, SOC 2 Type II, PCI DSS Level 1. Multi-AZ deployment, AES-256 encryption at rest, TLS 1.3 in transit. UK data residency confirmed (eu-west-2 London). DPA in place.

**Stripe** — Strong compliance posture. PCI DSS Level 1, ISO 27001, SOC 2 Type II. Payment card data never touches CyroPay infrastructure. Recommended: review subprocessor list annually.

**Salesforce** — Lowest score. ISO 27001 and SOC 2 T2 certified but CRM contains merchant PII with broader third-party integration surface. Recommended: enhanced due diligence, annual security review, confirm data residency for UK customer data.

---

## Deliverables

- Vendor risk questionnaire (25 questions, Excel)
- Completed assessments for all three vendors
- Risk heat map plotting vendors by inherent risk
- 2-page vendor risk report with recommendations
