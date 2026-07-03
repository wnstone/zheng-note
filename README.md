# zheng-note · 蒸笔记

一个 [Claude Code](https://claude.com/claude-code) skill:把一篇(或一批)**转写稿 / 文章 / 口述稿**,蒸馏成一张**结构化的认知笔记**——抓骨架、留判断,不逐句复述。

> A Claude Code skill that distills long transcripts / articles into structured "cognition notes" — extract the skeleton and the judgment, don't rephrase line by line. (Chinese-first.)

## 它解决什么

扒下来的转写稿又长又口语(几千上万字、带时间戳、满是「啊这个那个」),直接堆着没法用。蒸笔记把一篇长稿压成「一眼看清作者在说啥、哪些站得住、哪些该打问号、对我有啥用」的短笔记。

**核心理念:保真高于精炼**——宁可少提炼一条,绝不编一条原稿没有的。

## 两种格式(自动判断)

- **A · 观点提炼版**(默认):用于别人的观点 / 外部信息(政论 / 历史 / 访谈 / 文章)。骨架 = 他在说什么 / 核心论点 / 关键论据 / 预测与判断 / 存疑处 / 对我的价值。
- **B · 人生复盘版**:用于第一人称的人生 / 认知 / 情绪复盘。骨架 = 讲什么 / 关键转折 / 对我的意义。

## 安装

把 `zheng-note` 整个文件夹放进你的 Claude Code skills 目录:

- 项目级:`<你的项目>/.claude/skills/zheng-note/`
- 全局:`~/.claude/skills/zheng-note/`

## 用法

对 Claude Code 说其中任意一句:

- `/蒸笔记`
- 「把这篇转写稿蒸成笔记」
- 「distill this into a cognition note」
- 直接甩一篇稿子 +「蒸成笔记」

给一个文件夹就逐篇蒸、已存在同名笔记的跳过不覆盖。

## License

MIT © 2026 wnstone(万能石)
