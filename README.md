# Latenode Documentation

This repository is a public mirror of the [Latenode](https://latenode.com) documentation content, automatically synced from the private source repo on every push to `main`.

**Live docs site:** [documentation.latenode.com](https://documentation.latenode.com)

## Repository structure

```
docs/                     All documentation content
├── get-started/          Introduction and quickstarts
├── visual-builder/       Visual workflow builder guides
├── ai-agents/            AI agents and LLM integration
├── mcp/                  MCP (Model Context Protocol) nodes
├── databases/            Database and RAG database docs
├── integrations/         App nodes, core nodes, authorizations
├── account-management/   Plans, billing, workspace settings
├── white-label/          White-label and embedded SDK
├── changelog/            Product changelog
└── legal/                Privacy, DPA, subprocessors
```

Each directory contains:
- `.mdx` files — documentation pages written in MDX (Markdown + React components)
- `meta.json` — defines sidebar navigation order and section labels for that directory

## For LLMs and tooling

The full rendered documentation is also available as plain text via the API:

- **All pages index:** `https://documentation.latenode.com/api/structure`
- **Single page as plain text:** `https://documentation.latenode.com/api/page-markdown?slug=<page-slug>`

## About this mirror

This repo is **read-only**. Do not open pull requests or push changes directly — they will be overwritten on the next sync. To contribute, contact the Latenode team.

The docs site is built with [Next.js](https://nextjs.org) and [Fumadocs](https://fumadocs.vercel.app).
