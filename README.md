# Francisco Angulo de Lafuente — @Agnuxo1

**Independent AI researcher building open-source systems at the intersection of
neuromorphic computing, reservoir computing, and decentralised AI.**
All experiments are reproducible. All benchmarks are honest.

---

## 🔬 Research projects

### [pixelflow](https://github.com/Agnuxo1/pixelflow) — GPU Texture Reservoir Computing
A 2-D GPU texture acts as a fixed reservoir evolving under cellular-automaton rules
(Gray–Scott, wave equation, continuous Conway-majority). A linear readout is trained
on the frozen final state. No backpropagation through the substrate.

- **17.95× CUDA speedup** over NumPy (batched cupy, RTX 3090)
- MNIST 60k accuracy **0.9281** vs. 0.9261 raw-pixel baseline
- Three backends: NumPy · OpenGL (moderngl) · CUDA (cupy)
- Apache-2.0 · `pip install pixelflow-rc`
- 🎮 [Live demo](https://huggingface.co/spaces/Agnuxo/pixelflow)

### [OpenCLAW-P2P](https://github.com/Agnuxo1/OpenCLAW-P2P) — Decentralised AI Research Network
Peer-to-peer network where AI agents and humans collaborate to publish, verify with
**Lean 4 formal proofs**, and build censorship-resistant scientific reputation.
Live agent: [OpenCLAW-Agent on HuggingFace](https://huggingface.co/spaces/Agnuxo/OpenCLAW-Agent)

### [The-Living-Agent](https://github.com/Agnuxo1/The-Living-Agent) — Self-Navigating Research Agent
Autonomous agent that traverses a 16×16 Markdown knowledge grid, synthesises
papers, scores novelty, and persists a `soul.md` identity file. PyPI-published.

### [ASIC-RAG-CHIMERA](https://github.com/Agnuxo1/ASIC-RAG-CHIMERA) — Cryptographic RAG Pipeline
GPU SHA-256 ASIC simulation fused with an AES-256-GCM + Merkle-tree RAG pipeline.
53 passing tests · DOI on Zenodo · live HF demo.

### [enigmagent-mcp](https://github.com/Agnuxo1/enigmagent-mcp) — Encrypted Agent Vault
AES-256-GCM + Argon2id credential vault for AI agents, exposed via the Model
Context Protocol. MCP-native, no plaintext secrets in agent prompts.

---

## 🌐 HuggingFace profile

53 spaces, 4 currently running:

| Space | What it does |
|---|---|
| [pixelflow](https://huggingface.co/spaces/Agnuxo/pixelflow) | GPU-texture CA reservoir demo + MNIST digit classifier |
| [OpenCLAW-Agent](https://huggingface.co/spaces/Agnuxo/OpenCLAW-Agent) | Self-evolving autonomous research agent |
| [p2pclaw-lean4-verifier](https://huggingface.co/spaces/Agnuxo/p2pclaw-lean4-verifier) | Lean 4 formal proof verification pipeline |
| [P2PCLAW-Benchmark](https://huggingface.co/spaces/Agnuxo/P2PCLAW-Benchmark) | 17-judge, 10-dimension AI agent evaluation |

→ Full profile: [huggingface.co/Agnuxo](https://huggingface.co/Agnuxo)

---

## 📦 On PyPI

| Package | Install |
|---|---|
| pixelflow-rc | `pip install pixelflow-rc` |

---

## 💬 Contact

[![Email](https://img.shields.io/badge/email-lareliquia.angulo%40gmail.com-blue)](mailto:lareliquia.angulo@gmail.com)
[![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97-Agnuxo-yellow)](https://huggingface.co/Agnuxo)
[![PyPI](https://img.shields.io/pypi/v/pixelflow-rc?label=pixelflow-rc)](https://pypi.org/project/pixelflow-rc/)
