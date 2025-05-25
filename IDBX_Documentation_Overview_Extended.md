# IDBX Technical Documentation Overview

## File Structure and Naming Convention

All IDBX technical documents follow a standardized naming scheme:

```
[Title]-IDBX-[TYPE]-[MODULE]-v[VERSION].md
```

### Elements Explained:
- **Title**: Clear description using underscores (e.g., `AI_Ethics_and_Compliance_Policy`)
- **IDBX**: Constant tag indicating ownership by IDBX Corp
- **TYPE**:
  - `POL`: Policy
  - `PLAN`: Strategic or Incident Plan
  - `SPEC`: Technical Specification
  - `ARCH`: Architecture Blueprint
  - `WHP`: White Paper
  - `REG`: Regulatory Mapping or Register
  - `MAN`: Vision Manifesto
- **MODULE**:
  - `AI`, `CORE`, `SEC`, `TRADE`, `DATA`, `VENDOR`, `API`, `REG`
- **v[VERSION]**: Versioning format `vMAJOR-YEAR.minor` (e.g., v1-2025.0)

---

## Contextual Document Categories

### 1. Platform & Vision
- **Technology Manifesto**  
  Guiding vision of IDBX: modular, explainable, secure, and globally adaptive systems.

- **AI-Driven Infrastructure Blueprint**  
  Reference AI architecture with components like model serving, feature stores, explainability, and failover.

- **Trading Platform System Specification**  
  Specification for low-latency trade engine, compliance integration, and failover mechanics.

- **API & Integration Suite**  
  Institutional APIs including trading, compliance, and AIDANN insights, with versioning and onboarding flow.

---

### 2. Artificial Intelligence (AI)
- **AIDANN Technical White Paper**  
  Technical design and capabilities of IDBX’s AI core (AIDANN), including LSTM/transformer hybrid modeling.

- **AI Ethics & Compliance Policy**  
  Ethical principles, transparency mandates, and usage boundaries for internal/external AI use.

- **AI Risk & Governance Framework**  
  Risk classification, model lifecycle controls, and monitoring standards. Includes kill switch, drift detection, and fairness evaluation.

- **AI Compliance Register**  
  Inventory of all deployed models, their review cycles, explainability status, and regulatory labels.

---

### 3. Data Policies & Controls
- **Data Governance & Privacy Framework**  
  Classifies and governs internal and external data assets, stewards, encryption, and audit trails.

- **Data Localization & Cross-Border Transfer Policy**  
  Regional residency laws and transmission controls (e.g., GDPR, India, UAE, Turkey).

---

### 4. Continuity & Security
- **Business Continuity & Disaster Recovery Plan**  
  RTO/RPO targets, recovery workflows, and stakeholder communication plans post-disruption.

- **Cybersecurity Incident Response Plan**  
  Threat classification, alerting system, incident handling, evidence control, and forensic review cycle.

---

### 5. Trading Governance
- **Trade Lifecycle Management Policy**  
  Institutional trade lifecycle from signal ingestion to audit trail, with MiFID II traceability.

- **Third-Party AI Vendor Risk Policy**  
  Due diligence and sandboxing for external AI vendors based on explainability, bias controls, and SLAs.

---

### 6. Regulatory & Compliance Mapping
- **Regulatory Mapping Matrix**  
  Maps GDPR, MiFID II, EU AI Act, and Basel III to corresponding IDBX systems and document coverage.

---

## Document Index with Links

