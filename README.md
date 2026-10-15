# UOC CRIS vs. OpenAlex: Publication Coverage and Metadata Consistency

This repository presents a comparative assessment of publication coverage and metadata consistency between the **CRIS (Current Research Information System)** of the **Universitat Oberta de Catalunya (UOC)** and the **OpenAlex** database via DOIs.

**Author:** Bruna Santanach  
**Institution:** Universitat Oberta de Catalunya (UOC)  
**ORCID:**https://orcid.org/0009-0008-8851-3869
---

## 🔗 Interactive Report

You can view the full interactive HTML report generated from this study directly via GitHub Pages:
👉 **[View Interactive Coverage Report](https://<YOUR-GITHUB-USERNAME>.github.io/<YOUR-REPOSITORY-NAME>/)**

---

## 📊 Summary of Findings

- **Coverage Comparison:** Analysis of matching and non-matching DOIs across academic publication types (journal articles, book chapters, conference papers, reviews, etc.).
- **Open Access Bias:** Identification of how discrepancies in institutional attribution and repository versioning impact the institution's overall Open Access (OA) metrics.
- **Metadata Consistency:** Evaluation of metadata alignment regarding publication year, item typology, citation counts, and OA status/routes.

---

## 🔒 Data Sources & Availability

For privacy and institutional data protection reasons, the raw datasets used in this analysis are **not publicly available** in this repository. 

However, the data utilized in this study originates from two primary sources:
1. **OpenAlex Data:** Retrieved via the OpenAlex API filtering by the UOC ROR/Institution ID (`I138847295`):
   - Query endpoint: [`https://api.openalex.org/works?filter=authorships.institutions.id%3AI138847295`](https://api.openalex.org/works?filter=authorships.institutions.id%3AI138847295)
   - **Extraction Date:** October 15, 2026.
2. **CRIS UOC Data:** Extracted directly from the institutional CRIS of the Universitat Oberta de Catalunya (**Private / Non-disclosed raw dataset**).

---

## 📄 License

The HTML report and documentation in this repository are licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**. 

You are free to share and adapt the material, provided appropriate credit is given to the author and institution.
