# Exercise 8.5

# Capstone — AI Customer Engagement Assistant (Sales & Marketing)

## 🎯 Objective
Design and demonstrate an AI assistant that:
1) Drafts professional replies to customer complaints, and  
2) Suggests data-driven marketing ideas to improve retention and sales.

## 📂 Assets
- **Customer Emails (TXT, ~50 messages):** `oil_libya_customer_emails.txt`  
  Each email includes: Date, From, Phone, City, Station, Subject, and body.

> Download: place this file in your repo (e.g., `/data/oil_libya_customer_emails.txt`) and reference it in your notebook or prompt tool.

## 📌 Expected Outputs (for presentation)
- **Replies:** Clear **apology + fix assurance** for each complaint.  
- **Summaries:** Categorize issues into:
  - `pump issue`
  - `card issue`
  - `price sensitivity`
- **Marketing ideas:** at least two concrete actions:
  - “Discount weekends”
  - “Double loyalty points”
  - *(Optionally propose more: geo-targeted SMS, off-peak promos, fleet partner bundles.)*

---

## 🛠️ Workflow

### 1) Load & Inspect
- Open `oil_libya_customer_emails.txt`.  
- Skim through themes: pump/nozzle problems, card/POS failures, pricing concerns, loyalty/app issues.

### 2) Build the AI Prompts (Starter Prompts)
**Analysis prompt:**  
> “Extract each email’s `category` (pump issue / card issue / price sensitivity / other), `city`, `station`, and a 1–2 line summary. Return as a table.”

**Reply prompt (few-shot style):**  
> “Given a customer complaint, write a reply that starts with an apology, acknowledges the exact issue, states the immediate fix (or investigation), gives a timeline/next step, and invites the customer to respond. Keep it warm, professional, and concise. Use Oil Libya voice.”

**Marketing prompt:**  
> “From the categorized issues, propose 2–4 customer-facing campaigns to reduce churn and increase satisfaction. Include audience, channel, incentive, and success metric. Prioritize ‘Discount weekends’ and ‘Double loyalty points.’”

### 3) Produce Outputs
- **Replies:** One per email (apology + fix assurance + next steps).  
- **Summaries:** Counts per category and top 3 root causes.  
- **Ideas:** At least 2 marketing actions with brief roll-out plan.

### 4) Package for Presentation
- `summaries.md` — category counts, top stations with issues, quick insights.  
- `replies/` — a folder of AI-drafted replies (one text file per email) *or* a single compiled document.  
- `marketing_ideas.md` — 2–4 ideas with audience, channel, incentive, KPI.

---

## ✅ Evaluation Criteria
- **Accuracy:** Correctly classifies emails and tailors replies to the complaint.  
- **Tone & Professionalism:** Empathetic, concise, action-oriented replies.  
- **Actionability:** Marketing ideas are targeted, feasible, and measurable.  
- **Clarity:** Clean structure, tables, and clear recommendations.  
- **Ownership:** Concrete follow-ups (ticket ID, station check, POS reset plan, etc.).

---

## 🧪 Suggested Structure for Outputs

### A) Summary Table (example)
| Category         | Count | Top Locations             | Notes                           |
|------------------|------:|---------------------------|----------------------------------|
| pump issue       |   18  | Tripoli, Benghazi         | Nozzle leaks, pump downtime     |
| card issue       |   16  | Misrata, Zawiya           | POS freeze, double charges      |
| price sensitivity|   16  | Tripoli, Sirte            | Discount requests, comparisons  |
| other            |    –  | —                         | Loyalty/app, staff, receipts    |

### B) Reply Template (example)
> **Subject:** We’re on it — {Station}  
>  
> Dear {Customer Name},  
> We’re truly sorry about the issue you experienced with {specific problem}. Our team has opened a ticket and is checking {station details} today. We’ll {action/timeline}, and we’ll update you by {date/time}.  
> If it happens again or you have more details, please reply here or call {support line}.  
>  
> Thank you for your patience,  
> Oil Libya Support

### C) Marketing Ideas (example)
1. **Discount Weekends**  
   - **Audience:** Price-sensitive retail customers  
   - **Channel:** On-site banners, WhatsApp broadcast, app push  
   - **Incentive:** 3–5% off Fri–Sat evenings  
   - **Metric:** Weekend volume ↑, price complaints ↓

2. **Double Loyalty Points**  
   - **Audience:** Loyalty members & lapsed users  
   - **Channel:** App, SMS, receipts  
   - **Incentive:** 2× points for premium or off-peak hours  
   - **Metric:** Redemptions ↑, repeat visits ↑

*(Optionals)*  
3. **POS Reliability Pledge** (Card issue mitigation)  
4. **Pump Reliability Dashboard** (Transparency + QA trust)

---

## 🧩 Stretch Tasks
- Auto-detect sentiment per email and prioritize severe cases.  
- Create a **station heatmap** of issues by city.  
- Add **A/B test** design for Discount vs. Double Points.  
- Draft **FAQ macros** for agents (payment, pricing, pumps).

---

## 🧠 Presentation Questions to Prepare For
1. How did you ensure every reply includes **apology + fix assurance**?  
2. Which **three stations** contribute most complaints, and why?  
3. What quick fixes would reduce **pump** and **card** issues this week?  
4. How will you measure the success of **Discount weekends** and **Double loyalty points**?  
5. What are the **limits** of AI-generated replies, and how will humans stay in the loop?

---

## 🚀 Submission Checklist
- [ ] `summaries.md` (tables + bullet insights)  
- [ ] `marketing_ideas.md` (at least 2 ideas with metrics)  
- [ ] `replies/` (or one compiled doc) with 50 reply drafts  
- [ ] Optional visuals (bar chart by category, station heatmap)
