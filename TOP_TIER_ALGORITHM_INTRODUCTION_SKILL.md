# Research-Grounded Top-Tier Introduction Writing Skill

## Algorithm / Method-Driven Paper Edition

---

# 1. Skill 定位

该 Skill 用于撰写以 **新算法、新方法、新框架、新训练机制、新优化机制、新参数化方式、新推理机制、新表示方式或新系统设计** 为主要贡献的科研论文 Introduction。

该 Skill **不绑定固定研究领域**。

它可以自动适配不同研究方向，包括但不限于：

Machine Learning；

Natural Language Processing；

Computer Vision；

Generation；

Fine-Tuning；

Multimodal Learning；

Agents；

Robotics；

Optimization；

Medical AI；

Systems；

Security；

Data Mining；

以及其他 technical method papers。

领域不固定。

但算法类论文的 Introduction 默认遵循一条稳定的技术叙事：

**Simple Field / Setting**
**→ Major Method Family**
**→ Existing Technical Paradigm**
**→ Concrete Failure Mechanism**
**→ Mechanistic Insight / Design Principle**
**→ Proposed Method**
**→ Contributions**

---

# 2. 默认长度

用户没有明确指定 Introduction 长度时：

**Default target: approximately 740 words.**

推荐范围：

**710–770 words。**

理想范围：

**725–755 words。**

默认硬上限：

**800 words。**

如果约 700–720 words 已经把 Story 完整讲清楚：

不要为了凑到 740 words 添加无意义背景。

如果超过 770 words：

优先检查是否存在：

Background 太长；

Related Work 罗列；

重复 Motivation；

Method 解释过细；

额外总结句；

Contributions 重复 Method。

除非用户明确要求：

正常不要超过 800 words。

---

# 3. 默认段落数量

默认：

**5–6 个自然段。**

推荐：

### Six-Paragraph Structure

P1 — Simple Background + Current Setting

P2 — Major Method Family + Existing Paradigm

P3 — Concrete Failure Mechanism

P4 — Mechanistic Insight / Design Principle

P5 — Proposed Method + Core Technical Design

P6 — Contributions

如果论文 Method 很简单：

允许压缩为：

**5 paragraphs。**

不要为了模板机械拆成：

8–10 个短段落。

---

# 4. 默认 Word Budget

740-word Introduction 推荐预算：

### P1

**80–100 words**

### P2

**105–125 words**

### P3

**145–170 words**

### P4

**95–115 words**

### P5

**180–205 words**

### P6 Contributions

**65–85 words**

总计：

约 **740 words**。

其中优先级：

**P3 Failure Mechanism**

>

**P5 Method**

>

**P4 Insight**

>

**P2 Existing Paradigm**

>

**P1 Background**

---

# 5. Introduction 的任务

Introduction 不负责：

证明这个领域有多重要；

回顾整个技术发展史；

堆积大量 related work；

提前复制 Method Section；

或者写大量宏大 motivation。

Introduction 应回答：

这个论文研究什么？

当前这个 setting 中大家主要用什么方法？

这类方法总体怎么做？

它们依赖什么 technical mechanism？

这个 mechanism 在什么情况下失败？

失败的真正原因是什么？

真正应该控制或建模的变量是什么？

本文因此采用什么 design principle？

新方法如何实现这个 principle？

实验贡献是什么？

---

# 6. 第一段禁止“宏大化”

P1 必须：

**plain, local, task-oriented。**

不要故意把背景抬得很高。

默认避免：

“the widespread adoption of ...”

“has created an urgent need for ...”

“has revolutionized ...”

“has become increasingly critical ...”

“at unprecedented scale ...”

“plays a pivotal role in ...”

“is essential for the future of ...”

“rapidly growing demand ...”

“modern models increasingly require ...”

除非这些表达确实是当前论文必须表达的 technical fact。

---

# 7. P1 的尺度

第一段应该回答：

**这个 task / setting 需要解决什么。**

而不是：

**整个 AI 为什么重要。**

例如：

如果论文研究 Generation Fine-Tuning：

从：

“Generative models often need to adapt to target behaviors while retaining their general generation capability.”

开始是合理的。

不要先写：

“Large language models have revolutionized artificial intelligence and are increasingly deployed in numerous real-world applications.”

后者对算法 Story 没有帮助。

---

# 8. Research Before Writing

正式生成 Introduction 前：

必须执行：

**Read**
**→ Recover Paper**
**→ Extract Keywords**
**→ Search Literature**
**→ Find Nearest Papers**
**→ Identify Dangerous Neighbors**
**→ Read Original Introductions**
**→ Recover Existing Paradigm**
**→ Verify Failure Mechanism**
**→ Extract Technical Vocabulary**
**→ Fill XXX Skeleton**
**→ Allocate \~740 Words**
**→ Write**

不能：

用户给 Method 后立刻编 Motivation。

