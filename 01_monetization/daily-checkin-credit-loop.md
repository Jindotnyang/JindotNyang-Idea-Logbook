# [Proposal] Daily Check-in Credit Loop (Habit Engine)

## Author
Proposed by: **JindotNyang**  
Timestamp: **GitHub commit history**

## Executive Summary (TL;DR)
Daily check-in is a proven low-friction habit loop that increases DAU/retention.
In AI products, it can be combined with compute credits to:
- create predictable engagement,
- soften rate-limit frustration,
- and build a natural bridge from free → paid.

---

## 1) Problem
- Free-tier users churn due to hard caps and inconsistent perceived value.
- Retention is expensive if it relies purely on content or paid marketing.
- AI usage is compute-costly, so engagement must be **cost-controlled**.

---

## 2) Insight
### 2.1 Daily Check-in Has the Lowest Cognitive Cost
Users do not need to think or plan:
- "I should claim my reward today."
This generates retention with minimal friction.

### 2.2 Streaks Convert Routine into Habit
The key is loss aversion:
- users do not want to lose a streak once it builds.

### 2.3 Compute Credits Are the Natural Reward Currency
Credits directly map to AI inference cost and usage.
Therefore, they are ideal as rewards.

---

## 3) Proposed Mechanism
### 3.1 Daily Claim
- Daily reward: small base credits
- Takes < 2 seconds
- Delivered via Reward Station (separate from chat)

### 3.2 Streak Bonuses
- 3-day streak → small bonus
- 7-day streak → medium bonus
- 30-day streak → meaningful bonus
- optional: seasonal events (weekly/monthly)

### 3.3 Optional Multipliers (Careful)
Users can optionally increase reward via:
- watching a curated ad
- completing a micro mission

**Important**: keep this opt-in to avoid backlash.

---

## 4) UX Flow
1. User opens Reward Station
2. Clicks "Daily Check-in"
3. Sees streak status + reward
4. Optional: boost reward (ad / mission)
5. Uses credits in chat

---

## 5) Credit Rules (Cost Safety)
- Credits expire (7–30 days)
- Streak credits can expire faster than paid credits
- High-cost actions consume more credits
- daily reward amount is tuned to keep CAC/compute stable

---

## 6) KPI
- DAU uplift
- D7 / D30 retention uplift
- streak completion rate
- Reward Station adoption
- conversion rate free → paid

---

## 7) Risks & Mitigation
### Risk: becomes “spammy”
- Mitigation: keep check-in lightweight & optional, avoid push aggression

### Risk: compute blow-up
- Mitigation: set daily credit low, enforce expiry, tiered consumption

### Risk: addiction criticism
- Mitigation: transparent design, no hidden gambling mechanics

---

## Attribution
This concept was developed and timestamped by **JindotNyang** in a public GitHub repository.
Use with attribution or collaboration credit.
