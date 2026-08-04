### Hi, I'm Naveen

I build small, complete AI systems rather than large half-finished ones. Everything
below is tested against real engines — real filesystem events, real audio round
trips, real Docker containers — not mocked out for a demo.

#### 🗣️ [jarvis-cli](https://github.com/naveen578-hub/jarvis-cli)
A local AI agent built in four scoped steps, each one working before the next started:
- **Tool-calling agent** on Anthropic's Messages API, with local RAG (no API key
  needed to index — embeddings run on-device via `sentence-transformers`)
- **Real-time indexing** — a `watchdog`-based file watcher keeps the RAG index in
  sync as files change, no manual rebuilds
- **Voice interface** — a WebSocket server with fully local speech-to-text
  (`faster-whisper`) and text-to-speech (`pyttsx3`), no extra API keys
- **Sandboxed code execution** — the agent can run code inside a disposable Docker
  container with no network access, no host filesystem access, and a read-only
  root filesystem, verified by real integration tests, not just configured

#### 💬 [CODING-CHAT-INTERFACE](https://github.com/naveen578-hub/CODING-CHAT-INTERFACE)
A full-stack AI chat app — React/Vite frontend, Express backend streaming real
responses from Claude over Server-Sent Events. The API key never reaches the
browser.

---

I'd rather ship something small that's actually correct than something large that
only looks correct. If you look at the commit history on either repo, that's the
throughline.
