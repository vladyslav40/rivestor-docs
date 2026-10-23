> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Use the Mintlify MCP server, `https://mcp.mintlify.com`, to edit content and settings via MCP
- Use the Mintlify docs MCP server, `https://www.mintlify.com/docs/mcp`, to query information about using Mintlify via MCP

## Terminology

- Product name: Rivestor (an investment platform)
- Refer to the reader as "you"; don't invent fees, limits, regulators, timings, or endpoints. Mark unknown facts with `{/* TODO: confirm */}`

## Style preferences

{/* Add any project-specific style rules below */}

- Visual theme is "dark amethyst": background `#0B0A10`, cards `#120F1A`, borders `#221C30`
- Primary actions are white-on-obsidian or deep plum `#4C1D95`; don't use neon purple (`#7C3AED`, `#6D28D9`)
- No glows: no accent `box-shadow`, `text-shadow`, or blurred gradients

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document customer-facing features and the public API only
- Don't present anything as financial advice
