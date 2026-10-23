# 《AI 软件工程 101：软件物态、智力边界、驱动动力与物理交互指导手册》
## ——《软件物态学：晶体、流体与制度性实在》工程与理论参考指南
*AI Software Engineering 101: Phases of Software, Crystals, Fluids, and Institutional Reality*

> 🌐 **Language / 语言**: **[简体中文](./README.md)** | **[English (`./README_EN.md`)](./README_EN.md)** | **[English Docs (`./en/`)](./en/README.md)**

**作者**：时恒  
**开源协议**：[GNU GPLv3 (`./LICENSE`)](./LICENSE)  
**定位**：AI 系统工程 101 指导手册与实证文献核查库

---

## 📖 导读与四大课题导航

本仓库是一份面向 AI 软件工程实践的 **101 指导手册**，围绕**“什么软件需要 LLM？AI 是晶体还是流体智力？软件由代码还是 Agent 驱动？AI 如何与物理世界可靠互动？”**四个核心课题展开，结合了软物质统计物理、计算认知科学、形式化验证软件工程与社会本体论的 45 篇权威文献核查。

### 🌟 0. 101 速读指导手册（3,000 字精要版，含完整 45 篇参考文献列表）
- 📄 **[《AI 软件工程 101：软件物态、智力边界、驱动动力与物理交互指导手册》（`./overview_software_phases.md`）](./overview_software_phases.md)**  
  浓缩四大课题的核心判断、定量实证数据、架构设计准则与全部 45 篇文献题录，适合 10 分钟快速通读或直接复制分享。

---

### 🎬 1. 旗舰工程实战案例（液晶态软件落地解析）
- 🏆 **[《什么是液晶态软件，以及它为什么如此有用？——以多模态状态编译引擎 Apostle 为例》（`./case_study_liquid_crystal_apostle.md`）](./case_study_liquid_crystal_apostle.md)**  
  以多模态内容编译引擎 Apostle 为工程案例，复盘“《施公案》第 9 集敲碎契约引发的相变坍缩事故”，拆解 TFT-LCD 六大组件工程映射、确定性先行（MM 原则）、“液晶屏坏点与偏色”的局部容错校准机制、11 条跨集状态不变量符号门禁（`invariants.ts`）、`pipelineTid` 事务防越集跳步、TypeScript AST 语法树安全改写器以及统一双层透明舞台（DOM + Three.js）8 轨确定性时间轴编译。

---

### 📘 2. 完整版技术手册与深度推导
- 📘 **[《软件物态学：晶体、流体与制度性实在》（完整版手册 `./software_phases.md`）](./software_phases.md)**
  - **命题零（物态篇）：什么软件需要 LLM？（软件物态分类学与主体间实在凝华）**——按 `[目的 Telos, 过程 Process, 结构 Schema]` 的自由度将软件划分为三种实用工具物态：**固态（晶体传统软件）**、**液晶态（LLM+ 结构化转换）**、**受控液态（装在晶体容器内的 Agent 个人助理）**，以及跨越工具与存在主义主体边界的**第四态（气态）**；并结合约翰·塞尔（Searle）构成性规则与波普尔（Popper）“世界 3 向下因果律”，阐明群体虚无共识凝华为**「制度性晶体（Institutional Crystal）」**的物理机制。
  - **命题一（心智篇）：AI 是晶体智力还是流体智力？**——剖析参数化静态晶格检索（有限集深度搜索）与 Transformer 前向传播内嵌的预条件梯度下降（$GD++$）及二阶牛顿-舒尔茨伪逆迭代，确立**状态空间复杂度阈值定律**（亚临界流体模拟 vs. 超临界气化相变崩溃）。
  - **命题二（动力篇）：软件的驱动动力（代码驱动还是 Agent 驱动？）**——超越静态工作流（流工程）与早期臃肿 Agent（7,000 行 ACI）的二元对立，遵循《脚手架脆弱性定理》，确立**外硬内柔的有界混合状态机 $\mathcal{M}_{\text{hybrid}}$**（宏观 100% 确定性固态代码驱动 + 微观 ~100 行原生 Bash 极简液态 Agent 驱动 + 100% 符号形式化验证门禁）。
  - **命题三（交互篇）：AI 与物理世界的互动（有界操作型本体/制度性晶体与联邦 MCP 协议）**——遵循最小本体承诺与防上下文腐败（Context Rot）铁律，将企业操作型本体的底层**动力学原语（Object, Link, Kinetic Action Writeback, Funnel）100% 硬编码**为制度性晶体，并在顶层通过**多态接口（Interfaces）与联邦 Ontology MCP 按需作用域投射（$\Phi_{\text{MCP}}$）**赋予 AI 零容错改写物理世界的向下因果力。

---

### 🔬 3. 四大命题专题核查报告与原始文献清单（Fact-Checking & Bibliography）

> **文献获取说明**：为严格尊重各学术出版机构与原作者版权，本地 `.pdf` 原文已通过 [`.gitignore`](./.gitignore) 忽略。完整的 **45 篇权威文献编号、arXiv ID、DOI、官方下载直链及一键拉取脚本** 均收录于 [**`./papers/README.md`**](./papers/README.md)。

