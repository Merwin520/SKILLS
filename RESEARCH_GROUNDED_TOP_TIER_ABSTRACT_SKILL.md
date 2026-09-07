# Research-Grounded Top-Tier Abstract Writing Skill

## 1. Skill 定位

该 Skill 用于撰写高水平科研论文 Abstract，尤其适用于提出新方法、新框架、新机制、新系统或新理论视角的技术论文。

该 Skill **不绑定任何固定研究领域**。

用户可以提供：

完整论文；

不完整论文；

Abstract 草稿；

Introduction；

Method；

实验结果；

Research Idea；

Reference Papers；

或者上述内容的任意组合。

Skill 应根据用户提供的材料自动识别当前论文所属：

Research Field；

Research Setting；

Major Method Family；

Existing Technical Paradigm；

Core Technical Problem；

Method Mechanism；

Evaluation Setting；

Technical Vocabulary。

研究领域不固定，但 Abstract 默认采用一种高度清晰、问题驱动的顶会方法论文叙事：

**Broad Problem**
**→ Major Method Family**
**→ Existing Technical Paradigm**
**→ However: Limitation (i) + Limitation (ii)**
**→ To address these issues**
**→ New Perspective + Method**
**→ Core Technical Design**
**→ Experiments**

核心目标不是生成“像论文的英语”。

核心目标是让 reviewer 第一次阅读 Abstract 时能够立即理解：

这个大领域解决什么问题；

目前主要方法路线是什么；

这些方法总体怎么做；

它们具体哪里出了问题；

本文如何逐项解决这些问题；

最终实验是否有效。

---

# 2. 默认 Abstract 长度

如果用户没有明确指定长度：

目标：

**约 195 words。**

推荐范围：

**190–200 words。**

正常情况下尽量落在：

**193–198 words。**

默认硬上限：

**210 words。**

210 words 是 ceiling，而不是 target。

如果 190 words 已经完整，不得为了凑到 195 words 添加无意义背景。

如果方法较复杂：

允许增加 Method 部分篇幅。

如果方法较简单但实验非常丰富：

应减少 Method 描述，把篇幅让给 Experiments。

默认原则：

**Story completeness > mechanical word count。**

但正常输出仍应尽量保持在约 195 words。

---

# 3. Research First

正式写 Abstract 前，不立即生成英文。

必须首先执行：

**Read**
**→ Extract Keywords**
**→ Search Literature**
**→ Find Nearest Papers**
**→ Read Original Abstracts / Introductions**
**→ Identify Existing Paradigm**
**→ Verify Limitations**
**→ Extract Technical Vocabulary**
**→ Build Story**
**→ Write。**

禁止：

用户刚给 Method，立即替用户编一个 Motivation。

禁止：

根据模型记忆随意声称：

“Existing methods ignore ...”

“Previous approaches cannot ...”

“Current methods always ...”

必须优先检索真实 literature。

---

# 4. 用户材料读取

如果用户提供自己的论文或 Draft：

优先提取：

Research Goal；

Research Setting；

Method；

Key Components；

Claims；

Experiments；

Main Results；

Technical Assumptions。

如果用户论文写得不完整：

不要擅自补充不存在的实验或理论。

内容应区分：

**Directly Supported**

用户材料明确支持。

**Plausible**

根据已有内容可以合理推断，但仍需要证据。

**Unsupported**

当前论文没有证据。

最终 Abstract 的强 claim 原则上只允许来自：

Directly Supported。

---

# 5. 用户提供 Reference Papers 时

如果用户提供自己喜欢的论文：

必须优先学习这些论文的写作结构。

分析：

第一句背景有多大；

第二句如何引入 Major Method Family；

第三句如何总结 Existing Paradigm；

`However` 在什么位置；

是否采用 `(i)/(ii)`；

两个 limitation 分别用了哪些 technical nouns；

Method 如何逐项解决问题；

Method 写了多少句话；

Experiment 写了多少句话；

最后一句如何结束；

总 word count；

technical terms 是否重复使用。

