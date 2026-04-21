# Cognitive Endurance Skill

`cognitive-endurance` is a workplace-oriented skill for helping knowledge workers recover momentum when they are mentally blocked, overloaded, avoidant, or exhausted during real work.

This repository currently contains the `v2` version of the skill, which upgrades the original concept from a cognitive-state helper into a workplace progress system.

## What It Does

The skill is designed to diagnose two things at once:

1. The user's current cognitive state
2. The stage of work where progress is blocked

Instead of only offering emotional support, it routes the interaction toward the lightest intervention that can restore forward motion.

Core workplace routes:

- `clarify`: clarify the real deliverable and unknowns
- `start`: provide a 3-10 minute micro-start
- `decide`: compress too many options into a small decision set
- `communicate`: help draft the message that will unblock work
- `shape`: provide a lightweight outline or scaffold
- `recover`: pause task pressure and create a low-friction re-entry

## Repository Structure

```text
.
├── README.md
└── cognitive-endurance-v2/
    ├── SKILL.md
    ├── TODO.md
    ├── evals/
    │   └── prompts.md
    └── references/
        ├── block-types.md
        ├── deliverable-templates.md
        ├── manager-communication.md
        ├── reentry-protocols.md
        ├── risk-routing.md
        └── workplace-scenarios.md
```

## Main Files

- [Skill definition](./cognitive-endurance-v2/SKILL.md)
- [Reference: workplace scenarios](./cognitive-endurance-v2/references/workplace-scenarios.md)
- [Reference: risk routing](./cognitive-endurance-v2/references/risk-routing.md)
- [Reference: communication templates](./cognitive-endurance-v2/references/manager-communication.md)
- [Evaluation prompts](./cognitive-endurance-v2/evals/prompts.md)

## How To Use In Codex

To use this skill in Codex:

1. Copy the `cognitive-endurance-v2/` folder into your Codex skills directory.
2. Keep the full folder structure, not just `SKILL.md`, because the skill depends on the reference files.
3. Trigger it explicitly in a conversation by naming the skill, or implicitly through phrases like:
   - `我卡住了`
   - `不知道怎么开始`
   - `I am stuck`
   - `I don't know how to reply`

## Current Positioning

This version is optimized for realistic workplace and research scenarios such as:

- ambiguous asks from a manager or collaborator
- deadline pressure
- blank-page writing friction
- meeting aftermath chaos
- stakeholder communication blockage
- true cognitive depletion

## Presentation Asset

The repo currently does not include the presentation HTML deck. The latest presentation file was created locally outside this repository.

## Status

This is an actively iterated skill package and should be treated as a working `v2` rather than a final published release.
