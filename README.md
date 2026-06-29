# MaikoLabs Devil's Advocate Skill

A reusable pressure-test skill for Codex and Claude Code. It challenges ideas,
offers, products, scripts, automations, and strategy before time gets spent
building the wrong thing.

The canonical skill is `devils-advocate`. The optional `roast` alias routes into
the same workflow in high-intensity mode.

## What It Does

- Pressure-tests the idea through five perspectives.
- Separates the bull case from the red-team case.
- Checks first-principles logic, customer resistance, and real-world evidence.
- Forces one verdict: `GO`, `RESHAPE`, or `KILL`.
- Ends with the cheapest 48-hour test to de-risk the idea before building.

## Install For Codex

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/justmaiko12/maikolabs-devils-advocate-skill ~/.codex/skills/devils-advocate
mkdir -p ~/.codex/skills/roast
cp ~/.codex/skills/devils-advocate/aliases/roast/SKILL.md ~/.codex/skills/roast/SKILL.md
```

Restart Codex after installing.

## Install For Claude Code

```bash
mkdir -p ~/.claude/skills
git clone https://github.com/justmaiko12/maikolabs-devils-advocate-skill ~/.claude/skills/devils-advocate
mkdir -p ~/.claude/skills/roast
cp ~/.claude/skills/devils-advocate/aliases/roast/SKILL.md ~/.claude/skills/roast/SKILL.md
```

Restart Claude Code after installing.

## Usage

```text
Use devils-advocate on this: [idea]
```

```text
/roast [idea]
```

```text
Use devils-advocate in roast mode on this: [idea]
```

Use `devils-advocate` for a regular pressure test. Use `roast` when you want the
same framework with sharper delivery.
