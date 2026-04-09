<div align="center">

# 🎰 All-in.skill

**gamble smarter, not harder**

<br>

```
  ╔═══╦═══╦═══╦═══╦═══╗
  ║ A ║ K ║ Q ║ J ║ 10║
  ╚═══╩═══╩═══╩═══╩═══╝
```

<br>

> *"カードを確認したい！…カードに問題なし。オールインは知恵である。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

<br>

「上がる気がする」でオールインしたら、上がったのは心拍数だけで株価は下がった？

「今回は違う」と言って突っ込んだら、確かに違った——前回より多く損した

「みんな儲かってる」に焦って3時に全買い、起きたら天井付近に一人ぼっち

「インサイダー情報」を信じてオールイン、インサイドされたのは自分の財布

落ち着いて。ギャンブルの神が来た。

**ベットするべき時は大胆に、ベットしないべき時は止める。**

<br>

[**中文**](README.md) · [**English**](README_EN.md) · [한국어](README_KO.md) · [Español](README_ES.md)

</div>

---

## 🎲 対応資産タイプ

| タイプ | 特別分析 | ハイライト |
|:------:|:-------:|:---------:|
| 🪙 暗号通貨 | 半減期サイクル、恐怖貪欲指数、オンチェーンデータ | ミームコイン -20点 |
| 📈 株式 | ファンダメンタル、テクニカル、バリュエーション | A株T+1リマインダー |
| 🏠 不動産 | 利回り、立地評価、政策、流動性 | デベロッパーリスク |
| 📊 ファンド/ETF | マネージャー履歴、手数料、スタイルドリフト | アクティブ vs パッシブ |
| 💎 コレクション | コンセンサスリスク | 知らないものには触れない |
| 🌍 人生の決断 | 可逆性、フィアセッティング | Type 1 / Type 2 |

---

## ⚡ インストール

### Claude Code

```bash
git clone https://github.com/cyf1124906008-ai/allin-skill ~/.claude/skills/allin
```

### OpenClaw

```bash
git clone https://github.com/cyf1124906008-ai/allin-skill ~/.openclaw/workspace/skills/allin
```

### 📰 NewsNow リアルタイム金融ニュース接続（オプション）

[newsnow-mcp-server](https://github.com/ourongxing/newsnow-mcp-server) をインストールすると、allin 分析にリアルタイム金融ニュースが自動反映されます：

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

`BASE_URL` はご自身の NewsNow デプロイ先に変更可能。財聯社、ウォールストリート見聞、雪球、金十データなど 40+ のニュースソースに対応。

---

## 🎮 使い方

```text
/allin
```

| コマンド | 説明 |
|:--------:|:----:|
| `/allin`（別名 `/梭哈`） | 新しいオールイン分析を開始 |
| `/allin-review`（別名 `/梭哈复盘`） | 過去の決定と的中率を確認 |

---

## 🎭 3人のテーブルアドバイザー

| アドバイザー | 思考モデル | スタイル |
|:----------:|:--------:|:-------:|
| 🟢 **楽観派** | ピーター・ティール · Zero to One | 非対称のチャンスは？ |
| 🔴 **悲観派** | ナシム・タレブ · ブラックスワン | テールリスクはどこ？ |
| 🟡 **現実派** | チャーリー・マンガー · 逆転思考 | 失敗するならなぜ？ |

---

## 🤝 スポンサー [Dataeyes.AI](https://dataeyes.ai/?promoter_code=nqg9bv83)

<div align="center">

### ⚡ [Dataeyes.AI](https://dataeyes.ai/?promoter_code=nqg9bv83)

**1つのキーで全主要AIモデル対応 · 公式直結フルパワーAPI**

[今すぐ登録 →](https://dataeyes.ai/?promoter_code=nqg9bv83)

</div>

| | 特徴 | 説明 |
|:---:|:----:|:----:|
| 🌐 | **全モデル集約** | GPT5.4 · Claude Opus 4.6 · Gemini 3.1 Pro · Nanobanbana Pro · DeepSeek · GLM-5.1など |
| 🔌 | **マルチモデル集約** | 全主要モデルを1プラットフォームに集約、必要に応じて切替 |
| 🔑 | **1つのキー** | 複数登録不要、1つのキーで全モデル呼び出し可能 |
| 💰 | **透明な価格** | 統一課金、隠し費用なし |
| ⚡ | **超高速** | 低遅延、本番環境対応 |

---

## 🙏 クレジット

- **[colleague-skill](https://github.com/titanwings/colleague-skill)** — 「人をAI Skillに蒸留する」パターンの先駆者
- **[nuwa-skill](https://github.com/alchaincyf/nuwa-skill)** — 有名な思考モデルを使った分析

[AgentSkills](https://agentskills.io) オープン標準に準拠。Claude Code と OpenClaw に対応。

---

<div align="center">

MIT License © [cyf1124906008-ai (克劳德)](https://github.com/cyf1124906008-ai)

</div>
