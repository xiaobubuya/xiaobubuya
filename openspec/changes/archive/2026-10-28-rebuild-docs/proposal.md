# Proposal: 用 OpenSpec 建立 xiaobubuya（GitHub Profile） 的项目档案

## Why

xiaobubuya（GitHub Profile） 目前没有可检索的结构化文档入口（或只有上游英文文档）。本工作区需要知道
「这个仓库是什么、在本工作区里扮演什么角色、部署真相在哪里」，避免把上游文档
或 fork 误当成部署依据。

## What Changes

- 在仓库内建 `openspec/`，只记录**本工作区的项目档案与集成关系**，不复制上游实现文档。
- 新增能力 `project-profile`：项目身份、许可、与本工作区的关系（部署/不部署）、
  文档权威来源。
- 不修改上游代码与上游文档。

## Capabilities

- **New Capabilities**：
  - `project-profile` — 项目身份、许可、工作区角色、文档归属

## Impact

- 新增：`openspec/`（config、specs、changes）
- 新增：根 `AGENTS.md`（唯一入口）
- 不触碰：上游源码与既有文档
