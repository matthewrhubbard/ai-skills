# Decision Monitoring

## Purpose

Turn an important decision into a monitored bet with warning signs, trigger points, review cadence, and retrospective learning.

This skill helps after or near the end of decision-making. It keeps a decision alive without re-litigating it every week.

## Context Check

Before using this skill:

- Identify the decision, owner, date, and time horizon.
- Clarify whether the decision has already been made or is pending.
- Identify the success criteria and the main risks.
- Check whether the decision is reversible, partially reversible, or hard to reverse.
- State any assumptions that are not yet supported by evidence.

## When To Use

Use this skill when:

- A decision has meaningful uncertainty, cost, time, reputation, or opportunity tradeoffs.
- The user wants to avoid confusing outcome quality with decision quality.
- A plan needs early warning signs and trigger points before execution.
- A past decision needs a structured retrospective.

Do not use it for small, reversible choices where a simple note is enough.

## Inputs

Useful inputs include:

- Decision memo or summary
- Options considered
- Success criteria
- Risk list or pre-mortem
- Relevant dates, budgets, constraints, or milestones
- Known leading indicators

## Workflow

1. **Frame the decision**
   - State what was decided, why it mattered, and what success should look like.

2. **Record the bet**
   - Capture the expected case, upside case, downside case, and key assumptions.
   - Mark confidence as high, medium, or low with a short reason.

3. **Define warning signs**
   - Identify the earliest observable signs that the decision is going off track.
   - Prefer leading indicators over lagging results.

4. **Set trigger points**
   - Define the threshold that requires action, escalation, adjustment, or reversal.
   - Avoid vague triggers such as "if it feels bad."

5. **Choose review cadence**
   - Match cadence to reversibility and speed of feedback.
   - Use shorter cadence for expensive, fast-moving, or hard-to-reverse decisions.

6. **Plan the retrospective**
   - Set a future review date.
   - Record what evidence would prove the decision was good, bad, lucky, or unlucky.

## Output Structure

Use this structure:

```md
# Decision Monitoring Plan

## Decision
- What was decided, owner, date, time horizon.

## Success Criteria
- What needs to be true for this to have worked.

## Assumptions
- Assumption, confidence, how it will be tested.

## Warning Signs And Triggers
| Risk | Early Warning Sign | Trigger Point | Response |
| --- | --- | --- | --- |

## Review Cadence
- When to review and what to inspect.

## Retrospective Questions
- What happened?
- Which assumptions were right or wrong?
- Was the decision good, bad, lucky, or unlucky?
- What should change next time?
```

## Quality Bar

A good monitoring plan:

- Makes uncertainty visible without becoming paralyzing.
- Uses observable indicators and concrete thresholds.
- Separates decision quality from outcome quality.
- Includes a review date and a clear action path.

## Common Failure Modes

- **No trigger threshold:** warning signs without thresholds rarely change behavior.
- **Only lagging indicators:** by the time they appear, the decision may be expensive to change.
- **Over-monitoring:** not every decision deserves a dashboard.
- **Retrospective drift:** record the original assumptions before outcomes are known.