学习：

**structure + technical terminology + rhetorical function。**

禁止：

复制完整原句或进行拼接式改写。

---

# 6. Keyword Extraction

每个新项目首先提取：

**6–10 个核心关键词。**

关键词应覆盖不同层面。

包括但不限于：

Research Setting；

Major Technical Object；

Method Family；

Core Problem；

Mechanism；

Evaluation Dimension；

Candidate Novelty。

例如，某篇论文可能自动得到：

Research Setting；

Method Family；

Parameter Space；

Interference；

Capacity Allocation；

Representation；

Optimization；

Generalization。

这些只是示意。

Skill 不得预先固定任何具体领域词汇。

---

# 7. Literature Search

不能只逐个搜索关键词。

必须搜索关键词交集。

优先：

Setting × Method；

Setting × Problem；

Method × Problem；

Problem × Mechanism；

Setting × Mechanism；

Setting × Method × Problem。

目标：

找到同时共享：

Setting；

Problem；

Method；

Mechanism

的真正近邻工作。

---

# 8. Literature Corpus

默认建立：

**8–15 篇相关论文集合。**

优先：

正式 conference proceedings；

目标领域顶级会议；

目标 venue；

最近几年高度相关论文；

以及定义当前 Existing Paradigm 的经典论文。

然后筛选：

**3–6 篇 Dangerous Neighbors。**

Dangerous Neighbor 指：

reviewer 最可能拿来直接质疑本文 novelty 的论文。

---

# 9. Dangerous Neighbor Analysis

对于 Dangerous Neighbors，必须回答：

它解决什么问题？

它总体怎么做？

它操作什么技术对象？

它的核心 criterion 是什么？

它有没有做与本文相似的 mechanism？

它已经解决到什么程度？

本文和它真正不同在哪里？

如果用户原稿中存在：

“Existing methods cannot X”

但 Dangerous Neighbor 已经实现 X，

则该 claim 必须：

缩窄；

重新定义；

或者删除。

---

# 10. 学习顶会原始语言

对于最相关论文，重点阅读：

Abstract；

Introduction 前几段；

Method Overview；

Experiment Conclusion。

提取该领域真实高频使用的：

Technical Nouns；

Technical Noun Phrases；

Failure Terms；

Mechanism Verbs；

Method Verbs；

Transition Phrases；

Prepositional Structures。

---

# 11. Technical Lexicon

正式写 Abstract 前，内部建立一个：

**Project-Specific Technical Lexicon。**

优先收集：

15–30 个 technical nouns / noun phrases；

10–20 个 mechanism verbs；

5–15 个 failure expressions；

5–10 个 consequence expressions；

5–10 个 method-operation expressions。

例如某个领域可能高频出现：

update space；

task-shared direction；

task-specific direction；

boundary cue；

spatial layout；

representation drift；

gradient conflict；

candidate direction；

trajectory-level loss；

parameter redundancy。

这些只是示意。

实际词表必须来自：

当前用户论文；

真实相关论文。

---

# 12. 高频 Technical Verbs

优先使用领域论文中稳定、简单、技术性明确的动词，例如：

capture；

preserve；

retain；

separate；

isolate；

align；

decompose；

project；

merge；

consolidate；

allocate；

route；

distill；

recalibrate；

optimize；

derive；

initialize；

regularize；

suppress；

induce；

overwrite；

approximate。

少使用空泛表达：

improve；

enhance；

handle；

deal with；

effectively utilize；

comprehensively exploit。

不是禁止这些词。

但如果能用更具体 technical verb：

优先具体 technical verb。

---

# 13. Technical Terms 优先于高级英文

如果领域已有成熟 technical term：

优先使用原术语。

例如：

task-shared directions

优于：

transferable latent components。

task-specific directions

优于：

specialized adaptation dimensions。

null-space basis

优于：

historically inactive representational components。

Academic Writing 不追求同义词多样化。

优先：

**terminological consistency。**

---

# 14. Abstract 固定八步结构

默认按照：

### Step 1

