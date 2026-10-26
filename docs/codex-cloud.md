# Codex 云端配置与复用

更新日期：2026-10-26。

## 仓库已经提供什么

- 根目录 AGENTS.md：任务启动约定，按问题读取已有 Ask BFU 技能。
- skills/ask-bfu/：校园问答技能及版本化参考资料。
- docs/research-data-workflow.md：用户提出研究任务时的数据搜集、核对和续接流程。

这不代表插件已经安装、云端环境已经发布或其他聊天的文件已经迁入。

## 首次准备环境

在新任务选择 Work in → Cloud → Select environment，选已有环境；也可从 Settings → Codex Cloud → Environments 编辑。

确认关联 amber0306-lee/ask-bfu，使用已提交上述文件的 main。让设置对话检查根目录 AGENTS.md、技能及 references 的相对链接，运行一次真实问答并报告所读来源。

本仓库为 Markdown 资料和 SVG，不需要为了校园问答安装项目运行时。研究任务有需要时，再让设置对话检查 Python 和所需数据处理库，按任务安装并实际导入验证。不要假定 Stata、浏览器自动化、知网登录或本地技能在云端可用。

需要访问学校官网时，按实际来源增加允许域名并测试。域名许可、登录凭据与页面可达性是三件事；配置本身不能保证访问成功。

完成设置、检查结果并保存，选择 Publish 或 Republish。看到 Environment published 后启动新任务。保存草稿和发布不同。

## 每次使用

选 Work in → Cloud → 已发布环境，再提出任务。北林问答由 AGENTS.md 指向 skills/ask-bfu/SKILL.md；其他任务按实际需求处理。

复用的是仓库、准备好的工具与环境配置。每个新任务有独立工作空间；个人电脑技能、其他聊天的历史附件和未提交文件不会自动同步。

重要私人研究任务，应在其私人工作空间保留 TASK_BRIEF.md、DATA_DICTIONARY.md、PROGRESS.md 与真实数据。续接旧聊天时先检查它实际可读的文件；不要把本仓库更新误认为旧任务已更新。

## 验收标准

1. 平台显示环境已发布。
2. 新任务可读 AGENTS.md、skills/ask-bfu/SKILL.md 及引用的资料。
3. 真实问答给出适用范围与原文来源。
4. 研究任务需要的私人输入文件实际可读。
5. 需要的软件和来源访问经过该云端任务实际测试。

仅完成仓库文件检查，不等于以上五项已全部通过。

## 官方文档

- https://learn.chatgpt.com/docs/cloud
- https://learn.chatgpt.com/docs/environments/cloud-environments
- 旧入口说明：https://learn.chatgpt.com/docs/environments/cloud-environment
