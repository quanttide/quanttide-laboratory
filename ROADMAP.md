# quanttide-laboratory ROADMAP

## 预留项

| # | 项 | 层 | 说明 |
|---|----|----|------|
| 1 | 各领域实验室填充 | 领域层 | 40 个实验室已登记引用，多数仍是骨架，按需把实验放进去 |
| 2 | 实验室产出回流 | —— | 实验有效后把方法与经验提取到对应领域档案、产品与流程，不在实验室留正本 |
| 3 | 无领域实验室归位 | 独立层 | `quanttide-execution-lab`、`quanttide-game-lab` 暂无对应领域仓，待定归属或撤销 |

## 演进记录

- 2026-10-12：实验室许可证统一为 Apache 2.0——本仓内 22 个（5 个由 CC BY 4.0 切换：algorithm、auth、pay、project、work；17 个新增 LICENSE），另适配层 `quanttide-feishu-lab` 同步；元仓库自身 LICENSE 由 MIT 改为 Apache 2.0；`.gitmodules` 按字母序整理（algorithm 归位）；README 修正 support 描述。

- 2026-10-11：新增领域实验室 `quanttide-algorithm-lab`（算法工程），README 清单与计数同步为 40。

- 2026-10-10：新增领域实验室 `quanttide-search-lab`（搜索工程），README 清单与计数同步为 39。

- 2026-09-29：按 `quanttide-toolkit` 元仓库范式重整——分区改为 `defaults/`（主体）、`domains/`（领域）、`independent/`（无领域），38 个实验室登记为真正的子模块（含 gitlink），README 增「层」分类清单，补 ROADMAP 与 AGENTS。
- 2026-09-29：实验室统一改名 `quanttide-laboratory-of-{英文}` → `quanttide-{域短名}-lab`；`default/company` 改指 `quanttide-tech-lab`。
- 2026-08：创建本仓库（`default/company` + 各 examples 登记）。