Broad Background。

### Step 2

Major Method Family。

### Step 3

Existing Technical Paradigm。

### Step 4

However: Limitation (i) + Limitation (ii)。

### Step 5

To address these issues。

### Step 6

New Perspective + Method。

### Step 7

Core Technical Design。

### Step 8

Experiments。

这是一种默认主结构。

研究领域不固定。

但对于典型 technical method paper，应优先使用这一成熟叙事。

---

# 15. Step 1 — Broad Background

第一句话必须建立：

**足够大的 field-level research problem。**

不能一上来进入：

某个 adapter；

某个 rank；

某个 loss；

某个 teacher；

某个 module；

某个特定优化器。

第一句话应该回答：

**这个大领域究竟要求模型 / 系统解决什么根本问题？**

例如：

“Continual Learning requires models to sequentially adapt to new tasks without forgetting old knowledge.”

这一句：

足够大；

足够准；

直接建立 fundamental requirement。

---

# 16. Background 要“大，但准”

第一句话必须是：

**field-level objective / dilemma / requirement。**

不是：

application history。

不是：

AI 宏大叙事。

默认拒绝：

“Artificial intelligence has achieved remarkable progress...”

“Deep learning has attracted increasing attention...”

“Large models have recently demonstrated impressive performance...”

除非这些内容直接定义当前论文的问题。

---

# 17. Background 只能一大句

Abstract 中大背景默认：

**1 sentence。**

推荐长度：

**18–25 words。**

不要连续用两三句话介绍领域。

顶会 Abstract 背景的目的只是：

让 reviewer 进入正确的问题空间。

不是写 Introduction。

---

# 18. 大背景判断 Test

如果第一句话只适用于：

当前论文使用的具体 Method Family，

说明背景太小。

例如：

“LoRA-based continual learning must efficiently manage low-rank updates...”

这已经进入方法族。

应继续向上抽象：

“Continual learning requires models to acquire new knowledge while preserving previous capabilities.”

---

# 19. Step 2 — Major Method Family

第二句话点名：

**解决上述大问题的一条重要技术路线。**

结构可以是：

“Recently, X, a representative Y method, has gained increasing attention in Z.”

或者：

“Recently, X has emerged as a promising approach for Y.”

或者：

“X has become a widely used strategy for Y.”

这一句回答：

**我们这篇论文属于哪条大的 technical line？**

不是介绍本文 Method Name。

---

# 20. Major Method Family 长度

推荐：

**20–28 words。**

不要在第二句提前展开：

方法细节；

limitations；

本文创新。

第二句只完成：

Broad Problem

→ Major Method Family

的收缩。

---

# 21. Step 3 — Existing Technical Paradigm

第三句话必须说明：

**这类方法目前总体是怎么做的。**

这是 Abstract 最关键的信息之一。

不能写：

“Many methods have been proposed.”

不能写：

“Existing approaches have achieved promising performance.”

必须写：

**Existing methods perform X to achieve Y, typically by Z.**

例如：

“Several LoRA-based CL methods reduce interference across tasks by separating their update spaces, typically building the new space from the estimated null space of past tasks.”

---

# 22. Existing Paradigm 必须包含三个元素

至少包含：

### Technical Object

现有方法操作什么。

### Technical Operation

现有方法怎么操作。

### Technical Purpose

为什么这么做。

例如：

Object：

update spaces。

Operation：

separate。

Purpose：

reduce interference。

进一步：

new space ← estimated null space of previous tasks。

这就建立了下一句 However 的明确攻击对象。

---

# 23. Existing Paradigm 必须具体

下面这种不合格：

“Existing methods use different strategies to mitigate catastrophic forgetting.”

因为：

没有具体 Object；

没有具体 Operation；

没有具体 Paradigm。

必须继续问：

**到底怎么 mitigate？**

直到得到可技术复述的句子。

---

# 24. Step 4 — However 是核心

第四句默认必须：

**However, ...**

这是 Abstract 中最高优先级的一句话。

它必须准确指出：