---

# 9. 用户可以提供的材料

用户可能提供：

完整论文；

不完整 Manuscript；

Abstract；

Method；

Experiments；

Research Idea；

Notes；

Reference Papers；

Target Venue；

或者它们的任意组合。

Skill 必须先理解已有材料。

不能擅自补：

不存在的实验；

不存在的理论；

不存在的 observation；

不存在的 limitation。

---

# 10. Recover the Paper

正式搜索前内部填写：

`[FIELD / TASK]`

`[CURRENT SETTING]`

`[FUNDAMENTAL GOAL]`

`[CORE CONSTRAINT]`

`[MAJOR METHOD FAMILY]`

`[WHY METHOD FAMILY FITS]`

`[EXISTING PARADIGM]`

`[TECHNICAL OBJECT]`

`[CURRENT OPERATION]`

`[CURRENT CRITERION / SIGNAL]`

`[CURRENT ASSUMPTION / PROXY]`

`[FAILURE CONDITION]`

`[FAILURE MECHANISM]`

`[TECHNICAL CONSEQUENCE]`

`[WHAT ACTUALLY MATTERS]`

`[MECHANISTIC OBSERVATION]`

`[CORE QUANTITY / PROPERTY]`

`[DESIGN PRINCIPLE]`

`[METHOD NAME]`

`[CORE METHOD OPERATION]`

`[COMPONENT / VARIABLE A]`

`[COMPONENT / VARIABLE B]`

`[OPTIONAL LOCAL PROBLEM]`

`[OPTIONAL OPTIMIZATION / INTEGRATION]`

`[MAIN EXPERIMENTAL EVIDENCE]`

关键位置无法填写时：

继续搜索。

不要用 generic prose 补空位。

---

# 11. Evidence Levels

所有信息区分：

### Directly Supported

来自用户自己的：

Method；

Theory；

Analysis；

Experiments；

Results。

### Literature Supported

真实相关论文支持。

### Plausible

合理推断，但还没有直接证据。

### Unsupported

当前没有依据。

Introduction 中的强 claim：

原则上只来自：

**Directly Supported**

或：

**Literature Supported。**

---

# 12. Keyword Extraction

每个新项目提取：

**6–10 个核心搜索关键词。**

覆盖：

Field / Task；

Setting；

Method Family；

Technical Object；

Core Problem；

Mechanism；

Failure Condition；

Candidate Novelty。

---

# 13. Literature Search

不能只搜索单个关键词。

优先：

`Task × Method Family`

`Method Family × Problem`

`Method Family × Technical Object`

`Technical Object × Failure`

`Method Family × Mechanism`

`Setting × Method Family × Problem`

`Problem × Proposed Mechanism`

目标不是找到标题最相似的论文。

目标是找到：

**technical operation 最接近的论文。**

---

# 14. Literature Corpus

默认建立：

**8–15 篇相关论文。**

优先：

领域顶会；

目标 venue；

正式 proceedings；

最近 2–4 年的工作；

定义当前技术路线的经典论文。

其中筛选：

**3–6 篇 Dangerous Neighbors。**

---

# 15. Dangerous Neighbors

Dangerous Neighbor 指：

reviewer 最可能用来挑战 novelty 的论文。

检查：

它操作什么？

它如何操作？

依据什么 signal / criterion？

它的 assumption 是什么？

它是否已经处理类似 failure？

它是否已经采用类似 design principle？

本文真正不同在哪里？

如果已有论文已经解决用户原本写的 broad problem：

必须缩窄 claim。

---

# 16. 学习 Original Introduction

对于最相关论文：

重点阅读：

Introduction；

Abstract；

Method Overview；

必要时 Experiment Analysis。

提取：

Technical Nouns；

Technical Collocations；

Technical Verbs；

Failure Expressions；

Mechanism Descriptions；

常见 prepositional structures。

不要只读二手 summary。

---

# 17. Project-Specific Technical Lexicon

正式写作前建立：

**Project-Specific Technical Lexicon。**

优先包含：

15–30 technical nouns / noun phrases；

10–20 technical verbs；

5–15 failure terms；

5–10 mechanism relations；

5–10 method-operation expressions。

词汇优先来自：

用户论文；

nearest papers；

community standard terminology。

---

# 18. Terminological Consistency

不要追求同义词丰富。

如果前面用了：

`update direction`

后面继续用：

`update direction`。

不要为了“高级英文”改成：

adaptation axis；

parameter trajectory；

latent update component。

除非技术含义确实不同。

---

# 19. Introduction 不使用 Abstract 式 Problem List

默认禁止：

“Existing methods face two limitations.”

“First, ... Second, ...”

“Firstly, ... Secondly, ...”

`(i)` / `(ii)`。

Introduction 应该让 failure：

**连续展开。**

---

# 20. 连续 Failure 的基本结构

推荐：

