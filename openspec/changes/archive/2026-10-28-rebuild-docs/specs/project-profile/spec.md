## Purpose

登记 xiaobubuya（GitHub Profile） 的项目身份与本工作区定位，作为进入该仓库的第一份结构化说明；
实现细节以上游文档为准，这里只写「是什么、归谁、在本工作区怎么用」。

## ADDED Requirements

### Requirement: 项目身份与许可
系统 SHALL 明确记录项目身份：GitHub 个人主页 README 仓库，上游仓库 `xiaobubuya/xiaobubuya`，许可 无（个人主页内容）。
本仓库是上游的 fork/镜像，SHALL 保留上游许可与归属声明，不得移除 `LICENSE*`、
`ATTRIBUTION.md` 等文件。

#### Scenario: 能查到项目身份
WHEN 新成员进入本仓库
THEN 从本 spec 得知项目是什么、上游在哪、许可是什么。

#### Scenario: 保留上游归属
WHEN 修改或分发本仓库
THEN 上游许可与归属文件保持完整。

### Requirement: 本工作区中的角色
仅用于 GitHub 个人主页展示，无代码、无部署。

#### Scenario: 部署关系可查
WHEN 有人想知道这个仓库是否参与 muyaya 线上部署
THEN 本 spec 给出明确答案与部署真相所在位置。

### Requirement: 文档归属
文档权威来源 SHALL 以如下为准，本 `openspec/` 不得复制或替代上游文档：
无既有文档；本 `openspec/` 即其全部文档。 改这个仓库等于改个人主页，无构建流程。

#### Scenario: 不重复维护上游文档
WHEN 需要了解内部实现
THEN 去上游文档查，而不是在本 `openspec/` 里找（这里只记录工作区差异）。
