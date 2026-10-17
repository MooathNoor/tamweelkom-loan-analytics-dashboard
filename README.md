# 📊 Tamweelkom Loan Analytics & Financial Commitment Dashboard

An interactive Microsoft Excel dashboard designed to analyze, track, and visualize **Tamweelkom's** financing portfolio, client repayment behaviors, branch performance, and financial policy alignment.

---

## 🚀 Key Features & Analytical Insights

* **Key Performance Indicators (KPI Cards):** 
  * Total Portfolio Funding
  * Total Remaining Balance
  * Total Loan Approval Rate / Disbursement
  * Repayment Ratios & Balances

* **Category Averages vs. Company Benchmark:** 
  * Comparative analysis contrasting individual financing categories against Tamweelkom's overall financial policy benchmark (**5,400.00 JOD**).
  * Clear visual breakdown identifying categories above benchmark (*Agricultural Financing* & *Small Commercial Loans*) and below benchmark (*Professional* & *Women/Individual Financing*).

* **Branch Funding Comparison:**
  * Performance breakdown across major operating branches (**Amman, Irbid, Zarqa, Aqaba, Karak**).

* **Repayment & Portfolio Health Tracking:**
  * Categorized analysis of loan statuses (**Active, Completed, Delayed, Defaulted**).

* **Unified Dynamic Slicer:**
  * Connected across all underlying PivotTables (`Report Connections`), enabling one-click seamless filtering across the entire dashboard.

---

## 🛠️ Excel Functions & Techniques Applied

* **PivotTables & PivotCharts:** Advanced data aggregation and dynamic chart creation.
* **Calculated Formulas & Benchmarks:** Absolute references (`=AVERAGE($F$2:$F$11)`) for fixed policy comparison.
* **KPI Card Integration:** Direct cell linking to avoid `GETPIVOTDATA` range errors in dynamic shapes.
* **Table Total Rows:** Native Excel table total aggregation (`Average` / `Sum`).
* **Slicers & Report Connections:** Multi-PivotTable dynamic filtering.

---

## 📂 File Structure

| File Name | Description |
| :--- | :--- |
| `Tamweelkom_Loan_Financing_Dashboard.xlsx` | Main Excel workbook containing raw data, PivotTables, and the final interactive Dashboard. |

---

## 💻 How to View & Use

1. Download or clone the repository.
2. Open `Tamweelkom_Loan_Financing_Dashboard.xlsx` in Microsoft Excel (2016 or newer recommended).
3. Use the **Status Slicer** in the center of the dashboard to filter all KPIs and charts dynamically.

---

👤 **Author:** [MooathNoor](https://github.com/MooathNoor)  
📌 *Data Analyst & Computer Science Student*
