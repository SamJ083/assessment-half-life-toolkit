# Vendor Monitoring Playbook

## Purpose

This playbook defines the ongoing monitoring activities for third-party vendors after onboarding and initial risk assessment. It provides a structured approach for identifying changes in vendor risk posture, enabling timely reassessment and risk-based decision making.

---

# Monitoring Objectives

The objectives of continuous vendor monitoring are to:

- Detect changes in vendor security posture.
- Identify emerging cyber threats affecting critical suppliers.
- Monitor compliance with contractual obligations.
- Reduce the Assessment Half-Life through continuous evidence collection.
- Trigger reassessments when significant risk events occur.

---

# Monitoring Frequency

| Vendor Tier | Monitoring Frequency | Formal Reassessment |
|-------------|---------------------|---------------------|
| Critical | Continuous | Every 90 Days |
| High | Weekly | Every 180 Days |
| Medium | Monthly | Every 365 Days |
| Low | Exception-Based | Every 730 Days |

---

# Key Risk Indicators (KRIs)

The following indicators should be monitored throughout the vendor lifecycle.

| Category | Example Indicators |
|----------|-------------------|
| Security | Public breach notifications, ransomware incidents, exposed credentials, malware campaigns |
| Vulnerability Management | CISA KEV entries, critical CVEs, delayed patching, unsupported software |
| Operational | Service outages, SLA violations, incident trends, recurring support issues |
| Compliance | Certification expiry (ISO 27001, SOC 2), regulatory findings, audit observations |
| Financial | Bankruptcy filings, acquisitions, significant layoffs, credit deterioration |
| Supply Chain | Critical subcontractor incidents, geographic disruptions, concentration risk changes |

---

# Monitoring Triggers

The following events should initiate a review or reassessment.

- Confirmed cybersecurity incident.
- Vendor publicly discloses a data breach.
- Critical vulnerability affecting deployed technology.
- Expiration of a major certification.
- Material change in business operations or ownership.
- Significant degradation in service performance.
- Assessment Half-Life reaches its expiry date.
- Regulatory action or enforcement affecting the vendor.

---

# Response Actions

| Trigger | Recommended Action |
|----------|-------------------|
| Critical security incident | Immediate risk review and executive notification |
| CISA KEV affecting vendor technology | Verify exposure and request remediation timeline |
| Breach disclosure | Perform targeted reassessment and evaluate contractual obligations |
| Certification expiry | Request updated audit reports or certification evidence |
| Service degradation | Engage business owner and review operational impact |
| Financial instability | Review contingency plans and alternate suppliers |

---

# Escalation Matrix

| Risk Level | Escalation |
|------------|------------|
| Low | Business Owner |
| Moderate | Business Owner + Information Security |
| Elevated | Risk & Compliance Manager |
| High | Executive Risk Committee |

---

# Recommended Monitoring Sources

Examples of publicly available intelligence sources include:

- CISA Known Exploited Vulnerabilities (KEV) Catalog
- NIST National Vulnerability Database (NVD)
- Vendor security advisories
- Vendor trust centers and status pages
- CERT and government cyber advisories
- Industry Information Sharing and Analysis Centers (ISACs)
- Security ratings platforms (where available)

---

# Monitoring Workflow

1. Collect monitoring information.
2. Validate whether the event affects the vendor.
3. Assess business impact.
4. Update the vendor risk record.
5. Determine whether reassessment is required.
6. Escalate significant findings according to the escalation matrix.
7. Document decisions and evidence.

---

# Relationship to Assessment Half-Life

The Assessment Half-Life represents the period after which a vendor assessment should no longer be considered fully reliable without additional evidence.

Continuous monitoring extends the usefulness of an assessment by providing updated risk signals between formal reassessments. When significant monitoring events occur, the vendor should be reassessed regardless of the remaining Half-Life.

---

# Scope

This playbook supports the fictional NovaTide Logistics Enterprise Simulation and is intended for educational and portfolio purposes. Organizations should tailor monitoring activities to their regulatory obligations, risk appetite, and operational environment.
