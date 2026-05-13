# International Landing Page — shipped (2026-05-14)

**Who:** Yash + Claude · **Repo:** `abhishekslab/salesup-homepage` branch `new-positioning`
**Status:** Built locally, all routes 200, typecheck clean. **Not yet committed / pushed.**

---

## What was shipped

Three new routes layered onto the existing salesup.club site:

- `/workflows` — Growth hub for international audience
- `/workflows/outbound` — Spoke for outbound/SDR buyers
- `/workflows/ads` — Spoke for performance/ads buyers

Existing homepage, blog, case studies, /about, etc. untouched.

## 16 new components (workflows.io aesthetic)

Light cream `#FAF8F5` + white sections + navy headlines `#0F172A` + blue `#1665E8` accent. Diverges from main site's dark theme — deliberate sub-brand for international segment.

| Component | Purpose |
|---|---|
| IntlHero | Rotating word hero, 4-metric strip, BookDemo CTA |
| LogoWall | 5 logos (Razorpay, Freshworks, Springworks, Payoneer, GreytHR) |
| RetentionStat | 4 trust stats (2+ yr partnership, 92% renewal, 50+ brands, $1.5K pilot) |
| WedgeBand | Dark band: "Built in India · Deployed globally" — addresses India-agency objection head-on |
| Flywheel | Hand-coded circular SVG: SalesUP center, Outbound/Ads/Calling/RevOps orbit |
| ChannelGrid | 3-channel grid linking to spokes |
| WorkflowDiagram + WorkflowFlowsSection | Inline SVG flowcharts per channel |
| OnboardingTimeline | 4-week milestone timeline with deliverables |
| SampleWork | 4 anonymized samples: email · sequence · ad · attribution dashboard |
| ProofTiles | 5 case study cards + 50+ overflow |
| IndustryCoverage | 8 verticals with client counts |
| WorkShipped | 12-program gallery (Recur Club, Skydo, ByteDance, Pluxee, OnGrid, Ceipal, Multiplier, Eshopbox, Mpokket, PerAnnum, Pagarbook, Trufan) |
| WorkflowCatalog | 17 SKUs filterable by channel |
| POVSection | 5 opinionated takes (manifesto) |
| ComparisonTable | SalesUP vs in-house / agency / SaaS tool, 8 capabilities |
| FounderStrip | Yash + Abhishek bios + LinkedIn |
| PricingLadder | 4 tiers, pilot $1.5K with 5-SQM-or-refund guarantee |
| FAQSection | 9 Q&As (refund · data · security · SOC 2 · languages · regulations) |
| CTABand | Dark closer |

## Decisions locked

- **Pilot guarantee:** 5 booked SQMs in 30 days or full $1,500 refund
- **Pricing in USD, public:** Pilot $1,500 · Core $4K/mo · Plus $8K/mo · Premium $15K/mo
- **Wedge:** "Built in India · Deployed globally" — explicit, not hidden. 0.4× US cost, 24/7 coverage
- **Aesthetic:** Light theme, workflows.io-style. Deliberate divergence from main salesup.club dark brand
- **No fal images:** Inline SVG cleaner than photorealism for workflows.io aesthetic

## Open sign-off items (need Yash review)

1. **Founder LinkedIn URLs** — currently placeholder slugs
2. **Retention stat** — "92% renewal past month 3" is defensible default; confirm real number
3. **Pilot guarantee number** — "5 SQMs" is conservative; raise to 10 if confident
4. **POV wording** — 5 takes drafted, awaiting voice approval
5. **Sample work copy** — anonymized but voiced; Yash to OK
6. **Missing logo PNGs:** Keka, Sodexo, Spinny referenced in main hero but no asset file
7. **Commit + push + PR** to `abhishekslab/salesup-homepage` master

## Files created

```
components/workflows/{CTABand,ChannelGrid,ComparisonTable,FAQSection,Flywheel,
  FounderStrip,IndustryCoverage,IntlHero,LogoWall,OnboardingTimeline,POVSection,
  PricingLadder,ProofTiles,RetentionStat,SampleWork,WedgeBand,WorkflowCatalog,
  WorkflowDiagram,WorkflowFlowsSection,WorkShipped}.tsx

app/workflows/{page,outbound/page,ads/page}.tsx
```

## Next steps (out of LP, into outreach)

1. ICP-tag the 1,354-row Debbie + Ewan list → filter ~350 intl decision-makers
2. Hatch-verify those emails
3. Generate AI-personalized opening lines per contact
4. Upload to Instantly, queue Day 1 batch (50 sends)
5. HeyReach LI campaign on same list
6. Reply triage prompt + Calendly template

## Cross-references

- Strategy → `2026-05-08-growth-partner-30day-plan.md` in this repo
- Memory entry → `active/international-lp-workflows-2026-05.md`
