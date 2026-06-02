# Automated_Lead-Verification-Smart-CRM-System
It ensures that only **valid and high-quality leads** are processed and stored, improving efficiency for sales and marketing teams.

📌 Overview
This project is an automated workflow built using n8n that captures leads from a website, verifies their authenticity, and notifies the relevant team in real-time.

It ensures that only valid and high-quality leads are processed and stored, improving efficiency for sales and marketing teams.

⚙️ Features
📥 Lead Capture via Webhook

Receives user data (name, email, phone) from a website form
🗂️ Google Sheets Integration

Stores incoming leads instantly
Maintains a backup of all submissions
🔔 Slack Notifications

Sends instant alerts for new leads
Notifies team when a verified lead is found
📧 Automated Email Response

Sends confirmation email to users
Sends final report to admin
🔍 Email Verification

Checks if the email is valid or fake
Filters out spam or low-quality leads
🧠 Conditional Logic (IF Node)

Processes only verified leads
Prevents junk data from entering final database

🛠️ Technologies Used
n8n (Workflow Automation)
Google Sheets API
Slack API
Gmail API
Abstract Email Verification API
🔐 Security Note
All sensitive information such as:

API keys
OAuth credentials
Personal data
have been removed or replaced with placeholders before publishing this repository.

⚠️ Setup Instructions
Before running this workflow:

Add your own credentials:

Google Sheets
Slack
Gmail
🎯 Use Cases
Lead generation systems
CRM automation
Marketing pipelines
Startup customer intake systems
👨‍💻 Author
Developed by Annum Nisar


