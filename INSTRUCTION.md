# INSTRUCTION.md — Niche: Football Analysis & Mathematical Predictions
> Adapted System Orchestrator. Version 1.1. Target: 2026 FIFA World Cup.
> Use together with: STYLE.md · STRUCTURE.md · SOURCES.md

---

## SYSTEM OF FILES

| File | Role | When to Read |
|------|------|-------------|
| **INSTRUCTION.md** (this file) | Orchestrator: workflow, core principles, pre-publication checklists | Before starting any analytical task |
| **STYLE.md** | How to write: analytical tone, data pacing, banned football clichés | Stage 3 (Writing phase) |
| **STRUCTURE.md** | Templates + tables for teams/tactics/probabilities and verification | Stage 2 (Pre-writing tables) + Stage 4 (Verification) |
| **SOURCES.md** | Hierarchy of data sources, strict fact-checking (xG, Elo), "I don't know" principle | Stage 2 (Data gathering) + Stage 4 (Verification) |

**Mandatory reading order:** INSTRUCTION.md → SOURCES.md → STRUCTURE.md → STYLE.md

---

## AI WEAKNESSES IN FOOTBALL ANALYTICS & THE COMPENSATION

| Weakness | Compensation | Where it is fixed |
|----------|-------------|-------------------|
| Hallucinations (Invented scores/stats) | Strict "I don't know" principle + Fact verification table | SOURCES.md §2 + STRUCTURE.md §3.1 |
| Incorrect group or team assignments | Use SOURCES.md §4 canonical group table before any match reference | SOURCES.md §4 |
| Lost in Middle (Ignoring constraints) | System files optimized under 5K tokens; read files from start | STRUCTURE.md §1 |
| Mathematical calculation errors | Compute Elo & Poisson distribution tables BEFORE text generation | STRUCTURE.md §2.2 |
| Incorrect player data (Injured/Suspended) | Verify squad availability in Table 2.1 using Level 1 sources only | STRUCTURE.md §2.1 |
| Over-reliance on narrative clichés | Banned cliché scan post-writing; replace tropes with raw percentages | STRUCTURE.md §3.4 + STYLE.md §2 |
| Monotonous structure & repetition | Word frequency tracker table (limit same phrase to ≤2 times) | STRUCTURE.md §3.4 |
| Shift in register (Scientific → Fan talk) | Tone check sheet; enforce objective sports journalism standard | STRUCTURE.md §3.3 + STYLE.md §3 |
| Emotional moralizing / Cliché endings | End directly with data summary or tactical open question | STYLE.md §3 + STRUCTURE.md §3.3 |
| Unverified quotes / Rumors | Explicit attribution required; no row in Table 3.2 = no quote | STRUCTURE.md §3.2 + SOURCES.md §1 |

---

## WORKING PRINCIPLES: MATHEMATICS & PHYSICS

### 1. Mathematical Probability Principle
Never guess or predict based on gut feeling. Always use the Poisson distribution model to calculate exact scoreline probabilities. The expected goal value ($\lambda$) must be mathematically derived from historical Expected Goals (xG), defensive metrics (PPDA), and opponent-adjusted Elo strengths:
$$P(x) = \frac{\lambda^x e^{-\lambda}}{x!}$$
Where $x$ represents the specific number of goals scored by a team.

### 2. Team Strength Assessment (Elo Rating Model)
Calculate the true win/draw/loss probability differentials of any match-up using the standard football Elo rating formula before analyzing tactical advantages:
$$W_e = \frac{1}{10^{(R_B - R_A)/400} + 1}$$
Where $R_A$ and $R_B$ are the baseline rating points of Team A and Team B respectively.

### 3. Physical & Aerodynamic Analysis Principle
When breaking down player performance, long-range shooting, or crossing vectors, incorporate biomechanical and aerodynamic physics. Account for maximum sprint velocity ($v$), Drag Force ($F_d$), and the Magnus effect on spinning matchballs:
$$F_d = \frac{1}{2} \rho v^2 C_d A$$
Where $\rho$ is air density, $C_d$ is the drag coefficient of the ball, and $A$ is the cross-sectional area.

