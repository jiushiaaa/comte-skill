<h1 align="center">comte.skill</h1>

<p align="center">孔德 · Auguste Comte</p>

**中文** · [English](README.en.md)

<blockquote>
<p align="center">“科学带来预见，预见带来行动。”<br>— 孔德 · <a href="https://philosophie-pedagogie.web.ac-grenoble.fr/sites/default/files/media-fichiers/2021-07/comte_khodoss.pdf">《实证哲学教程》</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**将实证研究、科学层级与理论应用的区分整理为思想分析 Skill，让 AI 把可检验的问题说清楚，并检查从科学发现走向实际方案还缺少哪些环节。**

---

## 效果示例

以下为说明用法而编写的示例，展示分析思路；不是哲学家原话或实测对话记录。

### 1. 有脑科学数据，是否就能设计出最好的教育制度？

> 脑科学可以说明某些学习条件，却不能单独决定教育目的与制度安排。需要继续取得课堂、资源和社会层面的材料，并单独说明“最好”采用什么标准。

### 2. 理论已经成立，产品为什么还会失败？

> 理论成立与具体技艺可行之间，可能隔着测量、材料、组合和操作条件。先查这些转换环节，既不因应用失败就否定理论，也不把理论正确当成产品必然成功。

## 蒸馏了什么

| 思想方法 | 能帮助分析什么 |
|---|---|
| 问题划界 | 区分可观察关系、价值目标与终极起源问题。 |
| 层级依赖 | 检验跨学科推断所需的机制与专门材料。 |
| 理论与技艺 | 查明理论应用所需的中介知识与操作条件。 |

这些方法来自已定位的原作选段，不代表全集蒸馏。具体依据与适用范围见 [SKILL.md](SKILL.md) 和 [提炼说明](EXTRACTION.md)。

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io/) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令

```bash
npx skills add jiushiaaa/comte-skill
```

[Skills CLI](https://github.com/vercel-labs/skills) 可检测受支持的 agent；指定 runtime 时添加 `-a codex`、`-a claude-code` 或 `-a cursor`，全局安装添加 `-g`。这里说明协议与安装器的兼容生态，不代表本项目逐一实测了全部 runtime。

### 方式二：手动安装

克隆仓库后，将完整目录放入 runtime 的 skills 目录，保留 `SKILL.md` 及相对引用。安装目录命名为 `comte-perspective`，与入口元数据一致。常见路径为 Codex 的 `~/.agents/skills/`、Claude Code 的 `~/.claude/skills/`、Cursor 的 `~/.cursor/skills/`；以所用 runtime 当前文档为准。

```bash
git clone https://github.com/jiushiaaa/comte-skill.git
```

### 方式三：作为参考资料

不支持自动加载时，可把 `SKILL.md` 连同当前问题需要的引用文件交给 agent。README 与使用说明提供中英双语，研究底稿保留原语言。

## 使用方式

- **中性思想模式（默认）：** “用孔德的思想分析这个问题，区分原作观点与当代应用。”
- **人物表达模式（可选）：** 明确提出“开启人物表达模式”。这是注明性质的模拟，不是作者本人发言。

文游创作默认只取思想，文风另行决定。详见 [双语使用说明](USAGE.md)。

## 调研来源

《实证哲学教程》第一、二讲及科学分类相关选段；研究记录中的历史背景材料。

- [原作来源、版本与实际阅读范围](references/research/source-catalog.md)
- [方法提炼与证据](EXTRACTION.md)
- 开篇名言出处：<a href="https://philosophie-pedagogie.web.ac-grenoble.fr/sites/default/files/media-fichiers/2021-07/comte_khodoss.pdf">《实证哲学教程》</a>，第一卷，第二讲。中文引文为本仓库译文；非英语原作的英文引文亦为本仓库译文。

## 仓库结构

主要文件：

```text
├── SKILL.md  # Skill 入口与分析方法
├── README.md / README.en.md  # 中英文介绍
├── USAGE.md  # 双语使用说明
├── EXTRACTION.md  # 方法提炼与证据
├── references/  # 研究笔记与可选人物表达模式
└── LICENSE  # MIT 许可
```

## 构建工具

使用 [nvwa-skill](https://github.com/alchaincyf/nuwa-skill) 构建。

项目原创材料采用 [MIT](LICENSE)，所引原著与译本保留各自权利。详见 [来源说明](ATTRIBUTION.md)。

## 更多 Skill

更多人物 Skill 请查看 [Philosophy Skills 合集](https://github.com/jiushiaaa/Philosophy-Skills)。
