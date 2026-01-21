# AGENTS.md

This repository contains skills for building MCP servers with xmcp.

## Repository Structure

- `skills/` - Contains skill packages for xmcp development
  - `tool-design/` - Guide for creating xmcp tools
  - `mcp-server-design/` - Guide for designing MCP servers
  - `resource-design/` - Guide for creating xmcp resources
  - `prompt-design/` - Guide for creating xmcp prompts
  - `widget-design/` - Guide for designing UI widgets

## Skill Format

Each skill follows this structure:
- `SKILL.md` - Main skill file with frontmatter (name, description) and instructions
- `references/` - Supporting documentation loaded on-demand

## Using Skills

Skills are activated based on their description in the frontmatter. The full SKILL.md content loads only after activation.

## Contributing

When adding new skills:
1. Create a directory in `skills/` using kebab-case
2. Add `SKILL.md` with proper frontmatter
3. Keep SKILL.md under 500 lines
4. Use `references/` for detailed documentation