| 课题与命题 | 专题核查与数学推演报告（相对路径） | 文献清单与官方下载链接 | 核验状态 |
| :--- | :--- | :--- | :---: |
| **命题零（物态篇）** | [`./verification_prop0_software_phases_and_philosophy.md`](./verification_prop0_software_phases_and_philosophy.md)<br>*软件四态物态学、Lehman SPE 同构、塞尔制度性事实与波普尔向下因果律* | [`./papers/README.md`](./papers/README.md) ｜ [`./papers/prop0/`](./papers/prop0/) | ✅ `VERIFIED` |
| **命题一（心智篇）** | [`./verification_prop1_cognition_and_planning.md`](./verification_prop1_cognition_and_planning.md)<br>*认知科学 CHC、隐式二阶牛顿元优化与 IPC 自动规划混淆域实证* | [`./papers/README.md`](./papers/README.md) ｜ [`./papers/prop1/`](./papers/prop1/) | ✅ `VERIFIED` |
| **命题二（动力篇）** | [`./verification_prop2_code_vs_agent.md`](./verification_prop2_code_vs_agent.md)<br>*级联幻觉、自省失效、流工程与百行极简自演进代理（`mini/Live-SWE-agent`）* | [`./papers/README.md`](./papers/README.md) ｜ [`./papers/prop2/`](./papers/prop2/) | ✅ `VERIFIED` |
| **命题三（交互篇）** | [`./verification_prop3_enterprise_ontology_and_mcp.md`](./verification_prop3_enterprise_ontology_and_mcp.md)<br>*最小本体承诺、上下文腐败、Palantir 动力学本体与联邦 MCP 协议* | [`./papers/README.md`](./papers/README.md) ｜ [`./papers/prop3/`](./papers/prop3/) | ✅ `VERIFIED` |

---

### 🧭 4. 配套开山祖师把脉 Skill：`ask-shiheng`（自指闭环 · 三问一处方）

> **本门总纲：「固态守其常，液晶取其巧，液态控其界，晶体收其功。」**  
> **立宗铁律：先定物态，再动代码；无处方，不动刀。**

为了让本手册的理论直接成为所有 AI 编码 Agent 动刀前的“前置宪法”，仓库内置了百行极简架构领航 Skill —— **[`./skills/ask-shiheng/SKILL.md`](./skills/ask-shiheng/SKILL.md)**（兼容 Antigravity / Claude Code / Cursor 等支持 `SKILL.md` 的 AI 编程助手）。

#### 📦 安装方式
```bash
# 方式一：通过 skills CLI 一键安装（适用于 Cursor / Claude Code 等）
npx skills@latest add Pabears/phases_of_software --skill ask-shiheng

# 方式二：软链至本地 Agent 全局配置目录
# Antigravity:
ln -sfn "$(pwd)/skills/ask-shiheng" ~/.gemini/config/skills/ask-shiheng
# Claude Code:
ln -sfn "$(pwd)/skills/ask-shiheng" ~/.claude/skills/ask-shiheng
# Cursor:
ln -sfn "$(pwd)/skills/ask-shiheng" ~/.cursor/skills/ask-shiheng
```

#### 🚀 自指闭环与使用方式（「三问一处方，开方即收刀」）
`ask-shiheng` 先用 **`[目的 Telos=1, 过程 Process=柔性导引, 结果 Schema=1]`** 约束自身，再通过盘问目标系统的 `[目的, 过程, 结果]` 组合为你开方。在新立项或改造现有项目时，Agent 会在写代码前自动触发（或由你直接唤起）：
1. **第一步：初诊与「三问把脉」**：
   - **第一问（定物态 · $2^3 + 1 = 9$ 形态映射与排雷）**：按 `[目的, 过程, 结果]` 组合，将模块精准落位至 `🪨 固态 [1,1,1]（纯代码，严禁沾 LLM）`、`💧 液晶态 [1,0,1]（LLM + 强 Schema 掩码单步提取）`、`🌊 受控液态 [1,0,0]（百行极简探针 + 四重防爆沙盒）`、`☁️ 无界气态 [0,0,0]（创意/陪伴，物理隔离写操作）` 或 `💎 制度性晶体（二阶社会性凝华：Object + Link + Kinetic Action 2PC 回写）`，并自动排查**账本液化、过冷正则脆断、无沙盒裸奔、27% 迎合扯淡、伪命题僵尸态**五大禁区；
   - **第二问（定裁判 · 复杂度阈值 $L^*$ 降维）**：检查单步任务是否超临界（$L > L^*$），并按容错率知情选配 `🛡️ 档位 A：符号固态门禁`、`👀 档位 B：双模型初筛 + 人在环终审`、或 `🎲 档位 C：纯 LLM 自省放飞`（透明提示 `84.45%` 漏检风险后 100% 尊重用户选择）；
   - **第三问（定数据线 · Middle-Out Action）**：锁定第一期唯一真实改写现实世界的**“数据线”（Kinetic Action）**，强制执行**「AI 沙盒提议（Proposal）与固态代码提交（Commit）物理分离」**。
2. **第二步：开具《时恒物态架构处方单》**：
   - 输出一页纸高密度处方：**模块 `[目的, 过程, 结果]` 切分表** + **外硬内柔 $\mathcal{M}_{\text{hybrid}}$ 状态机拓扑图（Mermaid）** + **制度性晶体与防上下文腐败（$\Phi_{\text{MCP}}$）红线** + **第一步落子建议**。
3. **第三步：克制收刀（固化 `PHASE_SPEC.md` 制度性晶体）**：
   - 开完方子立即停手，经你确认后固化为项目根目录的 `PHASE_SPEC.md`，作为后续所有编码 Agent 的最高宪法。

---

## ⚖️ 开源许可协议 (License)

本项目采用 **[GNU General Public License v3.0 (GPLv3)](./LICENSE)** 授权发布：
- **署名与同源共享（Copyleft）**：允许自由阅读、使用、修改与分发，任何衍生修改版本须保留原作者 **时恒** 署名并以相同 GPLv3 协议开放；
- **无担保免责声明（Section 15 & 16）**：本手册作为技术研究与工程交流文档按“原样（AS IS）”提供，不附带任何明示或暗示的商业或适用性担保。

© 2026 时恒. Licensed under [GNU GPLv3](./LICENSE).