# AGENTS.md - quanttide-laboratory

本仓库是**元仓库**：只登记引用，不放内容。改动在各实验室仓库内发生。

## 分层

| 目录 | 放什么 |
|------|--------|
| `defaults/` | 主体实验室（公司层），如 `quanttide-tech-lab` |
| `domains/` | 各领域实验室，命名 `quanttide-{域短名}-lab` |
| `independent/` | 暂无对应领域仓的实验室 |

## 约定

1. 子模块独立维护：在实验室仓内提交推送，本仓库只更新指针
2. 新增实验室：云端建仓 `quanttide-{域短名}-lab` → 本仓库 `git submodule add` 到对应分区 → 同步 README 清单表与 ROADMAP
3. 实验室不留正本：实验有效后把方法与经验提取到对应领域档案、产品与流程
4. 命名跟域短名走，不跟英文全称走（如 `quanttide-work-lab`，不是 `quanttide-knowledge-work-lab`）
5. 提交即推送

## 评判指标

简洁、生动：能少则少，用真实例子说话。
