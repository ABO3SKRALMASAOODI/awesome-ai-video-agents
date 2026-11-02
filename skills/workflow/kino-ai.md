# Kino by Kino AI

Video editor for teams and agents: Claude Code and Codex edit the same timeline over MCP, with footage and review links.

- **Type:** Workflows · Edit Agents
- **Status:** live
- **Publisher:** Kino AI
- **License:** proprietary
- **Source:** <https://kino.ai/docs/working-with-agents>
- **Works in:** Claude Code, Codex, mcp
- **Tags:** `editor` `mcp` `timeline` `collaboration` `footage-search` `review-links` `desktop` `edit-agents` `app`
- **Full card, kept current:** <https://varg.ai/how-to/skills/kino-ai.md>

## Install

```bash
# Claude Code
claude mcp add kino --transport http http://127.0.0.1:45680/mcp --scope user

# Codex
codex mcp add kino --url http://127.0.0.1:45680/mcp
```

## Example

Watch: <https://s3.varg.ai/files/4325c578-378d-4c43-ae53-3cc3218df1ea/file_4ba863e71a5c.mp4>

## Run it on varg

Generation (images, video, voice, music, lip-sync, captions, render) runs with one account on [varg.ai](https://varg.ai): the `varg-ai` skill (`npx skills add vargHQ/skills --skill varg-ai`) or the MCP server `https://mcp.varg.ai/mcp`. Quote the cost first with `estimate_cost`. 1 credit = $0.01, free plan, no card.

---
Part of [Awesome AI video agents](https://github.com/vargHQ/awesome-ai-video-agents). Found a problem with this card? [Open an issue](https://github.com/vargHQ/awesome-ai-video-agents/issues/new/choose) or fix it at the source and [tell varg how to](https://varg.ai/how-to/skills/kino-ai).
