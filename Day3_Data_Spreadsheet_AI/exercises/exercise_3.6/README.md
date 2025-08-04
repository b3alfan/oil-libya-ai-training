# Exercise 3.6

# Exercise 3.6 – Build a Payroll Calculation Table

**Objective:**  
Use AI to generate payroll logic and formulas to calculate net salaries, bonuses, and deductions — useful for HR, finance, and admin teams.

---

## 🧠 Background

Payroll spreadsheets can be automated using formulas. With the right input, AI can help you:
- Calculate bonuses
- Apply tax and deduction logic
- Handle overtime or absence penalties

---

## 📝 Task

1. Open the file [`payroll_data.csv`](assets/payroll_data.csv).
2. Ask AI to help you write formulas that:
   - Calculate **gross salary** (Base Salary + Allowances + Overtime)
   - Deduct **tax (15%)** and **absences** (200 ERN per absence)
   - Output **Net Salary** = Gross - Tax - Absence Deductions

3. Prompt example:
   > **"Write an Excel formula to calculate Net Salary with 15% tax and 200 ERN penalty per absence."**

4. Try different versions:
   - “Highlight employees with Net Salary below 7,000 ERN”
   - “Which employee earned the most after deductions?”

---

## 🎯 Deliverable

Submit:
- The formulas used
- A sample row result
- Any AI-generated logic you tested

---

## 🔁 Bonus Task

Ask:
> “Generate a payslip summary for each employee in plain text.”

Example output:
> "Employee: Hagos T. | Gross: 8,900 | Deductions: 1,050 | Net Pay: 7,850"

---

## 💡 Tips

Useful Excel functions:
- `=SUM(...)`
- `=IF(...)`
- `=ROUND(...)`
- `=A2+B2+C2-(A2+B2+C2)*0.15-D2*200`

---

## 📁 Assets

- [`payroll_data.csv`](assets/payroll_data.csv) — Employee payroll data for January
