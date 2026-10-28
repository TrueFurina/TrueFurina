# TrueFurina / Dream

<div align="center">

<img src="https://img.shields.io/badge/Agent_Systems-Engineer-blueviolet?style=for-the-badge" alt="Agent Engineer" />
<img src="https://img.shields.io/badge/LLM-MARL-important?style=for-the-badge" alt="MARL" />
<img src="https://img.shields.io/badge/LangGraph-Pipelines-cyan?style=for-the-badge" alt="LangGraph" />
<img src="https://img.shields.io/badge/RedTeam-Security-red?style=for-the-badge" alt="RedTeam" />
<img src="https://img.shields.io/badge/DBAPPSecurity-🛡️-brightgreen?style=for-the-badge" alt="Company" />

<br><br>

### Open Source Contributions

<img src="https://img.shields.io/badge/PRs_Total-170+-blue?style=social&logo=github" alt="PRs" />
<img src="https://img.shields.io/badge/Merged-55-gold?style=social&logo=merge" alt="Merged" />
<img src="https://img.shields.io/badge/Repos-TencentCloud%20Octop%20Ecosystem-indigo?style=social" alt="Ecosystem" />

</div>

---

## About

I build **production-grade LLM agent systems** with LangGraph, run **multi-agent reinforcement learning** (MARL) for cybersecurity defense, and operate **adversarial red-team** tests against AI systems. Currently @ **DBAPPSecurity**.

- 🌐 Blog: [appmiaoda.com](https://app-a7lm1eejtypt.appmiaoda.com)
- 🏢 Company: [dbappsecurity.com](https://www.dbappsecurity.com/)
- 🧪 Orgs: [MARL-ECDSA-Consensus](https://github.com/MARL-ECDSA-Consensus) · [Circle1507](https://github.com/Circle1507)

---

## Open Source: TencentCloud / Octop Ecosystem

> In ~20 days I've submitted **170+ PRs** across the Octop agent platform. **55 merged**, **87 still open**.

| Upstream | PRs | Merged | Open |
|----------|:---:|:------:|:----:|
| [TencentCloud/Octop](https://github.com/TencentCloud/Octop) | 100+ | **18** | 59+ |
| [TencentCloud/octop-harness](https://github.com/TencentCloud/octop-harness) | 50 | **28** | 17 |
| [TencentCloud/octop-memory](https://github.com/TencentCloud/octop-memory) | 20 | **9** | 11 |
| **Total** | **170+** | **55** | **87+** |

**Recent merged work** (2026-10):
- 🧠 **feat**: add MCP managed sessions (harness PR #65)
- 🧠 **feat**: bound SQLite/PostgreSQL memory connections (memory PR #19)
- 🛠 **fix**: guard inbox worker contextvars leak — 185k AIMessageChunk memory leak (harness PR #116)
- 🛠 **fix**: fallback grep to single-file scope (Octop PR #2374)
- 🛠 **fix**: UTF-8 byte bound on download filenames (Octop PR #2376)

**Profile forks** (synced or ahead of upstream):
- [TrueFurina/Octop](https://github.com/TrueFurina/Octop) → upstream main (synced)
- [TrueFurina/octop-memory](https://github.com/TrueFurina/octop-memory) → upstream main
- [TrueFurina/octop-harness](https://github.com/TrueFurina/octop-harness) → **2 commits ahead** of upstream

---

## Featured Projects

| ⭐ | Repo | Domain |
|:-:|------|--------|
| 8 | [AGI-Distiller](https://github.com/TrueFurina/AGI-Distiller) | 🧠 Knowledge distillation |
| 6 | [passive-recon](https://github.com/TrueFurina/passive-recon) | 🛰️ OSINT / EASM |
| 5 | [MARS-408](https://github.com/TrueFurina/MARS-408) | 🎓 MARL |
| 4 | [xihu-sword-ctf-agent](https://github.com/TrueFurina/xihu-sword-ctf-agent) | ⚔️ CTF AI agent |
| 4 | [marl-ecdsa](https://github.com/TrueFurina/marl-ecdsa) | 🔐 ECDSA consensus via RL |
| 4 | [xuandun-cyber-range](https://github.com/TrueFurina/xuandun-cyber-range) | 🎯 AI RedTeam range |

---

## Research Interests

```
LLM Agents
├─ LangGraph pipelines (plan → act → observe → reflect)
├─ RAG optimization (retrieval quality vs latency)
└─ Knowledge distillation (small ≈ big?)

Multi-Agent RL
├─ Cooperative consensus (ECDSA, PBFT via RL)
├─ Adversarial games (cyber attack/defense as zero-sum)
└─ MARL × LLM hybrid (LLM as policy network)

AI Security
├─ Red-team automation (jailbreak benchmarking)
├─ Prompt injection defense
└─ AI agent supply chain security
```

---

## Now Building

- 🤖 **SecAutoMind** — LLM-powered automated security testing pipeline
- 🧪 **MARL for consensus** — ECDSA signing without a leader
- 🛡️ **AI red-team framework** — systematic adversarial evaluation
- 🧠 **Agent memory layer** — cross-session persistence

---

## Tech Stack

| Layer | Tools |
|-------|-------|
| Agent Frameworks | LangGraph · LangChain · AutoGen · Dify |
| LLMs | DeepSeek-V3 · GPT-4o · Claude-Sonnet · Qwen |
| MARL | PettingZoo · Ray RLlib |
| Security | ZAP · Nuclei · SpiderFoot · Promptfoo |
| Backend | FastAPI · Docker · PostgreSQL |

---

<p align="center"><sub>Code first, buzzwords never.</sub></p>
