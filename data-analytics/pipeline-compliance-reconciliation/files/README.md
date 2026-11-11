# Enterprise Pipeline Compliance & Automated Data Audit Engine

*(Check image: sap-p1-formula.png)*

**An automated multi-system audit framework designed to enforce single-source-of-truth accuracy across dynamic revenue pipelines.**

> **Privacy Guardrails:** All account names, values, and identifiers in project assets are replaced with 100% synthetic data of identical structure. The reporting architecture, formulas, and reconciliation workflows reflect real-world enterprise logic.

---

## 🎯 The Business Challenge
Following major enterprise system migrations and multi-CRM operations, sales opportunities frequently exist across dual-CRM environments that drift out of sync. 

Metadata attributes (account titles, industry codes, and entity IDs) regularly deviate from verified third-party data providers (e.g., D&B Hoovers), while incoming weekly opportunity flows introduce unverified records, creating forecasting risks for revenue leadership.

---

## 🛠️ Technical Solution & Audit Workflow

1. **Automated Reconciliation Framework:** Designed a self-updating Excel compliance engine that cross-references rolling CRM pipeline exports against audited master records.
2. **Dynamic Lookup Logic:** Integrated automated formulas (`XLOOKUP`, `INDEX/MATCH`, `ISNA`) running ~800 lookups per refresh cycle to auto-populate verified account metadata and instantly flag new, un-audited records.
3. **Multi-Point Attribute Auditing:** Evaluated every deal record across account metadata, industry classification, DUNS identification numbers, and quarter-end close boundary dates to automatically isolate stale opportunities.
4. **Standard Operating Documentation:** Embedded refresh protocols and auditing instructions directly inside the reporting workbook to ensure continuous team adoption.

---

## 📈 Key Outcomes & Technical Deliverables
- **Governance Coverage:** Reconciled 711 active deal records across 693 accounts, 51 opportunity owners, 7 sales regions, and 9 fiscal quarters within a single executive view.
- **Proactive Exception Isolation:** Built exception rules so new or corrupted records automatically flag themselves for review upon file refresh instead of relying on manual audits.
- **Audit Continuity:** Delivered a fully operational, self-updating workbook adopted as a standard quarterly governance template.

---

## 🖼️ Visual Evidence
![Every record checked against reference data, formula bar visible. Synthetic records, real structure.](images/compliance-tracker-overview.png)
*Every record checked against reference data, formula bar visible. Synthetic records, real structure.*

---

## 📁 Project Assets & Files
- **Cleaned Workbook:** [`SAP_Pipeline_Compliance_CLEANED.xlsx`](files/SAP_Pipeline_Compliance_CLEANED.xlsx) (Located in `/files/` folder — *Built with `INDEX`/`MATCH` formulas for universal spreadsheet compatibility*)

---

## 🛠️ Tech Stack & Core Competencies
Advanced Microsoft Excel · Dynamic Formulas (`XLOOKUP`, `INDEX/MATCH`, `ISNA`) · Dual-CRM Alignment · Third-Party Data Validation (D&B Hoovers) · Salesforce CRM · Data Reconciliation · Process Documentation