# AI ChatAssistant

> 🎓 **School assignment project** — a Chrome extension built as part of a class assignment to explore on-device AI, voice control, and accessibility in the browser.

A voice-controlled Chrome side-panel assistant that can search, navigate, take screenshots, and describe or analyze web pages using Chrome's built-in **Gemini Nano** model.

![Chrome Extension](https://img.shields.io/badge/Chrome-Extension-4285F4?logo=googlechrome&logoColor=white)
![Manifest V3](https://img.shields.io/badge/Manifest-V3-34A853)
![Gemini Nano](https://img.shields.io/badge/AI-Gemini%20Nano-8E75B2)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## ✨ Features

- 🎙️ **Voice control** — search, open websites, and trigger actions hands-free
- 📸 **Screenshots + AI descriptions** — regular and full-page scrolling captures
- 🧠 **Page analysis** — on-device content analysis with Gemini Nano
- 💬 **Follow-up chat** — ask the AI more questions about what it just saw
- 🔁 **Repeat response** — have the last answer read out again

## 🚀 Installation

1. Clone this repository
2. Open `chrome://extensions` in Chrome Dev/Canary
3. Enable **Developer mode**
4. Click **Load unpacked** and select the `AI ChatAssistant` folder
5. Allow microphone access when prompted

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Alt + Shift + Q` | Open the assistant side panel |
| `Alt + Shift + 1` | Toggle voice control |
| `Alt + Shift + 2` | Chat with the AI after a screenshot / analysis |
| `Alt + Shift + 3` | Repeat the AI's last response |

## 🗣️ Voice Commands

| Command | Example | What it does |
|---------|---------|--------------|
| `Search [query]` | "Search the weather today" | Opens a Google search |
| `Go to [website]` | "Go to google.com" | Opens the site *(.com only for now)* |
| `Take a screenshot` | — | Captures the view and describes it |
| `Take a scrolling screenshot` | — | Captures the full page and describes it |
| `Analyze content` | — | Analyzes the current page with Gemini Nano |

## 🗂️ Project Structure

```
AI ChatAssistant/
├── manifest.json     # Extension config (Manifest V3)
├── background.js     # Service worker: shortcuts & commands
├── sidepanel.html    # Side panel UI
├── sidepanel.js      # Chat, voice & AI logic
├── components/       # UI components
├── lib/              # Libraries
└── icons/            # Extension icons
```

## ⚠️ Current Limitations

| Limitation | Description |
|------------|-------------|
| Language support | English only |
| Chrome version | Requires Dev/Canary channel (built-in AI) |
| Hardware | Gemini Nano needs significant storage space |

## 📚 About

This project was made for a school assignment. It's a learning project, not a production tool — feedback and suggestions are welcome!

## 📄 License

Licensed under the MIT License. See [LICENSE](LICENSE) for details.
