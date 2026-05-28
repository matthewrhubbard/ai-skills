# AI Skills

Public, reusable AI skills for judgment, learning, execution, and review.

This repo is the canonical home for showcase-ready skills that can be used independently or referenced by a sibling Agent OS repo. It is intentionally separate from Agent OS so the portfolio can stand on its own on GitHub.

## Skills

| Skill | What it does |
| --- | --- |
| [`ai-workflow-failure-review`](skills/ai-workflow-failure-review/SKILL.md) | Reviews AI-assisted work for repeated behavior failures and turns them into system improvements. |
| [`decision-monitoring`](skills/decision-monitoring/SKILL.md) | Converts decisions into warning signs, trigger points, review cadences, and retrospective learning. |
| [`learning-loop-designer`](skills/learning-loop-designer/SKILL.md) | Designs microlearning loops with practice, feedback, spaced review, and application. |
| [`career-signal-router`](skills/career-signal-router/SKILL.md) | Routes career activity into no-regrets actions, option-preserving bets, portfolio assets, and decision gates. |
| [`treat-the-disease-not-the-symptom`](skills/treat-the-disease-not-the-symptom/SKILL.md) | Helps startup leaders diagnose the deeper operating disease behind visible company symptoms. |
| [`pre-mortem`](skills/pre-mortem/SKILL.md) | Helps project teams imagine failure before commitment and turn risks into leader-ready asks. |

## Repo Structure

```text
skills/
  <skill-slug>/SKILL.md
examples/
  <skill-slug>/README.md
evaluations/
  README.md
```

## Relationship To Agent OS

Agent OS can reference this repo as an optional sibling library at `../ai-skills`.

- If this repo is present, agents may use skills from `../ai-skills/skills/`.
- If this repo is absent, Agent OS should still work normally.
- Local Agent OS skills override external skills when names conflict.
- This repo does not depend on Agent OS to be useful.

## Skill Standard

Each skill should include:

- Purpose
- Context check
- When to use
- Inputs
- Workflow
- Output structure
- Quality bar
- Common failure modes
