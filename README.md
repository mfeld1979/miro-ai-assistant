# Miro AI Assistant Test

A simple prototype for embedding an AI assistant inside a Miro board.

This project uses:
- A minimal **HTML + JavaScript** frontend
- A **Make.com webhook** backend connected to an LLM (e.g. OpenAI)
- **GitHub Pages** for free hosting

## 🚀 How it works
1. The user enters a question in the web interface.
2. The question is sent to a Make webhook.
3. Make processes the request and returns an AI-generated response.
4. The answer is displayed directly in the embedded Miro frame.

## 🧩 Setup
1. Copy this repository.
2. Replace `DEINE_MAKE_WEBHOOK_URL` in `index.html` with your own Make webhook URL.
3. Enable **GitHub Pages** (Settings → Pages → Deploy from branch → `/root`).
4. Embed the resulting page in Miro via **Insert → Embed → Website**.

## 📄 License
Released under the [MIT License](./LICENSE).

