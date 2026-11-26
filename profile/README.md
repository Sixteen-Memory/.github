<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sixteen-Memory/.github/main/profile/lockup-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sixteen-Memory/.github/main/profile/lockup-light.png">
    <img src="https://raw.githubusercontent.com/Sixteen-Memory/.github/main/profile/lockup-light.png" alt="SixteenMemory" width="360">
  </picture>
</p>

<p align="center">
  <strong>Source-linked memory infrastructure for AI Agents.</strong><br>
  面向 AI Agent 的来源可追溯开源记忆基础设施（Apache-2.0）。
</p>

<p align="center">
  <a href="https://github.com/Sixteen-Memory/sixteen-memory"><strong>sixteen-memory</strong></a> ·
  <a href="https://github.com/Sixteen-Memory/sixteen-memory/blob/main/README.zh-CN.md">中文文档</a> ·
  <a href="https://github.com/Sixteen-Memory/sixteen-memory/releases/tag/v0.3.0">v0.3.0 Releases</a> ·
  <a href="https://www.sixteenmemory.com/">Website</a> ·
  <a href="https://github.com/Sixteen-Memory/sixteen-memory/discussions">Discussions</a>
</p>

---

**SixteenMemory** builds open-source memory and knowledge infrastructure where every claim stays bound to verbatim source evidence, optimistic version history, and server-enforced user isolation—running on Cloudflare Workers and SQLite Durable Objects with zero external vector or graph databases required.

| Project | What it provides |
| :--- | :--- |
| **[`Sixteen-Memory/sixteen-memory`](https://github.com/Sixteen-Memory/sixteen-memory)** | Core Worker + SQLite Durable Object memory engine, incremental source-linked Wiki, React console, TypeScript &amp; Python SDKs, Vercel AI SDK 7 adapter, and native MCP for Codex &amp; Claude Code. |
| **[`Release v0.3.0`](https://github.com/Sixteen-Memory/sixteen-memory/releases/tag/v0.3.0)** | Ready-to-install `@sixteen-memory/sdk`, `@sixteen-memory/vercel-ai`, and Python `sixteen-memory` archives with SHA-256 checksums. |

```sh
git clone https://github.com/Sixteen-Memory/sixteen-memory.git
cd sixteen-memory && npm run setup && npm run example:integration
```
