# c2-telegram-ai-powered-bot-latest

[![Language: Python](https://img.shields.io/badge/language-Python-blue.svg)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![CI Pipeline](https://github.com/krsna016/c2-telegram-ai-powered-bot-latest/actions/workflows/ci.yml/badge.svg)](https://github.com/krsna016/c2-telegram-ai-powered-bot-latest/actions/workflows/ci.yml)
[![Security: CodeQL](https://github.com/krsna016/c2-telegram-ai-powered-bot-latest/actions/workflows/codeql.yml/badge.svg)](https://github.com/krsna016/c2-telegram-ai-powered-bot-latest/actions/workflows/codeql.yml)

Professional engineering repository configurations deployed inside your GitHub profile.

---

## Overview & Core Description

An intelligent, memory-aware AI chatbot for Telegram — powered by Google Gemini AI.  
It serves as your 24/7 business assistant, handling both company-specific queries and open-domain conversations. 

---

## Features

- Gemini-powered AI for natural, helpful conversations  
- Chat memory for personalized user sessions  
- Loads your business profile from `company_profile.txt`  
- ️ Clean architecture (handlers, services, DB, utils)  
- Handles both business-specific and general questions  
- ️ SQLite DB to log user queries and responses  
- ️ Easily customizable context and behavior

---

## Setup Guide

1. **Install dependencies**
   ```bash
   pip install -r requirements.txt

## Create a .env file in the root directory:
- GEMINI_API_KEY=your_google_gemini_api_key
- BOT_TOKEN=your_telegram_bot_token

## Add your company context:
- add content to: app/assets/company_profile.txt

## Initialize the database:
- python db_init.py

## Run the bot:
- python main.py

---

## System Design & Folder Structure
```text
.github/                  # CI/CD pipelines, Dependabot, and Issue/PR schemas
.editorconfig             # Unified file formatting configuration
.gitattributes            # Normalization variables for LF line endings
.gitignore                # Local environment overrides and cache limits
.pre-commit-config.yaml   # Quality check execution triggers
LICENSE                   # Permissive open-source MIT License
Makefile                  # Development workspace orchestrator
CHANGELOG.md              # Historical version tracking
CONTRIBUTING.md           # Developer onboarding guidelines
CODE_OF_CONDUCT.md        # Communication guidelines
SECURITY.md               # Responsible vulnerability disclosures
```

---

## Tooling & Tech Stack
- **Primary Environment:** Python runtime.
- **Workflow Automation:** GitHub Actions CI, Dependabot, and CodeQL.
- **Standards Checkers:** Git `pre-commit` hook validations.

---

## Quickstart & Local Setup
1. Clone this repository locally:
   ```bash
   git clone https://github.com/krsna016/c2-telegram-ai-powered-bot-latest.git
   cd c2-telegram-ai-powered-bot-latest
   ```
2. Trigger the local setup runner:
   ```bash
   make help
   ```

---

## Security & Responsible Disclosure
For details on disclosing vulnerabilities or hardcoded secrets, refer directly to our [SECURITY.md](SECURITY.md) guidelines.

---

## License
This repository is licensed under the permissive **MIT License**. For details, see the [LICENSE](LICENSE) file.
