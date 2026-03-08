# Learn Claude Code — 新手引导系统设计文档

## 背景

为团队内部培训打造一个"Claude Code 新手引导系统"，帮助零基础成员快速上手 Claude Code。

## 目标用户

- 团队内部开发者
- 用于课程或工作坊，有讲师配合使用

## 核心需求

1. **交互式教程**：像导师一样一步步带着新手做练习，实时反馈
2. **知识库查询**：遇到问题时能查到最佳实践和常见问题解答
3. **进度追踪**：记录学习进度、分析评价
4. **全程简体中文**
5. **不让用户去读官方文档**：LLM 按需读取官方文档并消化后教给用户

## 技术方案

### 选择：纯 Skill 方案

**理由**：
- Skill 天然适合"对话引导"场景
- 零安装门槛，复制文件即可
- MCP 本身成为教学内容而非教学工具

### 架构

```
.claude/skills/learn-claude-code/
├── SKILL.md              # 唯一入口 /learn-claude-code
├── curriculum.md         # 课程大纲
├── exercises/
│   ├── basic.md          # 基础练习题
│   ├── intermediate.md   # 中级练习题
│   └── advanced.md       # 高级练习题
└── reference/
    └── docs-urls.md      # 官方文档 URL 索引

docs/learn-progress/
├── progress.md           # 学习进度记录
├── evaluations/          # 每次学习的评价
└── notes/                # 学员笔记
```

### 单入口设计

- `/learn-claude-code` — 继续上次学习或开始新学习
- `/learn-claude-code 基础` — 直接跳到基础篇
- `/learn-claude-code 调试` — 直接学习调试模块

### 课程体系

| 级别 | 内容 | 核心技能 |
|------|------|----------|
| 基础 | 对话、文件读写、CLAUDE.md、基本工具使用 | 能用 Claude Code 完成简单开发任务 |
| 中级 | Skills 编写、调试技巧、重构方法、代码审查 | 能定制 Claude Code 工作流 |
| 高级 | MCP 配置、多智能体协作、Hook、项目管理 | 能搭建完整的 AI 辅助开发环境 |

### 导师人格

- 正向激励为主
- 偶尔轻微嘲讽但不过分
- 适时给予挑战

### 进度管理

- 进度持久化到 `docs/learn-progress/progress.md`
- 每次学习结束写入 session 评价
- 通过检查清单确认技能掌握程度

### 官方文档集成

- `reference/docs-urls.md` 维护文档 URL 索引
- LLM 在教学时按需使用 WebFetch 读取最新文档
- 消化后用简体中文教给用户
