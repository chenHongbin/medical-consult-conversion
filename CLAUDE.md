# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **Claude skill repository** containing a single skill:

- **`medical-consult-conversion/`** — Medical/healthcare consultation conversion skill based on 15 years of practical experience from 赖静茹老师.

There is no build system, test suite, package manager, or executable code. The project consists entirely of markdown documentation files.

## Repository Structure

```
.
├── medical-consult-conversion/
│   ├── SKILL.md                    # Main skill entrypoint (module routing table, core formulas, user personas)
│   └── references/
│       ├── scripts.md              # Conversation scripts library
│       ├── mindset.md              # Mindset and energy management
│       ├── followup.md             # Follow-up SOP
│       ├── training.md             # Training system setup
│       ├── ai-empower.md           # AI efficiency enhancement
│       └── wechat-moments.md       # WeChat Moments / private domain operations
└── CLAUDE.md
```

## Architecture

### Module Routing

`medical-consult-conversion/SKILL.md` contains a decision table that maps user intents to reference files:

| User Need | Module | Reference File |
|---|---|---|
| Conversation scripts (any scene) | Scripts library | `references/scripts.md` |
| Low energy / burnout / no motivation | Mindset & energy | `references/mindset.md` |
| Follow-up / client revisit | Follow-up skills | `references/followup.md` |
| Training new hires / team training | Training system | `references/training.md` |
| AI tools / AI-generated scripts | AI empowerment | `references/ai-empower.md` |
| WeChat Moments / private domain | WeChat operations | `references/wechat-moments.md` |

**Always consult the routing table in `SKILL.md` before selecting a reference file.**

### Core Conversion Formula

> **Performance = Effective Conversations × Appointment Conversion Rate × Visit Conversion Rate × Mindset Energy Coefficient**

### User Persona Scenarios

- **First-time contact** — Ice-breaking → needs probing → appointment invitation (use `scripts.md`)
- **Contacted but not yet appointed** — Direct to follow-up SOP (use `followup.md`)
- **Resistant / hesitant user** — Reassurance scripts → value shaping (use `scripts.md` + `mindset.md`)
- **Team manager** — Training (`training.md`) + motivation (`mindset.md` + `scripts.md`) + AI tools (`ai-empower.md`)

## Output Principles

All outputs from this skill should follow the principles defined in `SKILL.md`:

1. **Ready-to-use** — All scripts should be directly copy-pasteable, not abstract theory
2. **Contextualized** — Adapt to specific business scenarios (dental / medical aesthetics / hair transplant / etc.)
3. **Modular composition** — Combine multiple modules based on actual user needs
4. **赖老师 style** — Down-to-earth, high-energy, direct and practical