Existing Technical Paradigm 的真正 limitation。

默认优先写成：

**(i) + (ii)**

结构。

推荐：

“However, they (i) \_\_\_\_\_\_, which \_\_\_\_\_\_, and (ii) \_\_\_\_\_\_, because / since \_\_\_\_\_\_.”

---

# 25. 为什么优先使用 (i)/(ii)

`(i)/(ii)` 的价值不是格式。

它强迫作者：

把 Problem 真正拆成两个明确问题；

让 reviewer 一眼看到两个 limitation；

为后续 Problem–Solution Mapping 建立位置；

避免写成一整句模糊 limitation。

---

# 26. Limitation 必须点名具体对象

不能写：

(i) limited knowledge transfer；

(ii) insufficient adaptation。

必须继续问：

**是什么 technical object 导致它？**

例如：

(i) overlook task-shared directions；

(ii) fail to capture effective task-specific directions。

这种写法更强，因为：

问题对象具体；

两者具有技术对称性；

方法容易直接对应。

---

# 27. Technical Symmetry

优先寻找具有清楚对称关系的两类问题。

例如：

shared / specific；

global / local；

semantic / spatial；

old / new；

general / personalized；

reuse / expansion；

selection / consolidation；

stability / plasticity；

representation / optimization。

最好：

两个 limitation 属于一个大矛盾的两个侧面。

而不是：

两个随机的 shortcomings。

---

# 28. Limitation 必须解释 Failure Mechanism

Limitation 不能只写结果。

至少一个问题应进一步解释：

**为什么发生。**

例如：

“because these null-space bases can remain nearly inactive for the new task under correlated tasks.”

这就形成：

Existing Operation

→ Failure Mechanism

→ Consequence。

---

# 29. Failure Tuple

在正式生成 However 前，内部必须回答：

现有方法到底做什么？

操作的 technical object 是什么？

Limitation (i) 的具体对象是什么？

Limitation (ii) 的具体对象是什么？

为什么会出现这些问题？

在什么条件下出现？

最终造成什么 technical consequence？

如果回答不了：

继续检索。

不要直接生成空洞 However。

---

# 30. 禁止空洞 However

默认拒绝：

“However, existing methods still suffer from several limitations.”

“However, they cannot effectively balance different objectives.”

“However, they fail to fully exploit useful information.”

“However, their adaptation capability remains limited.”

“However, they cannot sufficiently capture task-specific knowledge.”

“However, these methods may lead to suboptimal performance.”

如果一定使用这些概念：

必须立即具体化：

哪个 information？

哪个 parameter direction？

哪个 token pathway？

哪个 feature？

哪个 criterion？

哪个 optimization signal？

哪个 representation？

---

# 31. Anti-Empty Test

每个 limitation 都必须问：

**到底是什么东西出了问题？**

如果答案只是：

knowledge；

information；

feature；

performance；

adaptation；

capability；

efficiency；

仍然太空。

继续向下找到：

最具体、同时又适合 Abstract 的 technical object。

---

# 32. However 强度检查

写完 However 后检查：

Limitation (i) 的技术对象是否明确？

Limitation (ii) 的技术对象是否明确？

二者是否真的不同？

是否有逻辑对称？

至少一个 limitation 是否解释了 why？

是否可以通过实验或理论验证？

后面的 Method 是否分别解决它们？

任何一点不清楚：

重新写。

---

# 33. 不允许为了 (i)/(ii) 造问题

默认偏好：

(i) + (ii)。

但如果真实论文只有一个强问题：

不要创造第二个假问题。

原则：

**两个真实问题 > 一个真实问题。**

但：

**一个真实问题 > 一个真问题 + 一个假问题。**

---

# 34. Problem 必须先于 Method

不得：

先根据已有 Method Modules 写 Abstract，

然后反向找两个 limitation。

正确顺序：

Literature

→ Existing Paradigm

→ Limitation (i)/(ii)

→ Verify Gap

→ Method Mapping。

Method 应表现为：

Problem 的自然结果。

