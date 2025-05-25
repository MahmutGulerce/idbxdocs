---
title: "Data Localization & Cross-Border Transfer Policy"
document_id: "IDBX-POL-DATA-v1-2025.0"
module: "DATA"
version: "v1.0"
date: "2025-05-25"
authors: ["Mahmut Gülerce (Global CSTO)"]
---

# Data Localization & Cross-Border Transfer Policy

## Metadata

| Field         | Value                                  |
|---------------|----------------------------------------|
| Document ID   | IDBX-POL-DATA-v1-2025.0                |
| Module        | DATA                                   |
| Version       | v1.0                                   |
| Date          | 2025-05-25             |
| Authors       | Mahmut Gülerce (Global CSTO)           |

---

## 1. Purpose

To ensure IDBX manages personal, client, and trading-related data in compliance with international data residency laws, while enabling secure and lawful cross-border data transfers.

---

## 2. Scope

Applies to:
- All client data and internal logs
- Any storage or processing of data across borders
- Third-party platforms with access to IDBX data
- Regions with applicable data localization mandates (e.g. EU, UAE, India)

---

## 3. Data Localization Requirements

| Jurisdiction | Requirement Summary                                     | IDBX Implementation                                |
|--------------|----------------------------------------------------------|----------------------------------------------------|
| EU (GDPR)    | Data may be transferred outside EU with safeguards       | SCCs, encryption, approved vendors                 |
| UAE          | Some financial data must remain within UAE data centers | UAE-only storage for regulated activities          |
| India        | Sensitive data must be mirrored in India                | Dual-region architecture for regulated clients     |
| Turkey       | Law 6698 requires certain data to be retained locally   | Retention in Istanbul-based facility               |

---

## 4. Cross-Border Transfer Controls

- Transfers are allowed only under:
  - Standard Contractual Clauses (SCCs)
  - Binding Corporate Rules (BCRs)
  - Regulator-approved adequacy decisions
- All transfers are logged with:
  - Source and destination
  - Legal basis (SCC, BCR)
  - Encryption method

---

## 5. Encryption & Transmission

- Data in motion: TLS 1.3 with perfect forward secrecy
- Data at rest: AES-256 in cloud-native KMS systems
- Personal data: Tokenization and masking at service layer
- Logging: Cross-border log forwarding is pseudonymized

---

## 6. Vendor and Sub-Processor Requirements

- All vendors must disclose:
  - Location of processing and storage
  - Use of subcontractors
- Contracts must define:
  - Data jurisdiction and export controls
  - Security responsibilities

---

## 7. Data Access Restrictions

- No remote access to regulated data without VPN, MFA, and session recording
- Data access from embargoed jurisdictions is blocked
- Location-aware access enforcement for all admin roles

---

## 8. Compliance and Auditing

- Internal audit team reviews cross-border activity logs monthly
- Data protection officer (DPO) must review SCCs and BCRs annually
- Breach involving localized data triggers immediate regulator notice

---

## 9. Review & Updates

- Reviewed annually or upon change in law
- Legal team monitors geopolitical developments impacting data flow
- Updates approved by CSTO and DPO

---

*This document is proprietary to IDBX Corporation Ltd. Unauthorized use is prohibited.*
