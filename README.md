# 📑 Management Reporting Automation

Recurring MI packs shouldn’t require copy-paste.  
This project automates KPI calculation, regional summaries, and a monthly trend sheet, exporting everything to a clean multi-sheet Excel workbook for stakeholders.

---

## 🎯 Objectives
- Produce a repeatable MI report from raw sales data  
- Eliminate manual aggregation and human error  
- Generate a single Excel file with KPI summary + region + trend

---

## ⚙️ Workflow
1. **Load & Clean:** Normalize columns, parse dates, ensure numeric types  
2. **KPIs:** Total Sales, Average per Order, Total Orders, Unique Customers, Top Region  
3. **Visuals:** Sales by Region; Monthly Sales trend  
4. **Export:** Multi-sheet Excel (`management_report.xlsx`) using `xlsxwriter`

---

## 📊 Tools & Tech
- **Python (Colab)** — pandas, matplotlib, seaborn, xlsxwriter  
- **Dataset:** `train.csv` (e-commerce sales)  
- **Output:** `management_report.xlsx` (Data_Summary, Sales_by_Region, Monthly_Sales)

---

## 🧾 Deliverables
- `Management_Reporting_Automation.ipynb` — full code + outputs  
- `management_report.xlsx` — shareable MI workbook (optional to upload)  
- `README.md` — documentation and usage notes

---

## ✅ Key Takeaways
- One-click refresh of the management report  
- Consistent structure across runs (audit-friendly)  
- Easy to extend: targets, variance analysis, distribution list