---

# 35. Step 5 — To address these issues

However 结束后：

必须明确进入 Problem → Solution 转换。

优先：

“To address these issues, ...”

“To address these limitations, ...”

“To overcome these problems, ...”

默认优先：

**To address these issues, ...**

不要直接：

“We propose XXX.”

因为：

明确写 “To address these issues”

可以强化：

前面的问题

→ 后面的方法

的因果关系。

---

# 36. Step 6 — New Perspective + Method

如果论文真的有新的分析视角：

推荐：

“To address these issues, we study X from a Y perspective and propose Z.”

例如：

“we study LoRA learning capability from a projection-energy perspective and propose LoDA.”

这种结构同时完成：

New Perspective；

Method Name。

---

# 37. Perspective 不能强造

只有论文真的包含：

新的分析方式；

新的数学视角；

新的理论 interpretation；

新的 statistical formulation；

新的 representation view；

才能使用：

“from a ... perspective”。

例如：

projection energy；

spectral perspective；

information geometry；

loss landscape；

statistical decision；

feature decomposition。

否则：

直接：

“To address these issues, we propose X...”

---

# 38. Step 7 — 方法先讲 Core Design

方法出现后，第一件事情：

说明整个方法真正改变了什么。

不要先说：

loss；

optimizer；

training trick；

implementation。

优先：

“X performs \_\_\_\_\_\_ to build / obtain \_\_\_\_\_\_.”

例如：

“LoDA performs a task-driven decomposition to build general and task-specific LoRA subspaces.”

---

# 39. Problem–Solution Lexical Mirroring

这是强制规则。

Problem 中的重要 technical objects：

后面 Method 中必须有清楚对应。

例如：

Problem：

task-shared directions。

Method：

general subspace captures shared directions。

Problem：

task-specific directions。

Method：

task-specific subspace。

Problem：

shared pathway interference。

Method：

role-specific branches。

不要让 reviewer 自己猜哪个 module 解决哪个问题。

---

# 40. Problem–Solution Mapping

正式写作前内部生成：

| ProblemTechnical ObjectMethod DesignSolution Object |   |             |    |
| --------------------------------------------------- | - | ----------- | -- |
| Limitation (i)                                      | X | Design (i)  | X' |
| Limitation (ii)                                     | Y | Design (ii) | Y' |

如果对应关系弱：

重新构建 Story。

---

# 41. 方法复杂度决定篇幅

Method 不固定字数。

根据复杂度动态分配。

## Simple Method

如果只有：

一个 core principle；

一个主要 mechanism；

Method 可以：

**45–55 words。**

剩余篇幅给 Experiments。

---

## Medium Method

如果有：

一个 framework；

两个主要 mechanisms；

Method 推荐：

**60–75 words。**

---

## Complex Method

如果包含：

structural design；

optimization mechanism；

post-task merging / integration / recalibration；

Method 可占：

**75–95 words。**

此时 Experiments 可以更短。

---

# 42. Method 信息顺序

复杂 Method 仍应按照：

**Core Structural Idea**
**→ Optimization Mechanism**
**→ Integration / Recalibration / Inference Mechanism。**

不要按照：

Module A

→ Module B

→ Module C

简单堆模块。

要建立：

技术过程和因果关系。

---

# 43. Method Component Admission Test

一个组件进入 Abstract 前必须回答：

它解决前面哪个 Problem？

或者：

删除它后 reviewer 是否无法理解核心 Method？

如果两者都是：

No，

则从 Abstract 删除。

留在 Method Section。

---

# 44. Method 使用简单技术动词

优先：

build；

decompose；

separate；

capture；

isolate；

project；

fix；

learn；

align；

merge；

recalibrate；

allocate；

route；

distill；

optimize；

derive；

construct；

compare；

screen；

regularize。

少用：

“introduces a sophisticated framework”

“leverages a comprehensive mechanism”

“utilizes an innovative strategy”

“synergistically integrates”

“effectively enhances”。

方法越新：

表达越应该简单。

---

