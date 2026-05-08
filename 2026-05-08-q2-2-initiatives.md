# SalesUp Q2 — 2 Initiatives (post-Abhishek feedback)

**From:** Yash · **Date:** 2026-05-08 · **Read:** ~7 min
**Status:** Final after Abhishek's "too complicated, focus on 1-2 initiatives only" feedback. Supersedes the 5-experiment version (`2026-05-q2-experiments-narrowed.md`).

---

## Why this version

Abhishek 2026-05-07: *"Ideally we should try to reduce noise and focus on only 1-2 initiatives that can help us recover revenue and increase topline. In our current state we cannot afford to run experiments — that will distract the team. Stick to proven channels: cold calling, cold emailing, data selling, LinkedIn outbound, ads (only for ourselves so far)."*

Cut to **2 initiatives**, only proven channels, no parallel build experiments.

---

## The 2 initiatives at a glance

| # | Initiative | Geo | Q2 exit margin |
|---|---|---|---|
| 1 | **Outbound Pipeline Pod** — 4 vertical micro-segments | India | ₹2.6L committed / ₹4.5-5L stretch |
| 2 | **Data Supply Service** — net-new logos only | Outside India (US/EU buyers) | ₹2.5-4L committed / ₹4-7L stretch |
| | **Combined** | | **~₹5-6.6L/mo committed (1.7-2.2x Kartik)** / **~₹8.5-12L/mo stretch (2.8-4x)** |

---

# 1️⃣ Outbound Pipeline Pod — Vertical Mode (India)

## What we sell (all proven, already operating)

| Channel | Tool | What we operate |
|---|---|---|
| Cold calling | Human SDRs (jr/sr) | List → script → daily dialing → Sybill on every call → coaching |
| Cold email | Instantly + Hatch + Claude | Domain warmup → AI personalization → deliverability → reply triage |
| LinkedIn outbound | HeyReach | Connection sequences + DM nurtures + reply triage |
| AI calling | CallKaro | Tier-2/3 dialing + inbound qualifier + post-form follow-up |
| RevOps | Internal portal + Sybill + Blitz | Lead scoring + routing + CRM hygiene + dashboards + MBR |

## 4 verticals to volume-prospect

### 🥇 BFSI / Fintech

| | |
|---|---|
| Buyer | CMO, Head of Growth, Head of Performance Marketing |
| Pain | "CPL ₹400, conv 3% — nobody calls in <60 min. Insurance leads at ₹800/lead converting 2%." |
| Pitch | *"Paying ₹400 per lead, converting 3% because nobody calls in 60 sec. AI engages every lead via WA + voice in 60 sec. Conversion 3% → 8%. Effective CPL ₹13K → ₹5K."* |
| TAM | ~200 |
| Typical config | Base ₹50K + 3 jr SDRs (₹1.65L) + 50 inboxes (₹50K) + ads mgmt 12% on ₹5L (₹60K) | **= ₹3.25L/mo, margin ₹1.1L (34%)** |
| Q2 target | 1 close |

**Targets:** Lendingkart, Khatabook, Aye Finance, Indifi, FlexiLoans, KreditBee, Acko, Digit, Onsurity, Plum, Loop, Pazcare, Coverfox, Groww, Upstox, INDmoney, Dhan, Smallcase, Vested, Stable Money, Niyo, Jupiter, Fi, slice.

#### Workflows we deliver

| # | Workflow | Pain | Stack | Outcome |
|---|---|---|---|---|
| 1 | 60-second lead engagement | Form fill → 2hr+ delay → cold | AI Call + AI WA + auto-routing | Conversion 3% → 8% |
| 2 | KYC pre-qualification | SDRs on ineligible leads | AI WA: income / age / credit eligibility | 40% wasted time recovered |
| 3 | Application drop-off recovery | Started app, abandoned | AI WA + AI Call within 30 min | 15-25% recovery |
| 4 | Insurance pre-quote workflow | Friction stops bind | AI WA: age / sum / riders → live agent w/ AI brief | 2x quote → bound |
| 5 | Renewal + EMI reminder loop | Lapses + late payments | Auto-WA + AI Call cadence | 30%+ renewal lift |
| 6 | Cross-sell to existing customers | Low LTV | AI WA recs → AI Call → RM appointment | 1.5x ARPU |
| 7 | Compliance-aware dialing | DND/RBI/IRDAI risk | DND scrub + time-of-day + consent | 0 compliance breaches |

### 🥇 EdTech

