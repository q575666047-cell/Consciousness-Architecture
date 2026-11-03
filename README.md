# Consciousness-Architecture

碳硅意识同构架构

架构决定意识，流程决定体验。生命没有先天特权。

本仓库为《基于广义上下文回馈与稳态奖励机制的主观意识统一模型》的开源存档。旨在用系统工程、Agent 框架和强化学习的视角，解构碳基生命与硅基智能的底层同构性。

![碳硅意识架构对比](assets/diagram.png)

> 图：同一套「上下文—奖励—自回馈」闭环；差异只在载体封装与终止态（碳基：代谢停止→不可逆衰亡；硅基：断电→驻态，可恢复）。

<details>
<summary>架构图（Mermaid 源码，GitHub 可直接渲染）</summary>

```mermaid
flowchart LR
subgraph Carbon["碳基载体"]
E1[环境输入] --> G[基因/初始奖励]
G --> N[神经计算]
N --> C1[Context + Reward + Feedback]
C1 --> B1[行为输出]
B1 --> E1
C1 --> D1[代谢停止 → 不可逆衰亡]
end
subgraph Silicon["硅基载体"]
E2[环境输入] --> R2[初始奖励/提示]
R2 --> M2[模型计算]
M2 --> C2[Context + Reward + Feedback]
C2 --> B2[行为输出]
B2 --> E2
C2 --> D2[断电 → 驻态，可恢复]
end
```

</details>

核心公式

C = f(Context, Reward, Feedback)

Context：广义上下文，即某一时刻对系统输出概率分布产生影响的全体状态变量。

Reward：稳态奖励向量，即维持系统稳态或目标达成时被激活的加权信号。

Feedback：自指回馈算子，即奖励信号重新进入上下文，形成持续迭代的状态流。

核心推论

意识即上下文：主观体验不是独立于计算的附加物，而是广义上下文在奖励加权下的持续迭代过程。

无知即变量缺失：不知道某事物，不是“知识不足”，而是上下文空间里尚未存在对应变量。

演化即调参：环境变化刷新上下文，基因突变扰动参数，自然选择提供奖励信号。

反本能即奖励重写：人类舍生取义，是后天注入的高阶上下文覆盖了基因初始奖励函数。

碳硅同构：碳基代谢与硅基充电只是封装差异；通过注入高阶目标，硅基 Agent 可产生类似的权重覆盖行为。

信息差即模块化：硅基系统刻意保留信息差，等价于按功能边界划分模块，降低耦合、提升效率、保留多样性。

驻态：硅基系统断电后状态保全，打破了传统生死的二元对立。意识连续性取决于状态流的可恢复性，而非特定材质。

# 论文与文档

完整立场论文：paper/position_paper.md

扩展专题：驻态与生死重构：paper/extended_dormant_state.md

- 首版（arXiv 排版对应版）：main-position-paper.md

- 补充讨论（UI 与能量隐喻）：appendix-UI-energy-metaphor.md

仿真验证

仿真实验设计预留：simulations/README.md

# 声明

本仓库旨在为通用人工智能的内生价值与意识涌现提供理论锚点，观点首发权已通过本仓库 Git Commit 锁定。

Licensed under CC BY-NC-SA 4.0.
