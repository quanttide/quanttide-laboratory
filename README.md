# 量潮实验室（quanttide-laboratory）

量潮实验体系的**元仓库**——聚合各领域的实验原型，分置于 `domains/`、`defaults/` 与 `independent/` 三个目录。各实验室是独立仓库（Git 子模块），独立演进，本仓库只追踪引用。

## 架构思想

实验室承接一件事：**正式流程之外「先试一试」**。试出来的方法与经验提取到对应领域的档案、产品与流程——实验室是入口，不留正本。

与同级的两个元仓库分工：

| 元仓库 | 聚合什么 | 产物去向 |
|:--|:--|:--|
| `quanttide-toolkit` | 语言无关的 toolkit 包 | 被端侧依赖 |
| **`quanttide-laboratory`（本仓库）** | 各领域的实验原型 | 验证有效后提取为方法、产品与流程 |

各领域仓的 `examples/{域短名}-lab` 是入口指针，本仓库是这些实验室的聚合视图——便于横向比对、复用与统一索引。

## 实验室清单

| 层 | 实验室 | 所属 | 定位 |
|:--|:--|:--|:--|
| 主体层 | [`quanttide-tech-lab`](defaults/quanttide-tech-lab) | 量潮科技（`default/quanttide-tech`） | 公司级实验空间：正式流程之外先试一试 |
| 领域层 | [`quanttide-agent-lab`](domains/quanttide-agent-lab) | [`quanttide-agent`](../../domains/quanttide-agent) | 智能体工程领域的实验与原型 |
| 领域层 | [`quanttide-asset-lab`](domains/quanttide-asset-lab) | [`quanttide-asset`](../../domains/quanttide-asset) | 资产管理领域的实验与原型 |
| 领域层 | [`quanttide-auth-lab`](domains/quanttide-auth-lab) | [`quanttide-auth`](../../domains/quanttide-auth) | 身份认证领域的实验与原型 |
| 领域层 | [`quanttide-code-lab`](domains/quanttide-code-lab) | [`quanttide-code`](../../domains/quanttide-code) | 软件工程领域的实验与原型 |
| 领域层 | [`quanttide-connect-lab`](domains/quanttide-connect-lab) | [`quanttide-connect`](../../domains/quanttide-connect) | 沟通管理领域的实验与原型 |
| 领域层 | [`quanttide-course-lab`](domains/quanttide-course-lab) | [`quanttide-course`](../../domains/quanttide-course) | 课程研发领域的实验与原型 |
| 领域层 | [`quanttide-crowd-lab`](domains/quanttide-crowd-lab) | [`quanttide-crowd`](../../domains/quanttide-crowd) | 众包管理领域的实验与原型 |
| 领域层 | [`quanttide-customer-lab`](domains/quanttide-customer-lab) | [`quanttide-customer`](../../domains/quanttide-customer) | 客户关系领域的实验与原型 |
| 领域层 | [`quanttide-data-lab`](domains/quanttide-data-lab) | [`quanttide-data`](../../domains/quanttide-data) | 数据工程领域的实验与原型 |
| 领域层 | [`quanttide-design-lab`](domains/quanttide-design-lab) | [`quanttide-design`](../../domains/quanttide-design) | 交互设计领域的实验与原型 |
| 领域层 | [`quanttide-devops-lab`](domains/quanttide-devops-lab) | [`quanttide-devops`](../../domains/quanttide-devops) | DevOps 工程领域的实验与原型 |
| 领域层 | [`quanttide-docs-lab`](domains/quanttide-docs-lab) | [`quanttide-docs`](../../domains/quanttide-docs) | 文档工程领域的实验与原型 |
| 领域层 | [`quanttide-econ-lab`](domains/quanttide-econ-lab) | [`quanttide-econ`](../../domains/quanttide-econ) | 经济建模领域的实验与原型 |
| 领域层 | [`quanttide-entrep-lab`](domains/quanttide-entrep-lab) | [`quanttide-entrep`](../../domains/quanttide-entrep) | 创业管理领域的实验与原型 |
| 领域层 | [`quanttide-execute-lab`](domains/quanttide-execute-lab) | [`quanttide-execute`](../../domains/quanttide-execute) | 执行管理领域的实验与原型 |
| 领域层 | [`quanttide-finance-lab`](domains/quanttide-finance-lab) | [`quanttide-finance`](../../domains/quanttide-finance) | 财务管理领域的实验与原型 |
| 领域层 | [`quanttide-growth-lab`](domains/quanttide-growth-lab) | [`quanttide-growth`](../../domains/quanttide-growth) | 增长管理领域的实验与原型 |
| 领域层 | [`quanttide-health-lab`](domains/quanttide-health-lab) | [`quanttide-health`](../../domains/quanttide-health) | 健康管理领域的实验与原型 |
| 领域层 | [`quanttide-human-lab`](domains/quanttide-human-lab) | [`quanttide-human`](../../domains/quanttide-human) | 人力资源领域的实验与原型 |
| 领域层 | [`quanttide-innov-lab`](domains/quanttide-innov-lab) | [`quanttide-innov`](../../domains/quanttide-innov) | 创新管理领域的实验与原型 |
| 领域层 | [`quanttide-knowl-lab`](domains/quanttide-knowl-lab) | [`quanttide-knowl`](../../domains/quanttide-knowl) | 知识工程领域的实验与原型 |
| 领域层 | [`quanttide-learn-lab`](domains/quanttide-learn-lab) | [`quanttide-learn`](../../domains/quanttide-learn) | 学习管理领域的实验与原型 |
| 领域层 | [`quanttide-media-lab`](domains/quanttide-media-lab) | [`quanttide-media`](../../domains/quanttide-media) | 新媒体运营领域的实验与原型 |
| 领域层 | [`quanttide-meta-lab`](domains/quanttide-meta-lab) | [`quanttide-meta`](../../domains/quanttide-meta) | 元工程领域的实验与原型 |
| 领域层 | [`quanttide-org-lab`](domains/quanttide-org-lab) | [`quanttide-org`](../../domains/quanttide-org) | 组织管理领域的实验与原型 |
| 领域层 | [`quanttide-pay-lab`](domains/quanttide-pay-lab) | [`quanttide-pay`](../../domains/quanttide-pay) | 支付工程领域的实验与原型 |
| 领域层 | [`quanttide-product-lab`](domains/quanttide-product-lab) | [`quanttide-product`](../../domains/quanttide-product) | 产品研发领域的实验与原型 |
| 领域层 | [`quanttide-project-lab`](domains/quanttide-project-lab) | [`quanttide-project`](../../domains/quanttide-project) | 项目管理领域的实验与原型 |
| 领域层 | [`quanttide-secret-lab`](domains/quanttide-secret-lab) | [`quanttide-secret`](../../domains/quanttide-secret) | 密码管理领域的实验与原型 |
| 领域层 | [`quanttide-security-lab`](domains/quanttide-security-lab) | [`quanttide-security`](../../domains/quanttide-security) | 安全工程领域的实验与原型 |
| 领域层 | [`quanttide-strategy-lab`](domains/quanttide-strategy-lab) | [`quanttide-strategy`](../../domains/quanttide-strategy) | 战略管理领域的实验与原型 |
| 领域层 | [`quanttide-support-lab`](domains/quanttide-support-lab) | [`quanttide-support`](../../domains/quanttide-support) | quanttide-support领域的实验与原型 |
| 领域层 | [`quanttide-think-lab`](domains/quanttide-think-lab) | [`quanttide-think`](../../domains/quanttide-think) | 认知工程领域的实验与原型 |
| 领域层 | [`quanttide-work-lab`](domains/quanttide-work-lab) | [`quanttide-work`](../../domains/quanttide-work) | 知识工作领域的实验与原型 |
| 领域层 | [`quanttide-write-lab`](domains/quanttide-write-lab) | [`quanttide-write`](../../domains/quanttide-write) | 写作管理领域的实验与原型 |
| 独立层 | [`quanttide-execution-lab`](independent/quanttide-execution-lab) | —— | 暂无对应领域仓，独立演进 |
| 独立层 | [`quanttide-game-lab`](independent/quanttide-game-lab) | —— | 暂无对应领域仓，独立演进 |

## 目录结构

```text
quanttide-laboratory/
├── defaults/       # 子模块：主体实验室（公司层）
├── domains/        # 子模块：各领域实验室（见上表）
├── independent/    # 子模块：暂无对应领域仓的实验室
├── AGENTS.md       # 智能体约定
├── LICENSE         # MIT 许可证
├── README.md       # 本文件
└── ROADMAP.md      # 路线图
```

## 快速开始

```bash
# 克隆（含子模块）
git clone --recurse-submodules https://github.com/quanttide/quanttide-laboratory.git

# 已有克隆时初始化/更新子模块
git submodule update --init --recursive
```

子模块是独立仓库，改动请在各实验室仓库内提交推送，本仓库只更新引用；智能体约定见 [AGENTS.md](AGENTS.md)。

## 许可证

本项目采用 [MIT](LICENSE) 许可证。
