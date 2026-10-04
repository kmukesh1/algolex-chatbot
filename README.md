# ALGOLex Chatbot

Browser chatbot for students. It runs on GitHub Pages. The xAI API key is typed in the page and saved only in that browser (`localStorage`). It is not stored in this repo.

Repo: https://github.com/kmukesh1/algolex-chatbot

## Turn on the live page

1. Open the repo on GitHub.
2. Settings → Pages.
3. Build and deployment: Deploy from a branch.
4. Branch: `main`, folder: `/ (root)`.
5. Save. After 1–2 minutes open:

https://kmukesh1.github.io/algolex-chatbot/

## Use it

1. Open the page.
2. Paste an xAI API key from https://console.x.ai/
3. Pick a model (start with `grok-4-fast`).
4. Chat. Clear chat or forget the key from the top bar.

The bot answers short teaching questions: Python, maths, Quantum AI ideas, resumes, and study plans. It is not a substitute for a teacher or official exam answer key.

## Files

- `index.html` — full chat UI (no build step)
- `.nojekyll` — keeps GitHub Pages from skipping files

## Safety

Do not commit an API key. If a key was pasted into a public chat by mistake, revoke it in the xAI console and create a new one.