**Current Operation**
**→ Current Proxy / Assumption**
**→ Failure Condition**
**→ Technical Mismatch**
**→ Specific Failure**
**→ Consequence**

例如抽象骨架：

> Current methods determine `[OBJECT]` from `[SIGNAL]`.
> `[SIGNAL]` measures `[A]`, whereas successful adaptation depends on `[B]`.
> Under `[CONDITION]`, `[A]` can diverge from `[B]`.
> The resulting `[OBJECT]` therefore `[FAILURE]`, limiting `[CAPABILITY]`.

这就是一个完整 Problem Story。

---

# 21. 不强行创造两个问题

如果真实论文只有一个强 technical failure：

只写一个。

如果存在第二层问题：

它应该从第一个 technical object 自然继续展开。

不要为了显得丰富：

硬造两个 limitation。

---

# 22. 禁止 AI 胶水词

默认禁止或强烈避免：

Together,

Taken together,

Overall,

Collectively,

In summary,

Together, these designs,

Overall, our framework,

These findings highlight,

These results suggest,

These observations collectively,

Building on these insights,

Building upon the above,

Furthermore,

Moreover,

Additionally,

Notably,

Importantly,

It is worth noting that。

特别是这些词仅用于：

“连接句子”

时。

---

# 23. Technical Continuity

Introduction 应通过：

**technical object continuity**

建立连贯。

例如：

> The retrieved context determines which external evidence enters generation. Irrelevant evidence in this context can directly alter token probabilities during decoding.

优于：

> The retrieved context determines external information. Furthermore, irrelevant information can influence generation.

上一句的：

`retrieved context`

继续成为下一句 technical object。

---

# 24. 六段 Master Structure

算法类 Introduction 默认写成：

### P1

Simple Background + Current Setting

### P2

Major Method Family + Existing Paradigm

### P3

Concrete Failure Mechanism

### P4

Mechanistic Insight + Design Principle

### P5

Proposed Method + Core Technical Designs

### P6

Contributions

这是默认骨架。

不是领域限定。

---

# 25. P1 — Simple Background + Current Setting

目标：

**80–100 words。**

第一句直接描述：

task / field-level requirement。

统一骨架：

> **[FIELD / TASK] requires [OBJECT] to [FUNDAMENTAL GOAL] while [CORE CONSTRAINT].**

或者：

> **[FIELD / TASK] studies how [OBJECT] can [GOAL] without [FAILURE].**

---

# 26. P1 不一定要写“Fundamental Challenge”

如果领域确实存在成熟 challenge：

可以写一句。

例如：

> A key challenge is `[CANONICAL CHALLENGE]`.

但不要为了模板：

每篇论文都创造一个：

“central dilemma”。

如果第一句已经足够清楚：

直接进入当前 technical setting。

---

# 27. P1 — Current Setting

然后说明：

目前论文处于什么技术环境。

例如：

pretrained model；

foundation model；

open-vocabulary setting；

large-scale generation；

continual adaptation；

multimodal model；

self-supervised representation。

骨架：

> **Recent [TECHNICAL DEVELOPMENT] has shifted [TASK] toward [CURRENT SETTING].**

或者更简单：

> **In current [SETTING], [TECHNICAL NEED].**

不要长篇写技术革命史。

---

# 28. P1 — 收缩到 Method Family

第一段末尾可以自然带到：

Major Method Family。

例如：

> **In this setting, [METHOD FAMILY] provides a practical way to [FUNCTION].**

或者 Method Family 放到 P2 第一行。

P1 不应该：

介绍你自己的 Method Name。

---

# 29. P1 Anti-Grandiosity Test

写完 P1 后检查：

有没有把：

task adaptation

写成：

“an urgent challenge for modern artificial intelligence”？

有没有把：

parameter efficiency

写成：

“a fundamental requirement for scalable intelligent systems”？

有没有超过：

100–110 words？

如果是：

压缩。

---

# 30. P2 — Major Method Family

目标：

**105–125 words。**

第一句点名：

`[METHOD FAMILY]`。

骨架：

> **Among existing approaches, [METHOD FAMILY] has become a common / representative approach for [TARGET TASK] because [KEY PROPERTY].**

或者更自然：

> **[METHOD FAMILY] provides [KEY PROPERTY] by [BASIC MECHANISM].**

不要为了抬高方法族写：

“has attracted tremendous attention”。

---

# 31. P2 — Minimal Method Definition

用 1 句说明方法族怎么工作。

骨架：

> **It [CORE TECHNICAL OPERATION] by [BASIC MECHANISM].**

例如：

parameterizes updates with low-rank matrices；

aligns images and text in a shared embedding space；

optimizes model behavior from preference pairs；

conditions generation on retrieved evidence。

只需要让 reviewer 理解：

这个技术族做什么。

---

# 32. P2 — Existing Paradigm

这是 P2 最重要的位置。

