# Jarvis AI – Personal Text Assistant

A clean, minimal, single-file **AI chat interface** powered by **DeepSeek-R1** (via OpenRouter).

Features:
- Real-time text conversation with DeepSeek-R1
- Voice dictation / speech-to-text input (browser SpeechRecognition – best in Chrome/Edge)
- Clear conversation button
- Mobile responsive design
- Simple, ChatGPT-like light theme
- No build tools – just open `index.html` in browser

Made with ❤️ by **Atharva Phadnis**

## Demo

(i have another ai assistant just go here - https://atharvaassistant.netlify.app/)

https://yourusername.github.io/jarvis-ai/

## Features

- Pure HTML + CSS + JavaScript (no frameworks)
- Uses **DeepSeek-R1** model through OpenRouter API
- Voice input button (🎤)
- Enter to send, Shift+Enter for new line
- Auto-growing input textarea
- Syntax highlighting for code blocks
- Error handling & loading states
- Local conversation persistence not included (refresh clears chat)


```js
const OPENROUTER_API_KEY = "paste-your-openrouter-api-key-here";
