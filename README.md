# IB Assessment Skills

Reusable [Agent Skills](https://agentskills.io/specification) for IB Diploma Programme assessment practice and feedback.

## Mathematics: Analysis and Approaches (AA)

The four skills cover the assessment model first used in 2021, through November 2028. Paper skills explain the format, mark student solutions against the matching exam mark scheme, and help create worked solutions, practice papers and revision plans. The IA skill includes a writing workflow and the separate SL and HL bands for Use of mathematics. For May 2029 onward, check the revised assessment model. [IB curriculum update](https://www.ibo.org/university-admission/latest-curriculum-updates/dp-mathematics-analysis-and-approaches-updates/)

| Assessment | Example prompt for automatic selection | Explicit invocation |
| --- | --- | --- |
| [Paper 1 · SL and HL](.agents/skills/ib-math-aa-paper-1/SKILL.md) | “Math Paper 1 SL AA. Mark my working using this question and mark scheme.” | `$ib-math-aa-paper-1` |
| [Paper 2 · SL and HL](.agents/skills/ib-math-aa-paper-2/SKILL.md) | “Math Paper 2 HL AA. Show the calculator setup and tell me where I lost marks.” | `$ib-math-aa-paper-2` |
| [Paper 3 · HL](.agents/skills/ib-math-aa-paper-3/SKILL.md) | “Math Paper 3 HL AA. Check where follow-through applies in this response.” | `$ib-math-aa-paper-3` |
| [IA · SL and HL](.agents/skills/ib-math-aa-ia/SKILL.md) | “Math IA HL AA. Evaluate my draft and give me a revision plan for criteria A–E.” | `$ib-math-aa-ia` |

For paper marking, provide the question, the student's working, and the official mark scheme for the same session and version if available. Without that scheme, any points awarded are a practice estimate.

## Chinese A: Language and Literature

Three skills cover SL and HL under the guide for first assessment in 2026. Each skill explains the assessment, helps build a plan or practice response, and gives criterion-by-criterion feedback using an included Chinese rubric summary.

| Assessment | Example prompt for automatic selection | Explicit invocation |
| --- | --- | --- |
| [Paper 1 · 试卷1](.agents/skills/ib-chinese-a-paper-1/SKILL.md) | “Chinese Paper 1 HL：请用这两篇选文各列一份分析提纲。” | `$ib-chinese-a-paper-1` |
| [Paper 2 · 试卷2](.agents/skills/ib-chinese-a-paper-2/SKILL.md) | “Chinese Paper 2：请按 A、B1、B2、C、D 给这篇比较论文反馈。” | `$ib-chinese-a-paper-2` |
| [Individual Oral · 个人口试](.agents/skills/ib-chinese-a-io/SKILL.md) | “Chinese IO：请检查这个全球性问题和两段节选，并帮我安排 10 分钟提纲。” | `$ib-chinese-a-io` |

## Install in Codex

Clone or download this repository and open it as a Codex workspace. Codex discovers the skill folders under `.agents/skills` within the workspace. To use a skill across projects, copy its entire folder, including any `references/`, into `~/.agents/skills/`. For another Agent Skills-compatible host, follow that host's installation instructions.

The assessment names in the skill descriptions help a compatible agent choose the relevant skill from an ordinary prompt. Automatic selection depends on the host and prompt context. Use the explicit invocation in Codex when you want to select a specific skill. [Codex skills documentation](https://learn.chatgpt.com/docs/build-skills)

## Sources

The mathematics skills draw on the IB's *Mathematics: analysis and approaches guide*, first assessment 2021, printed pp. 72–90, and its specimen mark schemes. The public resource contains original workflows, practice illustrations and rubric summaries. Official materials are available from the IB. [IB mathematics guide](https://www.ibo.org/globalassets/new-structure/university-admission/pdfs/dp-mathematics-analysis-and-approaches-guide-en.pdf) · [IB sample exam papers](https://www.ibo.org/programmes/diploma-programme/assessment-and-exams/sample-exam-papers/)

The assessment summaries and coaching workflows use the IB's Chinese-language *语言A：语言与文学指南*, published in July 2025 for first assessment in 2026. Each rubric reference gives the guide's printed page numbers. The repository includes original study guidance and summarized mark bands. The official guide is available through IB or your school. This is an independent study resource. [IB course overview](https://www.ibo.org/programmes/diploma-programme/curriculum/language-and-literature/language-a-language-and-literature/) · [IB 2026 examiner instructions](https://ibpublishing.ibo.org/exinst/apps/exinst/index.html?chapter=1&doc=EX_instructions_2026_e&part=8)

The original material in this repository is available under the [MIT License](LICENSE).
