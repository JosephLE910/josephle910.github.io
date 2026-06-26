---
title: 代码工坊 · 协作蓝图
---

代码工坊（CodeWorkshop）的多智能体协作体系核心文档。以下四份构成**可移植部署蓝图**——新项目从顶层主本拷贝即可复用。

## 必读顺序

1. [AI 接入契约](ai-onboarding) — 任何 AI / 队友 / 工具，先读这份。一句话：动手前读 `shared/`，动完写回 `shared/`。
2. [多智能体协作蓝图](workflow) — 架构全貌：三角色、plan 生命周期、双分层、省 token 纪律、部署清单。
3. [规划者规则](planner-rules) — 规划者开工动作清单：读什么、出 plan、审查 merge、收尾提炼。
4. [执行者规则](executor-rules) — 执行者开工规则：worktree 隔离、git 分支、plan 修改权分层。

## 治理

- 顶层 `CodeWorkshop/shared/` = **主本 canonical**，仅由工坊主理人助手维护。
- 新项目从主本拷贝 → 各项目本地迭代；通用改进走「衍生本 → 提炼 → 回提主本」回路。
- 重心是协作流程 WORKFLOW 本身，不是领域踩坑 LESSONS。
