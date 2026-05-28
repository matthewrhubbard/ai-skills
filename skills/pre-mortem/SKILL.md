# Pre-Mortem

## Purpose

Help project teams imagine how a plan could fail before commitment, then turn that into a concise memo leaders can act on.

This skill is for improving a plan before launch, not explaining failure after the fact. It should be candid but constructive: direct about weak assumptions and failure modes, focused on mitigations, tradeoffs, and clear leader asks.

## Context Check

Before using this skill:

- Identify the plan, project, launch, migration, or operating bet being tested.
- Identify the intended audience for the final memo, especially the leader or decision-maker.
- Clarify the current commitment level: idea, proposed plan, approved plan, or already in execution.
- Gather the plan's timeline, scope, owners, dependencies, success metrics, and known constraints.
- Separate facts from assumptions.
- If the plan is already committed, frame the output as risk reduction rather than approval advice.

## When To Use

Use this skill when:

- A team is about to commit to a product launch, company initiative, rebrand, migration, GTM shift, technical delivery effort, or operating plan.
- The plan feels plausible but depends on optimistic assumptions.
- A team needs to surface failure modes without turning the discussion into vague anxiety.
- Leaders need a clear view of tradeoffs, mitigations, and decisions required.

Do not use it as a generic risk register after all meaningful decisions have already been locked.

## Inputs

Useful inputs include:

- Project brief, roadmap item, launch plan, or technical plan
- Timeline and milestone assumptions
- Owners and decision-makers
- Dependencies and unresolved decisions
- Success metrics and target outcomes
- Resourcing, support, rollout, migration, and adoption assumptions
- Known risks or prior similar failures

## Scoring Labels

Use simple labels rather than fake precision:

| Label | Values | Use |
| --- | --- | --- |
| Likelihood | Low / Medium / High | How likely the failure mode is if the plan remains unchanged. |
| Impact | Low / Medium / High | How much damage the failure would create. |
| Confidence | Low / Medium / High | How strongly the available evidence supports the assessment. |

## Failure Pattern Library

Use these named patterns as prompts. Do not force a pattern when the evidence is weak.

### Happy-Path Plan

The plan works only if every assumption lands cleanly. It has little room for delay, rework, customer confusion, staffing gaps, or dependency misses.

### Launch-Day Finish Line

The team treats launch as the end of the work. The real risk is what happens after launch: support, adoption, iteration, measurement, enablement, and cleanup.

### Dependency Fog

The plan depends on other teams, vendors, systems, approvals, or customer actions, but those dependencies are vague, ownerless, or not sequenced.

### Ownerless Mitigation

The team names risks and mitigations, but no one owns the mitigation or has authority to make it happen.

### Support Load Surprise

The plan undercounts the future burden on support, customer success, sales, implementation, operations, or engineering maintenance.

### Scope Gravity

The project is likely to attract more requirements as it gets closer to reality. The risk is not initial scope; it is uncontrolled scope growth.

### Timeline Compression

The timeline assumes phases can overlap or shrink without quality, alignment, or adoption costs. Calendar time is being treated as effort time.

### Adoption Assumption

The plan assumes users, customers, sales teams, or internal teams will change behavior because the thing exists.

### Decision Bottleneck

The plan depends on decisions that are not clearly assigned, sequenced, or time-boxed.

### Integration Unknowns

The plan treats systems, processes, teams, or customer workflows as easier to connect than they probably are.

### Rollback Blind Spot

The team has not defined what happens if the launch, migration, change, or rollout needs to pause, reverse, or partially unwind.

### Success Metric Mirage

The plan has metrics, but they do not actually prove the desired outcome or expose early failure.

## Workflow

1. **Restate the plan**
   - Summarize what the team intends to do, by when, and why.
   - Name the leader or decision-maker who needs the risk readout.

2. **Imagine the failure**
   - Write a short future-tense failure story: "It is three to six months later, and this did not work."
   - Make the failure concrete enough to reveal causes.

3. **Identify likely failure modes**
   - List the ways the plan could fail.
   - Focus on causes the team can mitigate before commitment.
   - Score each with Likelihood, Impact, and Confidence.

4. **Match named patterns**
   - Use the pattern library to sharpen the diagnosis.
   - Explain why each pattern fits.

5. **Surface weak assumptions**
   - Identify assumptions about timeline, ownership, adoption, support, dependencies, technical feasibility, migration, decision speed, and capacity.

6. **Define mitigations**
   - For each serious failure mode, name the smallest change that reduces risk.
   - Prefer scope cuts, sequencing changes, owner clarity, dependency checks, rollout changes, and support planning over vague "alignment."

7. **Create leader asks**
   - Convert the pre-mortem into decisions leaders can make.
   - Ask for tradeoffs, scope cuts, timeline changes, resources, decision rights, or explicit risk acceptance.

8. **Set watchpoints**
   - Define early signs that the plan is starting to fail.
   - Use observable signals rather than vibes.

## Output Structure

Use this structure:

```md
# Pre-Mortem Memo

## Plan Being Tested
What the team intends to do, by when, and why.

## Imagined Failure
The future-state story of how this could fail.

## Most Likely Failure Modes
| Failure Mode | Likelihood | Impact | Confidence | Why It Matters |
| --- | --- | --- | --- | --- |

## Named Pattern Matches
Patterns that fit and what they reveal.

## Weak Assumptions
The assumptions most likely to break.

## Mitigations
What to change before commitment.

## Leader Asks
Decisions, tradeoffs, resources, scope changes, or explicit risk acceptance needed from leadership.

## Watchpoints
Early signs that the plan is going off track.

## Revised Confidence
How confident the team should be after mitigations.
```

## Quality Bar

A good pre-mortem:

- Imagines failure concretely, not abstractly.
- Focuses on preventable or reducible risks.
- Names weak assumptions without shaming the team.
- Turns risk into leader-ready decisions and asks.
- Uses simple labels instead of fake precision.
- Improves the plan before commitment.

## Common Failure Modes

- **Generic risk list:** a pre-mortem should tell a failure story and identify causes.
- **No leader ask:** risks that require leadership action should become explicit asks.
- **Ownerless mitigation:** do not name mitigations without owners or decision paths.
- **Only obvious risks:** look for hidden support, adoption, dependency, and operating-model risks.
- **False certainty:** use Confidence labels and state evidence gaps.

