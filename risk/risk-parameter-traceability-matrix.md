# OpenIMMS – Risk–Parameter Traceability Matrix

**ISO 14971–Driven Linkage Between Risk, Process Parameters, and Validation Controls**

---

## 1. Purpose

This document defines the OpenIMMS Risk–Parameter Traceability Matrix (RPTM). It provides a structured method to link product and process risks (ISO 14971) to injection moulding process parameters, scientific studies, validation evidence, and ongoing controls.

The objective is to ensure that:

* Process controls are risk-justified
* Critical Process Parameters (CPPs) are clearly identified
* Validation activities demonstrably reduce risk
* Traceability is maintained for audits and regulatory review

---

## 2. Scope

This matrix applies to:

* Injection moulded products and components
* New process validation and revalidation
* Changes affecting materials, moulds, machines, or parameters

It is mandatory for medical and regulated applications and strongly recommended for all OpenIMMS implementations.

---

## 3. Reference Framework

* ISO 14971 – Risk management
* ISO 13485 – Validation and traceability
* OpenIMMS Validation Model (IQ–OQ–PQ)
* OpenIMMS SIM Framework
* AIAG MSA / VDA 6.3 (process control expectations)

---

## 4. Role of the Risk–Parameter Matrix in OpenIMMS

The Risk–Parameter Traceability Matrix acts as the **central integration tool** connecting:

* Risk Management File (hazards, harms)
* Process development (SIM studies)
* Validation evidence (OQ, PQ)
* Production controls (control plan, reaction plan)

This matrix shall be maintained as a **living document** throughout the product lifecycle.

---

## 5. Risk Identification Inputs

Prior to creating the matrix, the following inputs shall be available:

* Identified hazards and potential harms
* Severity and probability assessment
* Failure modes (process-related)
* Preliminary risk classification (e.g., High / Medium / Low)

---

## 6. Parameter Classification

Process parameters shall be classified based on risk impact:

* **CPP (Critical Process Parameter)**
  Parameter with direct impact on a high-risk hazard

* **KPP (Key Process Parameter)**
  Parameter influencing quality but with lower risk severity

* **MPP (Monitored Process Parameter)**
  Parameter monitored for stability or trend

Classification must be justified through risk analysis.

---

## 7. Risk–Parameter Traceability Matrix (Template)

| Hazard / Failure Mode | Potential Harm | Risk Level | Process Step | Parameter       | Classification (CPP/KPP/MPP) | SIM Study / Evidence       | Validated Range | Control Method | Reaction Plan   |
| --------------------- | -------------- | ---------- | ------------ | --------------- | ---------------------------- | -------------------------- | --------------- | -------------- | --------------- |
| Example: Under-fill   | Leakage        | High       | Injection    | Injection Speed | CPP                          | Short-shot, Pressure study | 80–110 mm/s     | SPC, alarms    | Stop & escalate |

---

## 8. Linkage to Validation Activities

Each CPP identified in the matrix shall be:

* Evaluated during OQ across upper and lower limits
* Included in PQ monitoring
* Reflected in the final validated process window

SIM studies referenced in the matrix provide justification for parameter limits.

---

## 9. Linkage to Control Plans

The approved matrix shall be used to:

* Populate control plans
* Define monitoring frequency
* Establish reaction plans
* Support operator training

Any CPP shall have a clearly defined and documented reaction plan.

---

## 10. Change Management and Revalidation

Changes affecting any CPP or high-risk linkage shall:

* Trigger a formal change request
* Require risk reassessment
* Result in partial or full revalidation as appropriate

The matrix shall be updated as part of the change record.

---

## 11. Review and Approval

The Risk–Parameter Traceability Matrix shall be:

* Reviewed during validation approval
* Updated during significant changes
* Approved by designated technical and quality authorities

---

## 12. Disclaimer

This matrix template is provided as part of OpenIMMS guidance. Organizations remain responsible for accurate risk assessment, implementation, and regulatory compliance.
