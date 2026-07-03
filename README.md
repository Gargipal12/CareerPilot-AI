# CareerPilot AI

An AI-powered career assistant built using **n8n**, **Groq LLM**, **Conversation Memory**, and **Google Docs** automation.

## Features

- 📄 Resume Review
- 💼 Interview Question Generator
- ✉️ Professional Email Generator
- 📝 LinkedIn Post Generator
- 🗺️ Learning Roadmap Generator
- 🧠 Conversational Memory
- 📂 Google Docs Export

## Architecture

```text
                User Prompt
                     │
                     ▼
              Chat Trigger
                     │
                     ▼
        CareerPilot AI Agent
           ┌─────────┴─────────┐
           │                   │
           ▼                   ▼
      Groq LLM        Conversation Memory
           │
           ▼
   AI Generated Response
           │
           ▼
    Google Docs Export
```

## Tech Stack

- n8n
- Groq (Llama 3.3 70B)
- Google Docs
- AI Agents
- Prompt Engineering

## Future Improvements

- WhatsApp Integration
- Gmail Automation
- External API Integration