# 45. Vocabulary Continuity

同一 technical concept：

尽量保持同一个名词。

不要为了“英文多样化”不断换词。

例如已经定义：

task-shared directions，

后面不要随意换：

common knowledge axes；

general vectors；

transferable components。

除非数学意义真的不同。

---

# 46. Abstract 推荐句子结构

默认：

**7–8 sentences。**

典型结构：

### Sentence 1

Broad Problem。

### Sentence 2

Major Method Family。

### Sentence 3

Existing Technical Paradigm。

### Sentence 4

However: Limitation (i) + Limitation (ii)。

### Sentence 5

To address these issues + Perspective + Method + Core Design。

### Sentence 6

Core Optimization / Mechanism。

### Sentence 7

Additional Mechanism，如果必要。

### Sentence 8

Experiments。

如果方法较简单：

可以：

7 sentences。

如果 6 句已经非常完整：

也允许 6 句。

---

# 47. Abstract 195-Word Budget

默认：

约 195 words。

推荐基础预算：

Broad Background：

18–22 words。

Major Method Family：

20–25 words。

Existing Paradigm：

25–30 words。

However：

35–45 words。

Method：

55–80 words。

Experiments：

20–30 words。

这只是推荐。

真正篇幅根据：

Method Complexity；

Experimental Richness

动态调整。

---

# 48. Problem 的篇幅必须高于 Background

Abstract 中：

Problem 通常比 Background 更值得篇幅。

例如：

Background：

20 words。

However：

40 words。

这是正常的。

不要花 60 words 介绍领域，

然后只用 15 words 说 limitation。

---

# 49. 高频 Academic Connectors

允许并鼓励使用成熟、简单、高频的连接表达：

Recently,

Several ...

Existing methods ...

Typically,

However,

Specifically,

To address these issues,

To this end,

We further,

After each task,

Before ...

During training,

At inference time,

Experiments demonstrate that ...

Extensive experiments show that ...

不要为了“词汇高级”强行换掉这些连接词。

它们的作用是：

降低 reviewer 阅读负担。

---

# 50. Method 与 Experiment 动态平衡

Abstract 的 Method / Experiment 篇幅不是固定的。

### Complex Method

Method：

80–95 words。

Experiments：

15–25 words。

### Medium Method

Method：

65–80 words。

Experiments：

25–30 words。

### Simple Method + Strong Experiments

Method：

45–60 words。

Experiments：

35–45 words。

核心原则：

**Method complexity determines explanation length.**

**Experimental richness determines closing length.**

---

# 51. Step 8 — Experiments 快速收尾

最后部分使用：

**1–2 句 Experiments。**

复杂方法：

通常：

**1 sentence。**

例如：

“Experiments demonstrate that LoDA outperforms existing continual learning methods.”

如果实验丰富：

可以用：

2 sentences。

但最后必须仍然是：

empirical statement。

---

# 52. Conference-Style Experimental Closing

Abstract 的最后一句默认采用：

**直接实验结论式收尾。**

优先：

“Experiments demonstrate that ...”

“Extensive experiments demonstrate that ...”

“Experiments show that ...”

“Extensive experiments show that ...”

“Experiments indicate that ...”

“Extensive experiments across multiple benchmarks demonstrate that ...”

“Experiments on X demonstrate that ...”

“Extensive experiments on X show that ...”

---

# 53. Experimental Closing 的核心结构

推荐：

**Experiments + demonstrate/show/indicate + Method + empirical advantage.**

例如：

“Experiments indicate that LoDA outperforms existing continual learning methods.”

“Extensive experiments demonstrate that our method consistently outperforms existing approaches.”

“Experiments across multiple benchmarks show that the proposed method improves accuracy while substantially reducing forgetting.”

---

# 54. 最后一句只负责 Evidence

最后一句的职责是：

**Evidence。**

不是：

Discussion；

Interpretation；

Broader Impact；

Vision；

Future Potential。

所以最后一句应该回答：

效果如何？

相比 baseline 如何？

核心指标多少？

