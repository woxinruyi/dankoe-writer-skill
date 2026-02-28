# Dan Koe 写作教练 Skill

基于 Dan Koe 内容创作方法论的 Claude Code 写作 Skill。

装上之后，AI 会像一个学过 Dan Koe 方法论的写作教练，一步步引导你完成从选题到成稿的完整流程。

## 功能

- **引导式写作流程**：不直接出稿，而是一步步问清楚再写
- **8 种写作框架自动匹配**：干货型 4 种 + 营销型 4 种，AI 根据需求自动选择
- **6 个平台适配**：小红书、公众号、推特、Newsletter、YouTube 脚本、落地页
- **内置质量检查**：钩子强度、痛点共鸣、收束句效果自动评估

## 安装

跟 Claude Code 说：

```
帮我全局安装这个 Skill：https://github.com/yinalin/dankoe-writer-skill
```

## 使用

以下任何一种说法都会触发：

- "帮我写一篇……"
- "写一篇小红书笔记，关于……"
- "用 Dan Koe 的方法帮我写……"

## 文件结构

```
dankoe-writer-skill/
├── SKILL.md                      # 主文件：写作流程和质量检查
└── references/
    ├── frameworks.md             # 8 种写作框架详解
    └── platform-guides.md        # 6 个平台格式规范
```
