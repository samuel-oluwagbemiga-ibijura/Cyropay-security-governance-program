# GDPR Data Protection Impact Assessment — CyroPay Ltd

**Project type:** GRC Portfolio · Privacy & Data Protection  
**Organisation:** CyroPay Ltd (fictional UK payment fintech)  
**Prepared by:** Samuel O. Ibijura · MSc Cybersecurity  
**Document ID:** DPIA-001  
**Date:** May 2026  
**Legal basis:** UK GDPR Article 35 — mandatory DPIA for high-risk processing

---

## Overview

A full Data Protection Impact Assessment completed using the ICO's official DPIA template for CyroPay's proposed biometric authentication feature — a high-risk processing activity under UK GDPR Article 35, as it involves special category data (biometric data processed to uniquely identify individuals).

The assessment covers all seven DPIA steps from processing description through DPO sign-off and ICO prior consultation assessment.

---

## Processing Activity

**Feature:** Biometric authentication for the CyroPay Merchant Portal  
**Implementation:** FIDO2/WebAuthn on-device processing (Apple Secure Enclave / Android Strongbox)  
**Key privacy design decision:** Raw biometric templates are processed entirely on-device and never transmitted to or stored on CyroPay servers. CyroPay receives only a cryptographic assertion confirming successful authentication.

---

## Legal Basis

| Basis | Reference | Application |
|---|---|---|
| Explicit consent | UK GDPR Art. 9(2)(a) | Biometric data — opt-in only, freely withdrawable |
| Contract performance | UK GDPR Art. 6(1)(b) | Authentication processing for merchant access |

Biometric authentication is strictly opt-in. Password-based login remains available without detriment.

---

## Risk Register Summary

| Risk ID | Risk | Rating | Residual |
|---|---|---|---|
| DR-001 | Consent not freely given — employer coercion | 🟠 High | 🟢 Low |
| DR-002 | Inadequate consent mechanism | 🟠 High | 🟢 Low |
| DR-003 | FIDO2 public key compromise | 🟢 Low | 🟢 Low |
| DR-004 | Auth logs used beyond security monitoring | 🟠 High | 🟢 Low |
| DR-005 | Data subject unable to exercise rights | 🟡 Medium | 🟢 Low |
| DR-006 | Device compromise bypasses biometric controls | 🟠 High | 🟡 Medium |
| DR-007 | Vendor OS update changes biometric API | 🟢 Low | 🟢 Low |
| DR-008 | Inadequate deletion on de-enrolment | 🟡 Medium | 🟢 Low |
| DR-009 | Cross-border transfer risk | 🟡 Medium | 🟢 Low |
| DR-010 | Demographic bias in biometric accuracy | 🟠 High | 🟡 Medium |

---

## Outcome

ICO prior consultation not required. Following implementation of all risk treatment measures, residual risks are within acceptable tolerance. DPO recommends proceeding subject to:
- Standalone opt-in consent screen (not bundled with T&Cs)
- Privacy Notice update before launch
- Self-service de-enrolment and rights portal
- Pre-launch independent bias and accuracy assessment

---

## Deliverables

- `DPIA-001_Biometric_Authentication_CyroPay.pdf` — Complete DPIA (7 steps, ICO template)
- `CyroPay_Biometric_Authentication_DFD.png` — Data flow diagram showing full biometric data lifecycle