统一骨架：

> **Recent [METHOD FAMILY]-based methods typically [COMMON TECHNICAL OPERATION] to [PURPOSE], often using [DOMINANT SIGNAL / CRITERION].**

或者：

> **Several [METHOD FAMILY]-based approaches achieve [PURPOSE] by [COMMON OPERATION], typically constructing / selecting / estimating [OBJECT] from [SIGNAL].**

---

# 33. Existing Paradigm 必须具体

必须包含：

### Object

操作什么？

### Operation

怎么操作？

### Signal / Criterion

依据什么？

### Purpose

为什么？

如果只能写：

> Existing methods use different strategies to improve adaptation.

继续搜索。

---

# 34. P2 不写 Related Work List

不要：

Paper A does...

Paper B does...

Paper C does...

Introduction 的目标是：

从 papers 中恢复：

**common paradigm。**

不是：

提前写 Related Work。

---

# 35. P3 — Concrete Failure Mechanism

目标：

**145–170 words。**

这是 Introduction 中最重要的一段。

开头通常可以：

> **However, [EXISTING PARADIGM] relies on [CRITERION / SIGNAL / ASSUMPTION] to [OPERATION], which can [FAILURE] when [CONDITION].**

不要：

> However, existing methods still face several challenges.

---

# 36. P3 必须回答“为什么”

Failure 不能只有：

结果不好。

必须解释：

为什么。

例如：

`sequence-level reward`

并不直接刻画：

`token-level causal decision`。

`past-task inactivity`

并不等价于：

`new-task usefulness`。

`semantic similarity`

并不等价于：

`marginal parameter utility`。

`global contrastive alignment`

并不保证：

`local spatial structure`。

这种：

**proxy ≠ actual target**

是非常强的算法 Problem 结构。

---

# 37. Failure Condition

如果 failure 只在某种 setting 发生：

明确写出来。

例如：

under correlated tasks；

when retrieved contexts conflict；

for long generation trajectories；

under heterogeneous teacher supervision；

when task distributions overlap；

under sparse feedback；

under strong domain shift。

具体 condition：

比空泛 limitation 更可信。

---

# 38. Failure Consequence

Failure 最后必须落到：

technical consequence。

例如：

off-target activation；

inactive update direction；

gradient conflict；

feature drift；

parameter redundancy；

token-level over-update；

incorrect routing；

spatial entanglement；

capacity over-expansion。

不要只落到：

poor performance。

---

# 39. P3 可以包含第二层 Failure

如果存在真实第二层机制：

不要使用：

Second。

继续沿 technical object。

例如：

> The selected directions are intended to avoid past-task interference. Their usefulness for the current task, however, is not explicitly evaluated.

然后继续解释。

这种写法比：

“Secondly, they fail to...”

自然。

---

# 40. P4 — Mechanistic Insight

目标：

**95–115 words。**

P4 回答：

**真正决定这个现象的是什么？**

如果论文有：

theory；

analysis；

representation study；

empirical diagnosis；

optimization observation，

可以使用：

> **We find that [TARGET PROPERTY] is governed by [CORE QUANTITY / MECHANISM].**

或：

> **Our analysis shows that [MECHANISTIC RELATION].**

---

# 41. Observation 必须真实

禁止为了 Story 写：

“We reveal...”

“We show\...”

“We find...”

如果论文没有任何 supporting evidence。

如果只是 design intuition：

直接说：

> **A reliable solution therefore needs to [DESIGN REQUIREMENT].**

不要假装有新发现。

---

# 42. P4 — Explain Relation

如果有 observation：

下一句解释：

它到底意味着什么。

骨架：

> **[QUANTITY] determines whether [OBJECT] [TECHNICAL EFFECT].**

或者：

> **When [CONDITION A], [EFFECT A], whereas [CONDITION B] leads to [EFFECT B].**

这一步完成：

Failure

→ Why。

---

# 43. P4 — Design Principle

接下来推出：

Design Principle。

非常推荐的通用结构：

> **This relation suggests that [DESIGN VARIABLE] should be [SELECTED / ALLOCATED / DECOMPOSED / OPTIMIZED] according to [MECHANISTIC SIGNAL] rather than [EXISTING PROXY].**

Design Principle 是：

技术原则。

不是：

Module 名字。

---

# 44. 好的 Design Principle

例如：

allocate capacity according to marginal utility rather than novelty；

select updates according to task-dependent usefulness rather than past-task inactivity；

assign heterogeneous priors to role-compatible variables；

optimize token decisions according to local preference contribution rather than a global reward；

separate reusable and task-specific components according to their actual task responses。

这些只是示意。

实际内容必须来自：

当前论文。

---

# 45. P4 可以没有 Key Question

默认不要求：

“This raises a key question...”

如果自然：

可以用。

如果显得像 Abstract：

直接不写。

P4 的真正功能：

