# Kii Chat

A personal AI chat interface with a clean Claude-inspired design.

## Features
- 🤖 Multi-model support (Claude, GPT-4, Gemini, Llama, and more via OpenRouter)
- 📁 Multiple file & image upload
- 💾 Code blocks auto-download with model name as filename (`claude-opus-4.6.js`)
- 🛠️ **Make App** — build and preview React apps in real time, one per model
- ↩️ Enter = new line (Ctrl+Enter to send)
- 📱 Mobile-friendly with a dedicated App view

## Deploy to Render (Free)

1. Fork this repo on GitHub
2. Go to [render.com](https://render.com) → New → Web Service
3. Connect your GitHub repo
4. Render will auto-detect `render.yaml` and deploy

## Local Development

```bash
npm install
npm run dev
```

Open http://localhost:3000 and add your [OpenRouter API key](https://openrouter.ai/keys) in Settings.

## Usage

1. Get a free API key at [openrouter.ai/keys](https://openrouter.ai/keys)
2. Click **Settings** → **API** and paste your key
3. Start chatting!

### App Builder
- Enable in **Settings → Make App**
- Ask a model to build a React component
- Click **▶ App** on any code block to preview it
- Use ← → to browse apps from different models
- On mobile, tap the **App** button near the send button

### File Upload
- Click the 📎 button to attach multiple files or images
- Images are sent to vision-capable models automatically

### Code Download
- Every code block shows a **Save** button
- File is named `{model-name}.{extension}` automatically
