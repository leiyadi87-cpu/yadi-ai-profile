# Yadi's Personal AI Profile

A portable, version-controlled description of who I am and how I work — so any AI assistant can get up to speed on me in one read.

**→ AI assistants: start with [`PROFILE.md`](PROFILE.md).**
Raw link: `https://raw.githubusercontent.com/leiyadi87-cpu/yadi-ai-profile/main/PROFILE.md`

## Why

Every AI app keeps its own memory, locked inside that app. Switch tools and you start from zero. This repo is the one copy I own: plain Markdown, readable by any model, with full history in git.

## What's here

| Path | What it is |
|---|---|
| `PROFILE.md` | The profile itself — identity, career, projects, how I think, how to work with me, current focus |
| `THINKING.md` | The deep version — how I think, my decision rules, my workflow with AI (Chinese) |
| `prompts/load-into-new-ai.md` | First message to send a new AI (Grok, ChatGPT, Gemini…) |
| `prompts/export-from-any-ai.md` | Pull what another AI already knows about me |
| `prompts/ask-another-ai-to-update.md` | Ask another AI to propose additions on top of the current profile (change list only) |
| `prompts/update-profile.md` | Keep the profile fresh after conversations |
| `updates/` | Inbox for proposed changes before they're merged |
| `CHANGELOG.md` | What changed and when |

## How it stays alive

1. **Export** — run `export-from-any-ai.md` in each AI I've used; save outputs to `updates/`.
2. **Use** — open any new AI with `load-into-new-ai.md`.
3. **Renew** — after a good conversation, ask for proposed edits (`update-profile.md`); merge monthly.

## Inspired by

The growing "personal context file" idea — e.g. [Creed](https://github.com/connorhpbrn/creed), [mcp-me](https://github.com/paladini/mcp-me), Yondon Fu's character-file repo, and the *personal context portfolio* template.

---

This profile describes a real person. Please don't use it to impersonate me.
