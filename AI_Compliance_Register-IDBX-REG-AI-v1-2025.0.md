---
title: "AI Compliance Register"
document_id: "IDBX-REG-AI-v1-2025.0"
module: "AI"
version: "v1.0"
date: "2025-05-25"
authors: ["Mahmut Gülerce (Global CSTO)"]
---

# AI Compliance Register

## Metadata

| Field         | Value                             |
|---------------|-----------------------------------|
| Document ID   | IDBX-REG-AI-v1-2025.0             |
| Module        | AI                                |
| Version       | v1.0                              |
| Date          | 2025-05-25        |
| Authors       | Mahmut Gülerce (Global CSTO)      |

---

## 1. Purpose

This register documents all AI systems deployed within IDBX and their compliance status relative to internal policies and external regulations (e.g., EU AI Act, GDPR, MiFID II).

---

## 2. Compliance Metrics

Each registered AI system must be assessed and logged for:

- Purpose and use case
- Risk level (per EU AI Act)
- Explainability level
- Data sources and fairness audits
- Human oversight integration
- Model version and retraining schedule
- Regulatory tagging (AI-Augmented, Compliant)

---

## 3. Register Format

| Model ID | Use Case              | Risk Level | Compliance Tags            | Last Review | Owner         | Notes |
|----------|------------------------|------------|-----------------------------|-------------|---------------|-------|
| AIDANN-v3.1 | Trade signal advisory | High       | GDPR, MiFID II, AI-Augmented| 2025-03-01  | ML Ops Team   | Fully explainable |
| COMPLY-AI | Regulatory tagging     | Medium     | GDPR, Internal Use          | 2025-02-12  | Compliance     | Semi-automated review |
| AUTO-ROUTER | Smart order routing  | High       | EU AI Act, RTS27            | 2025-01-30  | Algo Trade Team| Model retrained Q1 |

---

## 4. Change Management

- All model updates must be approved and versioned
- Compliance fields must be re-evaluated with every deployment
- Emergency changes must be noted with justification and risk memo

---

## 5. Oversight

- The AI Compliance Register is maintained by the CSTO office
- Reviewed quarterly by the AI Oversight Committee
- Shared with regulators upon formal request

---

*This document is proprietary to IDBX Corporation Ltd. Unauthorized access or sharing is strictly prohibited.*
