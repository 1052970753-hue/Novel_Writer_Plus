# Novel Writer Plus

AI 小说写作助手 — Claude Code Skill

一个专为 Claude Code 设计的 AI 小说创作 Skill，通过 **七阶段创作流程** 和 **17 人 Agent 团队协作系统**，帮助你从零开始完成高质量长篇小说创作。

## 特性

- **七阶段创作流程**：从世界观构建到终稿润色，覆盖小说创作全生命周期
- **17 人 Agent 团队**：主编、角色设计师、情节架构师、对话专家、风格校对等各司其职
- **反 AI 检测策略**：内置多种写作风格变换技术，提升文本自然度
- **多体裁支持**：玄幻、都市、科幻、言情、悬疑等主流网文类型
- **结构化大纲**：自动生成章纲、角色卡、时间线等创作辅助文档

## 安装

将 `skill.md` 复制到你的 Claude Code skills 目录：

```bash
# macOS / Linux
cp skill.md ~/.claude/skills/Novel_Writer_Plus/skill.md

# Windows
copy skill.md %USERPROFILE%\.claude\skills\Novel_Writer_Plus\skill.md
```

## 使用

在 Claude Code 中输入：

```
/Novel_Writer_Plus
```

然后按照引导，依次完成：

1. **世界观设定** — 构建故事背景、时代、规则
2. **角色设计** — 创建主角、配角、反派的人物卡片
3. **情节架构** — 设计主线、支线、冲突与高潮
4. **章纲编写** — 逐章规划剧情发展
5. **正文创作** — Agent 团队分工撰写
6. **风格润色** — 优化语言、节奏、对话
7. **终稿校对** — 检查逻辑、一致性、格式

## 工作原理

```
用户意图 → 主编 Agent → 任务分配 → 专项 Agent 执行 → 质量审核 → 交付
```

每个 Agent 有明确的职责边界和协作协议，确保输出质量和一致性。

## 适用场景

- 网文作者寻求 AI 辅助创作
- 写作爱好者尝试长篇小说
- 需要快速生成故事大纲和角色设定
- 学习小说创作结构和技巧

## License

MIT
