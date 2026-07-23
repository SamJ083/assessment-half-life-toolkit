# NovaTide Logistics Enterprise Simulation

# TPRM Vendor Scoring Framework: Assessment Half-Life Toolkit

<p align="center">
  <img src="diagrams/vendor-risk-workflow.png" width="750">
</p>


A practical Third-Party Risk Management (TPRM) toolkit demonstrating how organizations can move from **point-in-time vendor assessments** to **continuous, risk-based vendor monitoring**.

This repository accompanies my LinkedIn article:

**"Your Vendor Assessment Has a Half-Life: What the 2026 Black Kite Report Reveals About Modern TPRM."**

The project is built around the fictional enterprise **NovaTide Logistics**, which serves as a persistent business environment for demonstrating Governance, Risk, and Compliance (GRC) concepts through realistic enterprise simulations.

---

# Project Objective

Traditional TPRM programs often assess vendors during onboarding and revisit them annually. However, modern cyber threats evolve much faster than annual assessment cycles.

This toolkit demonstrates how organizations can:

- Build a structured vendor inventory.
- Assign vendors using a risk-based tiering model.
- Calculate composite vendor risk scores.
- Introduce the concept of **Assessment Half-Life** to determine when assessments lose reliability.
- Apply continuous monitoring based on vendor criticality.
- Support repeatable and auditable vendor governance processes.

---

# Repository Contents

```text
docs/
    methodology.md
    scoring-model.md
    implementation-guide.md
    monitoring-playbook.md

data/
    vendor_inventory.xlsx
    vendor_inventory.csv
    sample_dashboard.png

diagrams/
    vendor-risk-workflow.drawio
    vendor-risk-workflow.png
```

---

# Framework Overview

The framework follows a continuous vendor lifecycle:

```
Vendor Identification
        ↓
Vendor Inventory
        ↓
Vendor Tier Classification
        ↓
Risk Assessment
        ↓
Risk Decision
        ↓
Continuous Monitoring
        ↓
Assessment Half-Life Review
        ↓
Reassessment
```

---

# Assessment Half-Life

Assessment Half-Life is the central concept introduced in this project.

Rather than assuming a vendor assessment remains valid until the next scheduled review, the framework recognizes that assessment confidence naturally declines over time as vendor environments, threat landscapes, and business dependencies evolve.

The framework therefore recommends reassessment frequencies based on vendor criticality.

| Vendor Tier | Assessment Half-Life |
|-------------|--------------------:|
| Critical | 90 Days |
| High | 180 Days |
| Medium | 365 Days |
| Low | 730 Days |

---

# Dashboard Preview


<p align="center">
  <img src="data/sample_dashboard.png" width="900">
</p>


The Excel dashboard provides:

- Vendor inventory summary
- Vendor tier distribution
- Vendor category breakdown
- Composite vendor risk rankings
- Continuous monitoring metrics

---

# Vendor Risk Lifecycle

<p align="center">
  <img src="diagrams/vendor-risk-workflow.png" width="700">
</p>

The workflow illustrates how vendor assessments transition from onboarding activities to continuous monitoring and periodic reassessment.

---

# Who This Project Is For

This repository is intended for:

- Governance, Risk & Compliance (GRC) professionals
- Third-Party Risk Management (TPRM) teams
- Security and Compliance Analysts
- Internal Audit professionals
- Students building practical cybersecurity governance skills


---

# About the Enterprise Simulation

NovaTide Logistics is a fictional global logistics company used across my GitHub portfolio to demonstrate practical implementations of cybersecurity governance, AI governance, enterprise risk management, and third-party risk management.

Each repository builds upon the same enterprise environment to simulate realistic governance scenarios.

---

# Disclaimer

This project is intended for educational and portfolio purposes. All organizations, datasets, vendors, assessments, and scenarios are either fictional or based on publicly available information and should not be interpreted as production-ready governance guidance.
