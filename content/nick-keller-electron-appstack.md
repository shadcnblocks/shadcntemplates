---
title: Electron AppStack
author: nick-keller
avatarUrl: https://avatars.githubusercontent.com/u/2682443?v=4
createdAt: '2026-10-21T15:48:46.000Z'
demoUrl: 'https://electron-appstack.com'
description: >-
  Free Electron desktop app boilerplate with shadcn/ui, React 19, Tailwind CSS
  v4, typed IPC with tRPC, SQLite with Drizzle, auto update, signed releases
  and license keys.
distribution: premium
price: 0
affiliateUrl: 'https://electron-appstack.com'
githubUrl: 'https://github.com/nick-keller/electron-appstack'
themeKey: nick-keller-electron-appstack
category:
  - react
  - tailwind
  - shadcn-ui
  - radix-ui
  - boilerplate
---

## Overview
Electron AppStack is a free, production-ready boilerplate for building and selling desktop apps with Electron and shadcn/ui. The renderer uses React 19, shadcn/ui and Tailwind CSS v4 with system, light and dark themes, and everything a real desktop app needs is already wired and documented: typed IPC, a local database, auto update, code signing and license keys. Copy the template once with degit and every line of code is yours.

It is free and source-available: you can use it to build and sell commercial apps, but not resell it as a starter kit.

## Features
- shadcn/ui and Tailwind CSS v4 with system, light and dark themes
- React 19, TypeScript, TanStack Router and TanStack Query
- Typed IPC between renderer and main process with tRPC and zod
- SQLite with Drizzle ORM and migrations applied on startup
- Auto update with electron-updater
- Signed and notarized releases for macOS, Windows and Linux with GitHub Actions
- License keys and payments with Stripe
- V8 bytecode source protection, Electron fuses, sandboxed renderer and strict CSP
- Biome, Vitest and i18next with typed keys
- 16 guides from the first run to selling your app

## Installation
```bash
npx degit nick-keller/electron-appstack/template my-app
```
