# CMS Social Dynamics Simulator

> "Why do more successful people become more anxious? Why can't 'sober' people survive in this system?"

This is an interactive simulator based on the **Chinese Mathematical System (CMS)**, replicating cognitive dissonance dynamics in social interactions through code.

---

## Quick Start

```bash
git clone https://github.com/Orangeforce/-.git
cd -
open Chinese_Math_Simulator.html
```

Note: No dependencies required. Pure static HTML implementation - just double-click to open.

## What Is This? (Plain Language Version)

Imagine a social circle where each person has a self-esteem index ρ (0 ≤ ρ ≤ 1):

- **ρ < 0.5 (Green)**: IMSB State ("I'm not good enough") — Cognitively sober, though painful, they are in a rational state.
- **ρ > 0.5 (Red)**: IMNB State ("I'm pretty great") — Cognitive dissonance, generating entropy-seeking behaviors to maintain false confidence.

### Core Paradox (CM-2 Impossibility Theorem)

In high social density environments (σ > σ_c), "staying sober" is impossible. No matter how humble you start, system dynamics will eventually push you toward blind narcissism (ρ → 1).

## Three Core Mechanisms

### Vampirism

**Principle**: Undeserved success makes people more inflated.
Gaining resources through illegitimate means, succeeding despite knowing you don't deserve it → Self-esteem leap (VRA-1 Axiom).

**Operation**: Click any node to trigger a "Vampirism" event.

### Rice-planting

**Principle**: To maintain narcissism, one must constantly do stupid things.
People in IMNB state must make negative-expectation investments, and after failure, reinforce narcissism through "compensation" (RFA-2 Axiom).

**Examples**: Vanity consumption, addictive gambling.

### Group Unconsciousness Field (Φ)

**Principle**: You become like the people around you.

**Phenomenon**: When σ > σ_c, a "phase transition" occurs, and the system slides into a red ocean of universal narcissism.

---

## Experiment Guide

### Experiment 1: Verify CM-2 Theorem

1. Keep σ < 0.5, and the system remains relatively stable (more green dots).
2. Drag the "Social Density" slider above 0.6.
3. **Observation**: The system rapidly turns completely red.

### Experiment 2: Topological Tearing (CM-3 Theorem)

1. Run the system in supercritical state (all red).
2. Click the "Topological Tearing" button.
3. **Observation**: The system undergoes polarization — either becoming completely sober or falling into an "ghost state" where interaction is impossible.

---

## Parameter Description

| Parameter | Meaning | Real-world Correspondence |
|-----------|---------|---------------------------|
| α | Vampirism transition speed | Social tolerance for unearned success / get-rich-quick opportunities |
| β | Legitimate convergence speed | Feedback speed of effort |
| γ | Narcissism maintenance intensity | Stubbornness of cognitive dissonance |
| η | Unconscious field efficiency | Manipulation power of social media algorithms |
| σ | Social density | Urbanization level, internet penetration |
| σ_c | Critical density | Threshold for social consensus collapse |

---

## Theoretical Background

- **VRA (Vampirism-Rating Axiom)**: Vampirism-Rating Axiom
- **RFA (Rice-planting Forced Axiom)**: Rice-planting Forced Axiom
- **EA (Estrangement Axiom)**: Alienation/Path Dependency Axiom
- **GUA (Group Unconsciousness Axiom)**: Group Unconsciousness Axiom

### Correspondence with Classical Theories

| Classical Theory | CMS Equivalent |
|------------------|----------------|
| Arrow's Impossibility Theorem | CM-2 Impossibility Theorem |
| Blue Eyes Island Problem | Social phase transition trigger mechanism |
| Ising Model | IMNB Global Attractor |

---

## Tech Stack

- **Frontend**: HTML5 Canvas, Tailwind CSS
- **Engine**: Euler Method (solving coupled ODEs)
- **Chart**: Chart.js

---

## License

MIT

---

## Disclaimer

This project is a demonstration of sociological theory models. The name "Chinese Mathematics" originates from the literary characterization of specific dynamical mechanisms.

# CMS 社会动力学模拟器

> "为什么越成功的人越焦虑？为什么'清醒'的人在这个系统里活不下去？"

这是一个基于**中国数学公理系统（Chinese Mathematical System, CMS）**的交互式模拟器，用代码复现了社会互动中的认知失调动力学。

## 快速开始

```bash
git clone https://github.com/Orangeforce/-.git
cd -
open 中国数学模拟器.html
```

不需要安装任何依赖，纯前端实现。

---

## 这是什么？（人话版）

