# IB Diploma Programme Assessment Skills

Reusable [Agent Skills](https://agentskills.io/specification) for assessment planning, practice, and feedback in IB Diploma Programme Economics and Chinese A Language and Literature.

## Economics

Four skills based on the guide for first assessment in 2024. The paper skills explain what to write and how to assess it, with separate workflows for analytic marking and best-fit markbands. The IA skill helps students screen news articles, choose a key concept, plan and revise their own commentaries, and check the full portfolio.

| Assessment | Example prompt for automatic selection | Explicit invocation |
| --- | --- | --- |
| [Paper 1 · Extended response](.agents/skills/ib-economics-paper-1/SKILL.md) (SL/HL) | “Econ Paper 1: mark my 10-mark explanation and 15-mark evaluation separately.” | `$ib-economics-paper-1` |
| [Paper 2 · Data response](.agents/skills/ib-economics-paper-2/SKILL.md) (SL/HL) | “Econ Paper 2: does my part (g) use the extract to support its judgment?” | `$ib-economics-paper-2` |
| [Paper 3 · Policy paper](.agents/skills/ib-economics-paper-3/SKILL.md) (HL) | “Econ Paper 3: check my calculations and score my policy recommendation.” | `$ib-economics-paper-3` |
| [IA · Commentary portfolio](.agents/skills/ib-economics-ia/SKILL.md) (SL/HL) | “Econ IA: check whether this article fits and help me outline my commentary.” | `$ib-economics-ia` |

For the most reliable paper feedback, provide the exact question, your answer and diagrams, any source material, and the matching exam markscheme if available. The included guide summaries support practice estimates when the exam-specific scheme is unavailable.

## Chinese A Language and Literature

Three skills covering SL and HL under the guide for first assessment in 2026. Each explains the assessment, helps build a plan or practice response, and gives criterion-by-criterion feedback using an included Chinese rubric summary.

| Assessment | Example prompt for automatic selection | Explicit invocation |
| --- | --- | --- |
| [Paper 1 · 试卷1](.agents/skills/ib-chinese-a-paper-1/SKILL.md) | “Chinese Paper 1 HL：请用这两篇选文各列一份分析提纲。” | `$ib-chinese-a-paper-1` |
| [Paper 2 · 试卷2](.agents/skills/ib-chinese-a-paper-2/SKILL.md) | “Chinese Paper 2：请按 A、B1、B2、C、D 给这篇比较论文反馈。” | `$ib-chinese-a-paper-2` |
| [Individual Oral · 个人口试](.agents/skills/ib-chinese-a-io/SKILL.md) | “Chinese IO：请检查这个全球性问题和两段节选，并帮我安排 10 分钟提纲。” | `$ib-chinese-a-io` |

## Install in Codex

Clone or download this repository and open it as a Codex workspace. Codex discovers the skill folders under `.agents/skills` within the workspace. To use a skill across projects, copy its entire folder, including `references/`, into `~/.agents/skills/`. For another Agent Skills-compatible host, follow that host's installation instructions.

The assessment names in the skill descriptions help a compatible agent choose the relevant skill from an ordinary prompt. Automatic selection depends on the host and prompt context. Use the explicit invocation in Codex when you want to select a specific skill. [Codex skills documentation](https://learn.chatgpt.com/docs/build-skills)

## Sources

- **Economics:** IB DP *Economics guide*, first assessment 2024, published February 2020 and updated through October 2022. [IB Economics course overview](https://www.ibo.org/programmes/diploma-programme/curriculum/individuals-and-societies/economics/)
- **Chinese A:** IB *语言A：语言与文学指南*, published July 2025 for first assessment in 2026. [IB Language A course overview](https://www.ibo.org/programmes/diploma-programme/curriculum/language-and-literature/language-a-language-and-literature/) · [IB 2026 examiner instructions](https://ibpublishing.ibo.org/exinst/apps/exinst/index.html?chapter=1&doc=EX_instructions_2026_e&part=8)

The references cite the guides' printed page numbers. This independent study resource includes original coaching guidance and paraphrased rubrics; the IB guides and exam markschemes are available through the IB or your school. The original material in this repository is available under the [MIT License](LICENSE).
