---
author: mailkite
avatarUrl: https://avatars.githubusercontent.com/u/296139249?v=4
createdAt: '2026-07-15T07:05:01.000Z'
demoUrl: https://saas-startup.mailkite.dev
description: >-
  Next.js 15 SaaS starter with self-contained authentication — no auth vendor
  account required. Google and GitHub OAuth, email/password, Stripe
  subscriptions, team management, and Postgres with Drizzle ORM. Built with
  shadcn/ui and Tailwind CSS v4.
distribution: open-source
featured: false
githubUrl: https://github.com/mailkite/saas-startup
lastCommitOnDefaultBranch: '2026-07-19T13:20:19.000Z'
ranking: 0
stars: 0
themeKey: mailkite-saas-startup
title: MailKite SaaS Starter
category:
  - nextjs
  - react
  - tailwind
  - shadcn-ui
  - drizzle-orm
  - saas
  - dashboard
  - authentication
---

## Overview

MailKite SaaS Starter is an open-source Next.js 15 template for launching a SaaS product. It wires together authentication, Stripe subscriptions, team management, and a dark-first dashboard built with shadcn/ui and Tailwind CSS v4.

Its distinguishing choice is **self-contained authentication**. Unlike most SaaS starters, it does not depend on a hosted auth provider — the OAuth code exchange, password hashing, and session signing all run in your own Next.js server against your own database. There is no Clerk, Auth0, or Supabase account to create before the app runs. Passwords use PBKDF2 via WebCrypto (no native module, so it runs on edge runtimes), and sessions are JWTs signed with `jose`.

## Features

- **Self-contained auth** — Email/password plus Google and GitHub OAuth, implemented in-app with no auth vendor
- **Stripe billing** — Checkout, Customer Portal, webhooks, and full subscription lifecycle handling
- **Teams** — Invite members, manage permissions, shared workspace
- **shadcn/ui components** — Avatar, button, card, dropdown menu, input, label, radio group, extended with gradient cards and animated backgrounds
- **Dark-first UI** — Light/dark toggle plus a color theme picker, no flash on load
- **Postgres + Drizzle ORM** — Type-safe schema, migrations, and seed scripts
- **Turborepo monorepo** — `apps/web` plus a reusable auth package
- **Optional transactional email** — Sends a welcome email when a MailKite API key is present; skips it silently when not, so the template runs with no email provider at all

## Installation

1. Clone the repository: `git clone https://github.com/mailkite/saas-startup`
2. Install dependencies: `pnpm install`
3. Copy `.env.example` to `.env` and set `AUTH_SECRET`, `POSTGRES_URL`, and your Stripe keys
4. Run migrations: `cd apps/web && npx drizzle-kit migrate`
5. Start the dev server: `pnpm run dev` and open http://localhost:3000

One-click deploy to Vercel is available from the repository README.

## Summary

MailKite SaaS Starter targets developers who want a production-shaped SaaS foundation without adding a third-party authentication dependency. Everything needed to run — auth, billing, teams, database — is in the repository and under your control. Built with Next.js 15 App Router, TypeScript, Tailwind CSS v4, shadcn/ui, Drizzle ORM, and Stripe. MIT licensed, with a live demo at https://saas-startup.mailkite.dev.
