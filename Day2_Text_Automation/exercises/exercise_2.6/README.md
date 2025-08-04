# Exercise 2.6

# Exercise 2.6 – Label Document Types from Scanned Text

**Objective:**  
Use AI to identify the type of a document based on a partial or scanned-text excerpt — useful in file management, archiving, and OCR-based systems.

---

## 🧠 Background

When handling scanned or OCR-extracted text, it's often unclear what kind of document you're looking at. AI can infer:
- Whether the content is a **contract**, **policy**, **invoice**, **report**, or **memo**
- The **audience** and **purpose** of the document
- The **confidence level** of its guess

---

## 📝 Task

1. Open the file [`scanned_text_snippets.txt`](assets/scanned_text_snippets.txt). It contains raw OCR-style snippets from unknown documents.
2. Ask the AI:

   > **"Label each of these text snippets as either: Contract, Policy, Invoice, Technical Report, or Internal Memo. Justify your answer briefly."**

3. Ask the AI to return a table with:
   - Snippet ID
   - Type
   - Justification
   - Confidence (High, Medium, Low)

---

## 🎯 Deliverable

- A labeled table or list of all entries
- Your prompt(s) and refinements
- Optional: A brief summary of how accurate you found the AI

---

## 🔁 Bonus Task

Ask:
> “What keywords or structure helped you decide what each document was?”

This helps you reverse-engineer the AI’s reasoning.

---

## 💡 Tips

Prompts to try:
- “Classify based on language and structure”
- “Guess the document type and explain why”
- “Use context clues to infer category”

---

## 📁 Assets

- [`scanned_text_snippets.txt`](assets/scanned_text_snippets.txt) — OCR-like text samples to label
