# 从其他 AI 里"挖出"它对我的了解

用途：把散落在 ChatGPT、Claude、Gemini、豆包、Kimi 等里的记忆和聊天积累，抽出来合并进 `PROFILE.md`。

**用法：** 在那个 AI 里开一个新对话，粘贴下面的 prompt → 把输出存到 `updates/YYYY-MM-DD-<ai名字>.md` → 再用 `update-profile.md` 合并。

> 提醒：AI 的输出里会混进它"猜"的东西。合并前自己过一遍，只留你认可的。

---

```
I'm building a portable personal profile that I'll share with other AI assistants.
Please export everything you know about me — from saved memory AND from patterns
across our past conversations.

Organize it under these headings, as bullet points:

## Identity        — name, background, education, where I'm from / based
## Career          — roles, experience, skills, tools, target jobs
## Projects        — things I've built or planned; status of each
## Thinking        — how I make decisions, recurring frameworks, opinions I hold
## Working style   — how I want answers (language, length, tone, format), things I've told you NOT to do
## Goals           — short-term and long-term
## Interests       — hobbies and topics I keep coming back to

Rules:
- Mark each bullet [stated] if I told you directly, or [inferred] if you concluded it from patterns.
- Add a date (YYYY-MM) where you know roughly when it came up.
- Leave out passwords, ID numbers, addresses, financial account details, and other people's private info.
- Put the whole export in ONE markdown code block.
- After the block, tell me honestly whether this is complete or whether you're unsure about parts.
```
