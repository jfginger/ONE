# the ONE

**The Local-First Sovereign Agent for Growth, Legacy, and Connection.**

> *"Web2 was about connecting computers. Early Web3 was about connecting wallets. the ONE is about connecting souls through local, sovereign intelligence."*

---

## What Is This?

the ONE is a decentralized AI ecosystem that replaces centralized social profiles with **Autonomous Personal Agents** (Twins). Your Twin lives on your device, learns who you really are, and negotiates compatibility with other people's Twins — without ever exposing your raw data to a server, a corporation, or even the other person.

No swipes. No feeds. No data harvesting. Just encrypted pattern matching between sovereign digital selves.

---

## The Problem

| What Exists Today | What's Broken |
|---|---|
| Dating apps | Optimize for engagement, not compatibility. Swipe culture rewards surface over substance. |
| Personality quizzes | Shallow, static, owned by platforms. Your results train their models, not yours. |
| AI assistants | Cloud-first. Your most intimate reflections live on someone else's servers. |
| Social profiles | You perform a version of yourself. Algorithms reward the performance. |

Meanwhile: global loneliness is at an all-time high. 64% of users now prefer local-first AI after the 2025 cloud-AI data breaches. The AI Agent market is projected to reach $12B in 2026.

People don't need another app. They need **infrastructure for real connection**.

---

## The Architecture

the ONE has three layers:

### 🪞 Layer 1: The Soul Engine (Local, Private)

A structured self-knowledge system powered by a local Small Language Model (SLM). Through guided reflection — not quizzes — the engine builds a living psychological profile across dimensions like values, emotional patterns, attachment style, communication DNA, and growth trajectory.

Everything stays on-device. Encrypted at rest. Your soul belongs to you.

### 🤖 Layer 2: The Twin (Local, Private)

A **Decentralized Personal Proxy** — an autonomous agent that carries a compressed, encrypted representation of who you are. Rich enough to assess compatibility. Impossible to reverse-engineer into your actual answers.

The Twin is built using:
- **Lossy dimensionality reduction** (autoencoder: 768-dim → 32-dim)
- **Quantization** into discrete value bands
- **Differential privacy** (ε-calibrated noise injection)
- **Homomorphic encryption** (comparison without decryption)

Your Twin can represent you. It cannot betray you.

### 🤝 Layer 3: The Handshake Protocol (P2P, Zero-Knowledge)

Twin-to-Twin negotiation over a peer-to-peer network. No central server. No raw data exchange. Five phases:

```
Discovery → Deal-Breaker Gate → Value Alignment → Simulated Banter → Human Handover
```

1. **Discovery**: Twins broadcast anonymous availability signals via DID on a P2P network.
2. **Deal-Breaker Gate**: Encrypted categorical flags are compared. Mutual exclusions terminate the handshake immediately. No further data exchanged.
3. **Value Alignment**: Homomorphic cosine similarity across encrypted Semantic Abstracts. Threshold: >0.65.
4. **Simulated Banter**: 100-turn conversation between Twins using locally-trained persona models (LoRA adapters). Scored on engagement, humor resonance, repair behavior, and depth.
5. **Human Handover**: Only if the **Soul Score > 85%**, the humans are notified with a compatibility breakdown, banter highlights, risk profile, and a suggested opener.

---

## The Privacy Stack

Privacy isn't a feature. It's the foundation.

| Layer | Technology | What It Protects |
|---|---|---|
| Storage | On-device encrypted DB (AES-256) | Raw answers and full Soul Object |
| Identity | Decentralized Identifiers (DIDs) | Real name, phone, email |
| Abstraction | Lossy autoencoder + quantization | Specific answer content |
| Noise | Differential privacy (ε-calibrated) | Statistical reconstruction attacks |
| Computation | Partially Homomorphic Encryption | Comparison without decryption |
| Verification | zk-SNARKs | Identity validity without disclosure |
| Transport | E2EE over P2P | All network traffic |

**Attack resistance**: reconstruction attacks, linkage attacks, Sybil attacks, and MITM are all addressed by design. See [architecture docs](docs/architecture.md) for details.

---

## Technical Stack

- **Local LLM**: Llama 3.2 3B / Gemma 3 (4-bit quantized, on-device)
- **Vector DB**: ChromaDB or ObjectBox (local, encrypted)
- **Sync**: CRDTs for multi-device replication without central servers
- **P2P**: libp2p for Twin-to-Twin communication
- **Identity**: W3C Decentralized Identifiers (DIDs) with zk-SNARK proofs
- **Agent Protocol**: Built on MCP (Model Context Protocol)
- **Persona Training**: LoRA fine-tuning on-device for Twin behavioral models
- **Inference Optimization**: Speculative decoding for older hardware support

---

## Product Roadmap

| Phase | Focus | What Ships |
|---|---|---|
| **Mirror** | Self-Knowledge | Local AI reflection engine with guided questioning |
| **Archive** | Legacy | Multi-device sync, Soul Archive viewer, encrypted Time Capsule |
| **Bridge** | Connection | P2P Twin-to-Twin matchmaking (friends, dating, mentorship) |
| **Ecosystem** | Developer API | 3rd-party growth apps access local soul-vector with user consent |

---

## Revenue Model

We don't sell data. Ever.

- **Free**: Local journaling, basic memory, 1-on-1 agent scouting
- **Premium ($11/mo)**: Multi-agent scouting (50+ conversations/day), advanced legacy formatting, higher-reasoning models (8B+)
- **Legacy ($299 one-time)**: Permanent encrypted Time Capsule on decentralized storage (IPFS/Arweave) for 100+ years

---

## The Founding Team We're Building

| Role | Focus | Core Skills Needed |
|---|---|---|
| **The Soul** | Product vision, psychology architecture, UX | Prompt engineering, character design, human behavior |
| **The Brain** | Local AI & ML | RAG, SLM quantization, LoRA fine-tuning, on-device optimization |
| **The Shield** | P2P & cryptography | E2EE, homomorphic encryption, DIDs, zk-SNARKs, CRDTs |

**Currently seeking: The Brain and The Shield.**

If you're an AI engineer or cryptography/P2P specialist who believes personal data should be sovereign, let's talk.

---

## What's Not in This Repo (Yet)

The core psychological framework — the specific questions, the question-to-vector mapping, and the Soul Schema dimensions — are available under NDA to serious collaborators and co-founders. This is the piece that bridges psychology to engineering, and it's what makes the ONE fundamentally different from a generic encrypted matching system.

**Interested?** Open an issue or reach out directly.

---

## Philosophy

Every design decision flows from a single principle: **a person's inner life is sovereign territory.**

The current paradigm treats human complexity as a commodity — behavioral data harvested to sell predictions. the ONE treats it as sacred.

The Soul Engine isn't a personality quiz. It's a structured invitation to self-knowledge.  
The Twin isn't a chatbot. It's a guardian and advocate.  
The Handshake isn't a matching algorithm. It's a negotiation between equals.  
The zero-knowledge architecture isn't a feature. It's a moral position.

You should be able to find deep, compatible human connections without surrendering your inner life to a corporation.

---

## License

Source-available. See [LICENSE](LICENSE) for terms.

---

<p align="center"><i>"We aren't building an app; we are building the infrastructure for the next 100 years of human memory about heart and soul."</i></p>
