# 🧶 WeaveForward-ML: Minimal Project Optimizations

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/PySpark-3.5-orange.svg" alt="PySpark">
  <img src="https://img.shields.io/badge/Status-Optimized-success.svg" alt="Status">
</p>

---

### 📖 Repository Philosophy
> This project applies **surgical, minimal fixes** to the original baseline. The development strategy prioritizes repository-wide integrity and traceability over architectural refactoring.

<table width="100%">
  <thead>
    <tr>
      <th width="30%">Goal</th>
      <th width="35%">Strategy</th>
      <th width="35%">Outcome</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Auditability</b></td>
      <td>Preserve original notebook flow</td>
      <td>Transparent comparison with baseline</td>
    </tr>
    <tr>
      <td><b>Stability</b></td>
      <td>Target critical technical failures</td>
      <td>Resolved Spark crashes & scraping bugs</td>
    </tr>
    <tr>
      <td><b>Refinement</b></td>
      <td>Surgically polish data signals</td>
      <td>High-purity data without code bloat</td>
    </tr>
  </tbody>
</table>

---

### 📂 Optimization Audit Logs

<details>
<summary><b>🕸️ 1. Webscraper Extraction Audit</b> (Click to expand)</summary>
<br>

| Section | Feature | Original Logic | Optimized Change | Rationale |
| :--- | :--- | :--- | :--- | :--- |
| **1-A** | Brand Catalog | ~25 static list | 61 brands + `#api` routing | Scale & Shopify API support |
| **1-B-1** | Type Detection | Basic `in` checks | Regex `\b` + Title-priority | Eliminate "Dress/Polo" noise |
| **1-B-1** | Fiber Parser | Rounding/scaling | 100% "Strict Truth" | Prevent text duplicates |
| **1-B-3** | Scraper Engine | BeautifulSoup only | **NEW** `scrape_api` JSON | High-speed paginated extraction |
| **1-B-4** | Scrape Loop | Single-path crawler | Dual-engine routing | Integrated Shopify support |
| **1-D** | Archive Merge | `.values` indexing | Native numpy array indexing | Fixes boolean indexing bug |

</details>

<details>
<summary><b>🤖 2. Recommendation Model Audit</b> (Click to expand)</summary>
<br>

| Section | Feature | Original Logic | Optimized Change | Rationale |
| :--- | :--- | :--- | :--- | :--- |
| **4-B** | Data Structure | UUID strings | Integer counters + Surrogate PK | Spark serialization stability |
| **4-C-2** | Spark Ingestion | Direct DF creation | `clean_val` + Explicit Schema | Fixes `EOFException` crashes |
| **5-A-2** | Artisan Registry | 6 profiles | 109 profiles across NCR | Realistic geographic coverage |
| **5-C** | Feature Set | Included `artisan_id` | Removed ID & Demand Index | Eliminate model identity bias |
| **7-B** | Hyperparameters | Wide Optuna search | Constrained search space | Stabilize final model training |
| **8-C** | Evaluation | Standard metrics | SHAP + Routing Analysis | Calibration & Explainability |

</details>

---
<p align="center">
  <i>Generated with ❤️ by Antigravity AI Assistant</i>
</p>