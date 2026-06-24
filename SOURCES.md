# SOURCES.md — Niche: Football Analysis
> Data Verification & Fact-Checking Hierarchy · Target: 2026 FIFA World Cup

---

## ⚠️ CRITICAL RULES

> **The system must extract data EXCLUSIVELY from verified tier-sources listed below.**
> If a data point, match statistic, or squad update is missing from Level 1 or Level 2 sources, the system MUST invoke the "I Don't Know" principle.
> Speculating, hallucinating stats, or converting unverified social media rumors into analytical facts is STRICTLY PROHIBITED.

---

## 1. HIERARCHY OF SOURCES

### 🔴 LEVEL 1 — Primary Sources (Highest Priority)
Used for official match schedules, authenticated team sheets, discipline records, and advanced core performance metrics.

| # | Source | Domain / Focus | Data Categories | Update Frequency |
|---|--------|----------------|-----------------|------------------|
| 1 | **FIFA Official Platform** | fifa.com | Group standings, rosters, official bans, rule changes | Real-time / Daily |
| 2 | **Opta Analyst / FBref** | optasports.com / fbref.com | Expected Goals (xG), Expected Assists (xA), PPDA, progressive carries | Post-match / Live |
| 3 | **World Football Elo Ratings** | eloratings.net | Dynamic historical performance ratings, probability baselines | Post-match |
| 4 | **StatsBomb** | statsbomb.com | Advanced pressure maps, shot vectors, specific positional data | Bi-weekly articles |

### 🟠 LEVEL 2 — Reputable Sports Media & Analytical Journalism
Used for contextualizing squad harmony, training ground observations, physical conditions, and tactical adjustments.

| # | Source | Focus | Data Categories | Verification Rule |
|---|--------|-------|-----------------|-------------------|
| 1 | **The Athletic** | Deep-dive profiles, tactical breakdowns | Inside-squad updates, manager tactical philosophies | Cross-check author credentials |
| 2 | **Kicker / Marca / Sky Sports** | Regional team news | Injury reports, projected line-ups, press conference text | Must match across 2 distinct outlets |
| 3 | **ESPN / BBC Sport** | Broad match coverage and tournament reporting | Match results, squad news, post-match interviews | Cross-reference with Level 1 for statistics |

### 🟡 LEVEL 3 — Secondary Statements
- Official player or head coach verified press conferences (with date and outlet stamp).
- Official medical bulletins posted on national football association websites.
- **Note:** Level 3 sources may support narrative context but must never be the sole source for any statistical claim.

### 🔵 LEVEL 4 — BANNED SOURCES (Do Not Use)
- Dynamic social media transfer tipsters or anonymous leak accounts (Twitter/X, Telegram channels).
- Public fan forums, discussion boards, or subjective blog comments (Reddit, fan sites).
- Commercial betting tipster platforms promoting specific wager coefficients.
- AI-generated content from other platforms used as a factual source.
- Wikipedia as a primary source for live tournament data (acceptable only for historical biography context).

---

## 2. THE "I DON'T KNOW" PRINCIPLE
If a critical component of the upcoming match-up (e.g., the precise degree of a midfielder's hamstring strain) cannot be verified via Level 1 or Level 2 data nodes, the text must not hypothesize. Instead:
1. State the limitation clearly: *"The precise availability of Player X remains unconfirmed by official medical records."*
2. Append the tracking marker: `[SOURCE REQUIRED]`.
3. Never fabricate an xG metric, player top sprint speed, or tactical setup value.
4. Never use a Level 3 source to fill a gap that requires Level 1 or Level 2 verification.

---

## 3. FACT-CHECKING WORKFLOW

```
[Gather Data Request]
       │
       ▼
[Check Hierarchy Level] ────► Level 4? ───► REJECT IMMEDIATELY
       │
       ▼
[Is it Level 3 only?] ──────► YES? ───► Flag as [SOURCE REQUIRED], do not use as stat basis
       │
       ▼
[Verify with Level 1 or 2] ──► Discrepancy? ──► Use lower-bound value or invoke "I Don't Know"
       │
       ▼
[Log into Table 3.1 in STRUCTURE.md] ──────► Grant ✅ status upon URL/source cross-reference
```

---

## 4. 2026 FIFA WORLD CUP — VERIFIED GROUP REFERENCE
*(Level 1 verified via fifa.com — use this as the canonical group reference)*

| Group | Teams |
|-------|-------|
| A | Mexico, South Africa, Korea Republic, Czechia |
| B | Canada, Switzerland, Qatar, Bosnia and Herzegovina |
| C | Brazil, Morocco, Haiti, Scotland |
| D | United States, Paraguay, Australia, Türkiye |
| E | Germany, Curaçao, Côte d'Ivoire, Ecuador |
| F | Netherlands, Japan, Sweden, Tunisia |
| G | Belgium, Egypt, Iran, New Zealand |
| H | Spain, Cape Verde, Saudi Arabia, Uruguay |
| I | France, Senegal, Norway, Iraq |
| J | Argentina, Algeria, Austria, Jordan |
| K | Portugal, Uzbekistan, DR Congo, Colombia |
| L | England, Croatia, Ghana, Panama |

**Teams NOT in this World Cup** *(do not reference in any match analysis)*:
Italy, Denmark, Serbia, Cameroon, Chile, Russia, Romania, Poland, Wales, Republic of Ireland

---
*File: SOURCES.md · Niche: Football Analytics · Version 1.1*
*Ensures factual integrity across World Cup prediction sets.*

---
**CORRECTIONS LOG (v1.0 → v1.1)**
- [FIXED] "Tier 1 / Tier 2" inconsistency in Critical Rules header → unified to "Level 1 / Level 2"
- [ADDED] Level 2 Source §3 — ESPN / BBC Sport
- [ADDED] Level 3 — clarification note that it cannot be sole source for statistical claims
- [ADDED] Level 4 — AI-generated content and Wikipedia clarifications
- [ADDED] "I Don't Know" Principle §4 — rule about Level 3 filling Level 1/2 gaps
- [ADDED] Fact-Checking Workflow — Level 3-only check step added
- [ADDED] §4 — Verified Group Reference table (all 12 groups, Level 1 confirmed)
- [ADDED] §4 — List of teams NOT in the 2026 World Cup to prevent hallucination
