# Salesforce Pipeline Quality & Admin Dashboard Engine

*(Check image: salesforce-admin-dashboard-overview.png)*

## 📌 Executive Summary
This project is an enterprise-grade pipeline audit and governance engine built in Excel to evaluate Salesforce opportunity data, enforce strict CRM hygiene, and provide executive visibility across multi-region commercial pipelines. Designed as a functional technical replication of real-world Revenue Operations logic, the system runs 5 automated validation checks across 3,000+ formulas to catch forecast discrepancies, missing billing attributes, and overdue close dates. The exact analytical methodology and validation logic demonstrated in this project were implemented to lift global pipeline data quality by 5% and support quarterly forecast reviews for 100+ sales representatives at SAP Emarsys.

---

## 🎯 Business Context & Problem Statement
* **Legacy Tooling:** Outdated reporting templates often rely on manual formula overrides, leading to broken links and inconsistent evaluation across sales territories.
* **Lack of Standardization:** Regional leaders frequently audit deal pipelines using different criteria, introducing noise and inaccuracies into executive forecasting.
* **Revenue & Attribution Risk:** Missing billing metadata, unverified partner IDs, and past-due close dates directly impair pipeline reliability and lead attribution across enterprise sales cycles.

---

## 🛠️ Tools & Tech Stack
| Category | Technology / Technique | Applied Role |
| :--- | :--- | :--- |
| **Primary Platform** | Advanced Microsoft Excel | Dashboard Architecture & Logic Engine |
| **Core Functions** | `COUNTIFS`, `VLOOKUP`, `XLOOKUP`, `ISBLANK`, `AND`/`OR` | Data Validation & Exception Auditing (3,000+ formulas) |
| **CRM Data Source** | Salesforce CRM (SFDC) | Pipeline & Opportunity Data Model Ingestion |
| **Domain Expertise** | Revenue Operations (RevOps) | Pipeline Hygiene Guardrails & Regional Risk Scoring |
| **Documentation** | Refresh Handover Guides & SOPs | Operational Continuity & Data Governance Standards |

---

## ⚙️ Technical Implementation & Validation Engine
The reporting engine processes raw Salesforce opportunity exports using over **3,000 dynamic Excel formulas** with nested validation logic to execute 5 mandatory pipeline health checks:

1. **Forecast Category Validation:** Audits alignment between stage progression and assigned forecast tiers.
2. **Forecast MRR Validation:** Identifies recurring revenue entries violating pricing rules or missing technology MRR values.
3. **Billing Address Validation:** Flags account entries missing required billing address metadata prior to commercial submission.
4. **Business Partner ID Validation:** Ensures deal records contain registered partner IDs to guarantee accurate partner attribution.
5. **Overdue Close Date Monitoring:** Automatically isolates active opportunities with close dates past the active quarter boundary.

### Architecture Highlights
* **Single-Cell Quarter Control:** Dynamic date filtering allows sales leaders and executives to pivot the entire global dashboard across past, current, and future fiscal quarters via a single control cell.
* **Regional Risk Scoring:** Automated exception categorization tags regional pipelines as `REVIEW` or `FAIR` based on rule compliance thresholds.
* **Operational Documentation:** Complete refresh protocols and user guidelines ensure seamless handover and long-term reporting adoption.

---

## 📈 Quantified Outcomes & Commercial Impact
* 🟩 **5% Data Hygiene Improvement:** Demonstrates the exact logic used to raise pipeline data completeness and rule compliance across 7 global sales regions.
* 🟩 **Executive Visibility:** Consolidates multi-region operational data into a unified single-page executive overview.
* 🟩 **Enterprise Application:** Replicates real-world RevOps governance standards used to support 100+ sales reps and multi-million-pound pipeline reviews at SAP Emarsys.

---

## 📁 Project Assets & Files
* **Cleaned Workbook:** `Salesforce_Admin_Dashboard_file.xlsx` (Located in `/files/` folder - *100% Synthetic Data*)
* **Visual Evidence:** `salesforce-admin-dashboard-overview.png` (Located in `/images/` folder)