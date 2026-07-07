# 🤖 FreelanceOS AI CRM v2

> **An AI-powered CRM automation platform built with n8n, Gemini AI, Gmail, Google Sheets, and Telegram to automate lead management, follow-ups, business insights, and AI-powered CRM assistance.**

![License](https://img.shields.io/badge/License-MIT-green)
![n8n](https://img.shields.io/badge/Built%20With-n8n-orange)
![Gemini](https://img.shields.io/badge/AI-Gemini%202.0%20Flash-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📖 Overview

FreelanceOS AI CRM v2 is a complete AI-powered Customer Relationship Management (CRM) automation system designed for freelancers and small businesses.

Instead of manually managing client emails, follow-ups, CRM entries, and business reports, this project automates the entire workflow using AI.

The platform consists of **four integrated workflows**:

- 📥 AI Lead Processing Pipeline
- 📅 AI Follow-up Automation
- 📊 AI Dashboard & Business Insights
- 🤖 AI CRM Copilot (RAG)

Together, these workflows help businesses save time, organize leads, improve client communication, and gain actionable business insights.

---

# ✨ Features

## 📥 AI Lead Processing Pipeline

- Reads incoming Gmail inquiries
- Detects duplicate CRM entries
- Uses Gemini AI to analyze lead quality
- Calculates:
  - Priority
  - Lead Temperature
  - Opportunity Score
  - Sentiment
  - Project Category
- Stores leads in Google Sheets
- Automatically schedules follow-ups
- Generates Gmail reply drafts
- Sends Telegram notifications

---

## 📅 AI Follow-up Automation

Runs automatically every day.

Features:

- Checks pending follow-ups
- Verifies due dates
- Generates Gmail reply drafts
- Updates follow-up status
- Prevents missed client communications

---

## 📊 AI Dashboard & Business Insights

Automatically analyzes CRM data and generates:

- Executive Summary
- Business Risks
- AI Recommendations
- Lead Distribution
- Conversion Metrics
- Follow-up Analytics

Results are stored in Google Sheets for reporting.

---

## 🤖 AI CRM Copilot (RAG)

Natural language CRM assistant capable of answering questions like:

- Who has the highest opportunity score?
- Which clients requested meetings?
- Give today's CRM summary.
- What recommendations improve sales?
- Who needs follow-up tomorrow?

The chatbot retrieves CRM records and AI Insights before generating intelligent responses.

---

# 🏗️ System Architecture

```
                Gmail
                  │
                  ▼
        AI Lead Processing
                  │
      ┌───────────┴────────────┐
      ▼                        ▼
Duplicate Lead          New Lead
      │                        │
Update Record         Create CRM Entry
                               │
                               ▼
                     Schedule Follow-up
                               │
                               ▼
                     Generate Gmail Draft
                               │
                               ▼
                    Telegram Notification
                               │
                               ▼
                     CRM Dashboard
                               │
                               ▼
                    AI Business Insights
                               │
                               ▼
                     AI CRM Copilot
```

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Gemini 2.0 Flash | AI Lead Analysis & Insights |
| Gmail API | Email Automation |
| Google Sheets | CRM Database |
| Telegram Bot API | Notifications |
| JSON | Workflow Export |
| Google Workspace | Dashboard & Reporting |

---

# 📂 Repository Structure

```
FreelanceOS-AI-CRM-v2
│
├── assets/
│
├── workflows/
│   ├── ai-lead-processing-pipeline-v2.json
│   ├── ai-follow-up-automation.json
│   ├── ai-dashboard-business-insights-v2.json
│   └── freelanceos-ai-copilot-rag.json
│
├── LICENSE
└── README.md
```

---

# 📸 Screenshots

## AI Lead Processing Pipeline

New Lead Processing

![Lead Pipeline](assets/AI%20Lead%20Processing%20Pipeline%20v2.png)

Existing Lead Detection

![Duplicate Pipeline](assets/AI%20Lead%20Processing%20Pipeline%20v2.2.png)

---

## AI Follow-up Automation

![Follow-up](assets/AI%20Follow-up%20Automation.png)

---

## Gmail Draft Generation

![Draft](assets/GMAIL%20DRAFT.png)

---

## Telegram Alerts

![Telegram](assets/Telegram%20Alerts.png)

---

## AI Dashboard

![Dashboard](assets/📊AI%20Dashboard%20%26%20Business%20Insights%20v2.png)

---

## Dashboard Sheet

![Dashboard Sheet](assets/Dashboard%20sheet.png)

---

## AI Insights Sheet

![Insights](assets/AI%20Insights%20sheet.png)

---

## AI CRM Copilot

Workflow

![Copilot](assets/🤖FreelanceOS%20AI%20Copilot%20(RAG).png)

---

Chat Examples

![Chat1](assets/CRM%20AI%20CHAT1.png)

![Chat2](assets/CRM%20AI%20CHAT2.png)

![Chat3](assets/CRM%20AI%20CHAT3.png)

---

# 🚀 Workflow Summary

### AI Lead Processing

Incoming Email

↓

AI Analysis

↓

Duplicate Detection

↓

CRM Update / New Entry

↓

Schedule Follow-up

↓

Generate Draft

↓

Telegram Notification

---

### AI Follow-up

Daily Scheduler

↓

Check Due Date

↓

Generate Gmail Draft

↓

Update Follow-up Status

---

### AI Dashboard

Read CRM

↓

Generate Business Metrics

↓

AI Executive Summary

↓

Store Insights

---

### AI Copilot

User Question

↓

Retrieve CRM Context

↓

Retrieve AI Insights

↓

Gemini AI

↓

Natural Language Response

---

# 💡 Future Improvements

- CRM Web Application
- Voice-enabled AI Assistant
- WhatsApp Integration
- Calendar Integration
- Client Portal
- Multi-user Authentication
- PostgreSQL Support
- Vector Database for Advanced RAG
- Docker Deployment

---

# 📄 License

This project is licensed under the MIT License.

---

# 👩‍💻 Author

**Akshaya V**

Computer Science Undergraduate

Passionate about AI, Automation, Full Stack Development, and Workflow Engineering.

GitHub: https://github.com/akshayav316

LinkedIn: https://www.linkedin.com/in/akshaya-v-0199233ab/

---

⭐ If you found this project useful, consider giving it a star!
