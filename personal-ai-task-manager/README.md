Personal AI Task & Productivity Agent 

A lightweight, fully automated Personal AI Assistant built with n8n, integrated with Telegram and Google Sheets to streamline daily task management, automated reminders, and real-time activity tracking.

# How It Works

3:00 PM Daily Reminder: Automatically pings you via Telegram with today's customized task plan and priorities.

12:00 AM Midnight Check-in: Connects with you at midnight to review progress, log task completions, and plan upcoming tasks.

Real-time Google Sheets Sync: Direct updates to Google Sheets with accurate local timestamps (YYYY-MM-DD).

# Tech Stack

Automation Engine: n8n

User Interface: Telegram Bot API

Database & Storage: Google Sheets, Google Drive (Knowledge Base)

Timezone Config: Asia/Dhaka

# Workflow Architecture

[ Telegram / Schedule Trigger ]
               │
               ▼
       [ n8n AI Agent ] ◄──► [ Google Drive (Knowledge Base) ]
               │
               ▼
     [ Google Sheets Tool ] (Real-time Task Logging)


# Setup & Installation

Clone Repository:

git clone https://github.com/your-username/personal-ai-agent.git


Import Workflow: Load the provided .json workflow into your n8n workspace.

Connect Credentials:

Telegram Bot Token

Google Sheets OAuth2 / Service Account

Google Drive OAuth2

Set Schedule Triggers:

Trigger 1: 15:00 (3:00 PM) for daily task dispatch.

Trigger 2: 00:00 (12:00 AM) for midnight progress check-in.

Activate Workflow: Toggle to Active.

📝 License

MIT License. Free to use and modify.
