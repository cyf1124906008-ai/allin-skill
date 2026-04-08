<div align="center">

# 梭哈.skill

> *"该不该 all in？先看完这份分析再决定。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

<br>

投资、事业、人生大事——该不该梭哈？<br>
系统分析框架 + 多视角碰撞 + 一句犀利结论。<br>
不是告诉你"梭"或"不梭"，而是帮你把该想的都想清楚。<br>

[安装](#安装) · [使用](#使用) · [报告示例](#报告示例)

</div>

---

## 安装

### Claude Code

```bash
# 全局安装（所有项目都能用）
git clone https://github.com/YOUR_USERNAME/suoha-skill ~/.claude/skills/suoha

# 或安装到当前项目
mkdir -p .claude/skills
git clone https://github.com/YOUR_USERNAME/suoha-skill .claude/skills/suoha
```

### OpenClaw

```bash
git clone https://github.com/YOUR_USERNAME/suoha-skill ~/.openclaw/workspace/skills/suoha
```

---

## 使用

在 Claude Code 中输入：

```
/梭哈
```

或直接说："帮我分析该不该梭哈 XXX"

回答 4 个问题后，生成完整分析报告。

### 命令

| 命令 | 说明 |
|------|------|
| `/梭哈` | 开始新的梭哈分析 |
| `/梭哈复盘` | 查看历史决策记录和准确率 |

---

## 报告示例

> 输入："我想梭哈 50 万买 BTC"

```
━━━ 梭哈分析报告 ━━━

📊 梭哈指数：62/100
可以试，控制仓位

├─ 分析过程
│  ├─ 预期收益：
│  │  乐观（25%）：翻倍，+50 万
│  │  中性（45%）：±10%，基本持平
│  │  悲观（30%）：跌 40%，-20 万
│  │  期望值：+5.5 万
│  │
│  ├─ 下行风险：
│  │  最坏情况：BTC 跌 60%，亏损 30 万
│  │  可逆性：部分可逆（等得起就能回）
│  │  致命程度：痛但能接受（不涉及借贷）
│  ...
│
├─ 多视角碰撞
│  ├─ 🟢 乐观派说：BTC 减半周期 + ETF 资金流入...
│  ├─ 🔴 悲观派说：宏观利率环境不确定，你入场时机...
│  └─ 🟡 现实派说：逻辑有道理，但 50 万全仓太重...

━━━━━━━━━━━━━━━━━
🎯 一句话结论：
梭个 15-20 万就够了，别 50 万 all in。BTC 值得配置，
但你当前的判断里情绪占了不少，仓位控制在亏完不心疼的范围内。
━━━━━━━━━━━━━━━━━
```

---

## 功能特性

### 分析维度

| 维度 | 内容 |
|------|------|
| 预期收益 | 乐观/中性/悲观三情景 |
| 下行风险 | 最坏情况 + 可逆性 + 致命程度 |
| 概率评估 | 基于已知信息的主观概率 |
| 机会成本 | 不梭哈的替代选择 |
| 情绪体检 | 理性 vs 情绪驱动判断 |

### 多视角碰撞

- 🟢 **乐观派（彼得·蒂尔思维）**：不对称机会分析
- 🔴 **悲观派（塔勒布思维）**：黑天鹅和尾部风险
- 🟡 **现实派（芒格思维）**：反过来想，安全边际

### 决策框架

- 凯利公式（仓位管理）
- 期望值分析
- 贝佐斯 Type 1/Type 2 决策
- 杠铃策略
- 恐惧设定（Fear-Setting）

### 决策记录

每次分析自动保存，支持复盘验证准确率。

---

## 项目结构

```
suoha/
├── SKILL.md                # Skill 入口
├── prompts/                # Prompt 模板
│   ├── intake.md           #   信息收集
│   ├── investment_analyzer.md  # 投资分析
│   ├── life_decision_analyzer.md  # 人生决策分析
│   ├── risk_analyzer.md    #   风险评估
│   ├── perspective_advisor.md  # 多视角顾问
│   └── report_builder.md   #   报告生成
├── references/             # 参考材料
│   ├── frameworks.md       #   决策框架集合
│   └── cases.md            #   经典梭哈案例
├── records/                # 决策记录（自动生成）
└── LICENSE
```

---

## 致敬

项目架构灵感来源于：
- **[同事.skill](https://github.com/titanwings/colleague-skill)** — 首创"蒸馏人"的 Skill 架构模式
- **[女娲.skill](https://github.com/alchaincyf/nuwa-skill)** — 用名人思维模型做分析

本项目遵循 [AgentSkills](https://agentskills.io) 开放标准，兼容 Claude Code 和 OpenClaw。

MIT License