想象一个社交圈，每个人内心都有一个"自我评价指数"（ρ，0-1之间）：

| 自我评价指数 | 状态 | 特征 |
|------------|------|------|
| ρ < 0.5（绿色） | IMSB 状态（"我很差"） | 相对理性 |
| ρ > 0.5（红色） | IMNB 状态（"我不错"） | 认知失调 |

### 核心悖论（CM-2 不可能性定理）

在高社交密度（σ > σc）的环境下，"保持清醒"是不可能的。无论你一开始多么谦虚，系统最终会把你推向盲目自信（ρ→1）。**这不是你的错，是结构性的。**

---

## 三大核心机制

### 1. 吸血（Vampirism）

**"不配得的成功反而让人更膨胀"**

- 通过不正当手段获得资源
- 明知不配，但成功了 → 自我评价跃升（VRA-1 公理）

**操作**：点击任意节点触发吸血事件

### 2. 稻米（Rice-planting）

**"为了维持自恋，必须不断做蠢事"**

- IMNB 状态的人必须进行负期望投资
- 失败后反而强化自恋（RFA-2 公理）

**类型**：
- 类型1（虚荣）：买奢侈品装阔
- 类型2（故意）：赌博、成瘾

### 3. 群体无意识场（Φ）

**"你身边的人是什么状态，你就会变成什么状态"**

- 自我评价受邻居影响
- 当 σ > σc，相变发生，系统滑向全员自恋

**操作**：调节"社交密度"滑块到 0.6 以上观察相变

---

## 实验指南

### 实验一：验证 CM-2 不可能性定理

1. 保持 σ < 0.5，系统稳定（绿色）
2. 将 σ 调至 0.6 以上
3. **结果**：系统最终全变红，清醒无法维持

### 实验二：拓扑撕裂（CM-3 定理）

1. 让系统运行在超临界状态（全红）
2. 点击"拓扑撕裂"按钮
3. **结果**：两极分化，要么清醒，要么困在幽灵态

### 实验三：个体觉醒的代价（EA-2）

1. 让一个红色节点变绿
2. **结果**：周围节点加速变红
3. **结论**：一个人的觉醒，伴随他人的沉沦

---

## 参数说明

| 参数 | 含义 | 现实对应 |
|------|------|----------|
| α | 吸血导致的跃迁速度 | 社会容错度 |
| β | 正当成功的收敛速度 | 努力见效速度 |
| γ | 失败后维持自恋的强度 | 认知失调程度 |
| η | 无意识场催化效率 | 社交媒体算法 |
| σ | 社交密度 | 城市化、互联网普及 |
| σc | 临界密度 | 社会崩溃临界点 |

---

## 理论背景

| 公理 | 全称 | 说明 |
|------|------|------|
| VRA | 吸血-评级公理 | Vampirism-Rating Axiom |
| RFA | 稻米-强制公理 | Rice-planting Forced Axiom |
| EA | 异化/路径依赖公理 | Estrangement/Path Dependency Axiom |
| GUA | 群体无意识公理 | Group Unconsciousness Axiom |

### 与经典理论的对应

| 经典理论 | CMS 对应 |
|----------|----------|
| 阿罗不可能定理 | CM-2 不可能性定理 |
| 蓝眼睛岛问题 | 社会相变 |
| 伊辛模型 | IMNB 全局吸引子 |
| 凯恩斯选美竞赛 | 社会比较动力学 |

### 可检验的预言

- 城市化率超过某值，集体焦虑必然上升
- 大规模隔离后，社会分裂为清醒者和困住者
- 成功→焦虑→冒险→失败→归因→更自恋的周期性

---

## 技术栈

- **原生 HTML5 Canvas + Tailwind CSS**
- **Chart.js**
- **欧拉法求解耦合 ODE**
- 纯静态页面

---

## 延伸阅读

- 论文原文：[cms_chinese.html](cms_chinese.html) | [cms_english.html](cms_english.html)
- [蓝眼睛岛问题](https://en.wikipedia.org/wiki/Blue-eyed_island_puzzle)
- [认知失调理论](https://en.wikipedia.org/wiki/Cognitive_dissonance)

---

## 许可

MIT License - 欢迎 fork 和改进，如果用于学术研究请引用。

---

## 免责声明

> "这不是一个 bug，这是一个 feature。—— 社会系统"

这是一个理论模型，"中国数学"名称源于特定社会动力学机制的刻画，但模型具有普适性。

- 不要用它为个人道德缺陷开脱
- 不要为系统性不公辩护

**目的是理解结构，而非合理化现象。**

