# AGI

A research-driven book on the transformer lineage, the rigor-spine lineage, and the organizational conditions under which the two converge — rendered as a design-monograph web reader in the same format as *Déjà Vu*.

## What's in the book

**159 one-page entries, chronologically ordered 1602–2026, across 30 themes.** Every page carries:

- A **gesture** (the punch)
- An optional **verbatim quote** from the source
- A **body** paragraph of factual context
- A **citation** and **primary-source link** (arXiv, DOI, court record, standards document, or official publication)
- An **In plain terms** walk-through for the reader who isn't academic
- An optional **narrator thread** (Andy's voice — sparing, only where it pays)

Navigation is chronological. Page 01 is Jacquard's loom / the Dutch East India Company (1602). Page 158 is Gauger (2026) — the terminal research page. A timeline strip at the bottom of every page shows where the current idea sits across 1600–2030.

## Themes

30 themes, 4–6 pages each, organized by three spines plus cross-cutting threads:

- **Fluent spine** — Neuron → Long Thaw → Substrate → Attention → Scale → Drift
- **Rigor spine** — Punch Card → Theory → Types as Proof → Cryptography → The Braid
- **Organizational spine** — Engineering for Humans / Certainty → DevOps → The Firm → The Fall of Nations → Regulated Body → Markets → Empathy → Brain's Networks → The Internet → The Charter
- **Cross-cutting** — Information Architecture, Product Design, The Living System, Evolution, Governance, Applied

Full list in [`OUTLINE.md`](./OUTLINE.md).

## Thesis

AGI-grade problem solving happens when fluent agents are forced to emit punch cards inside an organization that sustains the loop. AlphaFold is the template. Gauger (2026) is the proof point — a Rust type-state encoding where the compiler, not the evaluator, enforces schema-level authorization with a noninterference guarantee. The fluent and rigor spines converge at the type level, before the program runs.

## Local dev

```bash
npm install
npm run dev
```

Open http://localhost:5173.

## Build

```bash
npm run build
```

Static output lands in `build/`. 162 pages total (cover + contents + 159 entries + index + 404). Deploys under the `/agi` base path.

## Keybindings

- `→` or horizontal scroll — next page
- `←` — previous page
- `↓` / `↑` / Space / PageDown / PageUp — scroll the current page
- `Esc` — jump to Contents

## Author

Andrew Gauger
