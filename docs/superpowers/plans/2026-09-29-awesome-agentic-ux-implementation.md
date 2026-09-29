# Awesome Agentic UX & Generative UI Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Build a curated repository that makes Agentic UX and Generative UI resources discoverable, comparable, and safe to extend.

**Architecture:** Markdown-first repository with `README.md` as the human-facing index, `llms.txt` as the agent-facing index, and focused supporting documents for concepts, contributions, media, and licensing. Canonical taxonomy and terminology are defined once and repeated consistently across the two indexes.

**Tech Stack:** Markdown, HTTPS links, Git.

**Spec:** `docs/superpowers/specs/2026-09-29-awesome-agentic-ux-design.md`

## Global Constraints

- Keep the six taxonomy names stable across README, `llms.txt`, and supporting docs.
- Use primary/official links and label research or experimental projects accurately.
- Preserve the Text-to-Code versus Text-to-Hydration distinction.
- Do not claim demo media exists unless the file or verified URL is present.

### Task 1: Create the human-facing index

**Files:**
- Create: `README.md`

- [ ] Write the six-section table of contents, seed entries, comparison table, and application/demo section.
- [ ] Add maintainer-friendly entry conventions and link all canonical seed resources.

### Task 2: Create the agent-facing index and concept notes

**Files:**
- Create: `llms.txt`
- Create: `docs/concepts.md`

- [ ] Mirror canonical categories and links in `llms.txt` using compact, retrieval-friendly bullets.
- [ ] Explain protocol flow, allowlists, widget registries, spatial guardrails, and staged commits in `docs/concepts.md`.

### Task 3: Add repository governance and media rules

**Files:**
- Create: `contributing.md`
- Create: `media/README.md`
- Create: `LICENSE`

- [ ] Define entry quality checks, source requirements, categorization rules, media rules, and CC0 licensing.

### Task 4: Review and validate the artifact

**Files:**
- Review: `README.md`, `llms.txt`, `docs/concepts.md`, `contributing.md`, `media/README.md`

- [ ] Check heading anchors, category names, duplicated links, unfinished text, and unsupported claims.
