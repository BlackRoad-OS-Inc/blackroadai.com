# blackroadai.com

> Lucidia — an AI companion that actually remembers you.

**Live at [https://blackroadai.com](https://blackroadai.com)**

## What Lucidia Is

Lucidia is an AI companion with persistent cross-session memory. Every conversation builds on the last. Your context lives in SQLite on your device — not on someone else's server.

## How It Works

- **Persistent memory** — SQLite-backed memory that survives across sessions, devices, and models
- **Multi-model orchestration** — routes prompts to the right model (Ollama local fleet, 16 models across 4 nodes)
- **Local inference** — AI runs on your hardware, not in the cloud
- **Ghost Mode** — full session with zero logging, zero storage, zero trace
- **Cross-session context** — Lucidia knows what you worked on yesterday, last week, last month

## Architecture

- Frontend served from Gematria (Caddy TLS)
- Inference handled by Ollama on Pi fleet (52 TOPS across 2x Hailo-8 accelerators)
- Memory stored in SQLite — portable, inspectable, yours
- No external AI APIs. Every token generated on hardware we own.

## Pricing

| Plan | Price | What You Get |
|------|-------|-------------|
| Starter | $29/mo | Lucidia core, 1 device, local memory |
| Pro | $99/mo | Multi-device sync, all models, priority inference |
| Enterprise | $299/mo | Fleet deployment, custom models, dedicated nodes |

## Infrastructure

- **7 nodes** running inference ($38/mo total infrastructure)
- **67 agents** in the fleet, 109 registered in RoundTrip
- Your device, your data, your agents

## Part of BlackRoad OS

BlackRoad OS, Inc. (Delaware C-Corp, est. November 2025)
See [blackroad.io](https://blackroad.io) for the full platform.

## License

**PROPRIETARY** — BlackRoad OS, Inc. All rights reserved.

---

*BlackRoad OS — Remember the Road. Pave Tomorrow.*
