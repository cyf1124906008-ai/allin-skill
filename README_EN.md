<div align="center">

# 🎰 All-in.skill

**gamble smarter, not harder**

<br>

```
  ╔═══╦═══╦═══╦═══╦═══╗
  ║ A ║ K ║ Q ║ J ║ 10║   ← Can you read your cards?
  ╚═══╩═══╩═══╩═══╩═══╝
```

<br>

> *"I want to check the cards! ...Cards are fine. Going all-in is a wisdom."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

<br>

You "felt it was going to moon" and went all-in. Now you're the one holding the bag?

You "risked it for the biscuit" and ended up with neither the risk nor the biscuit?

You said "this time is different" — and it was. You lost more than last time.

You FOMO-bought at 3 AM, woke up, and realized you bought the top. You were the only one up there.

You followed a "insider tip" and the only thing insider was your wallet getting cleaned out from the inside?

Relax. The God of Gamblers is here.

**Bold when you should, cautious when you shouldn't.**

<br>

Provide your decision scenario and stake size<br>
We break it down into a complete all-in analysis:<br>
**🔍 5-dimension card reading → 🎭 3-perspective showdown → 🎯 One-liner verdict**

<br>

[**中文**](README.md) · [日本語](README_JA.md) · [한국어](README_KO.md) · [Español](README_ES.md)

</div>

<br>

<div align="center">

