# Vibey

Vibe code in your browser.

**[Try it live →](https://martinpllu.github.io/vibey)** (requires an [OpenRouter](https://openrouter.ai) account)

Describe what you want, and iterate on your app in real-time. The generated code renders in an iframe while you chat.

**Features:**
- Multiple AI models via OpenRouter (Gemini 3 Flash, Claude Opus 4.5, etc)
- Gemini 3 Flash recommended for speed and cost
- Multiple apps with separate chat histories
- Token usage and cost tracking
- Auto-attach browser errors for easy debugging
- Attach console logs and screenshots to messages
- Community gallery to share and discover apps
- All data stored locally in your browser - nothing sent to any server except OpenRouter

## Running Locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Usage

1. Click "Sign in with OpenRouter"
2. Describe what you want to build
3. Press `Escape` to toggle the panel
