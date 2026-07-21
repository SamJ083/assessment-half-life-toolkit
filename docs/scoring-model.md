# Assessment Half-Life Scoring Model

**Version:** 1.0

---

# Purpose

The Assessment Half-Life Scoring Model provides a transparent and repeatable method for evaluating third-party vendor risk.

Rather than relying solely on questionnaire responses or security ratings, the model combines governance, operational, and continuous monitoring factors into a single composite score that supports vendor prioritization and ongoing oversight.

---

# Scoring Philosophy

The model is designed around three principles:

- Simplicity over complexity
- Transparency over black-box scoring
- Continuous assurance over point-in-time assessment

The objective is not to produce a perfect risk score but a practical and explainable one that can be implemented using standard spreadsheet software.

---

# Composite Score

The overall vendor score is calculated as a weighted average of five assessment domains.

| Assessment Domain | Weight |
|-------------------|-------:|
| Governance & Compliance | 25% |
| Security Posture | 25% |
| Business Dependency | 20% |
| Continuous Monitoring Signals | 20% |
| Concentration & Resilience | 10% |

**Total = 100%**

---

# Assessment Domains

## 1. Governance & Compliance (25%)

Evaluates the maturity of the vendor's governance practices.

Example factors include:

- Security policies
- ISO/IEC 27001 certification
- SOC 2 reports
- Privacy program
- Regulatory compliance
- Business continuity planning

---

## 2. Security Posture (25%)

Evaluates observable cybersecurity practices.

Example factors include:

- Multi-factor authentication
- Vulnerability management
- Patch cadence
- Endpoint protection
- Secure software development
- Incident response capability

---

## 3. Business Dependency (20%)

Measures how critical the vendor is to NovaTide's operations.

Considerations include:

- Business process supported
- Data sensitivity
- Operational impact
- Availability requirements
- Recovery objectives

---

## 4. Continuous Monitoring Signals (20%)

Captures changes occurring after the initial assessment.

Signals include:

- Security incidents
- Breach notifications
- Credential exposure
- Threat intelligence
- Certificate changes
- KEV exposure
- Exploited vulnerabilities
- Significant service disruptions

---

## 5. Concentration & Resilience (10%)

Measures systemic dependency.

Factors include:

- Shared industry dependence
- Geographic concentration
- Single points of failure
- Fourth-party exposure
- Exit strategy maturity

---

# Vendor Tiers

| Score | Tier | Recommended Action |
|------:|------|--------------------|
| 90–100 | Low Risk | Annual review with continuous monitoring |
| 75–89 | Moderate Risk | Quarterly monitoring and annual reassessment |
| 60–74 | Elevated Risk | Monthly review and targeted remediation |
| Below 60 | High Risk | Executive review and formal risk treatment |

---

# Assessment Frequency

| Vendor Tier | Reassessment |
|-------------|--------------|
| Critical | Every 6 months or trigger-based |
| High | Annual or trigger-based |
| Medium | Every 18 months |
| Low | Every 24 months |

Continuous monitoring applies to all Critical and High vendors regardless of reassessment schedule.

---

# Trigger Events

A reassessment should be initiated when one or more of the following occurs:

- Confirmed security breach
- Critical exploited vulnerability
- Significant infrastructure change
- Regulatory enforcement action
- Material service disruption
- Acquisition or merger
- Significant AI capability deployment
- Contract renewal for strategic vendors

---

# Future Enhancements

Future versions of this model may incorporate:

- Exploit Prediction Scoring System (EPSS)
- External security ratings
- Industry benchmarking
- Automated risk signal ingestion
- AI-assisted vendor risk analysis

---

# Relationship to the Toolkit

This scoring model is implemented by:

- Vendor Inventory
- Excel Scoring Workbook
- Monitoring Dashboard
- Vendor Assessment Template

Any changes to weighting or scoring logic should be reflected across all implementation artifacts.
