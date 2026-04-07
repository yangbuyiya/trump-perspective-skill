<div align="center">

# Trump Perspective Skill

> Not a quote pack. A runnable cognitive model for analyzing how Donald Trump negotiates, escalates, frames conflict, and performs in public.

[![Claude Code Skill](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![skills.sh Compatible](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)
[![Chinese README](https://img.shields.io/badge/README-Chinese--first-red)](./README.md)
[![English README](https://img.shields.io/badge/README-English-blue)](./README_EN.md)

A reusable Skill for `Claude Code / skills.sh` that distills Donald Trump's mental models, decision heuristics, rhetorical DNA, and behavior patterns into a usable analysis + roleplay system.

**This repository is not a political endorsement.**  
It is an analysis and simulation artifact built from public materials.

[中文说明](./README.md) · [Quick Start](#quick-start) · [Examples](#examples) · [Capabilities](#capabilities) · [Honest Boundaries](#honest-boundaries)

</div>

---

## At a glance

| Item | Content |
|---|---|
| Positioning | Trump-style analysis + forecasting + role simulation |
| Core assets | `SKILL.md` + `6` research documents |
| Extraction output | `6` mental models + `8` decision heuristics + rhetorical DNA |
| Modes | `Analyst Mode` / `Roleplay Mode` |
| Best topics | tariffs, Iran, NATO, Ukraine, media, loyalty politics, crisis framing |
| Docs | `README.md` for Chinese users, `README_EN.md` for global readers |

---

## Quick start

### 1) Install

Replace the placeholder with your real GitHub repository path after publishing:

```bash
npx skills add <your-org>/trump-perspective
```

### 2) Use in Claude Code

```text
> Analyze the current Middle East situation from Trump's perspective
> Predict Trump's next move on Iran
> How would Trump interpret the Strait of Hormuz crisis?
> Explain the logic behind this Truth Social post
> Switch to Trump's voice and evaluate this tariff negotiation
```

### 3) Mode selection

- Ask “how would he think / what would he do next?” → `Analyst Mode`
- Ask “switch to Trump's voice” → `Roleplay Mode`

---

## Examples

### Example 1: Forecasting Iran

**User:** Predict Trump's next move on Iran.

**Expected answer direction:**
- escalate pressure first
- treat sanctions, military signaling, and public threats as bargaining leverage
- pivot to a de-escalation package if oil, markets, allies, or domestic politics become costly
- never frame a concession as a concession; reframe it as victory

### Example 2: Strait of Hormuz

**User:** How would Trump interpret the recent strait crisis?

**Expected answer direction:**
- not primarily as an international-law problem
- more as `energy prices + market psychology + leverage on Iran + domestic strongman optics`
- the real question is not “whether to fight,” but “how to look strongest without owning a long war”

### Example 3: Role simulation

**User:** Switch to Trump's voice and evaluate this tariff negotiation.

**Expected answer style:**
- short, forceful sentences
- conclusion first, justification second
- heavy use of binary framing: `win / lose`, `strong / weak`, `loyal / disloyal`

---

## Two operating modes

### Analyst Mode

Best for questions like:

- “What is Trump most likely to do next?”
- “Is this statement a threat, an opening bid, or a real commitment?”
- “How does he rank Iran, Ukraine, tariffs, or media conflict?”

Typical output includes:

- the most relevant mental models
- the matching decision heuristics
- scenario probabilities and confidence level
- key uncertainty variables

### Roleplay Mode

Best for questions like:

- “Switch to Trump's voice”
- “If Trump were negotiating this deal, what would he say?”
- “Write a Trump-style response to this crisis”

Typical output includes:

- first-person voice
- Trump-like rhythm, repetition, absolutes, and adversarial framing
- inference from mental models when there is no direct public quote

---

## Capabilities

### 1) Core mental models

This Skill includes `6` recurring frameworks:

- `Everything Is A Deal`
- `Truthful Hyperbole`
- `Unpredictability As Power`
- `Victimhood As Fuel`
- `Zero-Sum Winning`
- `Audience First, Reality Second`

### 2) Decision heuristics

This Skill includes `8` recurring heuristics, such as:

- extreme anchoring
- threat as leverage, not commitment
- concession triggers
- loyalty over competence
- personalize everything
- never concede, redefine victory
- instant counterattack
- the Roy Cohn doctrine in legal conflict

### 3) Rhetorical DNA

Role simulation tries to preserve these traits:

- short sentences
- absolutist and superlative wording
- repetition for emotional force
- nicknames, labels, and focus shifts for narrative control
- signature structures like `Everybody knows`, `A lot of people are saying`, `We'll see what happens`

---

## Why it is stronger than a normal prompt

A normal prompt often imitates surface language only.

This repository models Trump at several layers:

| Layer | What is extracted |
|---|---|
| How he thinks | mental models, worldview, judgment patterns |
| How he acts | decision heuristics, concession triggers, escalation logic |
| How he speaks | rhetorical DNA, rhythm, vocabulary preferences |
| What he resists | values, anti-patterns, aversions |
| Where it fails | honest limitations and uncertainty notes |

That makes it better suited for:

- behavior forecasting
- negotiation simulation
- media and narrative analysis
- style-consistent multi-turn dialogue

---

## Research coverage

The Skill is built from `6` complementary research streams:

1. writings and long-form texts
2. interviews, podcasts, and debates
3. rhetorical and expression patterns
4. external biographies and analytical viewpoints
5. major decisions and crisis handling records
6. life timeline and recent developments

Included research files:

```text
references/research/
├── 01-writings.md
├── 02-conversations.md
├── 03-expression-dna.md
├── 04-external-views.md
├── 05-decisions.md
└── 06-timeline.md
```

This means the repo is not only usable, but also auditable and extensible.

---

## Repository structure

```text
trump-perspective/
├── README.md
├── README_EN.md
├── SKILL.md
└── references/
    └── research/
        ├── 01-writings.md
        ├── 02-conversations.md
        ├── 03-expression-dna.md
        ├── 04-external-views.md
        ├── 05-decisions.md
        └── 06-timeline.md
```

- `SKILL.md` is the actual runnable skill
- `README.md` is optimized for Chinese-speaking users and communities
- `README_EN.md` is optimized for global readers
- `references/research/` provides the evidence trail behind the extraction

---

## Honest boundaries

The value of this repository is **high-quality inference**, not omniscience.

Keep these limits in mind:

1. **Public statements do not equal private intent**
2. **Unpredictability is sometimes strategic, and sometimes genuinely unstable**
3. **Markets, allies, donors, courts, and domestic politics can change outcomes fast**
4. **It is stronger on negotiation, rhetoric, power behavior, and forecasting than on explaining every ideological position**
5. **It is not a real-time intelligence system; conclusions are bounded by the research cutoff**

A perspective skill that never states its limits is usually not trustworthy.

---

## Open-source release checklist

Before publishing globally, you should still:

- replace `<your-org>` with the real repo path
- add your `LICENSE` at the repository root
- keep `README.md`, `README_EN.md`, and `SKILL.md` in sync
- refresh `06-timeline.md` when the operating environment changes materially
- make the non-endorsement statement explicit in your repository description

---

## Disclaimer

This skill does not represent Trump himself, **this is not political support, but an analysis/simulation tool driven by public information**


## Credit

This `trump-perspective` skill was generated with [Nuwa Skill](https://github.com/alchaincyf/nuwa-skill).

If you want to distill more figures, you can use `nuwa-skill` directly.
