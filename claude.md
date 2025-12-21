# Vibey Development Notes

## Testing in Browser

Always test using the local web server at http://localhost:8888/index.html (not the file:// URL).

To start the server, run: `python3 -m http.server 8888`

To authenticate, use the "Sign in with OpenRouter" button. The API key is stored in localStorage so it persists across page refreshes.
