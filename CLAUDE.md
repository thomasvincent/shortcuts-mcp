# CLAUDE.md

Lets AI assistants run any Apple Shortcut on macOS. A thin MCP wrapper around the `shortcuts` CLI.

## Stack

- TypeScript, Node.js, ES modules
- MCP SDK

## Build

```sh
npm run build  # tsc
npm start      # node dist/index.js
npm run dev    # tsc --watch
```

## Repo Details

- Source in `src/index.ts`
- No test/lint/format tooling set up yet
- Build runs automatically on `npm install` via the `prepare` hook
