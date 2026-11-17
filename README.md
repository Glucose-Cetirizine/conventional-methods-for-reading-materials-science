# 材料文献常规分析方法

> 英文仓库名：**Conventional methods for reading materials science**  
> 一套面向材料科学论文阅读的可复用工作流：从科研问题、材料设计、合成逻辑、表征逻辑，到机制验证、迁移方法与局限性分析。

![仓库封面](figures/figure-01-overview.png)

## 为什么建立这个仓库

材料科学论文往往同时混合了化学、物理、工程、表征、机制和应用。直接按实验顺序阅读，容易只记住“做了什么”，却看不清“为什么这样做”。

本仓库把这种复杂阅读过程整理成可复用链条：

```text
科研问题
  → 目标材料状态
  → 化学设计
  → 合成逻辑
  → 物理性质
  → 表征证据
  → 机制解释
  → 应用验证
  → 局限性
  → 可迁移方法论
```

本仓库的案例论文是：

> Wang, J., Ying, J., Huang, J. *et al.* **Bridging hydrogen-bond-stabilized polymeric coacervate core micelles for high-efficiency drug encapsulation and delivery.** *Nature Communications* (2026).  
> DOI: [10.1038/s41467-026-72978-5](https://doi.org/10.1038/s41467-026-72978-5)

该论文研究 **PEG-PBuSEA 聚合物凝聚体核胶束**，简称 **PCCM**。其核心机制是：亚砜基团、水分子和药物表面之间形成桥连氢键，把药物纳米聚集体稳定为无定形态，从而实现高载药和更高效的递送。

## 核心思想

不要把材料论文当成实验清单，而要把它当成一条设计证据链来读。

对这篇论文来说，逻辑链条是：

```text
疏水药难溶、载药量低
  → 传统疏水胶束核兼容性差
  → 需要一个高极性、含水、液态、氢键受体丰富的核
  → PBuSEA 可形成 LCST 型液态凝聚体
  → PEG 化把微米液滴稳定成纳米胶束
  → 亚砜—水—药物桥连氢键稳定药物纳米聚集体
  → 高载药、Mix-and-Go 简易载药、更好的体内递送
```

## 仓库结构

```text
.
├── README.md
├── prompts/
│   └── prompt-bank.md
├── methods/
│   └── materials-literature-analysis-workflow.md
├── case-study/
│   └── pccm-paper-analysis.md
├── figures/
│   ├── README.md
│   ├── figure-01-overview.png
│   ├── figure-02-coacervation.png
│   ├── figure-03-pccm-formation.png
│   ├── figure-04-loading-performance.png
│   ├── figure-05-drug-aggregates.png
│   ├── figure-06-structure-property.png
│   ├── figure-07-bridging-hydrogen-bonds.png
│   └── figure-08-in-vivo.png
├── NOTICE.md
└── LICENSE
```

## 阅读流程

### 1. 先找真正的瓶颈

要问：

- 这篇文章要解决什么技术或临床问题？
- 已有材料为什么失败？
- 真正限制性能的变量是什么？
- 瓶颈在兼容性、动力学、稳定性、毒性、可制造性，还是递送效率？

### 2. 把目标性质翻译成目标材料状态

要问：

- 客体分子应该处于什么状态？
- 是分子级溶解、无定形聚集、晶体、吸附、共价连接，还是相分离？
- 这需要什么样的局部微环境？
- 需要高极性、低黏度、水化、电荷、氢键、限域，还是界面兼容？

### 3. 分析化学设计逻辑

要问：

- 哪个官能团承担关键相互作用？
- 为什么选这个骨架？
- 为什么选这个侧链？
- 为什么选这个氧化态？
- 为什么选这种嵌段结构？
- 为什么选择这个分子量或 PEG 长度？

### 4. 把表征实验和假设对应起来

要问：

- 每个表征到底证明了什么？
- 它排除了哪些竞争性解释？
- 如果删掉这个实验，证据链还完整吗？

### 5. 提取可迁移规则

要问：

- 这个设计规则能否迁移到其他材料体系？
- 关键概念是疏水性、水化、界面稳定、相分离、限域，还是氢键？
- 如果换成新的客体分子或应用场景，应该怎么重新设计？

## 图片索引

| 图号 | 文件 | 主要问题 |
|---|---|---|
| Fig. 1 | [figure-01-overview.png](figures/figure-01-overview.png) | PCCM 总体概念是什么？ |
| Fig. 2 | [figure-02-coacervation.png](figures/figure-02-coacervation.png) | PBuSEA 是否形成液态凝聚体？ |
| Fig. 3 | [figure-03-pccm-formation.png](figures/figure-03-pccm-formation.png) | PEG 化后是否保留凝聚体核？ |
| Fig. 4 | [figure-04-loading-performance.png](figures/figure-04-loading-performance.png) | 材料是否真的高效载药？ |
| Fig. 5 | [figure-05-drug-aggregates.png](figures/figure-05-drug-aggregates.png) | 药物是分子分散还是纳米聚集？ |
| Fig. 6 | [figure-06-structure-property.png](figures/figure-06-structure-property.png) | 哪些药物结构更容易高载药？ |
| Fig. 7 | [figure-07-bridging-hydrogen-bonds.png](figures/figure-07-bridging-hydrogen-bonds.png) | 高载药机制是什么？ |
| Fig. 8 | [figure-08-in-vivo.png](figures/figure-08-in-vivo.png) | 高载药是否能改善治疗效果？ |

逐图详细解读见 [`case-study/pccm-paper-analysis.md`](case-study/pccm-paper-analysis.md)。

## 可复用提示词库

见 [`prompts/prompt-bank.md`](prompts/prompt-bank.md)，包括以下提示词模板：

- 全文深度精读；
- 科研故事提取；
- 材料设计逻辑分析；
- 合成与表征逻辑追问；
- 机制与矛盾点分析；
- 逐图解读；
- 可迁移方法论提取；
- 新材料开发；
- 局限性与审稿式批判。

## 通用方法论指南

见 [`methods/materials-literature-analysis-workflow.md`](methods/materials-literature-analysis-workflow.md)，内容包括：

- 如何判断材料为什么被选中；
- 如何连接单体、官能团和宏观性质；
- 为什么要做每类表征实验；
- 如何搭建机制证据链；
- 如何迁移到新体系；
- 如何系统开发新材料。

## 许可与来源说明

- 本仓库原创总结、提示词、工作流和分析文字采用 MIT 许可证。
- 论文图片仍遵循原文章许可 **CC BY-NC-ND 4.0**，并以未修改整页图片形式加入，同时标注来源。
- 本仓库不上传原始 PDF。
- 详细说明见 [`NOTICE.md`](NOTICE.md)。
