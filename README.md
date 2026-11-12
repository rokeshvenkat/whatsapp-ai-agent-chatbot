# WhatsApp AI Agent Chatbot Using n8n & Google Gemini

## Project Overview

This project is an AI-powered WhatsApp chatbot built using n8n, Google Gemini, and Google Sheets.

The chatbot receives messages from users through WhatsApp, processes them using an AI Agent powered by Google Gemini, and sends intelligent responses back to the user. It also maintains conversational context using Simple Memory and stores conversation records in Google Sheets.

The main goal of this project is to automate WhatsApp conversations and provide quick, AI-powered responses with minimal manual intervention.

## Workflow Architecture

Workflow:

WhatsApp Trigger → AI Agent → Send WhatsApp Message → Google Sheets

The AI Agent is connected to:
- Google Gemini Chat Model – Generates AI responses.
- Simple Memory – Maintains conversational context.

## Technologies Used

- n8n: Workflow automation and integration.
- WhatsApp: Incoming and outgoing messaging.
- Google Gemini: AI-powered response generation.
- AI Agent: Processes user queries and generates responses.
- Simple Memory: Maintains conversation context.
- Google Sheets: Stores conversation records.

## Key Features

1. WhatsApp Integration: Automatically receives incoming messages through the WhatsApp Trigger node.
2. AI-Powered Responses: Uses Google Gemini to understand user queries and generate relevant responses.
3. Conversational Memory: Uses Simple Memory to maintain context across conversations.
4. Automated Messaging: Sends AI-generated responses directly to users through WhatsApp.
5. Conversation Logging: Stores conversation details in Google Sheets for record keeping and future analysis.
6. Workflow Automation: Connects multiple services into a single automated workflow.

## Workflow Explanation

### 1. WhatsApp Trigger
The workflow starts whenever a user sends a message to the connected WhatsApp account.

### 2. AI Agent
The incoming message is passed to the AI Agent, which processes the query and generates a response.

### 3. Google Gemini Chat Model
Google Gemini acts as the language model connected to the AI Agent. It understands the user's message and generates a suitable response.

### 4. Simple Memory
The Simple Memory node helps the AI Agent retain previous conversation context and provide more relevant responses during an ongoing conversation.

### 5. Send WhatsApp Message
The generated AI response is sent back to the user automatically through WhatsApp.

### 6. Google Sheets Integration
The conversation information is appended to a Google Sheet for tracking and record keeping.

## Tools & Integrations

| Tool | Purpose |
|---|---|
| n8n | Workflow automation |
| WhatsApp | User communication |
| Google Gemini | AI response generation |
| AI Agent | Query processing |
| Simple Memory | Conversation context |
| Google Sheets | Data storage |


## Author
ROKESH RV
AI & ML Engineer | Generative AI | LLMs | AI Automation

[LinkedIn](https://www.linkedin.com/in/rokeshvenkat/)

[GitHub](https://github.com/rokeshvenkat)
