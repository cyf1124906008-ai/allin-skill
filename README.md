<div align="center">

# 🎰 All-in.skill

** gamble smarter, not harder **

<br>

```
  ╔═══╦═══╦═══╦═══╦═══╗
  ║ A ║ K ║ Q ║ J ║ 10║   ← 你的牌面，你看清了吗？
  ╚═══╩═══╩═══╩═══╩═══╝
```

<br>

> *"窝腰验牌！……牌没问题，梭哈是一种智慧。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

<br>

你"感觉要暴涨"梭哈了一把，现在成了那把"暴涨"的韭菜？

你"搏一搏单车变摩托"，结果摩托变轮椅，轮椅还少个轮？

你"这次不一样"冲了进去，发现确实不一样——亏得比上次还多？

你半夜三点 FOMO 全仓买入，醒来发现买在了山顶，山顶上就你一个人？

你听信"内部消息"梭哈，结果那个"内部"是你的钱包被内部分析了？

别急，赌神来了。

**该梭的时候不怂，不该梭的时候拦得住。**

<br>

说出你的决策场景和投入规模<br>
赌神带你走完全流程：<br>
**🔍 5维算牌 → 🎭 3视角碰撞 → 🎯 赌神一句话结论**

<br>

[**English**](README_EN.md) · [日本語](README_JA.md) · [한국어](README_KO.md) · [Español](README_ES.md)

</div>

<br>

<div align="center">

