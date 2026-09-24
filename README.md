<div align="center">

<img src="assets/cover.svg" alt="Ask BFU | 北林校园问答" width="100%">

# Ask BFU · 北林问答

**从校园小事，到培养规定。**  
A source-aware student guide to Beijing Forestry University.

[试问](#试问--try-it) · [资料维护](#资料如何更新--sources) · [English](#english) · [版本记录](CHANGELOG.md)

</div>

> 独立社区项目，非北京林业大学官方服务。首版优先覆盖经济管理学院。制度性问题请核对适用年度的正式文件。

## 功能预览

| 问题 | 答案策略 | 状态 |
|:--|:--|:--|
| 经管学院的招生与培养 | 核对专业、培养层次和年份 | 部分官方资料已收录 |
| 研究生奖学金 | 引用明确的制度版本 | 已收录一项经管学院细则 |
| 博士毕业要求 | 先确认入学年份和专业，再查适用文件 | 手册待核对 |
| 校历、放假与课时 | 以当学年教务通知为准 | 回答时查最新公告 |
| 失物、修补、回收 | 核实办理路径、地点和核验日期 | 待积累校园经验 |

## 试问 · Try it

导入 [Ask BFU Skill](skills/ask-bfu/) 后，可以问：

1. “北林经管学院博士国家奖学金多少钱？”
2. “我是经管学院博一，发了一篇论文，能毕业吗？”
3. “北林今年什么时候放假？”
4. “裤子破了，学校周边哪里能缝？”

预期行为：第 1 题给出金额、文件版本和来源；第 2 题一次追问必要信息，并区分奖学金和毕业条件；第 3 题查询当前学年正式通知；第 4 题没有核实商户信息时明确说明，避免编造地址。

## 使用方法

本仓库遵循 Agent Skills 文件结构：入口是 [skills/ask-bfu/SKILL.md](skills/ask-bfu/SKILL.md)，引用资料在相邻的 references 文件夹。试用 Codex 本地版时，将整个 skill 文件夹复制到用户技能目录：

- Windows：`%USERPROFILE%\.codex\skills\ask-bfu`
- macOS / Linux：`~/.codex/skills/ask-bfu`

复制后确认该目录中有 `SKILL.md` 和 `references/`，再开启新对话，问“使用 ask-bfu 查询北林经管学院……”即可。**仅浏览或克隆 GitHub 仓库不会自动安装到 ChatGPT**；ChatGPT 的技能安装入口与 Codex 本地版可能不同。

- [经管学院参考资料](skills/ask-bfu/references/economics-management.md)
- [资料与更新规则](skills/ask-bfu/references/source-policy.md)
- [完整更新记录](CHANGELOG.md)

## 资料如何更新 · Sources

| 资料类别 | 仓库内 | 回答时 |
|:--|:--|:--|
| 稳定的校级、院级文件 | 保存核实摘要、官方链接、版本与适用范围 | 问该版本时直接回答 |
| 校历、招生、放假、评奖通知 | 保存主管部门入口 | 询问当前安排时核对当期原文 |
| 学生经验与周边商户 | 记录提供者描述及最后核验日期 | 明确属于经验信息 |
| 非公开的手册 | 核对版本后提炼可公开的条目 | 不直接上传整本原件 |

**目前仓库没有保存官方 PDF 全文**，经管学院资料页保存了已经核实的结论和原文链接。问“2024版细则规定多少”可直接答；问“今年是否仍是这个标准”才检索更新。

欢迎通过 Issue 反馈错误、失效链接和新的常见问题。请提供可核验的公开依据，不提交学生个人信息或未公开的内部材料。

## English

Ask BFU answers questions about campus life, teaching schedules, admissions, and student rules at Beijing Forestry University. Version 0.1 focuses on the School of Economics and Management. It distinguishes official rules from student experience, checks time-sensitive notices when answering, cites original sources, and asks only for details that change the answer.

This is an independent community project, not an official university service. Import the [skill directory](skills/ask-bfu/) in an Agent Skills-compatible Codex environment, keeping its reference files together. Ask in Chinese or English.

---

[MIT License](LICENSE) · v0.1.1