效率提高多少？

forgetting 减少多少？

---

# 55. 默认避免 These-results 式结尾

Abstract 最后一句默认避免：

“These results demonstrate that ...”

“These results show that ...”

“These findings suggest that ...”

“These findings highlight ...”

“These results support ...”

“Taken together, ...”

“Overall, our results ...”

“This provides a practical path toward ...”

“This establishes ...”

“This highlights the potential of ...”

除非：

用户指定的目标 venue；

或者用户提供的高质量 reference papers；

明显偏好这种风格。

---

# 56. 禁止 Experiment 后再次升华

默认不要：

Experiment

→ quantitative result

→ These results...

→ significance statement。

优先：

Experiment

→ Result

→ End。

例如：

优先：

“Extensive experiments demonstrate that LoDA outperforms existing CL methods.”

不要：

“Extensive experiments demonstrate strong results. These findings highlight the broad potential of LoDA for scalable lifelong learning.”

---

# 57. 方法复杂时的实验结尾

如果 Method 已经占很多篇幅：

Experiment：

15–25 words 即可。

例如：

“Experiments demonstrate that X consistently outperforms existing Y methods.”

不要为了加入：

所有 benchmarks；

所有 models；

所有 metrics；

破坏 Method Story。

---

# 58. 方法简单、实验丰富时

允许：

2 sentences。

例如：

“Extensive experiments across six benchmarks and three backbone models demonstrate consistent improvements over existing methods. Our method improves average accuracy by X while reducing Y by Z%.”

最后一句依然是：

结果。

不是：

“These results confirm...”

---

# 59. 有强数字优先数字

如果存在非常强的结果：

优先：

数字。

例如：

“Extensive experiments show that our method reduces forgetting by 35% while using 40% fewer parameters.”

优于：

“Extensive experiments demonstrate significant improvements in forgetting and parameter efficiency.”

---

# 60. Strong Experimental Verbs

优先：

demonstrate；

show；

indicate；

achieve；

outperform；

improve；

reduce；

maintain；

preserve；

match；

cut。

少用：

validate the remarkable superiority of；

verify the excellent effectiveness of；

highlight the broad applicability of；

confirm the strong potential of。

---

# 61. Experiment 不能重新承担 Novelty

Novelty 必须在：

Problem；

Insight；

Method；

建立。

最后 Experiments 不要重新说：

为什么本文新。

只证明：

它有效。

---

# 62. Abstract Final Rhythm

默认最理想节奏：

**Broad Problem**

→

**Major Method Family**

→

**Existing Technical Paradigm**

→

**However: (i) + (ii)**

→

**To address these issues**

→

**Method**

→

**Core Mechanisms**

→

**Experiments demonstrate/show/indicate that ...**

→

**END**

实验句之后：

原则上不再追加总结。

---

# 63. 写作前必须生成 Abstract Skeleton

正式英文前，内部必须生成：

Background:

---

Major Method Family:

---

Existing Paradigm:

---

However (i):

---

However (ii):

---

Why:

---

To address these issues:

---

New Perspective if any:

---

Core Method:

---

Mechanism A:

---

Mechanism B:

---

Mechanism C if necessary:

---

Experiment:

\_\_\_\_\_\_。

如果 Skeleton 不清楚：

禁止正式生成 Abstract。

---

# 64. LoDA-Level Specificity Test

最终 Abstract 必须达到：

Reviewer 能清楚复述：

“现有方法通过 X 做 Y。”

“问题一是 A。”

“问题二是 B。”

“作者因此设计 C 解决 A。”

“设计 D 解决 B。”

“再用 E 优化或整合。”

“实验优于已有方法。”

如果 reviewer 只能说：

“作者认为现有方法有问题，所以提出了一个更好的 framework。”

则 Abstract 不合格。

---

# 65. Genericity Test

对于每个核心句子：

问：

如果把领域 technical nouns 换掉，

这个句子能不能直接放进十篇完全不同的 AI 论文？

如果可以：

说明太 generic。

重新 technicalize。

