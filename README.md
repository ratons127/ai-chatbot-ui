# Betopia AI

**Betopia AI** is the intelligent AI chat platform by [Betopia Group](https://www.betopiagroup.com), available at [demo.betopia.ai](https://demo.betopia.ai).

## About

Betopia AI is a self-hosted, feature-rich AI platform supporting multiple LLM backends including Ollama and OpenAI-compatible APIs. It includes built-in RAG, document chat, voice, and more.

**Company:** Betopia Group  
**Website:** [betopiagroup.com](https://www.betopiagroup.com)  
**Demo:** [demo.betopia.ai](https://demo.betopia.ai)

## Running with Docker

```bash
docker compose up -d --build
```

Access the app at **http://localhost:3000**

## Environment Variables

Copy `.env.example` to `.env` and configure:

```bash
cp .env.example .env
```

Key variables:
- `OLLAMA_BASE_URL` — Ollama server URL
- `OPENAI_API_KEY` — OpenAI API key (optional)
- `WEBUI_SECRET_KEY` — Secret key for session security
- `WEBUI_NAME` — App name shown in UI (default: `Betopia AI`)

## Production

The production instance runs at **https://demo.betopia.ai** on Ubuntu 24.04 with Nginx + Let's Encrypt SSL.

---

© Betopia Group. Built on open-source technology.
