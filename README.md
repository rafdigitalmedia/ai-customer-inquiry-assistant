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

📸 Screenshots
Full Workflow
Gmail Trigger Configuration
AI Intent Classification
Smart Routing Logic
AI Response Generation
Auto-Reply Configuration
Human Alert Setup
Auto-Reply Received in Inbox
Execution Success
📦 Installation
Import ai-customer-inquiry-assistant.json to your n8n instance.
Configure Gmail credentials (for both the trigger and sending nodes).
Set up your OpenAI API key in the n8n credentials.
Customize the classification prompt in the "AI - Classify Intent" node based on your specific business categories.
Update the "To" email address in the "Email - Human Alert" node to your actual support team's email.
Activate the workflow and test by sending a sample email to the monitored Gmail account!
💼 Use Cases
🎫 Customer Support — Auto-respond to common FAQs and general inquiries.
💼 Sales Teams — Automatically route pricing and upgrade questions to sales.
🔧 Technical Support — Instantly escalate complex login or bug issues to human agents.
📞 Contact Requests — Forward partnership or collaboration emails to the right department.
🌐 Agencies & Freelancers — Maintain a professional, 24/7 responsive image for clients.
📝 License
MIT License — free to use and modify for personal or commercial projects.
Built with ❤️ using n8n and OpenAI
For inquiries or custom automation projects, feel free to reach out!
