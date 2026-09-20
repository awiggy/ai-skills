# AI Skills · awiggy 的技能分类目录

把项目实践中整理、维护或使用的 AI 技能集中展示，按解决的问题查找对应入口。

这里是 **展示与导航仓库**，不是一键安装包，也不是所有技能的源码合集。目前收录的 7 个 Skill 仓库均已公开，其中部分仓库包含多个独立 Skill，可通过下表查看具体文件。

## 分类总览

| 分类 | Skill | 解决的问题 | 获取状态 |
| --- | --- | --- | --- |
| AI 产品交付 | [AI 产品交付 Skills](https://github.com/awiggy/agent-product-delivery-skills) | 架构蓝图、技术适配与业务闭环、Agent 前端交互、发布检查与回滚 | 公开初版，含 4 个独立 Skill；已做结构校验与离线审查，待真实项目验证 |
| 项目记忆与工作流 | [Task Progress Memory](https://github.com/awiggy/task-progress-memory) | 用任务清单组织工作，将项目进度保存为可续接的记忆 | 公开，可查看源码与使用说明 |
| 内容创作 | [Human Writing](https://github.com/awiggy/human-writing) | 中文写作、研究与修改 | 公开，入口为 SKILL.md |
| 内容创作 | [Write and Polish Manju Script](https://github.com/awiggy/write-and-polish-manju-script) | 漫剧剧本创作与优化 | 公开，入口为 SKILL.md |
| 产品分析 | [Reverse AI Product](https://github.com/awiggy/reverse-ai-product) | 基于可观察证据分析 AI 产品 | 公开，入口为 SKILL.md |
| GEO 工作流 | [GEO Skills](https://github.com/awiggy/geo-skills) | 关键词、文章生成、发布与效果监测相关技能集合 | 公开，含多个 Skill |
| 浏览器自动化 | [Ego Browser](https://github.com/awiggy/ego-browser) | 面向 AI 的浏览器操作工作流；依赖 ego lite，并非浏览器本体 | 公开，保存的工具配套资料 |

## 公开技能精选

### AI 产品交付 Skills

按任务选择一个入口，不需要一次加载全部规则：

- **架构蓝图**：从点子/PRD 判断是否需要 Agent，选择必要组件并明确工具权限。
- **开发交付**：从需求和现有代码出发，适配技术方案，实现一个可验收的业务闭环。
- **前端交互**：处理流式输出、人工确认、断线恢复、历史结果和视觉一致性。
- **发布检查**：检查权限、持久化、恢复与回滚；评估任务不会自动部署。

附使用示例、阶段模板、设计说明与验证记录。当前为初版，未声称生产环境实测通过。

**使用入口**：[说明与 Skill 选择](https://github.com/awiggy/agent-product-delivery-skills#readme)。

**Blueprint 专项说明**：[准备资料、调用示例与范围](https://github.com/awiggy/agent-product-delivery-skills/blob/main/docs/agent-blueprint-usage.md)。

### Task Progress Memory

**适用场景**：持续迭代一个项目，跨对话、跨阶段恢复任务进度。

- 以清单启动任务，记录正在做什么。
- 将推进状态写入项目记忆文件。
- 再次开始工作时，根据已有记录续接。

**使用入口**：[仓库说明与安装方式](https://github.com/awiggy/task-progress-memory#readme)。以目标仓库的依赖、安装步骤和许可说明为准。

## Skill 和应用项目的区别

Skill 面向 AI 助手，提供任务规则、资料与配套工具；应用项目面向用户，提供可运行的界面或程序。

应用内部即使包含 `SKILL.md`，仍按应用项目展示，不放在此技能目录中。

## 使用与开放边界

- 本仓库本身不能安装为一个 Skill，请进入具体公开仓库阅读说明。
- 仓库公开不代表已完成运行验收；使用前阅读具体 Skill 的依赖与安全边界。
- 新增技能公开前，先检查密钥、个人资料、第三方来源和许可，再补充源码链接与使用说明。
- 各技能的使用许可请查看对应仓库。

## 维护方式

新增技能时，在分类总览中补充名称、用途、公开状态和有效入口。分类目录只维护介绍，不重复复制各仓库源码，以免版本分叉。

更新日期：2026-09-21。
