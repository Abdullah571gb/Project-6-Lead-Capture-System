# 🎯 Project 6: Lead Capture + Qualification System

A complete end-to-end lead processing automation that captures leads via webhook, uses AI to qualify them, sends personalized emails, and logs everything — replacing a manual, repetitive business process.

---

## 📌 What This Project Does

This system automates the full lifecycle of handling an incoming sales/business lead:
1. Captures lead data submitted through a webhook (e.g. a web form)
2. Validates that all required fields are present
3. Uses AI to qualify the lead — YES/NO decision with a score from 1-10
4. Routes qualified vs. unqualified leads differently
5. For qualified leads: AI writes a personalized email, which is sent automatically via Gmail
6. Sends a Telegram alert for every lead received (qualified or not)
7. Logs everything to Google Sheets for record-keeping

---

## ⚙️ How It Works (Workflow)

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **n8n** | Workflow automation / orchestration |
| **Webhook** | Captures incoming lead data |
| **Groq API (llama-3.3-70b-versatile)** | AI lead qualification + personalized email writing |
| **Gmail** | Sends personalized emails to qualified leads |
| **Telegram Bot API** | Real-time alert for every incoming lead |
| **Google Sheets** | Logs all lead data and outcomes |
| **Hoppscotch** | Used to test the webhook endpoint |

---

## 💼 Business Value

This system replaces a human who would otherwise manually:
- Read each incoming lead
- Decide whether they're worth pursuing
- Write a personalized response email
- Log the lead into a spreadsheet

The automation completes this entire process in under 30 seconds per lead, running 24/7 without any manual intervention.

---

## 📷 Screenshots

![n8n Workflow](workflow-screenshot.png)
*Full n8n workflow canvas showing the branching logic*

![Telegram Alert](output-telegram.png)
*Real-time lead alert sent to Telegram*

![Google Sheet Log](output-googlesheets.png)
*All leads logged with qualification status*

![Gmail Output](output-gmail.png)
*Personalized email sent to a qualified lead*

---

## 🎯 What I Learned

- Building complex, multi-branch workflows with conditional routing
- Using AI for business decision-making (qualification scoring)
- Parsing structured JSON responses from an AI model
- Professional, automated email generation and delivery
- Multi-step error handling across a longer pipeline

---

## 👤 Author

Built by Abdullah as part of a self-directed AI Automation learning program.
