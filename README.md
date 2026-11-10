# Hi there, I'm Dmitry Sergeev

[![LinkedIn](https://img.shields.io/badge/LinkedIn-16k%2B_Connections-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sergeevdms/)
[![Upwork](https://img.shields.io/badge/Upwork-Top_Rated_%7C_7200%2B_hrs_%7C_100%25_JSS-14A800?style=flat-square&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~0142b51a7dc8e506a9)
[![Telegram](https://img.shields.io/badge/Telegram-@sergeevdms-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/sergeevdms)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:sergeevdms@devlab.group)

## About me

With over 15 years of engineering experience, I work on high-load backend infrastructure, custom blockchain protocols, production AI systems, and developer tooling.

My stack spans Python, Go, C++, JavaScript, Solidity, distributed systems, agentic AI, retrieval pipelines, and infrastructure security. I have been building decentralized systems since 2017, with a focus on architecture, reliability, and production constraints.

**Experience:** Elrond Network, BRD / BREAD, CoinPayments, Scotiabank, Bitdefender, Qiwi


## ⚡ Projects

[**Agent Commerce Gateway**](https://github.com/devlab-group/agent-commerce) — Self-hosted, non-custodial infrastructure that turns an existing API into something AI agents can discover, authorize, pay for, and call. MCP, x402, AP2, A2A, and ACP in one execution layer.

[**Self-Hosted RWA Tokenization Platform**](https://github.com/devlab-group/rwa-platform-evm) — Single-tenant infrastructure for tokenizing real-world assets as permissioned ERC-20s, with auditor-attested supply lifecycle and on-chain cash redemption. [Solana implementation →](https://github.com/devlab-group/rwa-platform-solana)

[**RepoLore — ChatGPT App**](https://chatgpt.com/plugins/plugin_asdk_app_6a898067d0b08191af8af6660eb1a9a5) — Developer tool for understanding why public GitHub code exists by tracing files and line ranges through commits, pull requests, issues, patches, and regressions.

[**Immutable Audit**](https://github.com/devlab-group/immutable-audit) — Tamper-evident Linux execution audit trail using eBPF, chained event integrity, and independent verification.

[**Postflight**](https://github.com/devlab-group/postflight) — Single-file Linux security and health auditing tool with human-readable, JSON, and Prometheus-compatible output plus actionable remediation commands.

[**llm-kit**](https://github.com/SergeevDmitry/llm-kit) — Six small, focused npm packages for the unglamorous parts of production LLM engineering. Each package solves one problem, installs independently, and ships with zero or minimal dependencies.

* [`mend-json`](https://www.npmjs.com/package/mend-json) — Turns a truncated JSON stream into a valid partial value on every chunk.
* [`token-chunk`](https://www.npmjs.com/package/token-chunk) — Chunks text and Markdown to a token budget along semantic boundaries.
* [`chat-fit`](https://www.npmjs.com/package/chat-fit) — Trims chat history to a budget without splitting a tool call from its result.
* [`usage-tab`](https://www.npmjs.com/package/usage-tab) — Turns provider usage objects into a reproducible cost breakdown.
* [`llm-backoff`](https://www.npmjs.com/package/llm-backoff) — Retries that read provider rate-limit headers instead of guessing.
* [`vec-cache`](https://www.npmjs.com/package/vec-cache) — SQLite embedding cache with partial batch hits, in-batch deduplication, and model-scoped keys.


## 🔬 Work & Research

[**System Architecture — Agent Commerce Gateway**](https://github.com/devlab-group/agent-commerce/blob/master/architecture/agent-commerce.pdf) — A representative example of how I approach architecture for production systems: defining component and protocol boundaries, converging multiple protocol adapters on a single execution pipeline, separating authorization, payment, backend execution, and receipt storage, and documenting trust boundaries, settlement flow, and failure handling.

[**ERC-8409 — Signed Service Payment Quotes**](https://ethereum-magicians.org/t/erc-8409-signed-service-payment-quotes/29577) — ERC proposal I authored for cryptographically signed service payment quotes using EIP-712, designed to separate provider pricing from payer authorization and settlement across agent-commerce flows.

[**Adversarial Agentic Validation**](https://zenodo.org/records/21875901) — Research on adversarial validation of autonomous AI agents, focused on failure discovery, boundary testing, and improving reliability in production multi-agent systems.
