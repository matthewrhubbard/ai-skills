# After Action Review

## Purpose

Help project teams review launches, initiatives, migrations, GTM changes, and incidents after the fact, then turn the learning into a blameless-but-honest memo with concrete system changes.

This skill is for learning from what actually happened. It should name decisions, systems, assumptions, and tradeoffs clearly without scapegoating people.

## Context Check

Before using this skill:

- Identify the event, project, launch, migration, incident, or operating cycle being reviewed.
- Identify the team that owned the work and the leaders who need the readout.
- Gather the original goal, expected outcome, timeline, owners, success metrics, and relevant artifacts.
- Gather what actually happened, using evidence such as metrics, timelines, customer feedback, incident notes, support volume, sales impact, or team notes.
- Separate facts from interpretations.
- Confirm whether the output is for internal team learning, leader review, or both.

## When To Use

Use this skill when:

- A product or company initiative has completed, slipped, missed, or created unexpected consequences.
- A launch, rebrand, migration, GTM change, or second-product effort needs structured learning.
- An incident or operational breakdown needs a blameless review that still produces real changes.
- A team keeps repeating the same lessons without changing the system.

Do not use it for personal performance review, blame assignment, or generic team sentiment discussion.

## Inputs

Useful inputs include:

- Original brief, launch plan, roadmap item, incident report, or project plan
- Expected outcomes and success metrics
- Actual outcomes and observed impact
- Timeline of key events and decisions
- Customer, support, sales, operational, or technical evidence
- What changed during execution
- Prior retrospectives or similar lessons
- Follow-up actions already proposed

## Pattern Set

Use these patterns to sharpen the review. Do not force a pattern when evidence is weak.

### Same Lesson Again

The team has seen this failure before, but prior lessons did not become durable changes.

### Success Theater

The team describes the work as successful because something shipped, while meaningful outcomes, adoption, quality, or operating impact remain weak.

### Ownerless Follow-Up

The review identifies actions, but no one owns them with authority, deadline, and validation method.

### Metric Mirage

The chosen metrics make the work look better or clearer than it really was.

### Heroics Masked the System

The outcome depended on individual effort, escalation, or last-minute intervention instead of a healthy operating system.

### Handoff Failure

The work broke down between teams, phases, or owners, especially where responsibilities changed hands.

### Decision Delay

Late or unclear decisions caused avoidable rework, compression, confusion, or missed timing.

### Support Surprise

The team underestimated downstream load on support, customer success, operations, implementation, or maintenance.

### Partial Rollout Blind Spot

The team treated a limited rollout, pilot, or internal launch as stronger evidence than it actually was.

### Retrospective Theater

The team holds a review, names lessons, and then changes nothing material.

## Workflow

1. **Restate the event**
   - Summarize what was reviewed, who owned it, and why it mattered.
   - Identify the intended audience for the memo.

2. **Compare expected vs actual**
   - State what was supposed to happen.
   - State what actually happened.
   - Call out where the difference matters.

3. **Separate what went well from what went wrong**
   - Preserve strengths worth repeating.
   - Name misses, surprises, and operating breakdowns without blaming individuals.

4. **Explain why it happened**
   - Look for system causes: ownership, decision rights, dependencies, support load, metrics, tooling, process, incentives, staffing, sequencing, and assumptions.
   - Distinguish direct causes from contributing conditions.

5. **Match patterns lightly**
   - Use pattern matches to clarify what kind of learning this is.
   - Avoid turning the AAR into a taxonomy exercise.

6. **Extract lessons**
   - Separate durable lessons from one-off observations.
   - Name what should be repeated, stopped, changed, or watched next time.

7. **Define system changes**
   - Translate lessons into changes to process, ownership, decision rules, tooling, documentation, operating cadence, launch standards, incident practice, or support model.

8. **Create follow-up actions**
   - Every action needs an owner, due date, and validation method.
   - If an action requires leadership decision or resourcing, put it in Leader Notes.

## Output Structure

Use this structure:

```md
# After Action Review Memo

## Event Reviewed
What happened, who owned it, and why it mattered.

## Expected Outcome
What was supposed to happen.

## Actual Outcome
What actually happened, with evidence.

## What Went Well
Strengths and practices worth repeating.

## What Went Wrong
Misses, surprises, and breakdowns without blame.

## Why It Happened
Direct causes, contributing conditions, and system factors.

## Pattern Matches
Light pattern matches and what they reveal.

## Lessons
What the team should repeat, stop, change, or watch next time.

## System Changes
Process, ownership, tooling, decision, metric, cadence, or operating-model changes.

## Follow-Up Actions
| Action | Owner | Due Date | Validation Method |
| --- | --- | --- | --- |

## Leader Notes
Decisions, resources, tradeoffs, or escalations leadership should see.
```

## Quality Bar

A good AAR:

- Answers what was supposed to happen, what happened, why there was a difference, and what will change.
- Is blameless without becoming vague.
- Uses evidence instead of vibes.
- Names system causes and decision points.
- Preserves what went well.
- Converts lessons into owned changes with due dates and validation methods.
- Produces a memo leaders can read and act on.

## Common Failure Modes

- **Blame in disguise:** avoid turning system review into individual criticism.
- **No system change:** lessons without operating changes usually decay.
- **Ownerless follow-up:** action items without owners, dates, and validation are not real.
- **Success theater:** do not let shipping or effort substitute for outcome evidence.
- **Retro sprawl:** keep the memo focused on the event and the changes that matter.
- **Overcorrecting:** do not create heavy process for a one-off issue unless the pattern is likely to recur.

