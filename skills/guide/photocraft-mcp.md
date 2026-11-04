# PhotoCraft MCP (agent-driven photo editor)

Open-source Rust photo editor (PSD layers, masks, adjustment layers) whose 500+ commands an agent can run over MCP or CLI, e.g. batch-grade a folder of images.

- **Type:** Guides · Image
- **Status:** live
- **Publisher:** ArtCraft (storytold)
- **License:** Apache-2.0
- **Source:** <https://github.com/storytold/photocraft>
- **Works in:** Claude Code, Codex
- **Tags:** `photo-editing` `mcp` `layers` `psd` `open-source`
- **Full card, kept current:** <https://varg.ai/how-to/skills/photocraft-mcp.md>

## Install

```bash
# Claude Code
claude mcp add photocraft -- photocraft-cli mcp

# Codex
codex mcp add photocraft -- photocraft-cli mcp
```

## Example

![PhotoCraft MCP (agent-driven photo editor) example](https://raw.githubusercontent.com/storytold/photocraft/main/docs/images/photocraft-demo.jpg)

## Run it on varg

Generation (images, video, voice, music, lip-sync, captions, render) runs with one account on [varg.ai](https://varg.ai): the `varg-ai` skill (`npx skills add vargHQ/skills --skill varg-ai`) or the MCP server `https://mcp.varg.ai/mcp`. Quote the cost first with `estimate_cost`. 1 credit = $0.01, free plan, no card.

---
Part of [Awesome AI video agents](https://github.com/vargHQ/awesome-ai-video-agents). Found a problem with this card? [Open an issue](https://github.com/vargHQ/awesome-ai-video-agents/issues/new/choose) or fix it at the source and [tell varg how to](https://varg.ai/how-to/skills/photocraft-mcp).
