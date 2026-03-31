# 💰 AI Finance Tracker

A zero-manual-entry personal finance tracker powered by AI.
Just message your expense naturally on Telegram — the bot automatically
captures, categorizes, and logs it for you using OpenAI.

## 🧠 How It Works
1. You send a message on Telegram — e.g. "spent 200 on lunch"
2. n8n workflow triggers and sends it to OpenAI
3. GPT parses the amount, category, and date
4. Data is logged automatically to Google Sheets

## ✨ Features
- Zero manual data entry — just chat naturally
- Auto-categorization (Food, Travel, Shopping, Bills, etc.)
- Real-time expense logging via Telegram bot
- Google Sheets as a lightweight database
- Fully automated pipeline — no app needed

## 🛠 Tech Stack
- [n8n](https://n8n.io) — workflow automation
- Telegram Bot API — user interface
- OpenAI API (GPT) — natural language parsing
- Google Sheets API — data storage

## 🚀 How to Set Up
1. Clone this repo
2. Import the workflow into your n8n instance
3. Add your API keys:
   - OPENAI_API_KEY
   - Telegram Bot Token
   - Google Sheets credentials
4. Activate the workflow and start chatting!

## 💡 Why I Built This
Tracking expenses is painful — apps are clunky, spreadsheets are manual.
I wanted something that fits into how people already communicate.
This bot makes finance tracking feel like texting a friend.

## 👩‍💻 Author
Rittika Shaw — MCA Student & AI Automation Builder
🔗 linkedin.com/in/rittika-shaw-295a17248
📧 rittikashaw10@gmail.com
