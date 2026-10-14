# Cursor

Project notes for this workspace.

## About

This is `test-project`: a Node.js web app built with Next.js and TypeScript.

## Tech stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)

## Conventions

- Write all application code in TypeScript. Avoid new `.js` files except where Next.js requires them.
- Prefer the App Router (`app/`) over the Pages Router.
- Use Server Components by default. Add `"use client"` only when browser APIs, local state, or event handlers are needed.
- Keep API routes under `app/api/`.
- Match existing Next.js and TypeScript patterns when adding files.

## How to work in this repo

- Prefer small, focused changes.
- Do not commit unless asked.
