# AI Agent Telegram Image Generator

An intelligent Telegram bot that enhances user prompts using an AI agent before generating high-quality images. This project demonstrates the use of prompt engineering, AI agents, and workflow automation.
## Features

* AI-powered prompt enhancement
* Context-aware responses using memory
* High-quality image generation
* Automated workflow using n8n
* Real-time interaction via Telegram Bot

#How It Works

1. User sends a prompt in Telegram
2. AI Agent enhances the prompt with detailed context
3. Enhanced prompt is sent to the image generation model
4. Generated image is sent back to the user

Workflow:
User → Telegram Bot → AI Agent → Image Generator → Telegram Response

## Example

Input:
dog

Enhanced Prompt:
A realistic golden retriever sitting in a park during sunset, cinematic lighting, ultra-detailed, 4K

## Tech Stack

* Telegram Bot API
* n8n (Workflow Automation)
* Google Gemini (AI Agent)
* Image Generation API

## Setup Instructions

1. Clone the repository

```bash
git clone https://github.com/JoshmikaAvvaru/AI-agent.git
```

2. Open n8n and import the workflow

3. Add your API keys:

* Telegram Bot Token
* Gemini API Key
* Image Generation API Key

4. Run the workflow

## Future Improvements

* Style selection (anime, realistic, etc.)
* Prompt history tracking
* Image download option
* User credits system
## Contributing

Contributions are welcome. Feel free to fork and improve the project.
## Support

If you find this project useful, consider giving it a star on GitHub.