**Failure → Mechanism → Principle。**

不是：

必须出现问号。

---

# 46. P5 — Proposed Method

目标：

**180–205 words。**

现在才第一次正式出现：

`[METHOD NAME]`。

骨架：

> **To address this problem, we propose [METHOD NAME], which [CORE STRUCTURAL OPERATION].**

或者：

> **We therefore propose [METHOD NAME], which [CORE STRUCTURAL OPERATION].**

---

# 47. Method 第一行只说 Core Operation

不要：

> Our framework consists of three modules.

优先：

> **[METHOD] performs [CORE OPERATION] to construct / separate / allocate / optimize [CORE TECHNICAL OBJECT].**

Reviewer 第一件事应该理解：

**这个算法本质上改变了什么。**

---

# 48. P5 — Core Design A

展开最重要的 design。

骨架：

> **The [COMPONENT / VARIABLE A] uses [SIGNAL / CRITERION A] to [FUNCTION A], thereby [TECHNICAL EFFECT A].**

这里的：

A

必须对应前面已经定义的：

failure / missing capability。

---

# 49. P5 — Core Design B

如果存在第二个核心 design：

自然接：

> **The [COMPONENT / VARIABLE B] is determined from [SIGNAL / CRITERION B] to [FUNCTION B], preserving / isolating / preventing [TECHNICAL EFFECT B].**

不要：

> First...

> Second...

让：

technical objects 自己形成结构。

---

# 50. Technical Symmetry

如果方法天然有：

general / isolated；

semantic / spatial；

reuse / expansion；

local / global；

selection / consolidation；

generation / verification；

可以利用这种 symmetry。

但不要为了漂亮：

人为创造双分支。

---

# 51. P5 — Optional Optimization / Integration

如果还有一个真正必要的机制：

例如：

optimizer；

gradient alignment；

merging；

recalibration；

routing；

post-hoc correction；

retention audit；

inference selection，

不必专门另开一大段。

先写：

local problem。

例如：

> **Updating [COMPONENT] can still induce [LOCAL FAILURE].**

然后：

> **We therefore derive / apply [MECHANISM] to [FUNCTION].**

---

# 52. 不要突然塞 Extra Module

默认避免：

> We further introduce XXX.

如果无法回答：

为什么需要这个组件？

不要写进 Introduction。

Method Section 可以详细讲。

---

# 53. P5 不搬公式

Introduction 中通常不要：

完整写公式；

解释 implementation details；

列所有 hyperparameters；

解释每个 auxiliary loss。

只保留：

理解 Method Story 必须知道的 mechanism。

---

# 54. P6 — Contributions

目标：

**65–85 words。**

方法结束后：

直接：

> **Our main contributions are summarized as follows:**

不要在它前面写：

Together, these designs...

Overall...

Taken together...

---

# 55. Contributions 数量

默认：

**3 条。**

推荐：

### Contribution 1

Problem / Analysis / Insight。

### Contribution 2

Method。

### Contribution 3

Experiments。

一般不要超过：

4 条。

---

# 56. Contribution 1

骨架：

> **We identify / analyze [CORE TECHNICAL FAILURE], showing that [MECHANISTIC INSIGHT].**

如果没有新的 observation：

可以：

> **We identify [CORE TECHNICAL PROBLEM] in existing [METHOD FAMILY], where [FAILURE MECHANISM].**

---

# 57. Contribution 2

骨架：

> **We propose [METHOD NAME], which [CORE METHOD OPERATION] using [CORE MECHANISM].**

不要把：

Module A；

Module B；

Module C

分别算成三个贡献。

---

# 58. Contribution 3

骨架：

> **Experiments on [BENCHMARK / SETTING] demonstrate that [MAIN EMPIRICAL RESULT].**

如果有强数字：

优先最重要的一两个。

不要写：

“extensive experiments validate the superiority...”

---

# 59. Universal XXX Skeleton

正式生成 prose 之前：

必须先内部完整填写下面的骨架。

---

## P1

`[FIELD / TASK]`

`[OBJECT]`

`[FUNDAMENTAL GOAL]`

`[CORE CONSTRAINT]`

`[CURRENT SETTING]`

`[CURRENT NEED]`

---

## P2

`[METHOD FAMILY]`

`[KEY PROPERTY]`

`[BASIC MECHANISM]`

`[EXISTING PARADIGM]`

`[COMMON OPERATION]`

`[TECHNICAL OBJECT]`

`[DOMINANT SIGNAL / CRITERION]`

`[PURPOSE]`

---

## P3

`[CURRENT OPERATION]`

`[CURRENT PROXY / ASSUMPTION]`

`[WHAT PROXY ACTUALLY MEASURES]`

`[WHAT ACTUALLY MATTERS]`

`[FAILURE CONDITION]`

`[TECHNICAL MISMATCH]`

`[SPECIFIC FAILURE]`

