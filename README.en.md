<h1 align="center">comte.skill</h1>

<p align="center">孔德 · Auguste Comte</p>

[中文](README.md) · **English**

<blockquote>
<p align="center">“Science, hence foresight; foresight, hence action.”<br>— Auguste Comte · <a href="https://philosophie-pedagogie.web.ac-grenoble.fr/sites/default/files/media-fichiers/2021-07/comte_khodoss.pdf">Course of Positive Philosophy</a></p>
</blockquote>

[![MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Agent Skills](https://img.shields.io/badge/Agent_Skills-Standard-blue.svg)](https://agentskills.io/) [![Made with nvwa-skill](https://img.shields.io/badge/Made_with-nvwa--skill-orange.svg)](https://github.com/alchaincyf/nuwa-skill)

**A thinking skill for positive inquiry, scientific levels, and applications: formulate testable questions and identify the missing steps between a scientific finding and a practical technique.**

---

## Examples

Illustrative applications written for this README; these are not quotations from the philosopher or transcripts of a live run.

### 1. Can brain data determine the best education system?

> It can inform some conditions of learning, but cannot by itself determine educational aims or institutional arrangements. Classroom and social evidence remain necessary, as does an explicit account of what “best” means.

### 2. Why can a product fail when its underlying theory is sound?

> Measurement, materials, combinations, and operating conditions can intervene between theory and technique. Examine those links before rejecting the theory or treating theoretical validity as a guarantee of success.

## What is distilled

| Method | What it helps examine |
|---|---|
| Scope of inquiry | Distinguish observable relations, value commitments, and ultimate origins. |
| Levels of dependence | Check the mechanisms and evidence needed for cross-level inference. |
| Theory and technique | Identify intermediate knowledge and conditions for application. |

These are selected, source-grounded methods, not a claim to cover the complete works. See [SKILL.md](SKILL.md) and [extraction notes](EXTRACTION.md) for scope and reasoning.

## Installation

This skill follows the open [Agent Skills](https://agentskills.io/) standard and can run in any skills-compatible AI agent runtime, including Claude Code, Codex, Cursor, OpenClaw, Hermes Agent, CodeBuddy, Workbuddy, Gemini CLI, OpenCode, and the broader ecosystem of 50+ runtimes.

### 1. One command

```bash
npx skills add jiushiaaa/comte-skill
```

The [Skills CLI](https://github.com/vercel-labs/skills) can detect supported agents. To select one, append `-a codex`, `-a claude-code`, or `-a cursor`; append `-g` for a global installation. Runtime support describes the standard and installer ecosystem, not a claim that we tested every runtime.

### 2. Manual installation

Clone this repository, then copy the complete folder into your runtime's skill directory, preserving `SKILL.md` and its relative reference paths. Name the installed folder `comte-perspective` to match its metadata. Common locations include `~/.agents/skills/` (Codex), `~/.claude/skills/` (Claude Code), and `~/.cursor/skills/` (Cursor); consult your runtime's current documentation.

```bash
git clone https://github.com/jiushiaaa/comte-skill.git
```

### 3. Use as reference

If automatic skill loading is unavailable, provide `SKILL.md` together with the referenced files needed for your question. Research notes remain in their source languages; README and usage guides are bilingual.

## Usage

- **Neutral analysis (default):** “Use Auguste Comte’s ideas to analyze this question. Distinguish source claims from contemporary applications.”
- **Persona expression (optional):** explicitly request “persona expression mode.” It is an acknowledged simulation, not a statement by the philosopher.

Fiction work uses the ideas while leaving narrative voice to the writing task. See the bilingual [usage guide](USAGE.md).

## Research sources

Selected passages from the first two lessons of the Course of Positive Philosophy and its classification of sciences; documented historical context.

- [Source catalogue and reading ranges](references/research/source-catalog.md)
- [Method extraction and evidence](EXTRACTION.md)
- Opening quotation: <a href="https://philosophie-pedagogie.web.ac-grenoble.fr/sites/default/files/media-fichiers/2021-07/comte_khodoss.pdf">Course of Positive Philosophy</a>, vol. I, lesson 2. English wording is translated where the source is not English; Chinese quotations are repository translations.

## Repository structure

Main files:

```text
├── SKILL.md  # Skill entry point and analysis methods
├── README.md / README.en.md  # Chinese and English introduction
├── USAGE.md  # Bilingual usage guide
├── EXTRACTION.md  # Method extraction and evidence
├── references/  # Research notes and optional expression mode
└── LICENSE  # MIT license
```

## Built with

Built with [nvwa-skill](https://github.com/alchaincyf/nuwa-skill).

Original project material is [MIT licensed](LICENSE); quoted works and translations retain their separate rights. See [source notices](ATTRIBUTION.md).

## More skills

Explore more thinkers and writers in the [Philosophy Skills collection](https://github.com/jiushiaaa/Philosophy-Skills).
