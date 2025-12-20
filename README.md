# Vibey

**Vibe code in your browser.**

Try it live: [https://martinpllu.github.io/vibey](https://martinpllu.github.io/vibey)

(Requires an [OpenRouter](https://openrouter.ai) account for model access)

![Vibey screenshot](screenshot.png)

**Features:**
- Use multiple AI models via OpenRouter (Gemini 3 Flash is cheap and works really well)
- All data stored locally in your browser - nothing sent to any server except OpenRouter
- Create multiple apps with separate chats
- Token usage and cost tracking
- Restore previous versions of code
- Attach console logs and screenshots to messages for easy debugging
- Community gallery to share and discover apps

Try it at [https://martinpllu.github.io/vibey](https://martinpllu.github.io/vibey)

## Running Locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Usage

1. Click "Sign in with OpenRouter"
2. Describe what you want to build
3. Press `Escape` to toggle the panel