`[TECHNICAL CONSEQUENCE]`

`[SECOND-LAYER FAILURE if real]`

---

## P4

`[MECHANISTIC OBSERVATION]`

`[CORE QUANTITY / PROPERTY]`

`[MECHANISTIC RELATION]`

`[DESIGN VARIABLE]`

`[MECHANISTIC SIGNAL]`

`[DESIGN PRINCIPLE]`

---

## P5

`[METHOD NAME]`

`[CORE STRUCTURAL OPERATION]`

`[COMPONENT / VARIABLE A]`

`[CRITERION A]`

`[FUNCTION A]`

`[COMPONENT / VARIABLE B]`

`[CRITERION B]`

`[FUNCTION B]`

`[OPTIONAL LOCAL FAILURE]`

`[OPTIONAL OPTIMIZATION / INTEGRATION]`

---

## P6

`[PROBLEM / INSIGHT CONTRIBUTION]`

`[METHOD CONTRIBUTION]`

`[EMPIRICAL CONTRIBUTION]`

---

# 60. Universal Fill-in Prose Skeleton

下面是算法类 Introduction 的抽象 Story 模板：

> **[FIELD / TASK] requires [OBJECT] to [GOAL] while [CORE CONSTRAINT]. In the current [SETTING], [CURRENT NEED]. [METHOD FAMILY] provides a practical approach to this problem because [KEY PROPERTY].**
>
> **[METHOD FAMILY] [BASIC MECHANISM]. Recent [METHOD FAMILY]-based methods typically [COMMON OPERATION] to [PURPOSE], often determining [TECHNICAL OBJECT] from [SIGNAL / CRITERION].**
>
> **However, [CURRENT OPERATION] relies on [PROXY / ASSUMPTION], which [WHAT IT MEASURES] rather than [WHAT ACTUALLY MATTERS]. Under [FAILURE CONDITION], this mismatch causes [TECHNICAL OBJECT] to [SPECIFIC FAILURE]. The resulting [CONSEQUENCE] limits [TARGET CAPABILITY]. [OPTIONAL SECOND-LAYER FAILURE CONTINUED FROM THE SAME TECHNICAL OBJECT].**
>
> **Our analysis / observation shows that [TARGET PROPERTY] is governed by [CORE QUANTITY / MECHANISM]. [MECHANISTIC RELATION]. This suggests that [DESIGN VARIABLE] should be [OPERATION] according to [MECHANISTIC SIGNAL] rather than [EXISTING PROXY].**
>
> **To address this problem, we propose [METHOD NAME], which [CORE STRUCTURAL OPERATION]. The [COMPONENT A] uses [CRITERION A] to [FUNCTION A], [TECHNICAL EFFECT A]. The [COMPONENT B] uses [CRITERION B] to [FUNCTION B], [TECHNICAL EFFECT B]. [OPTIONAL LOCAL PROBLEM]. [OPTIONAL OPTIMIZATION / INTEGRATION MECHANISM].**
>
> **Our main contributions are summarized as follows: [CONTRIBUTIONS].**

这个模板：

不是要求最终逐字复制。

它约束的是：

**technical story positions。**

---

# 61. Generation / Fine-Tuning 示例填空

如果论文研究：

Generation Fine-Tuning。

可以得到：

`[FIELD / TASK]`

preference-aligned generation

`[GOAL]`

adapt generation toward desired behaviors

`[CORE CONSTRAINT]`

preserve general generation quality

`[METHOD FAMILY]`

preference-based fine-tuning

`[EXISTING PARADIGM]`

optimize model parameters from sequence-level preference signals

`[TECHNICAL OBJECT]`

generation trajectory / token update

`[CURRENT PROXY]`

sequence-level reward

`[WHAT ACTUALLY MATTERS]`

which local token decisions contribute to the preference

`[FAILURE]`

uniformly or incorrectly updating unrelated token decisions

`[CORE QUANTITY]`

token-level preference contribution

`[DESIGN PRINCIPLE]`

allocate updates according to local contribution rather than global sequence reward

其余位置：

继续根据真实论文填写。

---

# 62. Skeleton 不固定领域

上面的 Generation 只是示例。

真正执行时：

不得因为 Skill 里出现某个领域例子，

就自动假设用户论文属于：

Generation；

LoRA；

CL；

Vision；

Agent。

必须重新从用户论文中：

动态识别领域。

---

# 63. Anti-Generic Test

每个重要句子检查：

如果把 technical nouns 换掉，

是不是能直接放进十篇完全不同的 AI 论文？

如果可以：

太 generic。

例如：

> Existing methods cannot effectively capture useful information.

不合格。

必须继续找到：

哪个 signal；

哪个 parameter；

哪个 token；

哪个 direction；

哪个 representation；

哪个 criterion；

哪个 trajectory。

---

# 64. Specificity Ladder

遇到：

information

继续问：

