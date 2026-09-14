# Claude-Code-Mastery
A complete practical guide to learning Claude Code by building an AI-Powered company from scratch.

## MCP Servers

This project has the [prompts.chat](https://prompts.chat) MCP server configured in `.mcp.json`, giving Claude Code access to search and use thousands of community AI prompts.

Claude Code will prompt you to approve this project-scoped server the first time you open the repo. To add it manually in another project:

```sh
claude mcp add --transport http prompts-chat https://prompts.chat/api/mcp
```
