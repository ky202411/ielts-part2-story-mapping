# IELTS Speaking Part 2 故事串题 Skill

这是一个 Codex skill：用 3–4 个熟悉的个人故事尽量覆盖指定的雅思口语 Part 2 题单，同时逐题检查主语、时间限制和 `You should say` 提示。覆盖不了的题会标出缺少的事实或建议另备小故事，不会把无关经历硬套成答案。

## 能做什么

- 接受中文或英文故事；英文输入会先修正语法和不自然表达，再写成容易口述的英文。
- 将人物、地点、经历、物品、决定等事实拆成可复用的素材卡。
- 按人物、地点、事件、物品／媒介、决定／变化、法律等题型使用稳定的四段式讲述骨架。
- 以地点为记忆线索，将地点题与可能发生在该地点的事件题组成练习组；是否真正覆盖仍由具体事实决定。
- 输出题目覆盖表、缺失细节、英文答案和 3–5 个关键词的记忆提示。

## 题库范围

`references/2026-09-12-part2.md` 是使用者于 2026 年 9 月提供的 **9–12 月 53 道去重题卡快照**，不是 IELTS 官方公布的完整考试题库，也不保证不同地区或后续日期的题目完全一致。更新季度时，skill 按 `references/topic-sources.md` 仅从同桌英语读取可访问的 Part 2 题目，并如实标记未读到的内容。

## 使用

把本仓库整个目录放入 Codex 的 skills 目录，并以 `$ielts-part2-story-mapping` 调用。例如：

> 我跟父母和弟弟去了广州塔。我和弟弟在塔下打羽毛球。请先列出这段经历能直接回答、需要补细节和不能覆盖的当季 Part 2 题，再写可直接回答的英文答案。

主入口是 [`SKILL.md`](SKILL.md)。题型骨架见 [`references/answer-patterns.md`](references/answer-patterns.md)，故事串题方法见 [`references/story-mapping-patterns.md`](references/story-mapping-patterns.md)。

本仓库中的个人故事仅作串题示例；生成新答案时，应以当前学习者提供的事实为准。
