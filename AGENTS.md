# AGENTS.md

## Purpose

This repo is the canonical public library for Matt Hubbard's reusable AI skills.

Use it for showcase-ready skills that can stand on their own outside the private Agent OS while still being usable by Agent OS when this repo is present as a sibling folder.

## Source Of Truth

- Skill files in `skills/` are canonical for this repo.
- Do not duplicate these skills inside `../agent-os` or `../agent-os-core`.
- Agent OS may reference this repo as an optional external skill library.

## Editing Rules

- Keep skills portable, public-safe, and platform-neutral.
- Prefer `SKILL.md` files with clear purpose, context check, workflow, output structure, quality bar, and common failure modes.
- Keep examples sanitized and realistic.
- Do not add private personal context, live priorities, contact details, or sensitive project notes.