| Title | Link |
|-------|------|
| Technology Manifesto | [Technology_Manifesto-IDBX-MAN-CORE-v1-2025.0.md](Technology_Manifesto-IDBX-MAN-CORE-v1-2025.0.md) |
| AI-Driven Infrastructure Blueprint | [AI_Driven_Infrastructure_Blueprint-IDBX-ARCH-AI-v1-2025.0.md](AI_Driven_Infrastructure_Blueprint-IDBX-ARCH-AI-v1-2025.0.md) |
| Trading Platform Specification | [IDBX_Trading_Platform_System_Specification-IDBX-SPEC-TRADE-v1-2025.0.md](IDBX_Trading_Platform_System_Specification-IDBX-SPEC-TRADE-v1-2025.0.md) |
| API & Integration Suite | [API_Integration_Suite-IDBX-SPEC-API-v1-2025.0.md](API_Integration_Suite-IDBX-SPEC-API-v1-2025.0.md) |
| AIDANN Technical White Paper | [AIDANN_Technical_White_Paper-IDBX-WHP-AIDANN-v1-2025.0.md](AIDANN_Technical_White_Paper-IDBX-WHP-AIDANN-v1-2025.0.md) |
| AI Ethics & Compliance Policy | [AI_Ethics_and_Compliance_Policy-IDBX-POL-AI-v1-2025.0.md](AI_Ethics_and_Compliance_Policy-IDBX-POL-AI-v1-2025.0.md) |
| AI Risk & Governance Framework | [AI_Risk_and_Governance_Framework-IDBX-POL-AI-RISK-v1-2025.0.md](AI_Risk_and_Governance_Framework-IDBX-POL-AI-RISK-v1-2025.0.md) |
| AI Compliance Register | [AI_Compliance_Register-IDBX-REG-AI-v1-2025.0.md](AI_Compliance_Register-IDBX-REG-AI-v1-2025.0.md) |
| Data Governance & Privacy Framework | [Data_Governance_and_Privacy_Framework-IDBX-POL-DATA-v1-2025.0.md](Data_Governance_and_Privacy_Framework-IDBX-POL-DATA-v1-2025.0.md) |
| Data Localization Policy | [Data_Localization_and_Cross_Border_Transfer_Policy-IDBX-POL-DATA-v1-2025.0.md](Data_Localization_and_Cross_Border_Transfer_Policy-IDBX-POL-DATA-v1-2025.0.md) |
| Business Continuity & DR Plan | [Business_Continuity_and_Disaster_Recovery_Plan-IDBX-PLAN-CORE-v1-2025.0.md](Business_Continuity_and_Disaster_Recovery_Plan-IDBX-PLAN-CORE-v1-2025.0.md) |
| Cybersecurity Incident Response Plan | [Cybersecurity_Incident_Response_Plan-IDBX-PLAN-SEC-v1-2025.0.md](Cybersecurity_Incident_Response_Plan-IDBX-PLAN-SEC-v1-2025.0.md) |
| Trade Lifecycle Management Policy | [Trade_Lifecycle_Management_Policy-IDBX-POL-TRADE-v1-2025.0.md](Trade_Lifecycle_Management_Policy-IDBX-POL-TRADE-v1-2025.0.md) |
| Third-Party AI Vendor Risk Policy | [Third_Party_AI_Vendor_Risk_Policy-IDBX-POL-VENDOR-v1-2025.0.md](Third_Party_AI_Vendor_Risk_Policy-IDBX-POL-VENDOR-v1-2025.0.md) |
| Regulatory Mapping Matrix | [Regulatory_Mapping_Matrix-IDBX-REG-MAP-v1-2025.0.md](Regulatory_Mapping_Matrix-IDBX-REG-MAP-v1-2025.0.md) |

...


## Glossary of Key Terms

| Term                   | Definition                                                                 |
|------------------------|----------------------------------------------------------------------------|
| **AIDANN**             | Artificial Intelligence Dealer Adaptive Neural Network – proprietary AI engine of IDBX |
| **AI-Augmented**       | Regulatory tag applied to outputs generated by AIDANN used in trade decisions |
| **AOC**                | AI Oversight Committee responsible for governance, policy, and escalation  |
| **BCR**                | Binding Corporate Rules – GDPR mechanism for data transfer outside EU     |
| **CI/CD**              | Continuous Integration / Continuous Deployment practices for development  |
| **CSTO**               | Chief Strategy and Technology Officer, e.g. Mahmut Gülerce                 |
| **DPO**                | Data Protection Officer – manages privacy compliance and breach reporting |
| **Drift Detection**    | Monitoring for model input/output changes over time                        |
| **EU AI Act**          | EU regulation classifying AI systems by risk level                         |
| **Explainability (XAI)**| Techniques (e.g. SHAP, LIME) for interpreting model outputs               |
| **GDPR**               | EU data protection and privacy regulation                                  |
| **High-Risk AI System**| Systems with significant legal or ethical impact under the EU AI Act      |
| **IaC**                | Infrastructure as Code – declarative environment management                |
| **IDBX**               | Institutional trading platform by IDBX Corporation Ltd.                   |
| **Immutable Storage**  | Data storage that prevents post-write modification or deletion             |
| **KYC**                | Know Your Customer – identity verification process for clients             |
| **MiFID II**           | EU regulation on financial instruments and trade transparency              |
| **mTLS**               | Mutual Transport Layer Security for client/server authentication          |
| **PII**                | Personally Identifiable Information                                        |
| **RBAC**               | Role-Based Access Control                                                  |
| **RPO**                | Recovery Point Objective – maximum allowable data loss                    |
| **RTS 27/28**          | MiFID II technical standards for reporting trade execution quality         |
| **RTO**                | Recovery Time Objective – max acceptable downtime duration                |
| **SCCs**               | Standard Contractual Clauses for legal data transfers under GDPR           |
| **SHAP Values**        | SHapley Additive exPlanations – AI output interpretability method          |
| **Zero Trust**         | Network security model enforcing identity verification for all access      |

---

*This file summarizes the IDBX documentation index as of 2025 and is maintained by the Global CSTO Office. All content is confidential and proprietary.*
