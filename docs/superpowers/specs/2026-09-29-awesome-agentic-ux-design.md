# Awesome Agentic UX & Generative UI — Design Spec

## Goal

Create a focused, maintainable awesome-list repository for protocols, runtimes, design primitives, UX patterns, and evaluation methods that support agent-native and generative user interfaces.

## Scope

- Curated Markdown content only; no application runtime or package dependencies.
- Six stable taxonomy sections: protocols, runtimes, design systems, UX patterns, benchmarks, and applications/demos.
- A shared distinction between **Text-to-Code** (static code generation) and **Text-to-Hydration** (runtime component selection/data hydration from agent events).
- `llms.txt` as an agent-readable index kept synchronized with the README's canonical entries.
- Contribution and media guidance so future entries remain verifiable and useful.

## Content invariants

1. Every listed resource has one primary taxonomy home and an official or primary-source link.
2. Runtime entries state whether they stream UI, hydrate an allowlisted component, or generate code.
3. UX patterns describe both the user value and the guardrail/approval boundary.
4. Experimental or research claims are labeled as such; no unsupported maturity claims are made.
5. README and `llms.txt` use the same category names and link targets for canonical seed entries.

## Repository shape

```text
README.md
llms.txt
contributing.md
LICENSE
media/README.md
docs/
  concepts.md
  superpowers/specs/...
  superpowers/plans/...
```

## Acceptance criteria

- A reader can discover all six categories from the README table of contents.
- Seed resources from the request are represented with concise, useful descriptions.
- Text-to-Code and Text-to-Hydration are explicitly contrasted with examples.
- `llms.txt` is parseable plain Markdown and gives an AI coding agent enough context to find relevant entries.
- Contribution, media, and licensing guidance are present.
- No generated image/GIF is claimed unless the file or verified URL is present.
