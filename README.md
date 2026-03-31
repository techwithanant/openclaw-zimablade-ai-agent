# openclaw-zimablade-ai-agent

This project shows how to build a personal AI agent using OpenClaw running on a ZimaBlade ($60 setup).

Instead of just chatting with AI, this setup allows you to:
- connect to apps
- automate workflows
- generate content
- take real actions

---

## Video Walkthrough
Watch the full setup and demo here:
https://youtu.be/36jt0fz45go

---

## What This Setup Does
- Telegram-based AI assistant
- Fetch Gmail / data / analytics
- Update Google Sheets
- Generate content
- Post to LinkedIn / X
- Create avatar videos (ElevenLabs + ComfyUI)

---

## Hardware Used
ZimaBlade (Intel x86 SBC)
https://shop.zimaspace.com/

---

## OS Installation (Ubuntu)
Install Ubuntu Server or Desktop:
https://ubuntu.com/download/server

SSH into device:
ssh username@your-zimablade-ip

---

## OpenClaw Installation
curl -fsSL https://openclaw.ai/install.sh | bash

---

## Setup Flow
- Manual Setup
- LLM → OpenAI
- Auth → OAuth or API key
- Model → GPT-5.3 Codex
- Channel → Telegram

---

## Telegram Bot Setup
- Search @BotFather
- Run /newbot
- Name + username (_bot)
- Copy API token
- Paste in setup

---

## ClawHub
https://clawhub.openclaw.ai

---

## Folder Structure

.openclaw/
│
├── workspace/
├──── skills/
├── logs/
├── config/
└── hooks/

---

## 🧩 Skills
Skills can be:
- markdown files
- or markdown + Python

---

## 🛠 Custom Skills
Create under .openclaw/workspace/skills/

Example:
avatar_skill/
├── skills.md
├── main.py
