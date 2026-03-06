<!-- @format -->

<div align="center">

# 🦆 CONDUCKS

**Engineering governance for AI coding agents.**

*The MCP server that encodes senior engineering judgment into mandatory logic patterns.*

[![Version](https://img.shields.io/badge/version-0.6.4-brightgreen.svg?style=flat-square&color=00ff66&labelColor=000)](https://github.com/Conducks/conducks)
[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square&color=00ff66&labelColor=000)](https://opensource.org/licenses/MIT)
[![MCP](https://img.shields.io/badge/protocol-MCP-brightgreen.svg?style=flat-square&color=00ff66&labelColor=000)](https://github.com/modelcontextprotocol)

</div>

---

## What We Build

**CONDUCKS** is an open-source [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol) server.

It acts as an **engineering constitution** for AI coding agents — enforcing planning discipline, execution standards, verification laws, and design rules at the tool level, so agents can't vibe-code their way through your codebase.

---

## The Problem

AI agents by default:

- Skip planning and jump straight to code
- Ship bugs because there's no mandatory verification step
- Lose all context between sessions
- Hardcode values, scatter types, and ignore architecture

---

## The Solution: 4-Phase Governance

```
Plan → Execute → Verify → Remember
```

Each phase is enforced by a dedicated MCP tool that returns mandatory rules agents must follow before proceeding.

---

## 7 Governance Tools

| Tool | Phase | Enforces |
|---|---|---|
| `conducks.plan` | 1 | Codebase analysis, task atomicity, approval gates |
| `conducks.execute` | 2 | Clean code mandates, root-cause fixation, orchestration |
| `conducks.verify` | 3 | Test requirements, diff audits, output validation |
| `conducks.memory` | 4 | Cross-session persistence of critical findings |
| `conducks.documentation` | Standard | `docs/project/` lifecycle parity |
| `conducks.design_style` | Standard | Anti-Vibe Manifesto, Tailwind v4 @theme |
| `conducks.next_blueprint` | Standard | Service isolation, Manager Pattern |

---

## Quick Start

```bash
# Clone
git clone https://github.com/Conducks/conducks

# Build the MCP server
cd conducks/conducks && npm install && npm run build

# Add to your agent config (VS Code, Cursor, Antigravity, Windsurf, Claude Desktop...)
```

```json
{
  "conducks": {
    "command": "node",
    "args": ["/path/to/conducks/dist/index.js"]
  }
}
```

---

## Repositories

| Repo | Description |
|---|---|
| [`conducks`](./conducks/) | The MCP server — 7 tools, 7 resources, governance rules |
| [`website`](./website/) | This documentation site (Next.js 16 + Tailwind v4) |

---

## Works With

VS Code · Cursor · Antigravity · Windsurf · Claude Desktop · Any MCP-compatible client

---

<div align="center">

*Getting your ducks in a row since 2025.*

**[→ conducks.com](https://conducks.com)** · **[→ GitHub](https://github.com/Conducks/conducks)**

</div>
