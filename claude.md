# Vibey Development Notes

## Testing in Browser

Always test using the local web server at http://localhost:8888/index.html (not the file:// URL).

To start the server, run: `python3 -m http.server 8888`

To authenticate, use the "Sign in with OpenRouter" button. The API key is stored in localStorage so it persists across page refreshes.

## Adding Example Apps

To add a new example to the Community gallery:

1. Add the HTML file to `examples/`
2. Add an entry to `examples/index.html` with name, author, and description
3. Commit, push, and deploy to GitHub Pages
