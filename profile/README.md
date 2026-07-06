# Router One

**A unified LLM API gateway.** One OpenAI-compatible endpoint, one key, 40+ supported models — GPT, Claude, Gemini, DeepSeek, Mistral, Llama and more — at up to 90% off official prices, with smart routing, automatic provider fallback, and a cost trace for every request.

> Calling an LLM directly is a black box. Through a gateway, every call has a **ledger** (what it cost), a **trace** (which model and route served it), and **control** (per-key budgets and rate limits).

## Endpoints

| Protocol | Base URL | Use with |
| --- | --- | --- |
| OpenAI-compatible | `https://api.router.one/v1` | OpenAI SDKs, LangChain, Vercel AI SDK, Codex CLI |
| Anthropic-compatible | `https://api.router.one` | Claude Code, Anthropic SDKs |

Native Claude Code and Codex CLI support — no wrapper, no proxy, two environment variables. Reachable worldwide, including mainland China. No prompt or completion storage: the gateway logs metadata only.

## Repositories

- [**claude-code-codex-setup**](https://github.com/Router-One/claude-code-codex-setup) — Point Claude Code & Codex CLI at the gateway in 2 minutes, with config templates and troubleshooting
- [**router-one-examples**](https://github.com/Router-One/router-one-examples) — Runnable examples: curl, Python, Node, LangChain, Vercel AI SDK, Anthropic SDK
- [**awesome-llm-gateway**](https://github.com/Router-One/awesome-llm-gateway) — A curated list of LLM gateways, proxies, routers, and observability tooling

## Links

🌐 [router.one](https://router.one) · 📖 [API docs](https://router.one/docs) · 🗂 [Model catalog & rates](https://router.one/models) · 🧭 [Error codes reference](https://router.one/llm-api-error-codes) · 🐦 [@router_one](https://x.com/router_one)
