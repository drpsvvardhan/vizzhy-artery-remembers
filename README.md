# Vizzhy — The Artery Remembers · CodexOS Reasoning Trace

Launch site for Vizzhy (launch demo · September 14, 2026 · Austin, Texas).

React 19 + TypeScript + Vite 7 + Tailwind CSS 3.4 + shadcn/ui.

## Structure

- `src/sections/` — hero, library of tellings, console section, clocks/map, launch ledger, footer
- `src/components/` — ArteryCanvas (two-futures artery), AgentConsole (CodexOS Reasoning Trace), Teleprompter, DocPage, ContradictionTeaser, ThreeClocks
- `src/data/` — mainTalk, longTalk (4 chapters), treatise, consoleScripts (synthetic governed traces)
- `src/lib/` — sha256 (dependency-free, canonical JSON sealing), routing (hash routes)
- `public/videos/` — AI teaser films (hero + 4 chapters)

## Develop

```sh
npm install
npm run dev
npm run build
```

All demo input is processed locally in the browser — nothing is transmitted or stored.
