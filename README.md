# TrueFurina / Dream

<div align="center">

<img src="https://img.shields.io/badge/Agent_Systems-Engineer-blueviolet?style=for-the-badge" alt="Agent Engineer" />
<img src="https://img.shields.io/badge/LLM-MARL-important?style=for-the-badge" alt="MARL" />
<img src="https://img.shields.io/badge/LangGraph-Pipelines-cyan?style=for-the-badge" alt="LangGraph" />
<img src="https://img.shields.io/badge/RedTeam-Security-red?style=for-the-badge" alt="RedTeam" />
<img src="https://img.shields.io/badge/DBAPPSecurity-🛡️-brightgreen?style=for-the-badge" alt="Company" />

<br><br>

### Open Source Contributions

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

Active contributor to the Octop agent platform (CLI · harness · memory).
I'd rather point at merged work than quote counts — the table below lists changes that were
reviewed and merged by maintainers, with links you can click and check.

**Profile forks** (synced or ahead of upstream):
- [TrueFurina/Octop](https://github.com/TrueFurina/Octop) → upstream main (synced)
- [TrueFurina/octop-memory](https://github.com/TrueFurina/octop-memory) → upstream main
- [TrueFurina/octop-harness](https://github.com/TrueFurina/octop-harness) → **2 commits ahead** of upstream

---

## 🛠 Selected upstream contributions

只列**已被上游合并**的改动，每条都能点开核对（维护者原话在 PR 里）。

| 上游 / PR | 改了什么 | 规模 | 结果 |
|---|---|:--:|---|
| [unicode-rs/unicode-segmentation #183](https://github.com/unicode-rs/unicode-segmentation/pull/183) | `GraphemeCursor` 公共 API 的越界 panic：`offset`/`chunk_start` 切片、`prev_chunk` 反向迭代下溢、pre-context 分块校验 | +27/−5 | 维护者 **Manishearth** 要求 `cargo fmt` 后 APPROVED 并致谢 |
| [CodeGraphContext #1676](https://github.com/CodeGraphContext/CodeGraphContext/pull/1676) | 给 Cassandra / MySQL ingestor 加 SSL 连接参数（`CERT_REQUIRED` + 主机名校验，默认关闭、不影响旧配置） | +1214/−315，25 文件 | 维护者本地 trial-merge 验证后合并 |
| [TencentCloud/Octop #2171](https://github.com/TencentCloud/Octop/issues/2171) → [#2174](https://github.com/TencentCloud/Octop/pull/2174) | 报 issue：`OCTOP_HOME` 不迁移向导密码文件；逐行指出 4 处该同步修改的集成测试，维护者据此修复 | +173/−40 | 维护者 *"Looks merge-ready for #2171"*，changelog 署名 `(#2171)` |
| [seanmonstar/reqwest #3100](https://github.com/seanmonstar/reqwest/pull/3100) | `base64` 改 `default-features = false`，去掉 `simd-unsafe`，crate 恢复 `#![forbid(unsafe_code)]` | +1/−1 | 作者 **seanmonstar** 本人 APPROVED |
| [Unstructured-IO/unstructured #4463](https://github.com/Unstructured-IO/unstructured/pull/4463) | `Text` 元素在 `None` 文本时归一化为空串，修 `TypeError`（含测试） | +33/−4，4 文件 | 维护者 APPROVED |

> 我更擅长**定位**而不是堆代码：Octop 那条我没有直接改代码，而是把维护者需要同步修改的 4 处测试行号列清楚，他按清单改完就合了。

---

## Featured Projects

| ⭐ | Repo | Domain |
|:-:|------|--------|
| 8 | [AGI-Distiller](https://github.com/TrueFurina/AGI-Distiller) | 🧠 Knowledge distillation |
| 6 | [passive-recon](https://github.com/TrueFurina/passive-recon) | 🛰️ OSINT / EASM |
| 5 | [MARS-408](https://github.com/TrueFurina/MARS-408) | 🎓 MARL |
| 4 | [xihu-sword-ctf-agent](https://github.com/TrueFurina/xihu-sword-ctf-agent) | ⚔️ CTF AI agent |
| 0 | [marl-ecdsa](https://github.com/TrueFurina/marl-ecdsa) | 🔐 ECDSA consensus via RL |
| 3 | [xuandun-cyber-range](https://github.com/TrueFurina/xuandun-cyber-range) | 🎯 AI RedTeam range |

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
