# WhatsApp AI Agent

A WhatsApp AI chatbot powered by Google Gemini 2.0 Flash that acts as a personal AI assistant over WhatsApp DMs.

## Features

- QR-code WhatsApp Web authentication with persistent session storage
- Whitelist-based contact filtering (only responds to approved numbers)
- Custom Hinglish AI persona via Gemini system prompt
- Real-time message processing and AI response generation
- Automatic session recovery across Node.js restarts

## Tech Stack

- Node.js
- whatsapp-web.js (Puppeteer-based)
- Google Gemini 2.0 Flash API
- dotenv
- LocalAuth

## Setup

1. Clone the repo
2. Run `npm install`
3. Create a `.env` file with your Gemini API key and whitelisted numbers
4. Run `node index.js`
5. Scan the QR code with WhatsApp

## Author

**Prasad Rawas** - [GitHub](https://github.com/prasadrawas)

