---
title: snapcn
author: snapcndev
avatarUrl: https://avatars.githubusercontent.com/u/308587631?v=4
createdAt: '2026-08-25T00:00:00.000Z'
demoUrl: 'https://snapcn.dev/'
description: >-
  snapcn is a shadcn registry of Remotion components for React video: text
  animations, captions, device mockups, logo stings and full scenes. Install
  with the shadcn CLI and the source is copied into your project, so there is
  no runtime dependency and no version to pin. Every component is written
  against the plain Remotion API, and takes theme and mode props that resolve
  through the same design tokens shadcn's own primitives paint with.
distribution: open-source
githubUrl: 'https://github.com/snapcndev/snapcn'
category:
  - react
  - nextjs
  - tailwind
  - remotion
  - video
  - component-library
---

## Overview

snapcn is for the case where you have shipped something and now need a demo
video for it. Rather than opening an editor, you install components and compose
the video in React.

Install a component the same way you install anything else from a shadcn
registry:

```bash
npx shadcn@latest add @snapcn/text-reveal
```

The source lands in your project. Nothing is added to `package.json`.

## What is in it

- **Text** — reveals, kinetic titles, highlight sweeps, word flips
- **Captions** — karaoke and word-level caption tracks
- **Screens** — phone, laptop and terminal mockups
- **Logos** — assemble, flicker and wordmark stings
- **Scenes** — full compositions built from the primitives above

## Requirements

An existing Remotion project (`npx create-video@latest`) and the shadcn CLI.
MIT licensed.
