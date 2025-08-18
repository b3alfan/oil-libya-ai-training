# Exercise 8.4

# Capstone Exercise — Finance & Procurement AI Expense & Fraud Detector

## 🎯 Objective
Train staff to apply AI tools for **detecting unusual expenses, summarizing spending trends, and identifying fraud risks** in Oil Libya’s Finance & Procurement operations.

---

## 📋 Exercise Description
Trainees will work with a **mock expenses table** containing 120+ entries of departmental spending.  
The dataset includes:
- Routine purchases
- Travel and conference costs
- Vendor service fees
- Duplicate entries
- Suspicious charges

Using AI tools, trainees will:
1. Categorize expenses by department and vendor.
2. Detect anomalies (e.g., duplicates, unusually high costs).
3. Summarize spending patterns.
4. Generate visual insights (charts/tables) to share with management.

---

## 📂 Assets Provided
- **Mock Expenses Table (CSV):**  
  `mock_expenses_table.csv` (contains 120 entries)  
  Columns:
  - `Date`
  - `Department`
  - `Vendor`
  - `Amount (USD)`
  - `Notes`

Sample snippet:

| Date       | Department | Vendor     | Amount (USD) | Notes              |
|------------|------------|------------|--------------|--------------------|
| 2025-07-01 | HR         | OfficeMax  | 150          | Stationery         |
| 2025-07-02 | Sales      | TravelCo   | 5,500        | Conference         |
| 2025-07-02 | Sales      | TravelCo   | 5,500        | Duplicate entry    |
| 2025-07-03 | Fuel Ops   | TechServ   | 20,000       | System maintenance |
| 2025-07-04 | Finance    | Consultant | 50,000       | Advisory fee (susp.) |

---

## 🛠️ Steps to Perform

1. **Load Data into AI Tool**
   - Copy and paste the expenses table into your assigned AI tool (ChatGPT, Claude, Copilot, or Excel AI assistant).
   - Or upload the CSV if your tool supports it.

2. **Categorize Expenses**
   - Prompt:  
     *“Group all expenses by department and vendor, and calculate total spending per category.”*

3. **Spot Anomalies**
   - Prompt:  
     *“Highlight duplicate entries, unusually high amounts, and suspicious fees.”*

4. **Summarize Insights**
   - Prompt:  
     *“Summarize spending patterns in plain language suitable for management reporting.”*

5. **Visualize Trends**
   - Ask AI to suggest or generate bar/pie charts of spending by department and vendor.

6. **Prepare Output**
   - Export summarized tables and charts.
   - Document flagged anomalies.

---

## ✅ Expected Output
- **Anomaly Detection**
  - Flags duplicate TravelCo charges (2 × $5,500 on same date).
  - Highlights high Consultant advisory fee ($50,000).
  - Detects outliers like unusually high maintenance/service contracts.

- **Departmental Spending Summary**
  - Group totals (e.g., Sales: $XX,XXX; Fuel Ops: $XX,XXX).
  - Vendor-level breakdown.

- **Management Summary (1 page)**
  - Clear explanation of anomalies.
  - Key trends: top 3 biggest spenders, most frequent vendors.
  - Recommended controls.

---

## 📊 Deliverables
Each trainee (or team) must prepare:
1. **Analysis Report (Markdown/PDF)** — Summary of anomalies, trends, and findings.  
2. **Visualization** — At least 2 charts (spending by department, anomaly chart).  
3. **Presentation (5 min)** — Key findings and recommendations.  

---

## ❓ Extra Questions for Presentation
Trainees should be ready to answer:
1. Which **three departments** had the highest spending and why might that be?  
2. Which vendor(s) appear **most frequently**, and does that pose a procurement risk?  
3. What are **two examples of anomalies** you discovered, and what would you recommend doing about them?  
4. How would you **improve internal controls** to prevent duplicates or suspicious charges?  
5. If you were building an **AI tool in-house**, what features would you include to help Finance & Procurement?  
6. What are the **limitations** of relying only on AI for fraud detection?  

---

## 🏆 Evaluation Criteria
- **Accuracy** — Correctly identify anomalies and patterns.  
- **Clarity** — Clear, well-organized summary.  
- **Visuals** — Use of charts/tables to illustrate findings.  
- **Critical Thinking** — Practical recommendations to improve processes.  
- **Presentation** — Professional delivery, concise insights.  

---
