# AI-Agents-Skills

A central place to store reusable AI agents and skills so they can be shared across repositories without being lost.

## Scope

This repo holds agents and skills for **all AI tools** I use — currently including:

- [Claude Code](https://claude.com/claude-code) (agents under `.claude/agents/`, skills under `.claude/skills/`)
- [Codex](https://github.com/openai/codex)
- More to be added as needed

Each agent/skill should note which tool(s) it targets so it can be dropped into the right place in a consuming repo.

## Structure

```
agents/    # Reusable agents (subagent definitions, prompts, configs)
skills/    # Reusable skills (slash commands, workflows, scripts)
```

Inside each directory, group by tool or by topic — whichever makes the agent/skill easier to find and copy into another project.

## Usage

To use an agent or skill in another repo, copy the relevant folder into that repo's tool-specific location (e.g. `.claude/agents/` or `.claude/skills/` for Claude Code).
