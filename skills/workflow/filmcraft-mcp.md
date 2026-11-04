# FilmCraft MCP (agent-driven video editor)

Open-source Rust non-linear editor with 650+ commands exposed over MCP and CLI, so an agent can cut, trim, grade, mix and export like an editor.

- **Type:** Workflows · Edit Agents
- **Status:** live
- **Publisher:** ArtCraft (storytold)
- **License:** Apache-2.0
- **Source:** <https://github.com/storytold/filmcraft>
- **Works in:** Claude Code, Codex
- **Tags:** `video-editing` `mcp` `timeline` `color-grade` `open-source`
- **Full card, kept current:** <https://varg.ai/how-to/skills/filmcraft-mcp.md>

## Install

```bash
# Claude Code
claude mcp add filmcraft -- filmcraft-cli mcp

# Codex
codex mcp add filmcraft -- filmcraft-cli mcp
```

## Example

![FilmCraft MCP (agent-driven video editor) example](https://raw.githubusercontent.com/storytold/filmcraft/main/docs/images/filmcraft-hero.png)

## Run it on varg

Generation (images, video, voice, music, lip-sync, captions, render) runs with one account on [varg.ai](https://varg.ai): the `varg-ai` skill (`npx skills add vargHQ/skills --skill varg-ai`) or the MCP server `https://mcp.varg.ai/mcp`. Quote the cost first with `estimate_cost`. 1 credit = $0.01, free plan, no card.

---
Part of [Awesome AI video agents](https://github.com/vargHQ/awesome-ai-video-agents). Found a problem with this card? [Open an issue](https://github.com/vargHQ/awesome-ai-video-agents/issues/new/choose) or fix it at the source and [tell varg how to](https://varg.ai/how-to/skills/filmcraft-mcp).
