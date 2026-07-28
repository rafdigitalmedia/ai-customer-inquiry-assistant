# 🤖 AI Customer Inquiry Assistant

[![n8n](https://img.shields.io/badge/n8n-Automation-FF6D5A?style=flat-square)](https://n8n.io)
[![OpenAI](https://img.shields.io/badge/OpenAI_GPT-4285F4?style=flat-square)](https://openai.com)

> An intelligent email automation that classifies customer inquiries, generates AI responses, and routes complex issues to human agents — reducing response time by 95%.

## 🎬 See It In Action

![Workflow Demo](workflow-complete-demo.gif)

## ✨ Features

- 🤖 **AI-Powered Intent Classification** — Automatically categorizes incoming emails as TECHNICAL, CONTACT, PRICING, or GENERAL.
- 📧 **Smart Auto-Reply** — AI generates contextual, professional, and plain-text responses for general inquiries instantly.
- 🔔 **Human Escalation** — Instant email alerts to the support team for TECHNICAL and CONTACT issues requiring human intervention.
- 🧠 **Intelligent Routing** — Conditional logic (IF Node) seamlessly routes emails to the appropriate handler.
- ⚡ **Real-time Processing** — Under 60 seconds from email receipt to response or alert.
- 📝 **Clean Formatting** — Strict prompt rules ensure no markdown artifacts or placeholders leak into customer emails.

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **n8n** | Workflow automation engine |
| **OpenAI API** | Email intent classification and response generation |
| **Gmail API** | Email trigger monitoring and automated sending |
| **n8n Expressions** | Dynamic data mapping and
