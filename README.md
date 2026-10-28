# 🔬 TrueFurina

<div align="center">
  <img src="https://img.shields.io/badge/Agent_Systems-Engineer-blueviolet?style=for-the-badge&logo=github" alt="Agent" />
  <img src="https://img.shields.io/badge/LLM-MARL-important?style=for-the-badge" alt="MARL" />
  <img src="https://img.shields.io/badge/LangGraph-Pipelines-cyan?style=for-the-badge&logo=python" alt="LangGraph" />
  <img src="https://img.shields.io/badge/AI_Red--Team-Security-red?style=for-the-badge" alt="RedTeam" />
  <img src="https://img.shields.io/badge/DBAPPSecurity-🛡️-brightgreen?style=for-the-badge" alt="Company" />
</div>

<div align="center">
  <h1>👋 Hi, I'm Dream (TrueFurina)</h1>
  <p><em>Code first, buzzwords never.</em></p>
  <br>

  <!-- Dynamic GitHub Stats -->
  <img src="https://img.shields.io/badge/Followers-170-blue?style=social&logo=github" alt="followers" />
  <img src="https://img.shields.io/badge/Public_Repos-36_active-green?style=social&logo=git" alt="repos" />
  <img src="https://img.shields.io/badge/Total_Stars-92-gold?style=social&logo=star" alt="stars" />
  <img src="https://img.shields.io/badge/Orgs-2-indigo?style=social" alt="orgs" />
</div>

---

## 🎯 Who Am I?

I build **production-grade LLM agent systems** using LangGraph, run **multi-agent reinforcement learning** (MARL) experiments for cybersecurity defense, and operate **adversarial red-team** tests against AI systems to harden them against jailbreak and prompt injection attacks.

Currently @ **DBAPPSecurity** 🛡️ — building AI-powered security testing infrastructure.

---

## 📊 Live Stats

<div align="center">

### 🔴 Top Languages Over Time

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TrueFurina&layout=compact&theme=tokyonight&langs_count=10&hide_border=true&bg_color=0D1117" alt="Top Languages" />

### 📈 Contribution Activity

<img src="https://github-readme-stats.vercel.app/api?username=TrueFurina&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&include_all_commits=true&count_private=false" alt="GitHub Stats" />

### 🔥 Streak

<img src="https://github-readme-streak-stats.herokuapp.com/?user=TrueFurina&theme=tokyonight&hide_border=true&background=0D1117&ring=7C3AED&fire=FF6B35" alt="Streak" />

</div>

---

## 🏆 Featured Projects