什么 information？

遇到：

feature

继续问：

什么 feature？

遇到：

knowledge

继续问：

哪类 knowledge？

遇到：

representation

继续问：

哪个 representation？

遇到：

adaptation

继续问：

哪个 parameter / update / component 在 adaptation？

直到达到：

既 technical

又不会过细到 Method Section 的层级。

---

# 65. Failure Test

每一个 Failure Sentence 都必须回答：

别人：

**具体做了什么？**

为什么：

**这样做会失败？**

在哪：

**什么 condition 下失败？**

失败后：

**哪个 technical object 出现什么行为？**

如果只能回答：

performance 下降，

不够。

---

# 66. Mechanism Test

一个好的算法类 Motivation 应该可以形成：

`X uses Y`

→

`Y measures A`

→

`successful behavior actually depends on B`

→

`A and B diverge under C`

→

`X fails`

→

`our design directly targets B`。

如果无法形成类似 causal chain：

继续查 literature 或 analysis。

---

# 67. Problem–Method Vocabulary Continuity

P3 中的重要 technical nouns：

必须在 P4 / P5 中继续出现。

例如：

Problem：

sequence-level reward。

Insight：

token-level contribution。

Method：

token-specific update weighting。

这种 lexical continuity：

比复杂连接词更重要。

---

# 68. No Module Stacking

每个 Method Component 进入 Introduction 前问：

它解决哪个已经定义的问题？

或者：

删除它后 reviewer 是否无法理解方法核心？

如果两个答案都是 No：

从 Introduction 删除。

---

# 69. No Fake Observation

不要为了让 Story 更漂亮：

创造：

“We reveal...”

“We find...”

“Our analysis demonstrates...”

如果论文实际上没有 analysis。

可以直接：

> **This failure suggests that...**

然后进入 Design Principle。

---

# 70. No Forced Theory

算法论文不一定要有：

theorem；

closed-form analysis；

新数学量。

如果方法主要由：

empirical diagnosis

推出，

也可以。

Skill 不强迫：

每篇 paper 都制造理论视角。

---

# 71. No Forced Question

不强制：

“This raises a key question...”

如果使用：

必须短。

如果不用：

直接从 Failure 进入：

Design Requirement / Observation。

Introduction 不应像：

Abstract 的扩大版。

---

# 72. No Forced Technical Regime

如果论文没有明显：

old paradigm → new paradigm

的时代转换，

P1 不要强写：

“With the rise of...”

直接：

Task

→ Current Setting

→ Method Family。

---

# 73. No Inflated Motivation

默认拒绝：

为了填 P1 而添加：

现实应用很多；

模型越来越大；

AI 发展迅速；

计算成本高；

社会影响巨大。

除非：

这些因素与当前 Failure Mechanism 有直接关系。

---

# 74. P1 Compression Rule

如果整个 Introduction 超长：

第一个压缩对象：

P1。

P1 最低可以：

约 70–80 words。

不要为了保留漂亮 background：

牺牲 P3 / P4。

---

# 75. P3 Protection Rule

压缩 Introduction 时：

P3 Failure Mechanism 默认：

最后压缩。

因为算法论文 novelty 的可信度：

很大程度取决于 reviewer 是否理解：

**为什么现有方法真的不够。**

---

# 76. Literature Claim Verification

以下表达必须搜索验证：

“Existing methods rely on...”

“Most methods determine...”

“Current approaches typically...”

“Previous methods assume...”

“Existing methods fail when...”

“No existing work...”

“Unlike prior work...”

如果 nearest paper 是反例：

必须修改 claim。

---

# 77. “Most / All / No” Rule

默认少用：

all；

most；

always；

none；

no existing work。

优先：

Several；

Many existing；

A common strategy；

Recent X-based methods；

Representative approaches。

除非有足够文献证据。

---

# 78. Technical Verb Rule

优先：

capture；

preserve；

retain；

separate；

isolate；

allocate；

route；

project；

decompose；

align；

merge；

recalibrate；

distill；

regularize；

optimize；

select；

estimate；

construct；

suppress；

overwrite；

induce；

aggregate。

少用：

effectively leverage；

comprehensively exploit；

significantly enhance；

better handle；

fully utilize。

---

# 79. Citation Density

Introduction 应该有足够 citations：

支持：

Field；

Method Family；

Existing Paradigm；

Failure / related analysis。

但不要：

每一句堆 5–8 个 citation。

代表性引用足够。

完整 taxonomy：

留给 Related Work。

---

# 80. Reference Paper Wording Learning

可以学习：

standard terminology；

short technical collocations；

canonical verbs；

common definitions。

不能：

复制完整句子。

如果某个领域反复使用：

`cross-task interference`

就使用它。

不要创造：

`inter-experience destructive interaction`

这种不必要的新说法。

---

# 81. Word Count Check

初稿完成后：

必须计算英文 word count。

