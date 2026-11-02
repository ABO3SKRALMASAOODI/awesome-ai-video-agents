# Starter kit by Refs

Rebuild a Refs blueprint as your own film in Remotion or HTML: frame-exact timing, motion blur, master, check.

- **Type:** Guides · Launch
- **Status:** live
- **Publisher:** Refs
- **License:** Refs: free download, no license file in the ZIP
- **Source:** <https://refs.video/connect>
- **Works in:** claude-ai, Claude Code, Codex, Cursor, mcp
- **Tags:** `refs` `refs-video` `starter-kit` `remotion` `html-to-video` `playwright` `motion-blur` `loudness` `ffmpeg` `timeline` `launch-video` `code2video`
- **Full card, kept current:** <https://varg.ai/how-to/skills/refs-starter-kit.md>

## Install

```bash
# Claude Code
curl -fsSL -o /tmp/refs-starter.zip https://refs.video/starter.zip && unzip -oq /tmp/refs-starter.zip -d . && cd refs-starter && claude mcp add --transport http refs https://refs.video/mcp

# Codex
curl -fsSL -o /tmp/refs-starter.zip https://refs.video/starter.zip && unzip -oq /tmp/refs-starter.zip -d . && cd refs-starter && codex mcp add refs --url https://refs.video/mcp

# mcp
https://refs.video/mcp
```

## Example

Watch: <https://s3.varg.ai/files/4325c578-378d-4c43-ae53-3cc3218df1ea/file_e49f74b26ed1.mp4>

## Run it on varg

Generation (images, video, voice, music, lip-sync, captions, render) runs with one account on [varg.ai](https://varg.ai): the `varg-ai` skill (`npx skills add vargHQ/skills --skill varg-ai`) or the MCP server `https://mcp.varg.ai/mcp`. Quote the cost first with `estimate_cost`. 1 credit = $0.01, free plan, no card.

---
Part of [Awesome AI video agents](https://github.com/vargHQ/awesome-ai-video-agents). Found a problem with this card? [Open an issue](https://github.com/vargHQ/awesome-ai-video-agents/issues/new/choose) or fix it at the source and [tell varg how to](https://varg.ai/how-to/skills/refs-starter-kit).
