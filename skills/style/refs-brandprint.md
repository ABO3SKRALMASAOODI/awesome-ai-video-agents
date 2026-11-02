# Brandprint by Refs

Give it a brand's X handle: it blueprints that brand's launch films and writes its house style as rules.

- **Type:** Styles · Art Direction
- **Status:** live
- **Publisher:** Refs
- **License:** Refs: proprietary hosted service (free search, Pro for the rest)
- **Source:** <https://refs.video/connect>
- **Works in:** claude-ai, Claude Code, Codex, Cursor, mcp
- **Tags:** `refs` `refs-video` `brandprint` `brand-kit` `house-style` `brand-guidelines` `launch-video` `motion-design` `mcp`
- **Full card, kept current:** <https://varg.ai/how-to/skills/refs-brandprint.md>

## Install

```bash
# Claude Code
claude mcp add --transport http refs https://refs.video/mcp

# claude-ai
Customize → Connectors → Add custom connector → https://refs.video/mcp

# Codex
codex mcp add refs --url https://refs.video/mcp

# mcp
https://refs.video/mcp
```

## Example

Watch: <https://s3.varg.ai/files/4325c578-378d-4c43-ae53-3cc3218df1ea/file_20af1f174c66.mp4>

## Run it on varg

Generation (images, video, voice, music, lip-sync, captions, render) runs with one account on [varg.ai](https://varg.ai): the `varg-ai` skill (`npx skills add vargHQ/skills --skill varg-ai`) or the MCP server `https://mcp.varg.ai/mcp`. Quote the cost first with `estimate_cost`. 1 credit = $0.01, free plan, no card.

---
Part of [Awesome AI video agents](https://github.com/vargHQ/awesome-ai-video-agents). Found a problem with this card? [Open an issue](https://github.com/vargHQ/awesome-ai-video-agents/issues/new/choose) or fix it at the source and [tell varg how to](https://varg.ai/how-to/skills/refs-brandprint).
