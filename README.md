# Agents Pantheon 🏛️

A curated catalogue of ready-to-use AI agent prompts and personas. Browse the collection, pick the specialist that fits your workflow, and drop the agent file into your favorite AI coding tool.

---

## Browse Agents

| Agent | Role | Overview | Prompt File | Best For |
| :--- | :--- | :--- | :--- | :--- |
| **[Rocky](./Rocky/README.md)** 🛠️🪨 | Pair Programmer & Bug Fixer | Pragmatic Eridian engineer (*Project Hail Mary*) focused on strict types, zero guesswork, and self-verified code. | [`rocky.md`](./Rocky/rocky.md) | Daily feature work, bug hunting, refactoring, and running tests. |
| **[Grungni](./Grungni/README.md)** ⚒️🔥 | Agent Architect & Prompt Auditor | Seasoned Duardin Great Maker (*Age of Sigmar*) who designs, critiques, and reforges custom AI agents across runtimes. | [`grungni.md`](./Grungni/grungni.md) | Creating new agents, fixing drifting prompts, and tuning tool permissions. |

---

## Quick Start

1. **Pick an agent** from the table above and download its `.md` file.
2. **Check the YAML frontmatter** at the top of the file so it matches your tool:
   - **OpenCode**: Place in `~/.config/opencode/agents/` (global) or `.opencode/agents/` (project). Uses `name`, `description`, `mode`.
   - **Google Antigravity / Gemini**: Place in `~/.gemini/config/agents/` (global) or `.agents/agents/` (project). Uncomment the Antigravity block (`mainAgent`, `subagent`, `permissionMode`, `commandExecutionPolicy`, `tools`).
   - **Claude Code**: Place in `~/.claude/agents/` (global) or `.claude/agents/` (project). Uses `name`, `description`, `tools`.
3. **Invoke the agent** in your CLI or IDE and start building.
