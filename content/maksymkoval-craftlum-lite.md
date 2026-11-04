---
author: maksymkoval
avatarUrl: https://avatars.githubusercontent.com/u/50242673
createdAt: '2026-11-04T00:00:00.000Z'
demoUrl: https://demo.craftlum.com
description: Open-source LLM observability dashboard for AI agents. Trace explorer with URL-synced filters, span waterfall with input/output inspector, latency against SLO and top errors. Built with Next.js 16, shadcn/ui and Tailwind CSS v4.
distribution: open-source
featured: false
githubUrl: https://github.com/maksymkoval/craftlum-lite
lastCommitOnDefaultBranch: '2026-11-02T00:00:00.000Z'
ranking: 0
stars: 0
themeKey: maksymkoval-craftlum-lite
title: Craftlum Lite
category:
  - react
  - nextjs
  - tailwind
  - shadcn-ui
  - radix-ui
  - template
  - admin
---
## Overview
Craftlum Lite is an open-source dashboard template for teams building LLM apps and AI agents. It shows what each agent run did, how long every step took, what it cost and where it failed. Built with Next.js 16 App Router, React 19, shadcn/ui conventions, Tailwind CSS v4 and Recharts, with seeded demo data so it runs without a backend.

## Features
- **Overview** — KPIs with sparklines, latency against an SLO, top errors and the latest run waterfall
- **Briefings** — two or three ranked sentences computed from the data open each screen, with numbered pins that point to the moment on the chart
- **Trace explorer** — search, status, workflow and model filters, sorting and paging kept in the URL, latency histogram with p50 and p95
- **Span waterfall** — nested LLM, tool and retrieval spans positioned by start time, with an input/output inspector
- **Light and dark themes** — tuned separately, with a colorblind-checked chart palette
- **Typed data layer** — swap the seeded mock functions for Langfuse, OpenTelemetry or your own API
- **Static export** — deploy to Vercel, Cloudflare or any static host

## Installation
1. Clone the repository: `git clone https://github.com/maksymkoval/craftlum-lite.git`
2. Install dependencies: `pnpm install`
3. Start the dev server: `pnpm dev`
4. Open http://localhost:3000

## Summary
Craftlum Lite gives AI teams a production-grade starting point for an internal or customer-facing observability dashboard. MIT licensed. A full version with sessions, prompts, evals, datasets, costs and models screens is available at https://craftlum.com.