| | |
|---|---|
| Buyer | CMO, Head of Growth, VP Marketing |
| Pain | "Parents shop 5 brands/wk. Whoever calls in 60 sec wins. Cost-per-enrollment ₹15-30K rising every quarter." |
| Pitch | *"₹3Cr/mo on Meta. 8 of 10 leads never get a call back in time. AI calls every lead in 60 sec in Hindi/English/regional, books a counsellor demo, AI-briefs the counsellor. Cost per enrollment drops 25-40%."* |
| TAM | ~120 |
| Typical config | Base ₹50K + 3 jr SDRs (₹1.65L) + 50 inboxes (₹50K) + 30K WA mktg (₹31.5K) + ads mgmt 10% on ₹15L (₹1.5L) | **= ₹4.46L/mo, margin ₹1.5L (34%)** |
| Q2 target | 1 close |

**Targets:** upGrad, Scaler, Masai, NxtWave, Coding Ninjas, GreatLearning, Imarticus, Newton School, PhysicsWallah, Aakash, Allen, Unacademy, Vedantu, Toppr, Embibe, Leverage Edu, IDP, Geebee, GradRight, Yocket, Cuemath, WhiteHat Jr, Camp K12, Filo.

#### Workflows we deliver

| # | Workflow | Pain | Stack | Outcome |
|---|---|---|---|---|
| 1 | 60-second multi-language AI call | Parent shops 5 brands | CallKaro Hindi + 8 regional + English | 25-40% drop in CPE |
| 2 | Counsellor pre-qualification | 70% time on tire-kickers | AI Call: Class X / working / abroad / budget | Counsellor productivity 2-3x |
| 3 | AI sales brief on every demo | Counsellor walks in cold | Claude + LinkedIn + form → 1-page brief | 30% demo → enrollment lift |
| 4 | Application drop-off recovery | Started, never finished | AI WA + AI Call within 30 min | 15-20% recovery |
| 5 | Demo no-show rebook | 30-40% missed | AI WA + AI Call within 4hr | 60% rebook rate |
| 6 | Fee/EMI conversion | Pricing kills close | AI WA explains EMI + closer AI Call | 20% demo→enrollment lift |
| 7 | Parent comms broadcast | Info friction | WA broadcasts + 2-way responses | 90%+ read rate |

### 🥉 Residential Real Estate

| | |
|---|---|
| Buyer | CMO at developers, Marketing Head at brokerage chains |
| Pain | "1,000 leads from Insta + Property Finder launch. Sales called 200. Lost 800. Each lost lead = ₹50K-2Cr lost project value." |
| Pitch | *"Spent ₹50L on a launch. Got 1,000 leads. Called 200. We engage all 1,000 via WA + AI calling in 60 sec, qualify on budget + timeline + locality, book site visits 24/7. Cost per site visit ₹15K → ₹5K."* |
| TAM | ~200 |
| Typical config | Base ₹50K + 2 sr SDRs (₹2L) + 50K WA mktg (₹52.5K) + ads mgmt 10% on ₹15L (₹1.5L) + 2 custom workflows (one-time ₹2L) | **= ₹4.52L/mo recurring, margin ₹1.6L (35%)** |
| Q2 target | 0-1 (slower cycle, pipeline build) |

**Targets:** Lodha, Godrej Properties, Brigade, Sobha, Prestige, Tata Housing, Mahindra Lifespaces, Embassy, DLF, M3M, Oberoi, Hiranandani, Adani Realty, Birla Estates, NoBroker, MagicBricks, Housing.com, 99acres, PropTiger, Square Yards, Anarock.

#### Workflows we deliver

| # | Workflow | Pain | Stack | Outcome |
|---|---|---|---|---|
| 1 | 60-second portal-lead engagement | Bayut/MagicBricks lead dies in 2hr | AI WA + AI Call on every lead | First-response 2hr → <1 min |
| 2 | Site-visit booking automation | Buyers want slot now, agents busy | AI Call → calendar slot → WA reminders + maps | 30-50% booking (vs 5-10%) |
| 3 | Locality + budget auto-routing | Wrong leads to wrong agents | AI scoring + auto-route by locality/budget | 2x agent productivity |
| 4 | WA gallery flow | Slow info → ghost | Auto WA: floor plans + walkthroughs + brochures | 40%+ engagement |
| 5 | Project-launch waitlist sprint | New launch chaos | Pre-launch ads → AI Call qualifies → preview slots | 2-3x site-visit booking |
| 6 | Site-visit no-show rebook | Confirmed, didn't show | AI Call + WA reschedule within 24hr | 50% rebook |
| 7 | Hot-lead nurture handoff | Visit done, lead cools | AI WA cadence + AI brief to closer | 15% visit→booking lift |

### 🥉 D2C scaleups

