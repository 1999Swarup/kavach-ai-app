# Kavach App — BYOM AI Red-Team (product site)

Public product page for **Kavach App**: a "bring your own model" (BYOM) AI red-team.

- Single-file static site (`index.html`) — a **Connect your model** wizard + a live
  **AI Risk Snapshot** view rendering a real recorded scan.
- The real scanning engine lives in the private repo (`kavach_scanner`) and runs behind a
  backend API; this page is the public demo/marketing surface.
- Hosted on GitHub Pages.

Providers supported by the engine: OpenAI · Azure OpenAI / AI Foundry · Anthropic ·
Google Vertex AI · Local (Ollama) · GitHub Models (GHCP) · Generic HTTP · Foundry Prompt Agent.
