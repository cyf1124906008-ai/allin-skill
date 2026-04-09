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

> *"카드를 확인하겠습니다!…카드 이상 없습니다. 올인은 지혜입니다."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)](https://agentskills.io)

<br>

"오를 것 같은 느낌"에 올인했다가 오른 건 심박수뿐, 코인은 하락?

"이번엔 다르다" 했는데 확실히 달랐다 — 지난번보다 더 많이 잃었다

남들 다 수익난다길래 새벽 3시에 전량 매수, 아침에 보니 꼭대기에 혼자

"내부 정보" 믿고 올인, 내부당한 건 내 지갑

진정하세요. 도박의 신이 왔습니다.

**베팅할 때는 대담하게, 베팅하지 말아야 할 때는 막아드립니다.**

<br>

[**中文**](README.md) · [**English**](README_EN.md) · [日本語](README_JA.md) · [Español](README_ES.md)

</div>

---

## 🎲 지원 자산 유형

| 유형 | 특별 분석 | 하이라이트 |
|:----:|:--------:|:---------:|
| 🪙 암호화폐 | 반감기 사이클, 공포탐욕지수, 온체인 데이터 | 밈코인 -20점 |
| 📈 주식 | 펀더멘털, 기술적, 밸류에이션, 촉매 | A주 T+1 리마인더 |
| 🏠 부동산 | 임대수익률, 입지, 정책, 유동성 | 시공사 리스크 |
| 📊 펀드/ETF | 매니저 이력, 수수료, 스타일 드리프트 | 액티브 vs 패시브 |
| 💎 컬렉터블 | 컨센서스 리스크 | 모르는 것은 건드리지 마세요 |
| 🌍 인생 결정 | 가역성, 피어세팅 | Type 1 / Type 2 |

---

## ⚡ 설치

### Claude Code

```bash
git clone https://github.com/cyf1124906008-ai/allin-skill ~/.claude/skills/allin
```

### OpenClaw

```bash
git clone https://github.com/cyf1124906008-ai/allin-skill ~/.openclaw/workspace/skills/allin
```

### 📰 NewsNow 실시간 금융 뉴스 연동 (선택사항)

[newsnow-mcp-server](https://github.com/ourongxing/newsnow-mcp-server) 를 설치하면 allin 분석에 실시간 금융 뉴스가 자동으로 반영됩니다：

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

`BASE_URL` 을 본인의 NewsNow 배포 주소로 변경 가능. 재련사, 월스트리트견문, 쉐치우, 금10데이터 등 40+ 뉴스 소스 지원.

---

## 🎮 사용법

```text
/allin
```

| 명령 | 설명 |
|:----:|:----:|
| `/allin`（별명 `/梭哈`） | 새로운 올인 분석 시작 |
| `/allin-review`（별명 `/梭哈复盘`） | 과거 결정 및 적중률 확인 |

---

## 🎭 세 명의 테이블 어드바이저

| 어드바이저 | 사고 모델 | 스타일 |
|:---------:|:--------:|:-----:|
| 🟢 **낙관파** | 피터 틸 · Zero to One | 비대칭 기회는 어디에? |
| 🔴 **비관파** | 나심 탈레브 · 블랙 스완 | 테일 리스크는 어디에? |
| 🟡 **현실파** | 찰리 멍거 · 역발상 | 실패한다면 왜? |

---

## 🤝 스폰서 [Dataeyes.AI](https://dataeyes.ai/?promoter_code=nqg9bv83)

<div align="center">

### ⚡ [Dataeyes.AI](https://dataeyes.ai/?promoter_code=nqg9bv83)

**하나의 키로 모든 주요 AI 모델 사용 · 공식 직접 연결 풀파워 API**

[지금 바로 가입 →](https://dataeyes.ai/?promoter_code=nqg9bv83)

</div>

| | 특징 | 설명 |
|:---:|:----:|:----:|
| 🌐 | **멀티모델 통합** | GPT5.4 · Claude Opus 4.6 · Gemini 3.1 Pro · Nanobanbana Pro · DeepSeek · GLM-5.1 등 |
| 🔌 | **멀티모델 집약** | 모든 주요 모델을 하나의 플랫폼에 집약, 필요에 따라 전환 |
| 🔑 | **하나의 키** | 하나의 키로 모든 모델 호출 가능 |
| 💰 | **투명한 가격** | 통일 과금, 숨겨진 비용 없음 |
| ⚡ | **초고속** | 저지연, 프로덕션 환경 대응 |

---

## 🙏 크레딧

- **[colleague-skill](https://github.com/titanwings/colleague-skill)** — "사람을 AI Skill로 증류하는" 패턴의 선구자
- **[nuwa-skill](https://github.com/alchaincyf/nuwa-skill)** — 유명인 사고 모델을 활용한 분석

[AgentSkills](https://agentskills.io) 오픈 표준 준수. Claude Code 및 OpenClaw 호환.

---

<div align="center">

MIT License © [cyf1124906008-ai](https://github.com/cyf1124906008-ai)

</div>
