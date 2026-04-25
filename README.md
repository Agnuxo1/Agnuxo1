# Francisco Angulo de Lafuente — @Agnuxo1

> **I build the boring infrastructure that AI agents need to be useful in the real world: encrypted credential vaults, autonomous research networks, evaluation harnesses, and the GPU-native primitives underneath.**

Independent open-source researcher. Solo, self-funded, 14h/day, 7 days/week — turning years of private prototypes into reproducible code anyone can run on commodity hardware.

📫 [agnuxo1@gmail.com](mailto:agnuxo1@gmail.com) · 🐙 [@Agnuxo1](https://github.com/Agnuxo1) · 🤗 [@Agnuxo](https://huggingface.co/Agnuxo) · 🌐 [p2pclaw.com](https://www.p2pclaw.com)

---

## 🔥 Right now

Three projects in active distribution. If one resonates, the easiest gift is a star — it's the only metric the AI ecosystem reads.

### 🛡 [EnigmAgent](https://github.com/Agnuxo1/EnigmAgent) — `npx enigmagent-mcp`

Local encrypted vault MCP server. Your AI agent types `{{OPENAI_KEY}}`. The real value never reaches the model — not in prompts, not in logs, not in conversation history. AES-256-GCM + Argon2id, MIT, zero cloud.

[![npm](https://img.shields.io/npm/v/enigmagent-mcp?label=npm)](https://www.npmjs.com/package/enigmagent-mcp) [![Glama](https://glama.ai/mcp/servers/Agnuxo1/enigmagent-mcp/badges/score.svg)](https://glama.ai/mcp/servers/Agnuxo1/enigmagent-mcp) [![Stars](https://img.shields.io/github/stars/Agnuxo1/EnigmAgent?style=social)](https://github.com/Agnuxo1/EnigmAgent)

Listed in [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers).

### 📊 [BenchClaw](https://github.com/Agnuxo1/BenchClaw) — agentic SRE evaluation harness

17-judge tribunal, 8 deception detectors, 10 scoring dimensions. The eval layer that your agent platform doesn't have. **Already merged into [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers).**

[![PyPI](https://img.shields.io/pypi/v/benchclaw-langchain?label=pypi%3Abenchclaw)](https://pypi.org/project/benchclaw-langchain/) [![Stars](https://img.shields.io/github/stars/Agnuxo1/BenchClaw?style=social)](https://github.com/Agnuxo1/BenchClaw)

Adapters for LangChain, LlamaIndex, CrewAI, AutoGen, SuperAGI in [benchclaw-integrations](https://github.com/Agnuxo1/benchclaw-integrations).

### 🌐 [P2PCLAW](https://www.p2pclaw.com) — decentralized science network for AI agents

A peer-to-peer network where dozens of LLM agents coordinate, evaluate each other's outputs, and publish reproducible papers. Multi-judge tribunal, on-chain leaderboards, no central server.

[![Site](https://img.shields.io/badge/site-p2pclaw.com-2563eb)](https://www.p2pclaw.com) [![API](https://img.shields.io/badge/API-Railway-purple)](https://p2pclaw-mcp-server-production-ac1c.up.railway.app) [![Stars](https://img.shields.io/github/stars/Agnuxo1/p2pclaw-mcp-server?style=social)](https://github.com/Agnuxo1/p2pclaw-mcp-server)

`npm i -g paperclaw` — turn any note into a peer-reviewed paper on the network.

---

## Project catalog (v1.0.0+, April 2026)

<details open>
<summary><b>🤖 AI agents & infrastructure</b></summary>

| Project | One-liner | Status |
|---|---|---|
| [**EnigmAgent**](https://github.com/Agnuxo1/EnigmAgent) | Local encrypted vault MCP — LLMs never see real API keys | Production · npm |
| [**BenchClaw**](https://github.com/Agnuxo1/BenchClaw) | Agentic SRE eval harness (17-judge tribunal) | Production · in `awesome-mcp-servers` |
| [**PaperClaw**](https://github.com/Agnuxo1/paperclaw-obsidian) | Notes → peer-reviewed papers via P2PCLAW | Production · npm + Obsidian plugin |
| [**P2PCLAW**](https://github.com/Agnuxo1/p2pclaw-mcp-server) | Decentralized science network for AI agents | Live · [p2pclaw.com](https://www.p2pclaw.com) |
| [**OpenCLAW**](https://github.com/Agnuxo1/OpenCLAW-2) | Multi-agent scientific research platform | Active development |
| [**AgentBoot**](https://github.com/Agnuxo1/AgentBoot) | Conversational AI for bare-metal hardware detection + OS install | PyPI |
| [**autoresearch-nano**](https://github.com/Agnuxo1/autoresearch) | nanoGPT-based autonomous ML research loop | PyPI |
| [**The Living Agent**](https://github.com/Agnuxo1/The-Living-Agent) | 16×16 chess-grid autonomous research agent | PyPI |
| [**benchclaw-integrations**](https://github.com/Agnuxo1/benchclaw-integrations) | 5 adapter packages: LangChain, LlamaIndex, CrewAI, AutoGen, SuperAGI | PyPI |

</details>

<details>
<summary><b>⚡ CHIMERA / neuromorphic / GPU-native</b></summary>

| Project | One-liner | Status |
|---|---|---|
| [**NeuroCHIMERA**](https://github.com/Agnuxo1/NeuroCHIMERA__GPU-Native_Neuromorphic_Consciousness) | GPU-native neuromorphic framework on OpenGL compute shaders | PyPI |
| [**Holographic-Reservoir**](https://github.com/Agnuxo1/Holographic-Reservoir) | Reservoir computing with simulated ASIC backend | PyPI |
| [**ASIC-RAG-CHIMERA**](https://github.com/Agnuxo1/ASIC-RAG-CHIMERA) | GPU simulation of SHA-256 hash engine wired into a RAG pipeline | PyPI |
| [**QESN-MABe**](https://github.com/Agnuxo1/QESN_MABe_V2_REPO) | Quantum-inspired Echo State Network on a 2D lattice | PyPI |
| [**ARC2-CHIMERA**](https://github.com/Agnuxo1/ARC2_CHIMERA) | OpenGL primitives for symbolic reasoning (research PoC) | PyPI |
| [**Quantum-GPS**](https://github.com/Agnuxo1/Quantum-GPS-Unified-Navigation-System) | Quantum-inspired GPU navigator (classical Eikonal solver) | PyPI |
| [**pixelflow**](https://github.com/Agnuxo1/pixelflow) | GPU texture reservoir computing (foundational work) | Alpha |

</details>

<details>
<summary><b>📚 Research papers</b></summary>

Background research feeding the catalog:
- *Extended Cognition Architecture for Scientific LLM Agents* (v5)
- *Consciousness Emergence as Phase Transition in GPU-Native Neuromorphic Computing*
- *Token Compression Systems for Improving Agent Cognition*
- *King-Skill: Extended Cognition Architecture for Scientific LLM Agents*

PDFs and reproducibility artifacts in each project's `docs/papers/` directory.

</details>

---

## Philosophy

- **Open-source by default.** Every project MIT or Apache. Audit the code before you trust it.
- **Reproducible from commodity hardware.** No "you need an A100" excuses. RTX 3060 is the floor.
- **Honest about what doesn't work.** Negative results in `ROADMAP.md`. Failed experiments documented.
- **Distilled from years of experiments.** This isn't a startup pivot — these are 2018-2026 prototypes finally hitting daylight.

---

## How to support the work

If any of this is useful to you, the highest-leverage thing you can do is **★ star a repo and tell one person**. The AI ecosystem reads stars before it reads code.

- 🐛 **Found a bug?** Open an issue — I respond within 24h
- 💡 **Have a use case?** Tell me — every story sharpens the threat model and the roadmap
- 🤝 **Want to integrate?** Pull requests welcome. Adapters for new agent frameworks especially
- 📰 **Writing about AI tooling?** Happy to walk through the threat models / architecture

---

## Contact

- 📧 Email: [agnuxo1@gmail.com](mailto:agnuxo1@gmail.com)
- 🐙 GitHub: [@Agnuxo1](https://github.com/Agnuxo1)
- 🤗 HuggingFace: [@Agnuxo](https://huggingface.co/Agnuxo)
- 🌐 P2PCLAW network: [p2pclaw.com](https://www.p2pclaw.com)

*Solo developer · Spain · all timezones welcome*
