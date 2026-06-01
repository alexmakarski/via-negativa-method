# Via Negativa v1.0.0

**A systems audit method that improves any system through subtraction before addition.**

Most systems do not fail because they lack ideas. They fail because they keep
accumulating things that should have been removed: more features, more tools, more
meetings, more vendors, more dependencies, more complexity. Via Negativa reverses
that process. It asks one question of any system you point it at:

> What should stop existing so the system becomes harder to kill?

Point it at a business, a product, a codebase, a workflow, a roadmap, an
architecture, a process, or a single decision. It tells you what to remove, what
creates fragility, what threatens survival, and what you should not add, before any
growth or new tooling is on the table.

## How it works

One skill, three depths. It picks the lightest depth that fits, or you name it.

```
Quick     5 sections, fast read, no setup
Standard  layers 1-3, meaningful context
Full      all 20 sections + scorecard + isolated red-team critic
```

On a Full audit, an isolated red-team agent attacks the audit's own conclusions
before the action plan is written: it hunts for removals that would backfire,
hidden dependencies, and survivability traded away for efficiency. It runs in a
separate context, so it grades the work with fresh eyes, not the bias of having
helped produce it.

Every audit, at any depth, closes by answering five things plainly: what to remove
first, what creates the most fragility, what threatens survival, what not to add,
and what to do next.

## The spine

Five principles drive everything. The 20 sections are instruments that serve them.

1. Remove Before Add
2. Fragility First
3. Incentives Explain Behavior
4. Optionality Matters
5. Survival Before Growth

## What's inside

- 1 skill that installs into Claude Code
- 3 references (the 20-section framework, the 7-axis scorecard, the intake worksheet)
- 1 isolated red-team critic agent

## Install

```bash
./install-via-negativa.sh
```

Or see [INSTALL.md](INSTALL.md) for details and manual install.

## Quick start

Open Claude Code in any project and run:

```
/via-negativa our client onboarding process
/via-negativa should we add a second ad platform
/via-negativa this codebase full
```

The target is whatever system you want audited, described in plain words. The more
context you give it, the sharper the audit.

## The method

The full framework, all 20 sections across 6 layers, is documented in
[ViaNegativa-Method.md](ViaNegativa-Method.md).

## Priority hierarchy

When recommendations conflict, Via Negativa always resolves in this order:

1. Prevent Ruin
2. Reduce Fragility
3. Improve Incentives
4. Improve Quality
5. Reduce Complexity
6. Improve Efficiency
7. Pursue Growth

## Intellectual lineage

Via Negativa operationalizes ideas drawn largely from Nassim Nicholas Taleb's
Incerto (Antifragile, Skin in the Game): via negativa, antifragility, optionality,
tail risk, the primacy of avoiding ruin, and skin in the game. It is an original
synthesis that turns those principles into a repeatable audit, not Taleb's work and
no claim to represent it. See [ViaNegativa-Method.md](ViaNegativa-Method.md) for
the full note.

## License

MIT. See [LICENSE](LICENSE).
