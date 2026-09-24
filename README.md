<div align="center">

<img src="assets/cover.svg" alt="Ask BFU | 北林校园问答" width="100%">

# Ask BFU · 北林问答

**从校园小事，到培养规定。**  
A source-aware BFU student Q&A skill.

[安装](#安装与试用) · [资料](#文件与来源) · [测试](#五轮自测) · [English](#english) · [更新](CHANGELOG.md)

</div>

> 独立社区项目，非北京林业大学官方服务。v0.2.0 聚焦经济管理学院；涉及个人毕业或发放资格以其年级适用的正式文件和审核为准。

## 现在可以问什么

| 问法示例 | 参考答案与规则 |
|:--|:--|
| “2023级、2025级经管博士每月补贴一样吗？” | 旧版资助合计按10个月为2,300元/发放月；2025级起国家助学金1,500元/发放月，2、8月不发。按身份和学籍判断，岗位津贴另计。 |
| “经管博士国家奖学金多少钱？” | 30,000元/人·年，是竞争性奖学金，不是生活补贴。 |
| “我博一发了一篇论文，能毕业吗？” | 对照校级和学院成果路径，核期刊、署名、第一单位、论文关联及所在级培养方案；一篇不能直接推出毕业资格。 |
| “本科经管转专业、推免去哪看？” | 按当期学院公告和校级方案，不套用往年报名日期。 |
| “硕士复试、导师、课程重修怎么办？” | 已有2026复试方案、导师名录和2022课程学习办法的有版本事实卡。 |

[奖助与补贴](skills/ask-bfu/references/funding.md) · [毕业与学位](skills/ask-bfu/references/degree.md) · [本科至博士路径](skills/ask-bfu/references/pathways.md)

## 安装与试用

将 **整个** [skills/ask-bfu](skills/ask-bfu/) 目录复制到本机 Codex 技能目录，保留 SKILL.md 和 references 子目录：

- Windows：`%USERPROFILE%\.codex\skills\ask-bfu`
- macOS / Linux：`~/.codex/skills/ask-bfu`

开启新对话，输入“使用 ask-bfu 查询：我是2025级经管博士，每月国家助学金多少？”单纯浏览或克隆 GitHub 页面不会自动安装技能；其他 Agent Skills 客户端按其各自安装方式操作。

## 文件与来源

| 文件 | 作用 |
|:--|:--|
| [SKILL.md](skills/ask-bfu/SKILL.md) | 触发条件、问答顺序、版本判定 |
| [source-index.md](skills/ask-bfu/references/source-index.md) | 18项校院公开文件入口、发布日期和适用范围 |
| [funding.md](skills/ask-bfu/references/funding.md) | 旧版与2025级起研究生资助、国奖和岗位津贴 |
| [degree.md](skills/ask-bfu/references/degree.md) | 学术博士/硕士学位成果、经管学院补充路径 |
| [pathways.md](skills/ask-bfu/references/pathways.md) | 本科转专业/推免、硕士复试、博士招生、课程入口 |
| [tests/qa-runs.md](tests/qa-runs.md) | 五轮共50道人工模拟提问及来源对应 |

**目前仓库保存了版本化事实摘录和官方原文链接，没有官方 PDF 二进制副本。** 学校公开 PDF 包括[2025级起奖助新办法（31页）](https://graduate.bjfu.edu.cn/docs//2026-09/a0aa3251905341438b36b45c0eb2af6e.pdf)及[2022版研究生手册（162页）](https://graduate.bjfu.edu.cn/docs/2022-09/20220928174049112531.pdf)。我们没有把公开发布的研究生手册当作2026年现行所有条款的保证，也不公开上传用户尚未核验版本的个人手册。

## 五轮自测

按入学、课程、奖助、研究成果、毕业阶段各抽10题，覆盖本科、硕士、博士；[查看完整题目与期望答案](tests/qa-runs.md)。50题均可在已收录事实卡定位并追到官方原件。此结果是人工资料检索与索引核查，尚未在已安装的 Codex 中跑端到端问答。

**目前缺口：** 各专业各入学级培养方案与准确学分、现行本科学生手册、学院每届论文和毕业日程、校园生活商户信息。遇到这些问题 Skill 会指向主管部门并说明尚未核实，不会填造数字。欢迎通过 Issue 提交官方链接和错误报告；请勿上传个人信息或未授权内部文件。

## English

Ask BFU answers Chinese and English questions about student life and academic rules at Beijing Forestry University, starting with the School of Economics and Management. It uses versioned summaries of official sources, distinguishes monthly stipends from annual awards, and checks current notices when the answer depends on this year’s arrangements.

Install the entire [skill directory](skills/ask-bfu/) in an Agent Skills compatible Codex environment. The repository links to public university PDFs; it does not currently mirror their binary contents. The [50-question manual source audit](tests/qa-runs.md) documents coverage and remaining gaps.

---

[MIT License](LICENSE) · v0.2.0
