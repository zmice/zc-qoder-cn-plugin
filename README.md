# zc Quest CN Plugin

[![source repo](https://img.shields.io/badge/source-zc--ai--coding--toolkit-24292f)](https://github.com/zmice/zc-ai-coding-toolkit)
[![npm version](https://img.shields.io/npm/v/@zmice/zc)](https://www.npmjs.com/package/@zmice/zc)
[![license](https://img.shields.io/github/license/zmice/zc-ai-coding-toolkit)](LICENSE)

这是由 [zc AI Coding Toolkit](https://github.com/zmice/zc-ai-coding-toolkit) 自动导出的 Quest CN 插件包。

这个插件包面向 Quest CN 平台分发模型，提供：

- `.qoder-plugin/plugin.json` 插件元数据
- `commands/zc/` 命令入口
- `skills/zc-*/` 技能目录
- `agents/zc-*.md` 角色入口

## 安装

```bash
qodercli cn plugins install <path-or-url>
```

## 更新

```bash
qodercli cn plugins update zc-toolkit
```

## 常用入口

安装插件后，优先从这些入口开始：

- `zc:start`
- `zc:product-analysis`
- `zc:sdd-tdd`
- `zc:spec`
- `zc:task-plan`
- `zc:build`
- `zc:quality-review`
- `zc:verify`

## 目录说明

- `.qoder-plugin/plugin.json`
  - Quest CN 插件元数据
- `commands/zc/`
  - 统一任务入口和阶段入口
- `skills/zc-*/SKILL.md`
  - workflow 技能和专项方法
- `agents/zc-*.md`
  - 角色型入口

## 维护方式

这个仓库不是手工维护。

- 主仓库：<https://github.com/zmice/zc-ai-coding-toolkit>
- npm CLI：<https://www.npmjs.com/package/@zmice/zc>
- 同步方式：主仓库 GitHub Actions 自动导出并同步

如果你希望调整内容，请回到主仓库修改 `packages/toolkit/src/content/`，再由同步流程重新发布。

## 反馈与问题

- Issues：<https://github.com/zmice/zc-ai-coding-toolkit/issues>
- CLI README：<https://github.com/zmice/zc-ai-coding-toolkit/blob/main/apps/cli/README.md>
- 使用说明：<https://github.com/zmice/zc-ai-coding-toolkit/blob/main/docs/usage-guide.md>
