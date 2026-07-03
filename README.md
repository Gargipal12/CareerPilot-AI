# CareerPilot AI -Intelligent Career Assistant

An AI-powered career assistant built using **n8n**, **Groq LLM**, **Conversation Memory**, and **Google Docs** automation.

## Features

-Generate professional LinkedIn posts
- Review resumes and provide improvement suggestions
- Draft internship and placement emails
- Generate interview questions with answers
- Create personalized learning roadmaps
- Explain technical concepts in a beginner-friendly way
- Maintain conversation context using memory
- Export generated content to Google Docs

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

 ## Workflow

User Prompt
→ AI Agent
→ Groq LLM
→ Conversation Memory
→ Google Docs Export

## Skills Demonstrated

- AI Agent Development
- Workflow Automation
- LLM Integration
- Prompt Engineering
- Conversational Memory
- Google Workspace Integration

## Future Improvements

- WhatsApp Integration
- Gmail Automation
- External API Integration
