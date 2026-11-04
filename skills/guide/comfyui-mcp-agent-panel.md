# comfyui-mcp + ComfyUI Agent Panel

Local-first, agent-native control plane for ComfyUI: an MCP server (38 tools) and a sidebar agent that generates images, video and audio, authors and runs workf

- **Type:** Guides · Tooling
- **Status:** live
- **Publisher:** artokun
- **License:** MIT
- **Source:** <https://github.com/artokun/comfyui-mcp>
- **Works in:** Claude Code
- **Tags:** `comfyui` `mcp` `workflows` `local-models` `agent-panel`
- **Full card, kept current:** <https://varg.ai/how-to/skills/comfyui-mcp-agent-panel.md>

## Install

```bash
# Claude Code
/plugin marketplace add artokun/comfyui-mcp
/plugin install comfy
```

## Example

![comfyui-mcp + ComfyUI Agent Panel example](https://raw.githubusercontent.com/artokun/comfyui-mcp/main/docs/images/demo-poster.jpg)

## Run it on varg

Generation (images, video, voice, music, lip-sync, captions, render) runs with one account on [varg.ai](https://varg.ai): the `varg-ai` skill (`npx skills add vargHQ/skills --skill varg-ai`) or the MCP server `https://mcp.varg.ai/mcp`. Quote the cost first with `estimate_cost`. 1 credit = $0.01, free plan, no card.

---
Part of [Awesome AI video agents](https://github.com/vargHQ/awesome-ai-video-agents). Found a problem with this card? [Open an issue](https://github.com/vargHQ/awesome-ai-video-agents/issues/new/choose) or fix it at the source and [tell varg how to](https://varg.ai/how-to/skills/comfyui-mcp-agent-panel).