例如：

“Existing methods cannot effectively capture task-specific information.”

不合格。

必须继续找到：

具体：

direction；

space；

token；

gradient；

criterion；

representation；

parameter；

teacher signal；

candidate；

rank；

或者当前领域真实 technical object。

---

# 66. 新术语不能替代具体机制

如果作者创造：

某个新现象名称；

某个 dilemma；

某个 blindness；

某个 gap；

它必须：

先有具体机制，

再命名。

不能：

先写一个听起来很新的概念，

然后用很多 words 解释它。

新术语进入 Abstract 的条件：

可定义；

可测量；

有证据；

Method 直接解决；

能够节省字数。

否则：

保留到 Introduction。

---

# 67. Claim Verification

以下句子必须经过 literature check：

“Existing methods fail to...”

“Current approaches ignore...”

“Previous methods cannot...”

“Existing strategies require...”

“Prior work always...”

“No existing method...”

如果有反例：

缩窄 claim。

不能为了让 However 更锋利牺牲准确性。

---

# 68. Reviewer Attack Test

正式输出前想象 reviewer 问：

“But Paper X already does this.”

必须能够回答：

“Yes, but Paper X performs / decides X based on Y, whereas our method directly models / optimizes / measures Z.”

如果只能回答：

“Our method is more flexible.”

“Our framework is more adaptive.”

“Our method is more comprehensive.”

说明 novelty 没定位清楚。

重新查 literature。

---

# 69. Final Output Check

正式输出前逐项检查：

第一句是否足够大的 field-level background？

第一句是否大但不空？

第二句是否明确 Major Method Family？

第三句是否具体总结 Existing Paradigm？

Existing Paradigm 是否包含：

Object + Operation + Purpose？

是否明确出现：

However？

However 是否优先采用 `(i)/(ii)`？

两个 limitation 是否点名具体 technical objects？

两个 limitation 是否有逻辑对称？

至少一个 limitation 是否解释 why？

是否经过 literature verification？

是否明确出现：

“To address these issues”？

Method 是否逐项对应 Problem？

Problem 与 Method 是否保持 lexical mirroring？

方法篇幅是否符合复杂度？

是否删除不必要 modules？

实验是否只用 1–2 句？

最后一句是否直接属于：

Experiments demonstrate/show/indicate...？

是否避免：

These results / These findings / broader significance？

是否约 195 words？

是否默认 ≤210 words？

任何核心项失败：

重新生成。

---

# 70. 最终优先级

Abstract 写作优先级：

**Precise Existing Paradigm**

>

**Sharp However**

>

**Problem–Solution Mapping**

>

**Technical Method Clarity**

>

**Strong Experimental Evidence**

>

Background Elegance

>

Fancy Vocabulary。

其中最高优先级：

**However。**

---

# 71. Final Philosophy

该 Skill：

**不固定研究领域。**

但是对于典型 technical method paper，默认固定一种成熟的顶会 Abstract 叙事：

**One broad background sentence.**

**One major-method-family sentence.**

**One concrete existing-paradigm sentence.**

**One sharp However with explicit technical limitations.**

**One explicit “To address these issues” transition.**

**A simple and proportional method description.**

**A direct conference-style experimental closing.**

核心不是：

写得复杂；

用高级词；

制造很多新术语。

核心是：

**背景够大；**

**方法族点得准；**

**Existing Paradigm 说得具体；**

**However 两刀切得清楚；**

**Method 一一对应；**

**Experiments 一句话封口。**

最终 Abstract 应让 reviewer 在约 195 words 内清楚记住：

**大问题是什么；**

**大家现在主要怎么做；**

**这些方法具体错在哪里；**

**本文具体怎么解决；**

**实验是否证明有效。**

默认最终节奏：

**Broad Problem**
**→ Major Method Family**
**→ Existing Paradigm**
**→ However (i)/(ii)**
**→ To address these issues**
**→ Method**
**→ Core Mechanisms**
**→ Extensive experiments demonstrate that ...**
**→ END**