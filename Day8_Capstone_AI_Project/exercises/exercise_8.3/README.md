# Exercise 8.3

# 🖥️ IT Capstone Exercise: AI Log Analyzer

## 🎯 Goal
Use an AI assistant (e.g., ChatGPT or similar) to:
- **Summarize recurring errors** in the provided logs  
- **Suggest likely root causes**  
- **Recommend preventive actions**  

This simulates how IT teams at OilLibya could apply AI to accelerate incident investigation and improve system reliability.

---

## 📂 What’s Included
- `it_logs_capstone.log` → 700 lines of synthetic production-like system logs (DB, app, cache, gateway, worker nodes).
- `IT_Capstone_Log_Analyzer_Instructions.pdf` → detailed exercise instructions.
- `IT_Capstone_Log_Analyzer_Answer_Key.pdf` → instructor guide & sample answer.

---

## 📝 Exercise Steps (30–45 min)
1. Open the file: **`it_logs_capstone.log`**
2. Select a representative chunk (~150–200 lines) and paste into your AI tool.
3. Prompt the AI to:
   - Cluster messages by **error code**  
   - Count occurrences  
   - Summarize **impact** on the system  
4. Ask the AI to infer **root causes** and list **preventive actions** (prioritized by impact/effort).
5. Produce a **1-page summary** for your manager:  
   - Top 3 issues  
   - Root causes  
   - Recommended actions  

---

## 💡 Suggested Prompts
- “Cluster these logs by `code=...` and level; count occurrences; show a ranked table of the top problem types.”  
- “Based on these logs, what are the likely root causes? Cite 2–3 log lines for each cause.”  
- “Give me a prioritized action plan with owners, timeframes, and success metrics.”  
- “Draft alert rules (plain English) that would have caught these issues earlier.”  

---

## 📦 Deliverables
- Ranked list of issues (with counts)  
- Root-cause hypotheses (why it’s happening)  
- Preventive actions: scaling, indexing, monitoring, caching  
- (Optional) 5 alert rules + runbook (who to ping, what to check)

---

## 🚀 Stretch Goals
- Write example SQL indexes to relieve slow queries on `orders(created_at)` and `transactions(user_id, created_at)`.  
- Propose **SLOs**:  
  - API p95 latency < 800ms  
  - DB timeout rate < 0.2% of queries  
- Design a **Grafana dashboard**: CPU, DB connections, slow queries, error rates, cache hit ratio.  

---

## ✅ Expected Learning Outcomes
By completing this exercise, you will:
- Recognize patterns in noisy production logs  
- See how AI can accelerate **root-cause analysis**  
- Practice turning raw logs into **actionable insights**  
- Learn to write **preventive measures** that IT teams can implement immediately  

---