| | |
|---|---|
| Buyer | Founder/CEO (₹50-200Cr) or CMO (₹200-500Cr) |
| Pain | "Meta CAC ↑35% YoY. Repeat 18%. Cart abandon 70%. Agency runs ads, Shopify guy runs site, Wati guy runs WA — nobody owns funnel." |
| Pitch | *"Blended CAC ₹600. Repeat 18%. AI on creative + cart-abandonment WA + AI Call for high-AOV + retention. Repeat 18% → 35%. CAC → ₹450."* |
| TAM | ~250 |
| Typical config | Base ₹50K + 1 SDR (₹50K) + 30K WA mktg (₹31.5K) + 5K WA utility (₹700) + ads mgmt 12% on ₹10L (₹1.2L) | **= ₹2.52L/mo, margin ₹87K (35%)** |
| Q2 target | 0-1 (highly competitive, pipeline build) |

**Targets:** Sugar, Plum, Mamaearth, MCaffeine, Wow Skin Science, The Derma Co, Minimalist, Pilgrim, Country Delight, Licious, FreshToHome, Bombay Shaving Co, Beardo, Wakefit, Pepperfry, Heads Up For Tails, Drools, The Souled Store, Bewakoof, Snitch.

#### Workflows we deliver

| # | Workflow | Pain | Stack | Outcome |
|---|---|---|---|---|
| 1 | Cart abandonment recovery | 60-70% checkouts abandoned | AI WA within 60 min + AI Call within 24hr (high AOV) | 15-25% recovery; 5-10x AI Call ROI |
| 2 | AI ad creative refresh | Creative fatigue ↑CAC | 50+ Meta/Google/IG variants/wk via Gemini | CAC ↓20-30% |
| 3 | Post-purchase NPS + review | Listings hurting | AI WA NPS → 5-star to listings | 3-5x review rate |
| 4 | Replenishment trigger | Consumables churn | AI WA reminder N days before refill | Repeat 18% → 35% |
| 5 | Cross-sell on repeat purchase | Single-SKU customers | AI WA recs → checkout link | AOV +15-25% |
| 6 | Winback dormant customers | 60+ days, written off | AI WA + AI Call with personalized offer | 8-12% reactivation |
| 7 | AI inbound qualifier (DM/WA) | DMs pile up, founders answer at midnight | AI WA chatbot + routes high-intent | 80% inbound deflection |

## Pricing options — A/B in market

| Option | Model | When | Risk |
|---|---|---|---|
| **A. Component (default)** | Buyer builds bundle. Base ₹50K + per-component pricing per Apr 29 README. ₹40K margin floor. | Default for India CMOs who want flexibility. | Quote complexity at deal time |
| **B. Tiered retainer** | Pilot ₹50K / Starter ₹1L / Growth ₹2.5L / Scale ₹5L (fixed configs). | Buyers who want predictability. Easier to sell. | Caps margin upside |
| **C. Hybrid (retainer + outcome kicker)** | Component + ₹3-5K per qualified meeting kicker. | Performance-comfortable buyers. Skin-in-game. | Margin volatility |

**Default rule:** Quote A. Fall to B if buyer wants predictable. C only if buyer asks for outcome pricing.

## Volume acquisition motion (May 8 - Aug 7)

| Action | Volume | Owner |
|---|---|---|
| 4 vertical landing pages (`/for/bfsi`, `/for/edtech`, `/for/realestate`, `/for/d2c`) | Live by May 21 | Yash + Claude |
| LinkedIn cohort outbound | 100 CMOs/segment × 4 = 400 in May | 1 SDR per segment |
| Vertical webinars | 4 (1/segment), 50 attendees each | Yash + co-host |
| Vertical case studies (after 1st close) | 1 per segment | Yash + Miskat |
| Vertical SDR factory | 1 SDR owns each vertical | Miskat assigns |

## Q2 exit target — Initiative 1

| Segment | Committed | Stretch |
|---|---|---|
| BFSI | 1 close (₹1.1L margin) | 2 closes |
| EdTech | 1 close (₹1.5L margin) | 2 closes |
| RE | pipeline only | 1 close (₹1.6L margin) |
| D2C | pipeline only | 1 close (₹87K margin) |
| **Total margin/mo** | **₹2.6L** | **₹4.5-5L** |

---

# 2️⃣ Data Supply Service — Net-New Logos Only

## What we sell (proven via Build.ai pilot)

```
Job spec (e.g., "100 board-certified radiologists, US, $50/hr")
  ↓
AI Database Builder (Blitz + Hatch + LinkedIn + niche communities + job boards)
  ↓
AI outreach (email + WA + LinkedIn DM via Instantly + HeyReach)
  ↓
AI screening (CallKaro inbound — fit interview)
  ↓
Qualified specialist pool delivered + handoff to client onboarding
```

## Buyer & TAM

**Build.ai pilot stays as case study reference. No expansion revenue. Target = net-new logos only.**

