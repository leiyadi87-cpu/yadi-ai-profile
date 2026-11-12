# 定期更新 profile（renew）

两种场景：

## A. 聊完一次有收获的对话后（随手更新）

在那次对话的最后粘贴：

```
Here is my current personal AI profile:
https://raw.githubusercontent.com/leiyadi87-cpu/yadi-ai-profile/main/PROFILE.md

Based on THIS conversation only, what should change in it?
Give me a short list of proposed edits in this format:

- [ADD]    section → new line
- [CHANGE] section → old line  ⟶  new line
- [REMOVE] section → line (and why)

Only include things that will still be true a few months from now
(new projects, decisions, preferences, goals). Skip one-off details,
anything you guessed, and anything private.
```

把 AI 给的清单贴到 `updates/` 里一个新文件，或直接改 `PROFILE.md`。

## B. 每月一次大整理（合并 updates/ 里的东西）

把 `PROFILE.md` 和 `updates/` 里新增的文件一起交给一个能读写文件的 AI（比如 Claude），说：

```
Merge the notes in updates/ into PROFILE.md.
- Keep PROFILE.md short enough to read in about two minutes.
- Update "Current focus" and drop anything finished or outdated.
- Bump the version number and "Last updated" date.
- Add one line to CHANGELOG.md describing what changed.
- Show me the diff before committing.
```

合并完的 `updates/` 文件可以删掉（git 历史里都还在）。

---

### 小原则
- **只放长期成立的东西。** "这周在赶 deadline"不进 profile；"在做 X 项目"进。
- **永远自己最后过一眼。** AI 提议，你拍板。
- **公开仓库 = 全世界可见。** 求职进度、住址、生日、别人的信息都别放。
