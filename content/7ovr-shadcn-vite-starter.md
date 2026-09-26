---
author: 7ovr
avatarUrl: https://avatars.githubusercontent.com/u/331736689?v=4
createdAt: '2026-09-21T20:23:37.000Z'
demoUrl: https://starter.7ovr.com
description: >-
  A free, MIT-licensed Vite and React starter on shadcn/ui and Base UI, set up
  so coding agents follow its patterns, with routing, data fetching, forms and
  tables already wired.
distribution: open-source
featured: false
githubUrl: https://github.com/7ovr/shadcn-vite-starter
lastCommitOnDefaultBranch: '2026-09-26T18:07:17.000Z'
ranking: 0
stars: 1
themeKey: 7ovr-shadcn-vite-starter
title: 7Ovr Starter
category:
  - react
  - vite
  - tailwind
  - base-ui
  - boilerplate
  - admin
---
## Overview
7Ovr Starter is a free, MIT-licensed Vite and React starter built on shadcn/ui and Base UI. It ships a working app instead of a blank page, and it is set up so coding agents follow its existing patterns: `CLAUDE.md` holds every convention, `AGENTS.md` points to it, and vendored skills cover Claude Code, Codex and Cursor.

## Features
- **Built for coding agents:** agents keep one self-contained folder per feature, reuse the same data-fetching patterns, write the test first, keep comments to a minimum, and run lint, type checks, tests and the build before they finish.
- **App shell:** a collapsible sidebar with search, a Ctrl+K command menu, light and dark themes, and a sheet on phones.
- **Data fetching:** TanStack Router loaders prefetch with TanStack Query, the page and page size live in the URL, and each record is cached under its own key.
- **Forms:** TanStack Form with Zod validation, focus on the first invalid field, and errors after the first submit.
- **Tables:** TanStack Table with sorting, filtering and pagination.
- **Design system that enforces itself:** `@shadcn/lint` fails the build on raw colours, arbitrary values and restyled components.
- **Checked on every commit:** Oxlint, oxfmt, strict TypeScript 7, Vitest and a production build run in CI, and Lefthook formats and lints staged files.

## Installation
1. Clone the repository: `git clone https://github.com/7ovr/shadcn-vite-starter`
2. Install dependencies: `pnpm install`
3. Start the dev server: `pnpm dev`
4. Open http://localhost:5173

## Summary
A starter for React SPAs on shadcn/ui and Base UI where the stack is already wired and coding agents have clear conventions to follow, so new features land in the same shape as the existing ones.
