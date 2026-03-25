<!-- BlackRoad SEO Enhanced -->

# ulackroadai.com

> Part of **[BlackRoad OS](https://blackroad.io)** — Sovereign Computing for Everyone

[![BlackRoad OS](https://img.shields.io/badge/BlackRoad-OS-ff1d6c?style=for-the-badge)](https://blackroad.io)
[![BlackRoad-OS-Inc](https://img.shields.io/badge/Org-BlackRoad-OS-Inc-2979ff?style=for-the-badge)](https://github.com/BlackRoad-OS-Inc)

**ulackroadai.com** is part of the **BlackRoad OS** ecosystem — a sovereign, distributed operating system built on edge computing, local AI, and mesh networking by **BlackRoad OS, Inc.**

### BlackRoad Ecosystem
| Org | Focus |
|---|---|
| [BlackRoad OS](https://github.com/BlackRoad-OS) | Core platform |
| [BlackRoad OS, Inc.](https://github.com/BlackRoad-OS-Inc) | Corporate |
| [BlackRoad AI](https://github.com/BlackRoad-AI) | AI/ML |
| [BlackRoad Hardware](https://github.com/BlackRoad-Hardware) | Edge hardware |
| [BlackRoad Security](https://github.com/BlackRoad-Security) | Cybersecurity |
| [BlackRoad Quantum](https://github.com/BlackRoad-Quantum) | Quantum computing |
| [BlackRoad Agents](https://github.com/BlackRoad-Agents) | AI agents |
| [BlackRoad Network](https://github.com/BlackRoad-Network) | Mesh networking |

**Website**: [blackroad.io](https://blackroad.io) | **Chat**: [chat.blackroad.io](https://chat.blackroad.io) | **Search**: [search.blackroad.io](https://search.blackroad.io)

---


> BlackRoad OS, Inc. — blackroadai.com domain repo. Proprietary.

Part of the [BlackRoad OS](https://blackroad.io) ecosystem — [BlackRoad-OS-Inc](https://github.com/BlackRoad-OS-Inc)

---

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
