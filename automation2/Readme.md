# 🤖 AI Weather Agent Automation

An AI-powered weather assistant built with **n8n**, **Google Gemini**, external APIs, memory, and Gmail.

This workflow goes beyond traditional automation by using an **AI Agent** that can understand user requests, use external tools, maintain conversation context, and generate relevant responses.

## 🚀 Overview

The workflow allows users to interact with an AI weather assistant through chat.

The agent can understand a user's request, retrieve weather information using an API, maintain conversation context through memory, and send responses through Gmail.

### Workflow

User Message  
↓  
AI Agent  
↓  
Google Gemini  
↓  
Memory + Weather API + Gmail  
↓  
AI Generated Response

## ✨ Features

- AI-powered conversational assistant
- Google Gemini integration
- AI Agent with tool calling
- Real-time weather API integration
- Conversation memory
- Automated Gmail responses
- n8n workflow automation

## 🛠️ Tech Stack

- **n8n** — Workflow automation
- **Google Gemini** — Large Language Model
- **AI Agent** — Decision-making and tool usage
- **Simple Memory** — Conversation context
- **Weather API** — Real-time weather information
- **Gmail** — Automated email responses
- **JavaScript / JSON** — Data processing

## 🔄 How It Works

### 1. User Input

The user sends a message to the AI Agent.

Example:

> What's the weather today?

### 2. AI Agent

The AI Agent uses Google Gemini to understand the user's request and determine what action is required.

### 3. Weather Tool

If weather information is required, the agent calls the connected weather API and retrieves the relevant data.

### 4. Memory

The workflow uses memory to maintain conversation context.

Example:

> User: What's the weather today?  
> Agent: It's 34°C.  
> User: What about tomorrow?  
> Agent: Tomorrow is expected to be...

### 5. Gmail

The generated response can be sent automatically through Gmail.

## 📸 Workflow Preview

Add your workflow screenshot:

![AI Weather Agent Workflow](screenshots/ai-agent-workflow.png)

## ⚙️ Setup

### 1. Import the Workflow

Import the workflow JSON into your n8n instance.

n8n → Workflows → Import from File

### 2. Configure Gemini

Add your Google Gemini API credentials to the Gemini Chat Model node.

### 3. Configure Weather API

Add your weather API credentials and configuration to the weather tool.

### 4. Configure Gmail

Connect your Gmail account to the Gmail node.

### 5. Run the Workflow

Start the chat interface and test queries such as:

- What's the weather today?
- Will I need an umbrella today?
- How hot will it be today?
- What about tomorrow?

## 🔐 Security

Never commit API keys, OAuth tokens, or private credentials to GitHub.

Use n8n's credential management or environment variables to securely store sensitive information.

## 🧠 What I Learned

Building this workflow helped me understand:

- AI Agents
- LLM integration
- Tool calling
- Conversation memory
- API integration
- AI-powered automation
- Connecting AI models with external services
- Designing multi-step workflows

The main takeaway was understanding how an AI Agent can act as a layer between the user and external tools, rather than simply generating text.

## 🔮 Future Improvements

- Support multiple locations
- Add automatic location detection
- Add weather alerts
- Add WhatsApp or Telegram integration
- Improve long-term memory
- Add additional tools
- Add calendar integration
- Explore multi-agent workflows

## 📁 Project Structure

ai-weather-agent/
├── workflow/
│   └── ai-weather-agent.json
├── screenshots/
│   └── ai-agent-workflow.png
└── README.md

## 🎯 Goal

This project is part of my journey of exploring:

**Automation → AI Workflows → AI Agents → Autonomous Systems**

The goal is to learn by building practical AI-powered automation workflows and understand how AI models can interact with real-world tools and services.

## 👩‍💻 Author

**Pranavi Jain**

Computer Science Engineer · Software Developer · GenAI & Automation Enthusiast

Exploring **Generative AI, AI Agents, Backend Engineering, and Workflow Automation**.

---

⭐ More automation experiments coming soon.
