# Telegram AI Agent with Google Gemini and n8n

A simple Telegram AI chatbot built with n8n and Google Gemini.

## Features
- Receives Telegram messages.
- Generates AI responses using Google Gemini.
- Sends responses back to the same Telegram chat.
- Supports any languages.
- No PostgreSQL database required.

## Requirements
- n8n
- Telegram Bot Token (make a bot with Bot Father)
- Google Gemini API Key [Google AI Studio](https://aistudio.google.com/apikey?utm_source=chatgpt.com)

## Setup
1. Import the workflow JSON into n8n.
2. Create your Telegram credentials.
3. Create your Google Gemini API credentials.
4. Connect the credentials to the corresponding nodes.
5. Activate the workflow.

## Security
Never publish API keys, bot tokens, passwords, or private credentials.