[功能](#-功能特性) · [安装](#-安装) · [使用](#-使用) · [效果示例](#-效果示例) · [赞助商](#-赞助商-dataeyesai) · [结构](#-项目结构)

</div>

---

## ✨ 功能特性

### 🎲 支持的投资类型

| 类型 | 专属分析维度 | 特色 |
|:----:|:-----------:|:----:|
| 🪙 加密货币 | 减半周期、恐贪指数、链上数据、监管风险 | Meme币扣20分 |
| 📈 股票 | 基本面、技术面、估值、催化剂 | A股T+1/涨跌停提醒 |
| 🏠 房产 | 租售比、地段评估、政策面、流动性 | 烂尾风险检查 |
| 📊 基金/ETF | 基金经理评估、费率、风格漂移 | 主动 vs 被动 |
| 💎 收藏品 | 共识风险、真实价值评估 | 不懂不碰 |
| 🌍 人生决策 | 可逆性、恐惧设定、人生阶段适配 | Type 1 / Type 2 |

### 🃏 赌神分析流程

每个决策经过 5 步：

```
👁️ 看牌 → 🧠 识牌 → 🧮 算牌 → 🎭 亮牌 → 🎰 摊牌
 收集信息   判断类型   5维分析   3视角碰撞   指数+结论
```

### 🎭 三位赌桌顾问

| 顾问 | 思维模型 | 一句话风格 |
|:----:|:-------:|:---------:|
| 🟢 **乐观派** | 彼得·蒂尔 · 从0到1 | 不对称机会在哪？ |
| 🔴 **悲观派** | 塔勒布 · 黑天鹅 | 尾部风险有多大？ |
| 🟡 **现实派** | 芒格 · 反过来想 | 如果失败，输在哪？ |

### 📊 梭哈指数

| 分数 | 判断 | 赌神的话 |
|:----:|:----:|:-------:|
| 🟢 **80-100** | 可以梭哈 | 牌面好，筹码推出去 |
| 🟡 **60-79** | 可以试，控制筹码 | 值得跟，但别全押 |
| 🟠 **40-59** | 别梭，先看看 | 小筹码探探路 |
| 🔴 **0-39** | 别梭，收手 | 直接弃牌 |

### 🎬 赌片梗彩蛋

| 梗 | 来源 | 使用场景 |
|:--:|:----:|:-------:|
| "窝腰验牌" | 赌侠2 · 皮尔克松 | 信息不靠谱时 |
| "给我擦皮鞋" | 赌侠2 · 皮尔克松 | 牌面不行还硬上 |
| "搓牌" | 赌圣 · 周星驰 | 以为能操纵结果 |
| "吃巧克力" 🍫 | 赌神 · 周润发 | 需要冷静时 |
| "梭哈是一种智慧" | 网络梗 | 讽刺盲目自信 |
| "搏一搏单车变摩托" 🏍️ | 民间梗 | 完整版：摩托变轮椅 |

---

## ⚡ 安装

### Claude Code

> 💡 Claude Code 从 **git 仓库根目录** 的 `.claude/skills/` 查找 skill。

```bash
# 安装到当前项目
mkdir -p .claude/skills
git clone https://github.com/cyf1124906008-ai/allin-skill .claude/skills/allin

# 或安装到全局（所有项目都能用）
git clone https://github.com/cyf1124906008-ai/allin-skill ~/.claude/skills/allin
```

### OpenClaw

```bash
git clone https://github.com/cyf1124906008-ai/allin-skill ~/.openclaw/workspace/skills/allin
```

### 📰 接入 NewsNow 实时财经新闻（可选）

安装 [newsnow-mcp-server](https://github.com/ourongxing/newsnow-mcp-server) 后，allin 会自动获取实时财经快讯作为分析数据：

```json
{
  "mcpServers": {
    "newsnow": {
      "command": "npx",
      "args": ["-y", "newsnow-mcp-server"],
      "env": {
        "BASE_URL": "https://newsnow.busiyi.world"
      }
    }
  }
}
```

`BASE_URL` 可换成你自己部署的 NewsNow 地址。支持 40+ 新闻源，包括财联社、华尔街见闻、雪球、金十数据、格隆汇等。

---

## 🎮 使用

```text
/allin
```

> 💡 中文别名：`/梭哈` 也可以触发

回答 4 个问题（梭哈什么 · 筹码多大 · 最坏情况 · 当前状态），生成完整分析报告。

| 命令 | 说明 |
|:----:|:---:|
| `/allin` (别名 `/梭哈`) | 开始新的梭哈分析 |
| `/allin-review` (别名 `/梭哈复盘`) | 查看历史决策记录和命中率 |
| 自然语言 | 直接说"帮我分析该不该梭哈 BTC"也能触发 |

---

## 📖 效果示例

> 输入：`我要梭哈 50 万买 BTC，感觉要暴涨了`

```text
━━━ 🎰 梭哈分析报告 ━━━

📊 梭哈指数：62/100
🎲 牌面判断：可以试，控制筹码

├─ 🔍 算牌过程
│  ├─ 💰 预期收益
│  │  乐观（25%）：翻倍，+50万 🚀
│  │  中性（45%）：±10%，基本持平
│  │  悲观（30%）：跌40%，-20万 💀
│  │  期望值：+5.5万
│  │
│  ├─ ⬇️ 下行风险
│  │  最坏情况：BTC跌60%，亏30万
│  │  可逆性：部分可逆（等得起能回）
│  │  致命程度：痛但能接受
│  │
│  └─ 🧠 情绪体检
│     ⚠️ 检测到"感觉要暴涨"——兄弟，你这个"感觉"
│     上次凭感觉梭哈是什么结果来着？🤔

├─ 🎭 三位赌桌顾问
│  ├─ 🟢 乐观派：BTC减半周期+ETF资金流入，中长期逻辑硬
│  ├─ 🔴 悲观派：你说"感觉要暴涨"，法定货币也在"感觉"要加息
│  └─ 🟡 现实派：方向对了，但50万全仓太重

├─ ✅ 支持理由
│  1. BTC减半周期历史规律支撑
│  2. ETF通过带来机构资金
│  3. 长期趋势向上
│
├─ ❌ 反对理由
│  1. "感觉要暴涨"不是分析是情绪
│  2. 50万全仓单一标的风险过大
│  3. 没设止损

├─ 📝 建议策略
│  筹码比例：15-20%（7.5-10万）
│  止损线：-25%
│  分批建仓，别一次性梭完

└─ 💡 降低风险
   1. 先用15%探路，涨了再加仓
   2. 设好止损线，到了就跑，别犹豫
   3. 买之前想好：这笔钱亏完了影响生活吗？

━━━━━━━━━━━━━━━━━
🎯 赌神一句话：
梭个15-20万就够了，别50万 all in。"感觉要暴涨"
这四个字亏过的钱比你这个50万多多了。
先窝腰验牌，验完再梭也不迟。
━━━━━━━━━━━━━━━━━
```

---

## 🤝 赞助商 [Dataeyes.AI](https://dataeyes.ai/?promoter_code=nqg9bv83)

<div align="center">

### ⚡ [Dataeyes.AI](https://dataeyes.ai/?promoter_code=nqg9bv83)

**一个 Key 搞定所有主流大模型 · 官方直连满血 API**

[立即注册 →](https://dataeyes.ai/?promoter_code=nqg9bv83)

</div>

| | 特性 | 说明 |
|:---:|:----:|:---:|
| 🌐 | **全模型聚合** | GPT5.4 · Claude Opus 4.6 · Gemini 3.1 Pro · Nanobanbana Pro · DeepSeek · GLM-5.1 等 |
| 🔌 | **多模型聚合** | 一个平台聚合所有主流模型，按需切换 |
| 🔑 | **一个 Key** | 无需多家注册，一个密钥调用所有模型 |
| 💰 | **价格透明** | 统一计费，无隐藏费用 |
| ⚡ | **极速响应** | 低延迟，生产环境可用 |

---

## 📁 项目结构

遵循 [AgentSkills](https://agentskills.io) 开放标准：

```text
allin-skill/
├── SKILL.md                    # 🎰 入口（赌神分析师人设 + 完整流程）
├── prompts/                    # 📝 Prompt 模板
│   ├── intake.md               #    看牌（信息收集 + 情绪信号识别）
│   ├── investment_analyzer.md  #    算牌（投资：加密/股票/房产/基金）
│   ├── life_decision_analyzer.md #  算牌（人生：可逆性/恐惧设定）
│   ├── risk_analyzer.md        #    风险评估（分级/量化/杠杆规则）
│   ├── perspective_advisor.md  #    亮牌（三视角顾问）
│   └── report_builder.md       #    摊牌（报告模板 + 金句库）
├── references/                 # 📚 参考资料
│   ├── frameworks.md           #    8个决策框架（凯利/期望值/杠铃策略）
│   ├── cases.md                #    经典案例（成功+失败+民间搞笑）
│   └── memes.md                #    赌片梗词典
├── records/                    # 📁 决策记录（自动生成）
└── LICENSE
```

---

## ⚠️ 注意事项

- 🎯 **最终决定权在你**：分析是工具，决策是你的人生
- 🛡️ **安全底线不可突破**：借钱/杠杆/保命钱梭哈——赌神也得拦你
- 📊 **信息越具体，牌面越清楚**：你给的信息决定分析质量
- 🎲 **赌神也会翻车**：命中率高不代表每次都对，后果自负
- 📋 **这不是投资建议**：这是帮你想清楚的工具，不是理财顾问

---

## 🙏 致敬

本项目架构灵感来源于：
- **[同事.skill](https://github.com/titanwings/colleague-skill)**（by titanwings）— 首创"把人蒸馏成 AI Skill"的双层架构
- **[女娲.skill](https://github.com/alchaincyf/nuwa-skill)**（by alchaincyf）— 用名人思维模型做分析

赌片梗致敬：《赌神》周润发 · 《赌侠2》皮尔克松 · 《赌圣》周星驰

---

<div align="center">

MIT License © [cyf1124906008-ai (克劳德)](https://github.com/cyf1124906008-ai)

</div>
