# Cognitive Endurance

An AI skill for restoring progress when knowledge work gets mentally stuck.

`cognitive-endurance` began as a way to recognize cognitive friction: brain fog, overload, startup resistance, decision fatigue, and burnout.  
`v2` upgrades that idea into something more useful in real work:

**not just a cognitive-state skill, but a workplace progress skill.**

It does not only ask whether the user is tired or blocked. It asks:

- where the task is blocked in the workflow
- what the smallest visible next move is
- whether the user needs to think, decide, communicate, draft, or recover

## Why This Exists

A lot of knowledge workers are not blocked because they are incapable.

They are blocked because:

- the ask is vague
- the task is too large to start
- there are too many options
- the real blockage is a message to a manager or collaborator
- the deadline is too tight for the scope
- their cognitive battery is simply empty

Most assistants answer questions.

This skill is designed to **restore forward motion**.

## What Changed In v2

The original idea focused on cognitive state recognition and mode switching.

`v2` adds a more realistic operating model for work:

- dual routing by `cognitive state` and `task stage`
- workplace-specific routes such as `communicate` and `shape`
- risk checks for missing decisions, missing information, missing authority, and impossible scope
- low-takeover support levels: `Guide`, `Scaffold`, and `Co-draft`
- reusable templates for manager updates, clarification messages, follow-ups, and fast-start deliverables

## Core Routes

- `clarify`
  Distill a vague ask into a concrete deliverable, unknowns, constraints, and a next move.

- `start`
  Give one visible 3-10 minute action when the user knows the task but cannot begin.

- `decide`
  Compress too many options into 2-3 meaningful choices with clear tradeoffs.

- `communicate`
  Draft the message that will unblock the work: clarify, request input, request a decision, flag a risk, or push back lightly.

- `shape`
  Remove blank-page pressure with a lightweight outline, shell, or draft scaffold.

- `recover`
  Pause task pressure when the user is cognitively depleted, then create a low-friction re-entry.

## Repository Structure

```text
.
├── README.md
├── cognitive-endurance-v2/
│   ├── SKILL.md
│   ├── TODO.md
│   ├── evals/
│   │   └── prompts.md
│   └── references/
│       ├── block-types.md
│       ├── deliverable-templates.md
│       ├── manager-communication.md
│       ├── reentry-protocols.md
│       ├── risk-routing.md
│       └── workplace-scenarios.md
└── presentation/
    └── presentation-jobs-style.html
```

## Main Files

- [Skill definition](./cognitive-endurance-v2/SKILL.md)
- [Workplace scenarios](./cognitive-endurance-v2/references/workplace-scenarios.md)
- [Risk routing](./cognitive-endurance-v2/references/risk-routing.md)
- [Communication templates](./cognitive-endurance-v2/references/manager-communication.md)
- [Evaluation prompts](./cognitive-endurance-v2/evals/prompts.md)
- [Presentation deck](./presentation/presentation-jobs-style.html)

## Example Use Cases

This skill is built for realistic work and research situations such as:

- a manager gives an ambiguous ask
- a PhD student is blocked on how to restart a PDE numerical analysis task
- a writer cannot get past the blank page
- someone is stuck after a chaotic meeting and cannot turn notes into action
- a teammate knows the real next step is to message someone, but cannot bring themselves to send it
- a user needs to scope down and ship a minimum viable version today

## How To Use In Codex

To use this skill in Codex:

1. Copy the full `cognitive-endurance-v2/` folder into your Codex skills directory.
2. Keep the full folder structure, not just `SKILL.md`, because the skill depends on the reference files.
3. Trigger it explicitly by naming the skill, or implicitly with phrases like:
   - `我卡住了`
   - `不知道怎么开始`
   - `不知道怎么跟老板说`
   - `I am stuck`
   - `I don't know how to reply`

## Presentation

The repository includes a landscape HTML presentation:

- [Jobs-style presentation](./presentation/presentation-jobs-style.html)

It presents:

- the original product insight
- why `v1` was not enough for real workplace use
- the `v1 -> v2` upgrade logic
- the new workplace routing model
- a PDE PhD research demo

## Status

This repository is a working `v2` skill package under active iteration, not a final release.
