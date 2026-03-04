# Multi-Agent Workflows — A Deep Dive

**UID:** `BrendanJamesLynskey/MultiAgent_Workflows_guide`

A comprehensive, interactive guide to how AI agents coordinate, delegate, and execute — from the fundamental agent loop to production multi-agent orchestration.

**[View the live guide →](https://brendanjameslynskey.github.io/OpenClaw_Guide/)**

## Overview

This single-page interactive reference covers the full landscape of multi-agent AI systems, with real-world examples from **LangGraph** and the **OpenAI Agents SDK**. It is designed as an educational resource for engineers looking to understand and implement agentic architectures.

## Topics Covered

- **Fundamentals** — What agents, tools, handoffs, guardrails, tracing, and sessions are
- **The Agent Loop** — The universal ReAct loop (reason → act → observe → loop) that underpins every agent framework
- **Single → Multi-Agent** — When and why to split a single agent into specialised agents (routing complexity, knowledge separation, action isolation, review & policy)
- **Orchestration Patterns** — Manager/hierarchical, decentralised handoffs, chaining, and parallel execution
- **Handoffs in Detail** — Internal mechanics of control transfer between agents, with OpenAI Agents SDK code examples
- **Guardrails** — Input, output, and tool-level validation with tripwire-based halting
- **LangGraph** — Graph-based orchestration using StateGraph, nodes, conditional edges, and cycles (supervisor, collaboration, hierarchical teams, reflection, scatter-gather patterns)
- **OpenAI Agents SDK** — Code-first framework covering agents, handoffs, guardrails, sessions, tracing, function tools, and MCP servers
- **Tracing & Debugging** — Observability across agent runs
- **Production Checklist** — Deployment considerations for real-world multi-agent systems

## Tech Stack

The guide is a self-contained HTML page with inline CSS and JavaScript — no build step or dependencies required.

## Usage

Clone the repo and open `index.html` in a browser, or visit the [GitHub Pages deployment](https://brendanjameslynskey.github.io/MultiAgent_Workflows_guide/).

```bash
git clone https://github.com/BrendanJamesLynskey/MultiAgent_Workflows_guide.git
cd MultiAgent_Workflows_guide
open index.html
```

## Built With

This guide was built with the assistance of **Claude** (Anthropic).

## Author

**Brendan Lynskey** — [GitHub](https://github.com/BrendanJamesLynskey)

## Licence

This project is open source. See the repository for details.