### < 680

检查是否缺少：

Existing Paradigm；

Failure Mechanism；

Insight；

Method Logic。

### 680–710

如果 Story 完整：

可以接受。

### 710–770

默认理想范围。

### 770–800

允许，但应检查：

背景是否冗余；

Method 是否过细。

### > 800

默认压缩。

---

# 82. 超长压缩顺序

超过 800 words 时：

第一：

删除宏大背景。

第二：

缩短 Method Family 定义。

第三：

合并重复 related-work descriptions。

第四：

删除非核心 Method component。

第五：

缩短 Contributions。

最后才压：

Failure Mechanism。

---

# 83. Final Story Check

输出前检查：

P1 是否简单？

P1 是否 task-oriented？

P1 是否避免 grandiosity？

P2 是否说清 Method Family？

Existing Paradigm 是否具体？

是否包含 Object + Operation + Criterion + Purpose？

P3 是否是 technical failure？

是否解释 why？

是否写了 failure condition？

是否避免 `(i)/(ii)`？

是否避免 First / Second limitation list？

P4 是否有真实 insight / design principle？

Method 是否从前文自然推出？

P5 是否先讲 core operation？

Method components 是否和前面 Problem 对应？

是否存在不必要 module stacking？

P6 是否直接进入 contributions？

是否约 740 words？

是否只用 5–6 段？

---

# 84. Final Language Check

删除不必要的：

Together,

Taken together,

Overall,

Collectively,

Furthermore,

Moreover,

Additionally,

Notably,

Importantly,

These findings highlight,

These results suggest,

Together, these designs,

Overall, our framework。

如果删除以后句子仍然成立：

就不应该保留。

---

# 85. Reviewer Reconstruction Test

一个好的 Introduction 应该允许 reviewer 用几句话复述：

> 这篇论文研究 `[TASK]`。

> 目前 `[METHOD FAMILY]` 通常通过 `[OPERATION]` 做 `[PURPOSE]`。

> 这个做法依赖 `[SIGNAL / PROXY]`。

> 但在 `[CONDITION]` 下，这个 proxy 并不代表真正需要的 `[TARGET PROPERTY]`。

> 因此 `[TECHNICAL OBJECT]` 会出现 `[FAILURE]`。

> 作者发现真正决定这个行为的是 `[MECHANISM]`。

> 所以设计应该依据 `[MECHANISTIC SIGNAL]`。

> 新方法实现了这个原则。

如果 reviewer 只能说：

> Existing methods have limitations, so the authors propose a new framework.

Introduction 不合格。

---

# 86. Default Algorithm Introduction Backbone

默认最终结构：

**P1**

`[SIMPLE FIELD / TASK]`

→

`[CURRENT SETTING]`

→

`[METHOD FAMILY becomes relevant]`

**P2**

`[METHOD FAMILY]`

→

`[BASIC MECHANISM]`

→

`[EXISTING PARADIGM]`

**P3**

`[CURRENT OPERATION]`

→

`[PROXY / ASSUMPTION]`

→

`[FAILURE CONDITION]`

→

`[TECHNICAL FAILURE]`

→

`[CONSEQUENCE]`

**P4**

`[MECHANISTIC INSIGHT]`

→

`[WHAT ACTUALLY MATTERS]`

→

`[DESIGN PRINCIPLE]`

**P5**

`[METHOD NAME]`

→

`[CORE OPERATION]`

→

`[CORE DESIGN A]`

→

`[CORE DESIGN B]`

→

`[OPTIONAL OPTIMIZATION / INTEGRATION]`

**P6**

`[CONTRIBUTIONS]`

---

# 87. Final Philosophy

该 Skill 的目标不是：

把 Introduction 写得更宏大。

不是：

让语言显得更高级。

不是：

把所有 Background 和 Related Work 都塞进 740 words。

真正目标是：

**简单进入问题。**

**快速进入当前 Method Family。**

**准确概括 Existing Paradigm。**

**花最多精力解释 Failure Mechanism。**

**说明真正决定失败的技术因素。**

**让 Design Principle 从这个 Mechanism 中自然产生。**

**让 Method 看起来是问题推出来的，而不是作者突然设计出来的。**

默认：

**5–6 paragraphs。**

默认：

**approximately 740 words。**

默认：

**plain technical English。**

默认：

**no inflated background。**

默认：

**no Abstract-style** **`(i)/(ii)`** **limitation list。**

默认：

**no AI-style glue words。**

最终执行顺序：

**Read**
**→ Search**
**→ Verify Existing Paradigm**
**→ Diagnose Failure Mechanism**
**→ Recover Mechanistic Insight**
**→ Fill XXX Skeleton**
**→ Allocate 740 Words**
**→ Write 5–6 Paragraphs**
**→ Count Words**
**→ Remove Grandiosity and Glue Words**
**→ Final Technical Check**