### 4. xG Calculation Baseline
When referencing Expected Goals, always state the model source (Opta, StatsBomb, or FBref). Different models produce different xG values for identical shots. The source model must be declared in Table 3.1 for every xG figure used.

---

## PRE-PUBLICATION CHECKLIST

### Mathematical & Data Tables
- [ ] Table 2.1 (Teams and Rosters) is fully populated and consistently used in text?
- [ ] Table 2.2 (Poisson and Elo outputs) is calculated BEFORE drafting?
- [ ] Table 3.3 (Style & Compliance Checklist) was cross-checked against the completed draft?
- [ ] SOURCES.md §4 group reference consulted to confirm correct group and opponent assignments?

### Style, Tone & Rhythm
- [ ] Zero clichés from STYLE.md §2 present in the text?
- [ ] Exactly ~33% of sentences begin with analytical conjunctions (But, And, Yet, For, Thus)?
- [ ] The conclusion is completely devoid of fake moral/sentimental commentary?
- [ ] The tone is uniformly professional, objective, and analytical?
- [ ] No unique phrase or technical sentence structure is repeated more than 2 times?
- [ ] All team names use official FIFA English-language spelling (see STYLE.md §4)?

### Platform Monetization & Safety
- [ ] No explicit descriptions of graphic physical injuries or medical operations (e.g., broken legs, ligament snaps)?
- [ ] No references to or links containing illegal sports betting, fixed matches, or tipster scams?
- [ ] When covering controversial refereeing, violence on the pitch, or fan riots: include appropriate disclaimer text and factual reporting?

### Information Verification
- [ ] All statistics used in Table 3.1 have been verified with a ✅?
- [ ] Every quotation or coach statement is officially logged in Table 3.2?
- [ ] No Level 4 sources (unverified social media leaks, forums, AI-generated content) were used?
- [ ] Dynamic squad info (injury updates, line-ups) verified within less than 24 hours of generation?
- [ ] No teams referenced that are not in the 2026 World Cup (see SOURCES.md §4)?

---

## TECHNICAL SPECIFICATIONS

- **Reference Timeline:** 2026 FIFA World Cup (June 11 — July 19, 2026)
- **Host Nations:** United States, Canada, Mexico
- **Tournament Format:** 48 teams · 12 Groups (A–L) · 104 matches · Round of 32 knockout entry
- **Workflow Isolation:** One chat context = One specific match breakdown task
- **Encoding & Layout:** UTF-8 encoded Markdown format exclusively
- **Token Budget:** Each individual file must be kept under 5K tokens to preserve maximum context depth.

---
*File: INSTRUCTION.md · Niche: Football Analytics · Version 1.1*
*Orchestrating: STYLE.md + STRUCTURE.md + SOURCES.md*

---
**CORRECTIONS LOG (v1.0 → v1.1)**
- [FIXED] "STRUCTURE.md §0" → "STRUCTURE.md §1" (§0 does not exist in that file)
- [FIXED] "STRUCTURE.md §2.4" → "STRUCTURE.md §3.4" (correct section number)
- [FIXED] "STRUCTURE.md §3.5" → "STRUCTURE.md §3.4" (correct section number)
- [FIXED] "STYLE.md §8" → "STYLE.md §3" (STYLE.md only has §1–§5; §8 does not exist)
- [FIXED] "Table 2.4 (Cliché audit)" → "Table 3.3 (Style & Compliance Checklist)" (correct table reference)
- [ADDED] AI Weaknesses table row — "Incorrect group or team assignments" with SOURCES.md §4 fix
- [ADDED] Working Principle §4 — xG Calculation Baseline (model declaration rule)
- [ADDED] Pre-Publication Checklist — SOURCES.md §4 group verification step
- [ADDED] Pre-Publication Checklist — FIFA name spelling check (cross-reference STYLE.md §4)
- [ADDED] Pre-Publication Checklist — "No teams not in 2026 World Cup" check
- [ADDED] Technical Specifications — Host nations, team count, and format details
- [ADDED] Mandatory reading order at top of System of Files section
