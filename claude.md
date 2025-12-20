# Vibey Development Notes

## Testing in Browser

Always test using the local web server at http://localhost:8888/index.html (not the file:// URL).

To start the server, run: `python3 -m http.server 8888`

When testing the app in a browser via DevTools and you need to authenticate with OpenRouter:
- Read the API key from `.secrets` file (gitignored)
- Inject it into localStorage using: `localStorage.setItem('vibey_openrouter_api_key', 'YOUR_KEY')`
- Reload the page to apply the key
