# AI Workflow Failure Review

## Purpose

Review AI-assisted work for repeated behavior failures and convert the useful findings into concrete operating-system improvements.

This skill is for improving how agents work over time. It is not a general project retrospective.

## Context Check

Before using this skill:

- Identify the workflow, project, or time window being reviewed.
- Identify the evidence sources available, such as chat transcripts, PRs, docs, issues, calendar notes, or task records.
- Separate one-off mistakes from repeated patterns.
- Confirm whether the intended output is only a review memo or also proposed edits to an operating system.
- If evidence is thin, state that clearly before making recommendations.

## When To Use

Use this skill when:

- AI assistance repeatedly missed context, over-asked questions, skipped validation, or used the wrong source of truth.
- A project or user wants better agent behavior, not just a corrected output.
- A weekly or milestone review needs to propose changes to prompts, wrappers, skills, templates, or operating rules.

Do not use it for ordinary code review, personal journaling, or generic productivity reflection.

## Inputs

Useful inputs include:

- Recent AI chat summaries or transcripts
- Project wrappers such as `AGENTS.md`
- Relevant skills, templates, or system rules
- Examples of bad outputs or repeated friction
- Any accepted standards for validation, tone, context, or file hygiene

## Workflow

1. **Collect evidence**
   - Gather concrete instances before forming conclusions.
   - Prefer recent, repeated, and high-impact examples.

2. **Classify the failure**
   - AI behavior quality: wrong context, weak validation, verbosity, repeated questions, poor tool use.
   - Workflow alignment: missed cadence, poor handoff, weak follow-through, unclear ownership.
   - Source-of-truth hygiene: stale docs, duplicate instructions, wrong file layer, private/public drift.

3. **Diagnose the cause**
   - Identify whether the issue came from missing instructions, conflicting instructions, weak retrieval, stale context, tool limits, or user-facing process gaps.

4. **Propose the smallest useful fix**
   - Recommend the narrowest durable change that would reduce recurrence.
   - Prefer editing an existing skill, template, wrapper, or system rule over adding a new artifact.

5. **Separate advice from implementation**
   - If the review is advisory, propose changes but do not mutate the operating system.
   - If implementation is explicitly approved, record exactly which files should change.

## Output Structure

Use this structure:

```md
# AI Workflow Failure Review

## Top Findings
- Finding, evidence, why it matters.

## Suggested Changes
- Target layer or file, edit shape, expected behavior improvement.

## Not Worth Changing
- Issues observed but not systemic or severe enough to encode.

## Follow-Up
- Owner, next action, and validation method.
```

## Quality Bar

A good review:

- Leads with findings, not a source-by-source recap.
- Grounds each recommendation in evidence.
- Distinguishes repeated patterns from isolated misses.
- Produces edits that are small enough to adopt.
- Does not turn every annoyance into a new rule.

## Common Failure Modes

- **Overfitting to one bad exchange:** require repetition or unusually high impact.
- **Fixing behavior in the wrong layer:** wrappers handle project context; skills handle reusable workflow; core docs handle durable standards.
- **Generating vague advice:** every suggested change should name the behavior it changes.
- **Silent mutation:** do not implement system changes unless the user explicitly approved them.

