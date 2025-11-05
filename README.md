# alpha_factorio

## Goal: 利用两个模块自动完成给定任务
### Modules 1: 产能/科技规划器（Planner）
- 使用计算器或配方库将目标任务逐层分解：  
  最终目标（火箭） → 所需科学包 → 各科学包的生产速率 → 原材料与中间件的生产速率 → 矿石与油品等基础资源。

### Modules 2: 蓝图生成器（RL 设计器）
 - 针对每一条生产线，用强化学习（RL）自动生成满足目标产率的蓝图。
 -  可能的Reward: 达成目标产率（主奖励）, 占地、功耗、建造所需材料
 -  为了简化设计，可以进一步给定原料出口和进口的位置？

## 🔗 Some Useful Links

| Topic | Description | Link |
|:------|:-------------|:------|
| **Factorio Calculator** | Online calculator for production ratios and crafting chains. | [kirkmcdonald.github.io/calc](https://kirkmcdonald.github.io/calc.html#data=2-0-55&items=advanced-circuit:f:1) |
| **Official Scripting Tutorial** | The official guide for creating scripts and mods in Factorio. | [wiki.factorio.com/Tutorial:Scripting](https://wiki.factorio.com/Tutorial:Scripting) |
| **Factorio TAS Mod (Any%)** | A tool-assisted speedrun (TAS) mod that automates rocket launch in vanilla Factorio. | [gotyoke/Factorio-AnyPct-TAS](https://github.com/gotyoke/Factorio-AnyPct-TAS/blob/master/README.md) |
| **Reddit Discussion** | Community discussion on controlling the player through mods. | [reddit.com/r/factorio/...](https://www.reddit.com/r/factorio/comments/b4i1yx/controlling_the_player_through_a_) |

---

## 🧩 About the TAS Mod

The [Factorio Any% TAS project](https://github.com/gotyoke/Factorio-AnyPct-TAS) is a **Tool-Assisted Speedrun** mod for the Factorio PC game by *Wube Software LTD*.

- The included scripts automate a **complete Any% rocket launch** in single-player mode.  
- Version **0.2.2** achieves a full run for **Factorio 0.18** in **1h 21m 20s** using a specific map seed.  
- 我们可以通过这个项目看一些怎么写scripts来自动控制人物。
