# Exercise 6.3

# Exercise 6.3 – Clean and Classify Procurement Invoices

**Objective:**  
Use AI to fix messy entries in a procurement invoice sheet and categorize them by vendor and product type.

---

## 📝 Task

1. Open the file `procurement_invoices_raw.csv`
2. Ask AI to:
   - Fix typos, normalize vendor/product names
   - Classify purchases into categories (e.g. Fuel, Office Supplies, Spare Parts)
   - Provide a cleaned CSV or markdown table
   - Bonus: total spending per vendor or category

---

## 🎯 Deliverables

- Cleaned table with corrected names and categories
- Optional summary (e.g. "Total spent on Office Supplies = X")

---

## 💡 Prompt Ideas

- “Clean this CSV and fix misspelled vendor names”
- “Group this procurement list by item type”
- “Summarize total spending per vendor and product category”

---

### 📁 Asset: `procurement_invoices_raw.csv`

```csv
Invoice No,Vendor,Product,Amount (Nfk),Date
PR-1001,Oilibia Fuel Depot,Diesel (5000L),171250,2024-06-01
PR-1002,Unicef Offce Supplies,Paper Boxes (A4),3200,2024-06-03
PR-1003,oil libya fuel depo,Petrol (3000L),102750,2024-06-04
PR-1004,TotalTech Eritrea,Toner Cartriges,4500,2024-06-0
