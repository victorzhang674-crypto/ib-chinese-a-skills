# IB Chinese A Language and Literature Skills

Three reusable [Agent Skills](https://agentskills.io/specification) for IB Diploma Programme Chinese A Language and Literature, covering SL and HL under the guide for first assessment in 2026. Each skill explains the assessment, helps build a plan or practice response, and gives criterion-by-criterion feedback using an included Chinese rubric summary.

| Assessment | Example prompt for automatic selection | Explicit invocation |
| --- | --- | --- |
| [Paper 1 · 试卷1](.agents/skills/ib-chinese-a-paper-1/SKILL.md) | “Chinese Paper 1 HL：请用这两篇选文各列一份分析提纲。” | `$ib-chinese-a-paper-1` |
| [Paper 2 · 试卷2](.agents/skills/ib-chinese-a-paper-2/SKILL.md) | “Chinese Paper 2：请按 A、B1、B2、C、D 给这篇比较论文反馈。” | `$ib-chinese-a-paper-2` |
| [Individual Oral · 个人口试](.agents/skills/ib-chinese-a-io/SKILL.md) | “Chinese IO：请检查这个全球性问题和两段节选，并帮我安排 10 分钟提纲。” | `$ib-chinese-a-io` |

## Install in Codex

Clone or download this repository and open it as a Codex workspace. Codex discovers the three folders under `.agents/skills` within the workspace. To use a skill across projects, copy its entire folder, including `references/`, into `~/.agents/skills/`. For another Agent Skills-compatible host, follow that host's installation instructions.

The assessment names in the skill descriptions help a compatible agent choose the relevant skill from an ordinary prompt. Automatic selection depends on the host and prompt context. Use the explicit invocation in Codex when you want to select a specific skill. [Codex skills documentation](https://learn.chatgpt.com/docs/build-skills)

## Sources

The assessment summaries and coaching workflows use the IB's Chinese-language *语言A：语言与文学指南*, published in July 2025 for first assessment in 2026. Each rubric reference gives the guide's printed page numbers. The repository includes original study guidance and summarized mark bands. The official guide is available through IB or your school. This is an independent study resource. [IB course overview](https://www.ibo.org/programmes/diploma-programme/curriculum/language-and-literature/language-a-language-and-literature/) · [IB 2026 examiner instructions](https://ibpublishing.ibo.org/exinst/apps/exinst/index.html?chapter=1&doc=EX_instructions_2026_e&part=8)

The original material in this repository is available under the [MIT License](LICENSE).
