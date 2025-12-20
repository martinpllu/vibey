# Vibey

A self-contained HTML file for vibe coding single-page apps through chat.

Describe what you want, and iterate on your app in real-time. The generated code renders in an iframe while you chat.

**Features:**
- Sign in with OpenRouter (OAuth)
- Multiple AI models via OpenRouter (Claude, GPT-4, Gemini, etc.)
- Multiple apps with separate chat histories
- Token usage and cost tracking
- Auto-attach browser errors for easy debugging
- Attach console logs and screenshots to messages
- Everything persists in IndexedDB

## Running Locally

Run a local web server:

```bash
cd vibey
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Usage

1. Click "Sign in with OpenRouter"
2. Describe what you want to build in the chat
3. Press `Escape` to toggle the panel
