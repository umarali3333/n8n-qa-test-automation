# n8n QA Test Automation 🚀

This project automates test case generation and storage using n8n.

## Features

- ✅ AI-based test case generation (Groq)
- ✅ Stores test cases in Google Sheets
- ✅ Creates Jira Test issues (Zephyr integration)
- ✅ Supports structured QA format (TC-01, TC-02...)

## Workflow

Input → AI (Groq) → Generate Test Cases  
→ Parse → Save to Google Sheets  
→ Create Jira Test Issues
![Workflow](Test%20case%20generator%20work%20flow.png)

## Tech Stack

- n8n
- Groq LLM
- Google Sheets API
- Jira API (Zephyr)

## How to Use

1. Import JSON into n8n
2. Add credentials:
   - Groq API
   - Google Sheets
   - Jira
3. Run the workflow

## Output

- Structured test cases
- Excel-like format
- Jira-linked test cases

---

Built as part of QA automation learning 💡

