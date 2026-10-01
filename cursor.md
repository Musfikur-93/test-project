# Cursor

Project guidance for Cursor agents working in this repository.

## Project

This is a **Node.js** app written in **TypeScript**, using **Next.js**.

Keep changes small, match existing style, and only edit files needed for the task.

## Tech stack

- Runtime: Node.js
- Language: TypeScript (strict; avoid `any` unless there is a clear reason)
- Framework: Next.js (App Router unless the repo already uses Pages Router)
- Package manager: follow whatever lockfile exists (`package-lock.json`, `pnpm-lock.yaml`, or `yarn.lock`)

## Conventions

- Prefer TypeScript types and Next.js patterns already in the repo.
- Use Server Components by default; add `"use client"` only when the component needs browser APIs, state, or event handlers.
- Colocate route UI in `app/` (or `src/app/` if that is the project layout).
- Prefer clear, readable code over clever shortcuts.
- Do not add docs, comments, or extra files unless they are requested.
- Do not commit unless the user asks for a commit.

## Agent notes

- The user's name is Md. Role: software engineer.
- Work directly in code: create, debug, and iterate.
