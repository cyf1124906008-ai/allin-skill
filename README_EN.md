<div align="center">

# 🎰 梭哈.skill

> *"I want to check the cards! ...🃏 Cards are fine. Going all-in is a wisdom."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

<br>

💰 Investment · 💼 Career · 💕 Life decisions — **should you go all-in?**

The God of Gamblers helps you read the cards: 📊 structured analysis + 🎭 multi-perspective debate + 🎯 one sharp verdict.<br>
We don't tell you to "go" or "not go" — we help you **see the cards clearly before you bet**.

**🔥 Bold when you should, cautious when you shouldn't.**

<br>

Provide your decision scenario and stake size 🎤<br>
We break it down into a complete all-in analysis report:<br>
**🔍 5-dimension card reading → 🎭 3-perspective showdown → 🎯 One-liner verdict**

<br>

[🎲 Asset Types](#supported-asset-types) · [⚡ Install](#install) · [🎮 Usage](#usage) · [📖 Examples](#examples) · [🤝 Sponsor](#sponsor) · [**中文**](README.md) · [日本語](README_JA.md) · [한국어](README_KO.md) · [Español](README_ES.md)

</div>

---

## 🎲 Supported Asset Types

| Type | 🧠 Special Analysis | 💡 Highlight |
|------|:------------------:|:------------:|
| 🪙 Crypto | Halving cycle, Fear & Greed, on-chain data, regulation | Meme coins -20pts |
| 📈 Stocks | Fundamentals, technicals, valuation, catalysts | A-share T+1 reminder |
| 🏠 Real Estate | Rent-to-price, location, policy, liquidity | Developer risk check |
| 📊 Funds / ETFs | Manager track record, fees, style drift | Active vs Passive |
| 💎 Collectibles | Consensus risk, real value assessment | Don't touch what you don't know |
| 🌍 Life Decisions | Reversibility, fear-setting, life stage fit | Type 1 / Type 2 |

---

## ⚡ Install

### Claude Code

> **💡 Tip**: Claude Code loads skills from `.claude/skills/` in the **git repo root**. Make sure you're in the right directory.

```bash
# 📦 Install to current project (run in git repo root)
mkdir -p .claude/skills
git clone https://github.com/cyf1124906008-ai/suoha-skill .claude/skills/suoha

# 🌐 Or install globally (available in all projects)
git clone https://github.com/cyf1124906008-ai/suoha-skill ~/.claude/skills/suoha
```

### OpenClaw

```bash
git clone https://github.com/cyf1124906008-ai/suoha-skill ~/.openclaw/workspace/skills/suoha
```

---

## 🎮 Usage

```
/梭哈
```

Or just say: "Help me analyze whether I should go all-in on BTC"

Answer 4 questions (🎯 Target · 💰 Stake · 💀 Worst case · 🧠 Emotional state) to get your full analysis report.

### Commands

| Command | 📝 Description |
|---------|------|
| `/梭哈` | 🎰 Start a new all-in analysis |
| `/梭哈复盘` | 📜 Review past decisions and hit rate |

---

## 📖 Examples

> 💬 Input: `I want to go all-in 500k on BTC, I feel it's about to moon`

```
━━━ 🎰 All-in Analysis Report ━━━

📊 All-in Score: 62/100
🎲 Verdict: Worth a try, but control your position

├─ 🔍 Card Reading
│  ├─ 💰 Expected Return:
│  │  Bull (25%): 2x, +500k 🚀
│  │  Neutral (45%): ±10%, break even 😐
│  │  Bear (30%): -40%, -200k 💀
│  │  Expected Value: +55k
│  │
│  ├─ ⬇️ Downside Risk:
│  │  Worst case: BTC drops 60%, lose 300k
│  │  Reversibility: Partially reversible (can wait)
│  │  Severity: Painful but survivable
│  │
│  ├─ 🧠 Emotion Check:
│  │  ⚠️ Detected "I feel it's about to moon"
│  │  Last time you went with your gut, what happened? 🤔

├─ 🎭 Three Table Advisors
│  ├─ 🟢 Optimist: BTC halving cycle + ETF inflows...
│  ├─ 🔴 Pessimist: You "feel" it's going to moon while
│  │  macro rates are "feeling" like going up too... 😏
│  └─ 🟡 Realist: Direction is right, but 500k full position
│      is too heavy...

├─ ✅ Top 3 Supporting Reasons
├─ ❌ Top 3 Against Reasons
├─ ⚠️ Key Risk Points
│
├─ 📝 If you go, suggested strategy:
│  💰 Position: 15-20% (75-100k)
│  🛑 Stop loss: -25%
│  📉 Scale in, don't dump all at once

└─ 💡 3 Ways to Reduce Risk
   1. 🧪 Start with 15%, add more if it rises
   2. 🛑 Set stop-loss and stick to it
   3. 🪑 Ask yourself: can I survive losing it all?

━━━━━━━━━━━━━━━━━
🎯 God of Gamblers says:
Put in 150-200k, don't all-in 500k. "I feel it's about to moon" 💸
has lost more money than your entire bet. Check the cards first, 🃏
then push the chips.
━━━━━━━━━━━━━━━━━
```

---

## 🧩 Features

### 🃏 5-Step God of Gamblers Process

| Step | Description |
|------|-------------|
| 👁️ **Read Cards** | Collect 4 key inputs: target, stake, worst case, emotional state |
| 🧠 **Identify Cards** | Auto-detect type: investment / life decision / mixed |
| 🧮 **Calculate Cards** | 5 dimensions: return, downside, probability, opportunity cost, emotion |
| 🎭 **Show Cards** | 3 perspectives: Optimist / Pessimist / Realist |
| 🎰 **Reveal Cards** | All-in score + strategy + one-liner verdict |

### 🎭 Three Table Advisors

| Advisor | 🧠 Mental Model | 🎤 Style |
|---------|-------------|--------|
| 🟢 **Optimist** | Peter Thiel (Zero to One) | Where's the asymmetric upside? 🚀 |
| 🔴 **Pessimist** | Nassim Taleb (Black Swan) | Where's the tail risk? 🦢 |
| 🟡 **Realist** | Charlie Munger (Inversion) | If this fails, why? 🤔 |

### 📊 All-in Score

| Score | 🎲 Verdict | 🎤 God of Gamblers says |
|-------|------|---------|
| 🟢 80-100 | Go all-in | Cards look great, push the chips 💪 |
| 🟡 60-79 | Worth a try, control position | Worth following, but don't bet the house ✋ |
| 🟠 40-59 | Don't go, observe first | Test with small chips first 🔍 |
| 🔴 0-39 | Don't go, fold now | Don't even look at the cards, just fold 🚫 |

### 📜 Decision Logging + Review

- 📁 Every analysis auto-saved locally
- 🔄 `/梭哈复盘` to review history and hit rate
- ✏️ Backfill actual results to track accuracy

---

## 🤝 Sponsor

<div align="center">

### ⚡ [Dataeyes.AI](https://dataeyes.ai/?promoter_code=nqg9bv83) — AI Model API Aggregator

**🔑 One Key for All Major AI Models · Official Direct Full-Power API**

</div>

| ✨ Feature | 📝 Description |
|------------|--------|
| 🌐 **All Models** | GPT-4o, Claude, Gemini, DeepSeek, Llama and all mainstream models |
| 🔌 **Official Direct** | Full-power API, no relay, stable and reliable |
| 🔑 **One Key** | No need to register at multiple providers, one key for all models |
| 💰 **Transparent Pricing** | Unified billing, no hidden fees |
| ⚡ **Ultra-Fast** | Low latency, production-ready |

> 🎯 **Recommended pairing with 梭哈 skill**: Power your AI apps with Dataeyes.AI's full-power API — one key for all models.
>
> 👉 [Sign up now at Dataeyes.AI](https://dataeyes.ai/?promoter_code=nqg9bv83)

---

## 📁 Project Structure

```
suoha/
├── SKILL.md                    # 🎰 Skill entry point
├── prompts/                    # 📝 Prompt templates
│   ├── intake.md               #   👁️ Card reading (info collection)
│   ├── investment_analyzer.md  #   🧮 Investment analysis
│   ├── life_decision_analyzer.md # 🌍 Life decision analysis
│   ├── risk_analyzer.md        #   ⚠️ Risk assessment
│   ├── perspective_advisor.md  #   🎭 Multi-perspective advisors
│   └── report_builder.md       #   🎯 Report template + quote library
├── references/                 # 📚 Reference materials
│   ├── frameworks.md           #   🧠 8 decision frameworks
│   ├── cases.md                #   📖 Classic all-in cases
│   └── memes.md                #   🎬 Gambling movie meme dictionary
├── records/                    # 📁 Decision logs (auto-generated)
└── LICENSE
```

---

## ⚠️ Disclaimer

- 🎯 **The God of Gamblers only helps you read cards — the final call is yours**
- 🛡️ **Safety lines are non-negotiable**: borrowed money, leverage, life savings — we'll stop you
- 📊 **Analysis quality depends on your input**: more specific info = clearer cards
- 🎲 **Even the God of Gamblers misses sometimes**: not financial advice

---

## 🙏 Credits

Inspired by:
- 🌟 **[colleague-skill](https://github.com/titanwings/colleague-skill)** — pioneered the "distill a person into AI Skill" pattern
- 🌟 **[nuwa-skill](https://github.com/alchaincyf/nuwa-skill)** — using celebrity mental models for analysis

This project follows the [AgentSkills](https://agentskills.io) open standard. Compatible with Claude Code and OpenClaw.

---

<div align="center">

MIT License © [cyf1124906008-ai](https://github.com/cyf1124906008-ai)

</div>
