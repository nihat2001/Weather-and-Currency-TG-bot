🤖 **AI-Powered Weather & Currency Telegram Bot**
This repository contains the n8n workflow JSON for a smart Telegram bot that sends automated, AI-personalized daily briefings including weather updates for Baku and current exchange rates.

📋 **Features**
Real-time Data: Fetches weather via Open-Meteo and currency rates via Open-ER-API.

AI-Powered: Uses Groq (Llama 3) to transform raw data into a friendly, motivating message.

Automated: Scheduled to run every morning automatically.

🚀 **How to Install**
Since this repository only contains the workflow logic, follow these steps to get it running:

Download the JSON:

Open the workflow.json file in this repository.

Click the "Raw" button and copy the entire code (or download the file).

Import to n8n:

Open your n8n instance.

Create a new workflow.

Simply Paste (Ctrl+V) the copied JSON code directly into the editor, or go to Workflow Settings > Import from File.

Configure Credentials:

Telegram: Create a bot via @BotFather and add your credentials to the "Telegram" node.

Groq AI: Get your API key from Groq Cloud and add it to the "HTTP Request" node (api.groq.com).

Activate:

Set the "Schedule Trigger" to your preferred time and click Execute Workflow to test.

🛠️ **Tech Stack**
n8n (Automation Engine)

Docker (Self-hosted environment)

Groq AI (Large Language Model)

Telegram Bot API
