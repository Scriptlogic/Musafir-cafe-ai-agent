# Musafir Cafe AI Customer Support Agent

## About the Project
Musafir Cafe AI Customer Support Agent is an AI-powered chatbot built using n8n. It helps customers communicate with Musafir Cafe through Telegram and provides automated responses to their queries.

## Features
- Telegram chatbot integration
- AI-powered customer responses using Google Gemini
- Cafe menu information using Google Sheets
- Automated replies to customer messages
- Workflow automation using n8n

## Technologies Used
- n8n
- Telegram Bot API
- Google Gemini API
- Google Sheets

## How It Works
1. The customer sends a message to the Telegram bot.
2. The Telegram Trigger receives the message in n8n.
3. The AI Agent processes the customer's query.
4. Google Sheets provides menu information when configured.
5. The Telegram bot sends a response to the customer.

## Requirements
- An n8n account or local installation
- A Telegram bot created using BotFather
- A Google Gemini API key
- A Google Sheet containing cafe menu information

## Setup Instructions
1. Download or clone this repository.
2. Import the exported workflow JSON file into n8n.
3. Configure your Telegram credentials in n8n.
4. Configure your Google Gemini API credentials.
5. Connect your Google Sheet if required by the workflow.
6. Test the workflow by sending a message to your Telegram bot.
7. Activate the workflow after successful testing.

## Security
- Never upload API keys, Telegram bot tokens, passwords, or private customer information to GitHub.
- Store credentials securely in n8n.
- Use your own credentials when importing the workflow.

## Project Objective
The objective of this project is to automate cafe customer support, provide quick responses, and make menu information easily accessible through a Telegram chatbot.

## Author
Musafir Cafe AI Agent Project
