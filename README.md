# Local AI Email Auto-Responder

This project is a fully local AI-powered email auto-responder built using:

- n8n
- Ollama
- Docker
- SMTP/IMAP

## Features

- Reads incoming emails
- Uses local AI model for generating replies
- Sends automated responses
- Fully local and privacy-focused

## Tech Stack

- n8n
- Ollama
- Docker Compose
- TinyLlama Model

## Files

- docker-compose.yml
- workflow.json

## Run Project

```bash
docker compose up -d

Pull Model
docker exec -it ollama_responder ollama pull tinyllama

Save it.
```

---

# 2️⃣ submission.json

Open `submission.json`

Paste:

```json
 id="q3n7xp"
{
  "project": "Local AI Email Auto-Responder",
  "status": "completed",
  "tools": [
    "n8n",
    "Ollama",
    "Docker"
  ],
  "model": "tinyllama"
}

```
Save it.

3️⃣ .env.example

Open .env.example

Paste:
EMAIL_USER=your_email@gmail.com
EMAIL_APP_PASSWORD=your_app_password
SMTP_HOST=smtp.gmail.com
IMAP_HOST=imap.gmail.com
OLLAMA_MODEL=tinyllama