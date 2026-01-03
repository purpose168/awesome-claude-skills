<a href="https://github.com/VoltAgent/voltagent">
<img width="1500" height="500" alt="claude-skills" src="https://github.com/user-attachments/assets/39c54dfd-129e-4b43-8b92-20824a56e069" />
</a>

<br/>
<br/>

<div align="center">
    <strong>Claude Skills 官方和社区构建资源的精彩合集。
    </strong>
    <br />
    <br />

</div>

<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![最后更新](https://img.shields.io/github/last-commit/VoltAgent/awesome-claude-skills?label=Last%20update&style=flat-square)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)
[![GitHub forks](https://img.shields.io/github/forks/VoltAgent/awesome-claude-skills?style=social)](https://github.com/VoltAgent/awesome-claude-skills/network/members)

</div>

# Awesome Claude Skills

Claude Skills（Claude技能）是包含指令、脚本和资源的文件夹，用于教授Claude完成特定任务。技能可以包含可执行代码，并且仅在需要时加载，允许您维护数百个技能而不会影响性能。多个技能可以一起运行以完成复杂任务，如文档创建、代码测试和数据分析。



### 基本技能的结构是什么样的？

```YAML
---
name: api-tester  # 技能名称：api-tester
description: Test REST APIs and validate responses  # 技能描述：测试REST API并验证响应
---

# API测试器

测试HTTP端点并验证响应结构。

## 何时使用此技能

当您需要测试API端点并验证响应数据时，请使用此技能。

## 说明

测试API时：

1. 向指定端点发送请求
2. 检查响应状态码
3. 验证响应体结构
4. 报告任何错误或意外结果

## 响应验证

- 验证必填字段是否存在
- 检查数据类型是否匹配预期值
- 确认嵌套对象具有正确的结构
```

有关更多详细信息，请参阅[官方仓库](https://github.com/anthropics/skills)和[创建指南](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills)。

<br/>

<a href="https://github.com/VoltAgent/voltagent">
<img width="3082" height="592" alt="cta" src="https://github.com/user-attachments/assets/74dbaad4-8285-420b-95df-245948c766c8" />
</a>

<br/>

## 官方Claude技能

### 文档创建

- **[anthropics/docx](https://github.com/anthropics/skills/tree/main/skills/docx)** - 创建、编辑和分析Word文档
- **[anthropics/doc-coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring)** - 协作文档编辑和共同创作
- **[anthropics/pptx](https://github.com/anthropics/skills/tree/main/skills/pptx)** - 创建、编辑和分析PowerPoint演示文稿
- **[anthropics/xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx)** - 创建、编辑和分析Excel电子表格
- **[anthropics/pdf](https://github.com/anthropics/skills/tree/main/skills/pdf)** - 提取文本、创建PDF和处理表单

### 创意与设计

- **[anthropics/algorithmic-art](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art)** - 使用p5.js和种子随机性创建生成艺术
- **[anthropics/canvas-design](https://github.com/anthropics/skills/tree/main/skills/canvas-design)** - 设计PNG和PDF格式的视觉艺术
- **[anthropics/frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design)** - 前端设计和UI/UX开发工具
- **[anthropics/slack-gif-creator](https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator)** - 创建针对Slack大小限制优化的动画GIF
- **[anthropics/theme-factory](https://github.com/anthropics/skills/tree/main/skills/theme-factory)** - 使用专业主题为工件设置样式或生成自定义主题

### 开发

- **[anthropics/web-artifacts-builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder)** - 使用React和Tailwind构建复杂的claude.ai HTML工件
- **[anthropics/mcp-builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder)** - 创建MCP服务器以集成外部API和服务
- **[anthropics/webapp-testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing)** - 使用Playwright测试本地Web应用程序

### 品牌与沟通

- **[anthropics/brand-guidelines](https://github.com/anthropics/skills/tree/main/skills/brand-guidelines)** - 将Anthropic的品牌颜色和排版应用于工件
- **[anthropics/internal-comms](https://github.com/anthropics/skills/tree/main/skills/internal-comms)** - 编写状态报告、新闻通讯和常见问题解答

### 元技能

- **[anthropics/skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator)** - 创建扩展Claude功能的技能指南
- **[anthropics/template](https://github.com/anthropics/skills/tree/main/template)** - 创建新技能的基本模板

## 社区技能

### 生产力与协作

- **[notiondevs/Notion Skills for Claude](https://www.notion.so/notiondevs/Notion-Skills-for-Claude-28da4445d27180c7af1df7d8615723d0)** - 用于Notion协作的技能
- **[PleasePrompto/notebooklm-skill](https://github.com/PleasePrompto/notebooklm-skill)** - 与NotebookLM交互进行基于文档的对话
- **[obra/superpowers-lab](https://github.com/obra/superpowers-lab)** - Claude超能力实验室环境
- **[obra/brainstorming](https://github.com/obra/superpowers/blob/main/skills/brainstorming/SKILL.md)** - 生成和探索想法
- **[obra/writing-plans](https://github.com/obra/superpowers/blob/main/skills/writing-plans/SKILL.md)** - 创建战略文档
- **[obra/executing-plans](https://github.com/obra/superpowers/blob/main/skills/executing-plans/SKILL.md)** - 实施和运行战略计划
- **[obra/dispatching-parallel-agents](https://github.com/obra/superpowers/blob/main/skills/dispatching-parallel-agents/SKILL.md)** - 协调多个同时运行的代理
- **[obra/sharing-skills](https://github.com/obra/superpowers/blob/main/skills/sharing-skills/SKILL.md)** - 分发和传达功能
- **[obra/using-superpowers](https://github.com/obra/superpowers/blob/main/skills/using-superpowers/SKILL.md)** - 利用核心平台功能
- **[ComposioHQ/content-research-writer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/content-research-writer)** - 通过研究增强写作能力
- **[ComposioHQ/meeting-insights-analyzer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/meeting-insights-analyzer)** - 分析会议沟通模式
- **[ComposioHQ/competitive-ads-extractor](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/competitive-ads-extractor)** - 分析竞争对手的广告
- **[ComposioHQ/image-enhancer](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/image-enhancer)** - 提高图像质量
- **[wrsmith108/linear-claude-skill](https://github.com/wrsmith108/linear-claude-skill)** - 使用MCP工具、SDK脚本和GraphQL回退管理Linear问题、项目和团队

### 开发与测试

- **[zxkane/aws-skills](https://github.com/zxkane/aws-skills)** - 具有基础设施自动化和云架构模式的AWS开发
- **[conorluddy/ios-simulator-skill](https://github.com/conorluddy/ios-simulator-skill)** - 控制iOS模拟器
- **[sanjay3290/postgres](https://github.com/sanjay3290/ai-skills/tree/main/skills/postgres)** - 针对PostgreSQL数据库执行安全的只读SQL查询，支持多连接
- **[jthack/ffuf-claude-skill](https://github.com/jthack/ffuf_claude_skill)** - 使用ffuf进行Web模糊测试
- **[lackeyjb/playwright-skill](https://github.com/lackeyjb/playwright-skill)** - 使用Playwright进行浏览器自动化
- **[scarletkc/vexor](https://github.com/scarletkc/vexor)** - 具有Claude/Codex技能的矢量驱动CLI，用于语义文件搜索
- **[obra/test-driven-development](https://github.com/obra/superpowers/blob/main/skills/test-driven-development/SKILL.md)** - 在实现代码之前编写测试
- **[ComposioHQ/changelog-generator](https://github.com/ComposioHQ/awesome-claude-skills/tree/master/changelog-generator)** - 将git提交转换为发布说明
- **[obra/subagent-driven-development](https://github.com/obra/superpowers/blob/main/skills/subagent-driven-development/SKILL.md)** - 使用多个子代理进行开发
- **[obra/systematic-debugging](https://github.com/obra/superpowers/blob/main/skills/systematic-debugging/SKILL.md)** - 代码中的系统化问题解决
- **[obra/root-cause-tracing](https://github.com/obra/superpowers/blob/main/skills/root-cause-tracing/SKILL.md)** - 调查并识别根本问题
- **[obra/testing-skills-with-subagents](https://github.com/obra/superpowers/blob/main/skills/testing-skills-with-subagents/SKILL.md)** - 协作测试方法
- **[obra/testing-anti-patterns](https://github.com/obra/superpowers/blob/main/skills/testing-anti-patterns/SKILL.md)** - 识别无效的测试实践
- **[obra/finishing-a-development-branch](https://github.com/obra/superpowers/blob/main/skills/finishing-a-development-branch/SKILL.md)** - 完成Git代码分支
- **[obra/requesting-code-review](https://github.com/obra/superpowers/blob/main/skills/requesting-code-review/SKILL.md)** - 启动代码审查流程
- **[obra/receiving-code-review](https://github.com/obra/superpowers/blob/main/skills/receiving-code-review/SKILL.md)** - 处理和整合代码反馈
- **[obra/using-git-worktrees](https://github.com/obra/superpowers/blob/main/skills/using-git-worktrees/SKILL.md)** - 管理多个Git工作树
- **[obra/verification-before-completion](https://github.com/obra/superpowers/blob/main/skills/verification-before-completion/SKILL.md)** - 在完成前验证工作
- **[obra/condition-based-waiting](https://github.com/obra/superpowers/blob/main/skills/condition-based-waiting/SKILL.md)** - 管理条件暂停或延迟
- **[obra/commands](https://github.com/obra/superpowers/tree/main/skills/commands)** - 创建和管理命令结构
- **[obra/writing-skills](https://github.com/obra/superpowers/blob/main/skills/writing-skills/SKILL.md)** - 开发和记录功能
- **[fvadicamo/dev-agent-skills](https://github.com/fvadicamo/dev-agent-skills)** - Git和GitHub工作流技能：git-commit（规范提交）、github-pr-creation、github-pr-merge、github-pr-review，以及创建技能指南
- **[omkamal/pypict-skill](https://github.com/omkamal/pypict-claude-skill/blob/main/SKILL.md)** - 成对测试生成
- **[alinaqi/claude-bootstrap](https://github.com/alinaqi/claude-bootstrap)** - 带有安全优先防护措施、规范驱动的原子待办事项、LLM测试模式和CLI工具编排（gh、vercel、supabase）的意见性项目初始化

### 上下文工程

- **[muratcankoylan/context-fundamentals](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-fundamentals)** - 了解上下文是什么、为什么重要以及代理系统中上下文的构成
- **[muratcankoylan/context-degradation](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-degradation)** - 识别上下文失败模式：中间丢失、污染、分心和冲突
- **[muratcankoylan/context-compression](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-compression)** - 为长时间运行的会话设计和评估压缩策略
- **[muratcankoylan/context-optimization](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/context-optimization)** - 应用压缩、掩码和缓存策略
- **[muratcankoylan/multi-agent-patterns](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/multi-agent-patterns)** - 掌握编排器、对等和分层多代理架构
- **[muratcankoylan/memory-systems](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/memory-systems)** - 设计短期、长期和基于图的内存架构
- **[muratcankoylan/tool-design](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/tool-design)** - 构建代理可以有效使用的工具，包括架构简化模式
- **[muratcankoylan/evaluation](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering/tree/main/skills/evaluation)** - 为代理系统构建评估框架

### 专业领域

- **[K-Dense-AI/claude-scientific-skills](https://github.com/K-Dense-AI/claude-scientific-skills)** - 科学研究和分析技能
- **[NotMyself/claude-win11-speckit-update-skill](https://github.com/NotMyself/claude-win11-speckit-update-skill)** - Windows 11系统管理
- **[sanjay3290/imagen](https://github.com/sanjay3290/ai-skills/tree/main/skills/imagen)** - 使用Google Gemini的API生成UI原型、图标和视觉资产的图像
- **[jeffersonwarrior/claudisms](https://github.com/jeffersonwarrior/claudisms)** - SMS消息集成
- **[SHADOWPR0/security-bluebook-builder](https://github.com/SHADOWPR0/security-bluebook-builder)** - 为敏感应用构建简洁、规范的安全蓝皮书（威胁模型、数据类、认证/会话、日志/审计、保留、事件响应、安全门控）
- **[obra/defense-in-depth](https://github.com/obra/superpowers/blob/main/skills/defense-in-depth/SKILL.md)** - 多层安全方法
- **[haunchen/n8n-skill](https://github.com/haunchen/n8n-skills)** - 使AI助手能够理解和操作n8n工作流，包含542个节点和20个模板的信息
- **[materials-simulation-skills](https://github.com/HeshamFS/materials-simulation-skills)** - 计算材料科学的代理技能：数值稳定性、时间步长、线性求解器、网格生成、模拟验证、参数优化和后处理
- **[wrsmith108/varlock-claude-skill](https://github.com/wrsmith108/varlock-claude-skill)** - 安全环境变量管理，确保机密信息永远不会在Claude会话、终端、日志或git提交中暴露

## 文章和教程

### 📚 官方

- **[Claude Skills Quickstart](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/quickstart)** - Claude Skills快速入门
- **[Claude Skills Best Practices](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/best-practices)** - 创建技能的最佳实践
- **[Skills Cookbook](https://github.com/anthropics/claude-cookbooks/blob/main/skills/README.md)** - 技能示例和指南
- **[What Are Skills](https://support.claude.com/en/articles/12512176-what-are-skills)** - Claude Skills介绍
- **[Using Skills in Claude](https://support.claude.com/en/articles/12512180-using-skills-in-claude)** - 如何在Claude中使用技能
- **[How to Create Custom Skills](https://support.claude.com/en/articles/12512198-how-to-create-custom-skills)** - 创建自定义技能的分步指南
- **[Create a Skill Through Conversation](https://support.claude.com/en/articles/12599426-how-to-create-a-skill-with-claude-through-conversation)** - 通过与Claude对话创建技能
- **[Claude for Financial Services Skills](https://support.claude.com/en/articles/12663107-claude-for-financial-services-skills)** - 金融服务的行业特定技能
- **[Equipping Agents for the Real World](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills)** - 代理技能的技术深度解析
- **[Teach Claude Your Way of Working](https://support.claude.com/en/articles/12580051-teach-claude-your-way-of-working-using-skills)** - 使用技能自定义Claude以适应您的工作方式

### 👥 社区

- **[Simon Willison: Claude Skills](https://simonwillison.net/2025/Oct/16/claude-skills/)** - Claude Skills介绍
- **[Nick Nisi: Claude Skills](https://nicknisi.com/posts/claude-skills/)** - Claude Skills入门
- **[Young Leaders: Skills, Commands, Subagents, Plugins](https://www.youngleaders.tech/p/claude-skills-commands-subagents-plugins)** - Claude功能比较

### 🎥 视频

- **[Claude Skills Just 10x'd My AI Agents by Greg Isenberg](https://www.youtube.com/watch?v=G-5bInklwRQ)** - Greg Isenberg：Claude Skills让我的AI代理能力提升10倍
- **[Claude Skills: Build Your Own AI Experts (Full Breakdown)](https://www.youtube.com/watch?v=46zQX7PSHfU)** - Claude Skills：构建您自己的AI专家（完整解析）
- **[Agent Skills: Specialized capabilities you can customize](https://www.youtube.com/watch?v=IoqpBKrNaZI)** - 代理技能：您可以自定义的专业能力
- **[Claude Skills—From TOY to TOOL: Grab My Tutorial](https://www.youtube.com/watch?v=WKFFFumnzYI)** - Claude Skills—从玩具到工具：获取我的教程
- **[Claude Skills: Glimpse of Continual Learning?](https://www.youtube.com/watch?v=FOqbS_llAms)** - Claude Skills：持续学习的一瞥？
- **[Stop Using MCP... Use NEW Claude Skills Instead](https://www.youtube.com/watch?v=M8yaR-wNGj0)** - 停止使用MCP...改用新的Claude Skills
- **[Claude Skills explained: How to create reusable AI workflows](https://www.youtube.com/watch?v=MZZCW179nKM)** - Claude Skills详解：如何创建可重用的AI工作流

## 🤝 贡献

我们欢迎贡献！请参阅[CONTRIBUTING.md](CONTRIBUTING.md)了解指南。

- 通过PR提交新技能
- 改进现有定义
- 添加新的文档、视频和文章

* 这是一个精选列表。我们不审核、认可或保证列出项目的安全性或正确性。
