# test-project

A Node.js app in TypeScript, built with Next.js.

The repo is still in early setup. The intended stack is below; Next.js and TypeScript have not been scaffolded yet.

## Tech stack

- **Runtime:** Node.js
- **Language:** TypeScript
- **Framework:** Next.js (App Router)
- **Package manager:** npm

## Prerequisites

- Node.js 18 or later
- npm (comes with Node.js)

## Getting started

```bash
npm install
```

There is no app entry or `dev` script yet. After Next.js is added, typical commands will be:

```bash
npm run dev      # local development
npm run build    # production build
npm run start    # run the production build
```

## Project layout

```
.
├── cursor.md          # guidance for Cursor agents
├── package.json
└── package-lock.json
```

Environment variables should go in a `.env` file (loaded with `dotenv` once the app is wired up). Do not commit secrets.

## License

ISC
