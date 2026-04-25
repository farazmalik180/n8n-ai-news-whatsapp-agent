# n8n AI News WhatsApp Agent

An automated AI workflow built with n8n that fetches AI news from RSS, selects a relevant article, summarizes it using an LLM, formats the summary, and sends it to WhatsApp using Twilio.

## Features

- Scheduled daily automation
- AI news RSS ingestion
- Article filtering and selection
- LLM-powered summarization
- WhatsApp delivery via Twilio
- Modular n8n workflow design

## Tech Stack

- n8n
- Groq / Llama
- Twilio WhatsApp Sandbox
- RSS Feed
- JavaScript Code Node

## Workflow

```text
Schedule Trigger
→ Fetch AI News RSS
→ Filter & Select Best Article
→ Summarize with Llama
→ Format WhatsApp Message
→ Send WhatsApp via Twilio
