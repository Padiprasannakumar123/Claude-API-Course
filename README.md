# Claude API Course

Hands-on course materials for learning the [Claude API](https://docs.anthropic.com/) using the official Anthropic Python SDK.

## Overview

This repository is organized by course section. Each section lives on its own feature branch and is merged into `master` as it is completed.

## Sections

| Section | Branch | Topics |
| ------- | ------ | ------ |
| 1 | `feat/claude-api-1` | Setup, client, messages, system prompts, temperature, streaming |

## Getting Started

1. **Clone the repo**
   ```bash
   git clone git@github.com:Padiprasannakumar123/Claude-API-Course.git
   cd Claude-API-Course
   ```

2. **Create a virtual environment**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate        # macOS / Linux
   # .venv\Scripts\Activate.ps1     # Windows PowerShell
   ```

3. **Install dependencies**
   ```bash
   pip install anthropic python-dotenv jupyter
   ```

4. **Configure your API key**

   Create a `.env` file in the project root (this file is gitignored and must never be committed):
   ```env
   ANTHROPIC_API_KEY=your-key-here
   ```

## Notes

- Never commit your `.env` file or hardcode API keys in notebooks — clear cell outputs before committing.
- Get an API key from the [Anthropic Console](https://console.anthropic.com/).
