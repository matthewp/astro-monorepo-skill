# Astro Monorepo Skill

An [Agent Skill](https://agentskills.io) for working on the [Astro](https://github.com/withastro/astro) framework monorepo.

## What's included

This skill teaches AI coding agents how to:

- Navigate the Astro monorepo structure
- Use the build system (pnpm + Turbo)
- Run tests (node:test, Playwright E2E)
- Follow coding conventions (Biome/Prettier formatting, linting rules)
- Handle runtime code restrictions
- Create proper pull requests with changesets
- Download StackBlitz reproductions from bug reports

## Installation

```shell
npx skills add matthewp/astro-monorepo-skill
```

## Supported Agents

This skill works with any agent that supports the [Agent Skills specification](https://agentskills.io/specification), including:

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code)
- [OpenCode](https://opencode.ai)
- [Cursor](https://cursor.sh)
- [GitHub Copilot](https://github.com/features/copilot)
- [Cline](https://cline.bot)
- [Windsurf](https://codeium.com/windsurf)
- And [many more](https://skills.sh)

## Usage

Once installed, agents will automatically see this skill and can load it when working on Astro-related tasks. You can also prompt the agent directly:

```
Load the astro-monorepo skill and help me fix this test
```

## License

BSD-3-Clause