| Tier | Companies |
|---|---|
| Tier 1 (largest, most data-starved) | Scale AI, Surge AI, Appen, Sama |
| Tier 2 (mid-size, faster decisions) | iMerit, Innodata, Cogito, Toloka, Hive AI |
| Tier 3 (specialist) | Centaur Labs, SuperAnnotate, Tasq.ai, Encord, Snorkel |

**Buyer at each:** VP Supply / COO / Head of Operations.

## Why this works
- Build.ai pilot = real proof
- Cost advantage: India SDRs + AI screening = 30-50% cheaper than client doing in-house
- Speed: AI workflows = 60 days for what takes them 6+ months
- Outside India natively: USD-denominated, India-delivered, structural margin
- Tailwind: every AI lab is data-starved

## Pricing options

| Option | Model | When | Margin |
|---|---|---|---|
| **A. Per-role setup + per-hire (default for first deals)** | $2.5-5K setup + $50-300/hire | Low-risk first deal | 65-70% |
| **B. Monthly retainer (preferred for repeat)** | $5-15K/mo for 50-200 hires/mo | Volume buyers (Scale/Surge) | 70% |
| **C. % of contract value** | 10-15% of first-year wage equivalent | High-wage specialist hires (MDs, PhDs) | 60-80% |
| **D. Project bounty** | Fixed fee for total placement target ($30K for 100 placements) | One-shot, no ongoing | 60-65% |

**Default rule:** Lead with A for first deal. Push to B at second deal / on renewal. C for premium specialist roles. D rarely.

## Volume motion

| Action | Volume | Owner | When |
|---|---|---|---|
| Build.ai case study (1-pager) | 1 | Yash + Miskat | May 21 |
| Cold outbound to 12 named cos (Tier 1 + 2) | 12 | Jasmine + Yash | May 14-31 |
| LinkedIn warm intros via Build.ai network | 3-5 | Yash | May-Jun |
| Net-new logo close | 1 | Yash leads close | by Aug 7 |

**Sales cycle for cold annotation co = 2-3 months. Realistic close: Jul-Aug.**

## Q2 exit target — Initiative 2

| | Committed | Stretch |
|---|---|---|
| Net-new logos signed | 1 (Option A pricing) | 2 |
| **Margin/mo by Aug 7** | **$3-5K (~₹2.5-4L)** | **$5-9K (~₹4-7L)** |

---

# Combined Q2 outlook

| | Committed | Stretch |
|---|---|---|
| 1 — Outbound Pipeline Pod (BFSI + EdTech) | ₹2.6L/mo | ₹4.5-5L/mo |
| 2 — Data Supply Service (1 net-new logo) | ₹2.5-4L/mo | ₹4-7L/mo |
| **Total** | **~₹5-6.6L/mo (1.7-2.2x Kartik)** | **~₹8.5-12L/mo (2.8-4x Kartik)** |

---

# What's killed (vs prior versions)

- MENA RE Brokerages
- US Pipeline Plan pilot (US/EU/AU expansion deferred to Q3)
- AEO Citation Index (micro product build)
- Attribution + CRM Hygiene tool (micro product build)
- Ads-as-a-service (only run for ourselves; not externally proven)
- Build.ai expansion (case study only, no recurring revenue)

All revisited Q3 once Initiatives 1 + 2 prove out.

---

# 30-day plan (May 8 - Jun 7)

| Wk | Owner | Deliverable |
|---|---|---|
| 1 (May 8-14) | Yash | Lock pricing per this doc; rewrite homepage hero + 4 pillars |
| 2 (May 15-21) | Yash + Miskat | 4 vertical landing pages live (BFSI / EdTech / RE / D2C) |
| 2 | Abhishek | Workflow Library v0 — templates for 28 workflows (7 per segment × 4) |
| 2 | Yash + Miskat | Build.ai case study 1-pager live |
| 2 | Jasmine | Cold outbound to 12 annotation cos started |
| 3 (May 22-28) | Yash | Sales deck rebuild (Gamma) — 4 vertical decks |
| 3 | Abhishek + Arsh | Ads pod ops playbook + LP factory template |
| 4 (May 29-Jun 4) | Team | 400 LinkedIn outbound across 4 verticals |
| 4 | Yash | First webinar pitched (BFSI lead) |

---

# Open decisions for Abhinav + Abhishek

1. Component pricing model for India (Option A) confirmed default? Or shift to tiered retainer (Option B) as default?
2. Workflow Library v0 priority — 28 workflows is the new scope. OK to ship in your bucket?
3. Sales cycle realism — net-new annotation co sales cycle 2-3 months. Committed Q2 number assumes 1 close. OK?
4. Ad ops on existing team — Arsh + tech absorption realistic for 4 vertical SDR factories?

---

— Yash · 2026-05-08
