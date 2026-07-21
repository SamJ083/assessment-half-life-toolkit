# NovaTide Assessment Half-Life Methodology

**Version:** 1.0  
**Repository:** Assessment Half-Life Toolkit  
**Enterprise Context:** NovaTide Enterprise Simulation

---

# Executive Summary

Traditional Third-Party Risk Management (TPRM) programs rely heavily on point-in-time vendor assessments performed during onboarding and refreshed annually or biannually. While these assessments provide a useful baseline, they rapidly lose their ability to accurately represent a vendor's current risk posture.

The **Assessment Half-Life Methodology** addresses this challenge by introducing a continuous, signal-based approach to vendor assurance. Rather than treating assessments as static snapshots, this methodology recognizes that vendor risk evolves as vulnerabilities emerge, business relationships change, threat actors adapt, and suppliers modify their environments.

The methodology combines traditional governance practices with continuous monitoring signals to provide a more current view of third-party risk while remaining practical for organizations of all sizes.

---

# Background

The methodology was developed in response to an increasingly common problem observed across modern supply chains:

- Vendors are assessed once but monitored infrequently.
- Critical security events often occur months after onboarding.
- Supplier ecosystems become more interconnected over time.
- Public breach disclosures frequently lag actual compromise by weeks or months.

As a result, organizations often make decisions using assessments that no longer accurately reflect present-day risk.

---

# Assessment Half-Life

## Definition

**Assessment Half-Life** is the period after which a point-in-time vendor assessment no longer provides sufficient assurance that the vendor's current risk posture is accurately represented.

Just as radioactive material decays over time, the confidence provided by a vendor assessment also diminishes as new vulnerabilities, incidents, infrastructure changes, and supplier dependencies emerge.

The higher a vendor's criticality and exposure, the shorter its effective assessment half-life.

---

# Guiding Principles

The methodology is built upon six principles.

## 1. Continuous Assurance

Risk should be evaluated continuously rather than exclusively through periodic assessments.

---

## 2. Evidence Over Assumptions

Monitoring should rely on observable signals instead of assumptions about a vendor's security posture.

---

## 3. Business Context Matters

The same technical issue may represent very different levels of risk depending on the business capability the vendor supports.

---

## 4. Prioritize Exploitability

Exploitability is a stronger indicator of operational risk than severity scores alone.

---

## 5. Concentration Risk Is Enterprise Risk

Widely shared suppliers represent systemic risk because a single compromise can affect many organizations simultaneously.

---

## 6. Simplicity Enables Adoption

Small and medium-sized organizations should be able to implement this methodology without expensive commercial tooling.

---

# Methodology Components

The methodology consists of five integrated components.

## 1. Vendor Tiering

Vendors are classified based on:

- Business criticality
- Data sensitivity
- Operational dependency
- Regulatory impact
- Concentration exposure

---

## 2. Baseline Assessment

Each vendor receives an initial governance assessment covering:

- Information security
- Privacy
- Business continuity
- Regulatory compliance
- AI governance (where applicable)
- Contractual obligations

---

## 3. Continuous Monitoring

Rather than waiting for the next annual assessment, organizations monitor observable indicators such as:

- Breach notifications
- Vulnerability exposure
- Patch cadence
- Certificate changes
- Domain security
- Threat intelligence
- Public disclosures
- Credential exposure
- Supplier incidents

---

## 4. Composite Risk Scoring

Risk scores combine multiple dimensions instead of relying on a single questionnaire result.

Inputs include:

- Assessment score
- Security monitoring signals
- Breach history
- Concentration risk
- Vendor criticality
- Operational dependency

---

## 5. Trigger-Based Reassessment

Formal reassessments occur when predefined thresholds are exceeded rather than solely according to a calendar.

Example triggers include:

- Confirmed security incident
- Material infrastructure changes
- Critical exploited vulnerability
- Regulatory findings
- Significant service disruption
- AI model deployment affecting regulated processes

---

# Assessment Lifecycle

The methodology follows a continuous lifecycle.

```
Vendor Onboarding
        ↓
Initial Assessment
        ↓
Risk Tier Assignment
        ↓
Continuous Monitoring
        ↓
Risk Signal Evaluation
        ↓
Score Adjustment
        ↓
Threshold Exceeded?
        ↓
Targeted Reassessment
        ↓
Updated Vendor Assurance
```

---

# Intended Audience

This toolkit is designed for:

- Third-Party Risk Managers
- GRC Professionals
- Cybersecurity Teams
- Procurement Functions
- Internal Audit
- Compliance Teams
- Small and Medium Enterprises
- Students learning enterprise risk management

---

# Scope

This methodology supports governance activities including:

- Third-Party Risk Management
- Continuous Vendor Monitoring
- Supplier Assurance
- AI Vendor Governance
- Operational Resilience
- Regulatory Compliance

It is designed to complement existing frameworks such as ISO/IEC 27001, ISO/IEC 27002, ISO 31000, NIST Cybersecurity Framework (CSF), NIST AI RMF, and the EU AI Act rather than replace them.

---

# Limitations

This toolkit is intended as an educational implementation of a practical TPRM methodology.

Organizations should tailor scoring criteria, monitoring frequency, contractual requirements, and governance processes to their own business objectives, regulatory obligations, and risk appetite.

---

# Relationship to the NovaTide Enterprise Simulation

This repository extends the NovaTide Enterprise Simulation and assumes the enterprise context defined in the **NovaTide Logistics Enterprise Profile** repository.

Applications, vendors, business capabilities, governance structures, and technology platforms referenced throughout this toolkit are inherited from that simulation to provide a consistent and realistic implementation environment.

---

# Version History

| Version | Date | Description |
|----------|------|-------------|
| 1.0 | July 2026 | Initial public release |