[Features](#-features) · [Install](#-install) · [Usage](#-usage) · [Examples](#-examples) · [Sponsor](#-sponsor-dataeyesai) · [Structure](#-project-structure)

</div>

---

## ✨ Features

### 🎲 Supported Asset Types

| Type | Special Analysis | Highlight |
|:----:|:---------------:|:---------:|
| 🪙 Crypto | Halving cycle, Fear & Greed, on-chain data | Meme coins -20pts |
| 📈 Stocks | Fundamentals, technicals, valuation, catalysts | A-share T+1 reminder |
| 🏠 Real Estate | Rent-to-price, location, policy, liquidity | Developer risk check |
| 📊 Funds / ETFs | Manager track record, fees, style drift | Active vs Passive |
| 💎 Collectibles | Consensus risk, real value assessment | Don't touch what you don't know |
| 🌍 Life Decisions | Reversibility, fear-setting, life stage fit | Type 1 / Type 2 |

### 🃏 God of Gamblers Process

Every decision goes through 5 steps:

```text
👁️ Read → 🧠 Identify → 🧮 Calculate → 🎭 Debate → 🎰 Verdict
 Collect    Classify     5-dimension    3 advisors    Score+Conclusion
```

### 🎭 Three Table Advisors

| Advisor | Mental Model | One-liner Style |
|:------:|:----------:|:--------------:|
| 🟢 **Optimist** | Peter Thiel · Zero to One | Where's the asymmetric upside? |
| 🔴 **Pessimist** | Nassim Taleb · Black Swan | How big is the tail risk? |
| 🟡 **Realist** | Charlie Munger · Inversion | If this fails, why? |

### 📊 All-in Score

| Score | Verdict | God of Gamblers says |
|:-----:|:-------:|:-------------------:|
| 🟢 **80-100** | Go all-in | Cards look great, push the chips |
| 🟡 **60-79** | Worth a try, control position | Worth following, don't bet the house |
| 🟠 **40-59** | Don't go, observe first | Test with small chips first |
| 🔴 **0-39** | Don't go, fold now | Just fold, don't even look |

### 🎬 Gambling Movie Easter Eggs

| Meme | Source | When to Use |
|:----:|:------:|:-----------:|
| "Check the cards" | God of Gamblers | Info seems unreliable |
| "Shine my shoes" | God of Gamblers 2 | Bad hand, still going all-in |
| "Rub the cards" | Saint of Gamblers | Thinking you can control the outcome |
| "Eat chocolate" 🍫 | God of Gamblers | Need to calm down |
| "All-in is wisdom" | Internet meme | Sarcastic confidence |
| "Bike to motorcycle" 🏍️ | Folklore | Full version: motorcycle to wheelchair |

---

## ⚡ Install

### Claude Code

> 💡 Claude Code loads skills from `.claude/skills/` in the **git repo root**.

```bash
# Install to current project
mkdir -p .claude/skills
git clone https://github.com/cyf1124906008-ai/allin-skill .claude/skills/allin

# Or install globally (available in all projects)
git clone https://github.com/cyf1124906008-ai/allin-skill ~/.claude/skills/allin
```

### OpenClaw

```bash
git clone https://github.com/cyf1124906008-ai/allin-skill ~/.openclaw/workspace/skills/allin
```

### 📰 Connect NewsNow for Real-time Financial News (Optional)

Install [newsnow-mcp-server](https://github.com/ourongxing/newsnow-mcp-server) to automatically feed real-time financial news into allin analysis:

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

Replace `BASE_URL` with your own NewsNow deployment. Supports 40+ news sources including CLS, Wallstreet CN, Xueqiu, Jin10, Gelonghui, Fastbull and more.

---

## 🎮 Usage

```text
/allin
```

> 💡 Chinese alias: `/梭哈` also works

Answer 4 questions (Target · Stake · Worst case · Emotional state) to get your full analysis report.

| Command | Description |
|:------:|:---------:|
| `/allin` (alias `/梭哈`) | Start a new all-in analysis |
| `/allin-review` (alias `/梭哈复盘`) | Review past decisions and hit rate |
| Natural language | "Help me analyze should I go all-in on BTC" also triggers it |

---

## 📖 Examples

> Input: `I want to go all-in 500k on BTC, I feel it's about to moon`

```text
━━━ 🎰 All-in Analysis Report ━━━

📊 All-in Score: 62/100
🎲 Verdict: Worth a try, but control your position

├─ 🔍 Card Reading
│  ├─ 💰 Expected Return
│  │  Bull (25%): 2x, +500k 🚀
│  │  Neutral (45%): ±10%, break even
│  │  Bear (30%): -40%, -200k 💀
│  │  Expected Value: +55k
│  │
│  ├─ ⬇️ Downside Risk
│  │  Worst case: BTC drops 60%, lose 300k
│  │  Reversibility: Partially reversible (can wait)
│  │  Severity: Painful but survivable
│  │
│  └─ 🧠 Emotion Check
│     ⚠️ Detected "I feel it's about to moon"
│     Last time you went with your gut, what happened? 🤔

├─ 🎭 Three Table Advisors
│  ├─ 🟢 Optimist: BTC halving cycle + ETF inflows, solid mid-term thesis
│  ├─ 🔴 Pessimist: You "feel" it's going to moon while rates are "feeling" up too
│  └─ 🟡 Realist: Direction is right, but 500k full position is too heavy

├─ ✅ Supporting Reasons
│  1. BTC halving cycle historical pattern
│  2. ETF approval brings institutional capital
│  3. Long-term uptrend
│
├─ ❌ Against Reasons
│  1. "Feel it's about to moon" is emotion, not analysis
│  2. 500k single-asset position is overconcentrated
│  3. No stop-loss in place

├─ 📝 Suggested Strategy
│  Position: 15-20% (75-100k)
│  Stop loss: -25%
│  Scale in, don't dump all at once

└─ 💡 Risk Reduction
   1. Start with 15%, add more if it rises
   2. Set stop-loss and stick to it
   3. Ask yourself: can I survive losing it all?

━━━━━━━━━━━━━━━━━
🎯 God of Gamblers says:
Put in 150-200k, don't all-in 500k. "I feel it's about to moon"
has lost more money than your entire bet. Check the cards first,
then push the chips.
━━━━━━━━━━━━━━━━━
```

---

## 🤝 Sponsor [Dataeyes.AI](https://dataeyes.ai/?promoter_code=nqg9bv83)

<div align="center">

### ⚡ [Dataeyes.AI](https://dataeyes.ai/?promoter_code=nqg9bv83)

**One Key for All Major AI Models · Official Direct Full-Power API**

[Sign up now →](https://dataeyes.ai/?promoter_code=nqg9bv83)

</div>

| | Feature | Description |
|:---:|:-------:|:-----------:|
| 🌐 | **Multi-Model Aggregation** | GPT5.4 · Claude Opus 4.6 · Gemini 3.1 Pro · Nanobanbana Pro · DeepSeek · GLM-5.1 and more |
| 🔌 | **One Platform** | Aggregate all mainstream models, switch on demand |
| 🔑 | **One Key** | One API key for all models, no multi-site registration |
| 💰 | **Transparent** | Unified billing, no hidden fees |
| ⚡ | **Ultra-Fast** | Low latency, production-ready |

---

## 📁 Project Structure

Follows the [AgentSkills](https://agentskills.io) open standard:

```text
allin-skill/
├── SKILL.md                    # 🎰 Entry point
├── prompts/                    # 📝 Prompt templates
│   ├── intake.md               #    Card reading (info collection)
│   ├── investment_analyzer.md  #    Investment analysis
│   ├── life_decision_analyzer.md #  Life decision analysis
│   ├── risk_analyzer.md        #    Risk assessment
│   ├── perspective_advisor.md  #    Multi-perspective advisors
│   └── report_builder.md       #    Report template + quote library
├── references/                 # 📚 Reference materials
│   ├── frameworks.md           #    8 decision frameworks
│   ├── cases.md                #    Classic all-in cases
│   └── memes.md                #    Gambling movie meme dictionary
├── records/                    # 📁 Decision logs (auto-generated)
└── LICENSE
```

---

## ⚠️ Disclaimer

- 🎯 **Final call is yours**: analysis is a tool, decisions are your life
- 🛡️ **Safety lines are non-negotiable**: borrowed money, leverage, life savings — we'll stop you
- 📊 **Better input = better analysis**: more specific info = clearer cards
- 🎲 **Even the God of Gamblers misses sometimes**: not financial advice

---

## 🙏 Credits

Inspired by:
- **[colleague-skill](https://github.com/titanwings/colleague-skill)** — pioneered "distill a person into AI Skill"
- **[nuwa-skill](https://github.com/alchaincyf/nuwa-skill)** — celebrity mental models for analysis

---

<div align="center">

MIT License © [cyf1124906008-ai](https://github.com/cyf1124906008-ai)

</div>
