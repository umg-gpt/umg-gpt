<div align="center">

# Umang Gupta

**AI-Native Builder · Founder · India**

*Building production infrastructure with AI tools — no traditional coding background.*

[![](https://img.shields.io/badge/MoltPe-Payment%20Infra%20for%20AI%20Agents-black?style=for-the-badge&logo=ethereum)](https://moltpe.com)
[![](https://img.shields.io/badge/x402-Coinbase%20Protocol-blue?style=for-the-badge)](https://x402.org)
[![](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-purple?style=for-the-badge)](https://modelcontextprotocol.io)

[![Security Headers: A](https://img.shields.io/badge/Security%20Headers-A-brightgreen?style=for-the-badge)](https://securityheaders.com/?q=moltpe.com&followRedirects=on)
[![Mozilla Observatory: B+](https://img.shields.io/badge/Mozilla%20Observatory-B+-blue?style=for-the-badge)](https://observatory.mozilla.org/analyze/moltpe.com)
[![0 Critical Findings](https://img.shields.io/badge/Critical%20Findings-0-brightgreen?style=for-the-badge)](https://moltpe.com/security)

</div>

---

## What I'm Building

### [MoltPe](https://moltpe.com) — Payment Infrastructure for AI Agents
AI agents need wallets. MoltPe gives every agent its own isolated USDC wallet with spending limits, policy enforcement, and the ability to pay for things autonomously — no human in the loop.

- Agents pay for API calls via **x402** (Coinbase's HTTP 402 payment protocol)
- AI assistants (Claude, ChatGPT) control payments via **MCP** (Model Context Protocol)
- Multi-chain: **Base**, **Polygon**, **Tempo** (Arc testnet)
- Full dashboard for humans to oversee agent spending

```
Agent → MoltPe Wallet → x402 Paywall → API Response
         ↑
    Claude / ChatGPT via MCP tools
```

---

## Stack

| | |
|---|---|
| **Runtime** | Node.js |
| **Frontend** | React, Vite, Tailwind |
| **Database** | Supabase (PostgreSQL + Auth) |
| **Blockchain** | viem, Coinbase x402 SDK, USDC |
| **AI** | Claude (MCP), OpenAI |
| **Infra** | GCP Cloud Run, Docker, Cloud Build CI/CD |
| **Protocols** | x402, MPP, MCP, HTTP 402 |

---

## How I Build

I'm a non-technical founder. Every line of production code in my repos is written by AI (Claude Code, Lovable, Replit Agent) — directed, reviewed, and debugged by me.

This is a new way of building. The tools have changed what's possible for founders without a CS background. What used to require a 3-person engineering team, I ship solo.

**Last 90 days:**
- 670+ commits
- Production blockchain payment infrastructure
- MCP server with 5 agent tools
- 40+ unit tests
- Multi-chain USDC settlement on Base, Polygon, and Tempo

---

## Security

MoltPe handles real money — security is non-negotiable. Every layer is hardened, scanned, and independently verified.

**[Full Security Report →](https://moltpe.com/security)**

### Independent Scan Grades

| Scanner | Grade | Verify |
|---------|-------|--------|
| **SecurityHeaders.com** | **A** | [Scan →](https://securityheaders.com/?q=moltpe.com&followRedirects=on) |
| **Mozilla Observatory** | **B+** | [Scan →](https://observatory.mozilla.org/analyze/moltpe.com) |

### Infrastructure

* **GCP Cloud Run** — managed TLS, auto-scaling, DDoS protection
* **Supabase PostgreSQL** — AES-256 encryption at rest, Row Level Security
* **GCP Security Command Center Premium** — continuous vulnerability scanning
* **CIS Google Cloud Foundation Benchmark** — compliance mapped

### Payment Security

* Atomic DB guards preventing double-spend
* Idempotency keys preventing duplicate transactions
* On-chain USDC settlement — every payment verifiable on blockchain
* Isolated agent wallets — agents never access user funds

[![Security Headers](https://img.shields.io/badge/Security%20Headers-A-brightgreen?style=flat-square)](https://securityheaders.com/?q=moltpe.com&followRedirects=on)
[![Mozilla Observatory](https://img.shields.io/badge/Mozilla%20Observatory-B+-blue?style=flat-square)](https://observatory.mozilla.org/analyze/moltpe.com)
[![0 Critical Findings](https://img.shields.io/badge/Critical%20Findings-0-brightgreen?style=flat-square)](#)
[![0 npm Vulnerabilities](https://img.shields.io/badge/npm%20Vulnerabilities-0-brightgreen?style=flat-square)](#)

---

## Stats

### Profile Overview
![Metrics](https://github.com/umg-gpt/umg-gpt/raw/main/metrics.svg)

### Languages
![Languages](https://github.com/umg-gpt/umg-gpt/raw/main/metrics.languages.svg)

### Streak
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=umg-gpt&theme=tokyonight" alt="Streak" />
</p>

---

## Timeline

| | |
|---|---|
| **Jan 2026** | Started exploring AI-native product ideas |
| **Feb 2026** | Built and scrapped 5 crypto wallet prototypes (fast learning) |
| **Feb 2026** | Launched MoltPe — pivot to AI payment infrastructure |
| **Mar 2026** | Integrated Coinbase x402 SDK + MCP server |
| **Mar 2026** | Added Base chain + MPP paywall protocol |
| **Apr 2026** | Multi-chain, 40+ tests, live on moltpe.com |

---

<div align="center">

**moltpe.com** · [x402 Protocol](https://x402.org) · [MCP Docs](https://modelcontextprotocol.io)

</div>
