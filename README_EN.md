<div align="center">

# 梭哈.skill

> *"I want to check the cards! ...Cards are fine. Going all-in is a wisdom."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

<br>

Investment, career, life decisions — should you go all-in?<br>
The God of Gamblers helps you read the cards: structured analysis + multi-perspective debate + one sharp verdict.<br>
We don't tell you to "go" or "not go" — we help you see the cards clearly before you bet.

**Bold when you should, cautious when you shouldn't.**

<br>

Provide your decision scenario and stake size<br>
We break it down into a complete all-in analysis report:<br>
**5-dimension card reading + 3-perspective showdown + One-liner verdict**

[Supported Assets](#supported-asset-types) · [Install](#install) · [Usage](#usage) · [Examples](#examples) · [**中文**](README.md)

</div>

---

## Supported Asset Types

| Type | Special Analysis | Highlight |
|------|:----------------:|:---------:|
| Crypto | Halving cycle, Fear & Greed, on-chain data, regulation | Meme coins -20pts |
| Stocks | Fundamentals, technicals, valuation, catalysts | A-share T+1 reminder |
| Real Estate | Rent-to-price, location, policy, liquidity | Developer risk check |
| Funds / ETFs | Manager track record, fees, style drift | Active vs Passive |
| Collectibles | Consensus risk, real value assessment | Don't touch what you don't know |
| Life Decisions | Reversibility, fear-setting, life stage fit | Type 1 / Type 2 |

---

## Install

### Claude Code

```bash
# Install globally
git clone https://github.com/cyf1124906008-ai/suoha-skill ~/.claude/skills/suoha

# Or install to current project
mkdir -p .claude/skills
git clone https://github.com/cyf1124906008-ai/suoha-skill .claude/skills/suoha
```

### OpenClaw

```bash
git clone https://github.com/cyf1124906008-ai/suoha-skill ~/.openclaw/workspace/skills/suoha
```

---

## Usage

```
/梭哈
```

Or just say: "Help me analyze whether I should go all-in on BTC"

### Commands

| Command | Description |
|---------|-------------|
| `/梭哈` | Start a new all-in analysis |
| `/梭哈复盘` | Review past decisions and hit rate |

---

## Examples

> Input: `I want to go all-in 500k on BTC, I feel it's about to moon`

```
━━━ All-in Analysis Report ━━━

📊 All-in Score: 62/100
🎲 Verdict: Worth a try, but control your position

├─ Card Reading
│  ├─ Expected Return:
│  │  Bull (25%): 2x, +500k
│  │  Neutral (45%): ±10%, break even
│  │  Bear (30%): -40%, -200k
│  │  Expected Value: +55k
│  │
│  ├─ Downside Risk:
│  │  Worst case: BTC drops 60%, lose 300k
│  │  Reversibility: Partially reversible (can wait)
│  │  Severity: Painful but survivable
│  │
│  ├─ Emotion Check:
│  │  ⚠️ Detected "I feel it's about to moon"
│  │  Last time you went with your gut, what happened?

├─ Three Table Advisors
│  ├─ 🟢 Optimist: BTC halving cycle + ETF inflows...
│  ├─ 🔴 Pessimist: You "feel" it's going to moon while
│  │  macro rates are "feeling" like going up too...
│  └─ 🟡 Realist: Direction is right, but 500k full position
│      is too heavy...

━━━━━━━━━━━━━━━━━
🎯 God of Gamblers says:
Put in 150-200k, don't all-in 500k. "I feel it's about to moon"
has lost more money than your entire bet. Check the cards first,
then push the chips.
━━━━━━━━━━━━━━━━━
```

---

## Features

### 5-Step God of Gamblers Process

| Step | Description |
|------|-------------|
| **Read Cards** | Collect 4 key inputs: target, stake, worst case, emotional state |
| **Identify Cards** | Auto-detect type: investment / life decision / mixed |
| **Calculate Cards** | 5 dimensions: return, downside, probability, opportunity cost, emotion |
| **Show Cards** | 3 perspectives: Optimist / Pessimist / Realist |
| **Reveal Cards** | All-in score + strategy + one-liner verdict |

### Three Table Advisors

| Advisor | Mental Model | Style |
|---------|-------------|-------|
| 🟢 **Optimist** | Peter Thiel (Zero to One) | Where's the asymmetric upside? |
| 🔴 **Pessimist** | Nassim Taleb (Black Swan) | Where's the tail risk? |
| 🟡 **Realist** | Charlie Munger (Inversion) | If this fails, why? |

### Decision Logging + Review

- Every analysis auto-saved locally
- `/梭哈复盘` to review history and hit rate
- Backfill actual results to track accuracy

---

## Project Structure

```
suoha/
├── SKILL.md                    # Skill entry point
├── prompts/                    # Prompt templates
│   ├── intake.md               #   Card reading (info collection)
│   ├── investment_analyzer.md  #   Investment analysis
│   ├── life_decision_analyzer.md # Life decision analysis
│   ├── risk_analyzer.md        #   Risk assessment
│   ├── perspective_advisor.md  #   Multi-perspective advisors
│   └── report_builder.md       #   Report template + quote library
├── references/                 # Reference materials
│   ├── frameworks.md           #   8 decision frameworks
│   ├── cases.md                #   Classic all-in cases
│   └── memes.md                #   Gambling movie meme dictionary
├── records/                    # Decision logs (auto-generated)
└── LICENSE
```

---

## Credits

Inspired by:
- **[colleague-skill](https://github.com/titanwings/colleague-skill)** — pioneered the "distill a person into AI Skill" pattern
- **[nuwa-skill](https://github.com/alchaincyf/nuwa-skill)** — using celebrity mental models for analysis

This project follows the [AgentSkills](https://agentskills.io) open standard. Compatible with Claude Code and OpenClaw.

---

<div align="center">

MIT License © [cyf1124906008-ai](https://github.com/cyf1124906008-ai)

</div>
