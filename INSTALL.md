# Installing Via Negativa

## Prerequisites

1. **Claude Code** (Anthropic's CLI) installed and working
2. An active Claude subscription
3. macOS or Linux (Windows: use WSL)

## Quick Install (30 seconds)

1. Download this entire folder to your computer
2. Open Terminal
3. Run:

```bash
cd /path/to/via-negativa-method
./install-via-negativa.sh
```

The script copies the skill into `~/.claude/skills/` and the red-team agent into
`~/.claude/agents/`.

## Manual Install

If the script doesn't work, copy the two folders yourself:

```bash
cp -r skills/via-negativa ~/.claude/skills/via-negativa
cp -r agents/via-negativa-redteam ~/.claude/agents/via-negativa-redteam
```

## Install via plugin marketplace (alternative)

```
/plugin marketplace add alexmakarski/via-negativa-method
/plugin install via-negativa
```

## Verify It Works

Restart Claude Code (some versions cache the skill list on startup), open it in any
project, and type:

```
/via-negativa
```

You should see Via Negativa ask what system you want audited. If you see "skill not
found," the files weren't copied to the right location.

## What Gets Installed

| Component | What It Does |
|-----------|-------------|
| `via-negativa` (skill) | The audit. Escalates Quick / Standard / Full automatically. |
| `via-negativa-redteam` (agent) | Isolated critic. Attacks the audit's conclusions on Full audits. |

## How to Use

The target is any system, described in plain words. The skill picks the depth, or
you append `quick`, `standard`, or `full`.

```
/via-negativa our vendor stack
/via-negativa the service-delivery model full
/via-negativa should we hire a second sales rep
/via-negativa this repo quick
```

The quality of the audit tracks the quality of what you feed it. A bare target
gets a thin audit built on assumptions; a target plus real context (how it works,
where it breaks, what people keep trying to add) gets something real.

## Updating

When a new version is released, run `./install-via-negativa.sh` again. It
overwrites the existing skill and agent.

## Troubleshooting

**"Command not found" when running the installer:**
```bash
bash install-via-negativa.sh
```

**Skill doesn't appear in Claude Code:**
```bash
ls ~/.claude/skills/via-negativa
ls ~/.claude/agents/via-negativa-redteam
```
Both should exist. Restart Claude Code after installing; the slash-command menu is
built at startup.