| ⭐ | Project | Domain | Description |
|:-:|---------|--------|-------------|
| ⭐9 | [AGI-Distiller](https://github.com/TrueFurina/AGI-Distiller) | 🧠 Knowledge | Self-evolving knowledge distillation — small models learn from big ones |
| ⭐7 | [passive-recon](https://github.com/TrueFurina/passive-recon) | 🛰️ OSINT | Purely passive EASM / CTEM platform — 15+ data sources |
| ⭐6 | [MARS-408](https://github.com/TrueFurina/MARS-408) | 🎓 MARL | Multi-Agent personalized learning for China's 408 CS exam |
| ⭐5 | [xihu-sword-ctf-agent](https://github.com/TrueFurina/xihu-sword-ctf-agent) | ⚔️ CTF | AI agent for automated CTF solving — recon → exploit → flag |
| ⭐4 | [marl-ecdsa](https://github.com/TrueFurina/marl-ecdsa) | 🔐 Research | ECDSA consensus protocol via Multi-Agent RL |
| ⭐4 | [xuandun-cyber-range](https://github.com/TrueFurina/xuandun-cyber-range) | 🎯 RedTeam | 玄盾 · AI 攻防靶场 — multi-agent offense/defense training |

---

## 🛠 Selected upstream contributions

只列**已被上游合并**的改动，每条都能点开核对（维护者原话在 PR 里）。

| 上游 / PR | 改了什么 | 规模 | 结果 |
|---|---|:--:|---|
| [unicode-rs/unicode-segmentation #183](https://github.com/unicode-rs/unicode-segmentation/pull/183) | `GraphemeCursor` 公共 API 的越界 panic：`offset`/`chunk_start` 切片、`prev_chunk` 反向迭代下溢、pre-context 分块校验 | +27/−5 | 维护者 **Manishearth** 要求 `cargo fmt` 后 APPROVED 并致谢 |
| [CodeGraphContext #1676](https://github.com/CodeGraphContext/CodeGraphContext/pull/1676) | 给 Cassandra / MySQL ingestor 加 SSL 连接参数（`CERT_REQUIRED` + 主机名校验，默认关闭、不影响旧配置） | +1214/−315，25 文件 | 维护者本地 trial-merge 验证后合并 |
| [TencentCloud/Octop #2171](https://github.com/TencentCloud/Octop/issues/2171) → [#2174](https://github.com/TencentCloud/Octop/pull/2174) | 报 issue：`OCTOP_HOME` 不迁移向导密码文件；**逐行指出 4 处该同步修改的集成测试**，维护者据此修复 | +173/−40，11 文件 | 维护者 *"Looks merge-ready for #2171"*，changelog 署名 `(#2171)` |
| [seanmonstar/reqwest #3100](https://github.com/seanmonstar/reqwest/pull/3100) | `base64` 改 `default-features = false, features = ["std"]`，去掉 `simd-unsafe`，crate 恢复 `#![forbid(unsafe_code)]` | +1/−1 | 作者 **seanmonstar** 本人 APPROVED |
| [Unstructured-IO/unstructured #4463](https://github.com/Unstructured-IO/unstructured/pull/4463) | `Text` 元素在 `None` 文本时归一化为空串，修 `TypeError`（含测试） | +33/−4，4 文件 | 维护者 APPROVED |

> 我更擅长的是**定位**而不是堆代码：Octop 那条我没有直接改代码，而是把维护者需要同步修改的 4 处测试行号列清楚，他按清单改完就合了。

---

## 📜 Contribution policy

三条自己定的规矩，因为踩过坑：

1. **一个 PR 只做一件可验证的事。** 不做跨仓库批量模板 PR——那类 PR 的合并率不到 13%，还会消耗维护者耐心。
2. **不用 LLM 代写 issue / PR 正文。** 上游对这点很敏感（Pallets 全线关闭 LLM 相关投稿，zola 的 CONTRIBUTING 明确写了不接受）。
3. **docs-only 的 PR 不自荐、不催更。** 内容已被后续改动覆盖时主动关闭，而不是留着等合并。

## 🔬 Research Interests

```
LLM Agents ─────────────────────────────────────────────────────┐
  ├─ LangGraph pipelines (plan → act → observe → reflect)      │
  ├─ RAG optimization (retrieval quality vs latency tradeoff)   │
  └─ Knowledge distillation (small ≈ big?)                      │
                                                                 │
Multi-Agent RL ──────────────────────────────────────────────────┤
  ├─ Cooperative consensus (ECDSA, PBFT via RL)                │
  ├─ Adversarial games (cyber attack/defense as zero-sum)       │
  └─ MARL × LLM hybrid (LLM as policy network)                  │
                                                                 │
AI Security ────────────────────────────────────────────────────┤
  ├─ Red-team automation (jailbreak benchmarking)              │
  ├─ Prompt injection defense (robustness vs capability)        │
  └─ AI agent supply chain security                             │
                                                                 │
Open Source Contribution ────────────────────────────────────────┘
  ├─ TencentCloud/Octop ecosystem (agent memory, harness)
  └─ LangGraph community tooling
```

---

## 🔥 What I'm Building Now

- 🤖 **SecAutoMind** — LLM-powered automated security testing pipeline
- 🧪 **MARL for consensus** — training agents to collectively sign ECDSA without a leader
- 🛡️ **AI red-team framework** — systematic adversarial evaluation for LLM systems
- 🧠 **Agent memory layer** — cross-session persistence for LLM agent state

---

## 🤝 Open Source Contribution: TencentCloud/Octop

I fork and contribute to the Octop AI assistant ecosystem:
- [TrueFurina/Octop](https://github.com/TrueFurina/Octop) → upstream [TencentCloud/Octop](https://github.com/TencentCloud/Octop)
- [TrueFurina/octop-memory](https://github.com/TrueFurina/octop-memory) → upstream [TencentCloud/octop-memory](https://github.com/TencentCloud/octop-memory)
- [TrueFurina/octop-harness](https://github.com/TrueFurina/octop-harness) → upstream [TencentCloud/octop-harness](https://github.com/TencentCloud/octop-harness)

---

## 🔧 Tech Stack

| Layer | Tools |
|-------|-------|
| **Agent Frameworks** | LangGraph · LangChain · AutoGen · Dify |
| **LLMs** | DeepSeek-V3 · GPT-4o · Claude-Sonnet · Qwen |
| **MARL** | PettingZoo · Ray RLlib · JAXMARL |
| **Security** | OWASP ZAP · Nuclei · SpiderFoot · Promptfoo |
| **Backend** | FastAPI · Docker · Redis · PostgreSQL |
| **Frontend** | Streamlit · Vue3 · Next.js |
| **Infra** | GitHub Actions · Kubernetes · Cloudflare |

---

## 📫 Let's Connect

- 🌐 **Blog**: [appmiaoda.com](https://app-a7lm1eejtypt.appmiaoda.com)
- 🏢 **Company**: [DBAPPSecurity](https://www.dbappsecurity.com/)
- 🐙 **GitHub**: [@TrueFurina](https://github.com/TrueFurina)
- 🧪 **Orgs**: [MARL-ECDSA-Consensus](https://github.com/MARL-ECDSA-Consensus) · [Circle1507](https://github.com/Circle1507)

---

<div align="center">
  <sub>Agent systems · LLM-MARL · adversarial security</sub>
</div>
