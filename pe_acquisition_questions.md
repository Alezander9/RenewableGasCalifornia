# PE Acquisition Due Diligence Questions — California RNG Industry

Five questions a private equity firm would ask when evaluating an acquisition target in the California renewable gas space, each answerable using this knowledgebase.

---

## Question 1: What is the realistic timeline for LCFS credit price recovery, and how does the 2025 CI step-down and Auto-Acceleration Mechanism change the supply-demand balance?

### Why a PE firm would ask this
LCFS credits are a primary revenue driver for every RNG company in this market. Credit prices collapsed from ~$200/MT in 2020 to ~$70/MT by early 2024 due to a massive surplus bank. Any acquisition model needs a defensible view on where prices go from here.

### What the knowledgebase provides
- The surplus bank totaled **43.0 million MT** at the end of 2Q2025 (`carbon_credit_markets/lcfs_credit_prices.md`, `regulations/lcfs_program.md`).
- The July 2025 step-down increased the CI target from **13.75% to 22.75%**, immediately increasing deficit generation (`regulations/lcfs_program.md`).
- In **3Q2025**, the program recorded its **first quarterly net deficit since 1Q2021** at 1.71 million MT, and credit prices rose ~10% in early Feb 2026 (`regulations/lcfs_program.md`).
- **Enverus** forecasts the surplus peaks at 41.4M credits in 4Q2027, with the market becoming "bullishly undersupplied" post-2027 when the Auto-Acceleration Mechanism activates (`carbon_credit_markets/lcfs_credit_prices.md`).
- **W|Carbon** predicts prices above $100/MT through Q1 2026; **Stillwater** notes 2026 as the year quarterly surpluses start shrinking (`carbon_credit_markets/lcfs_credit_prices.md`).

### Ratings

| Criterion | Score (1-5) | Rationale |
|:---|:---:|:---|
| **Value to a PE firm** | 5 | Directly determines revenue projections in any DCF model. A $30/MT difference in LCFS price assumption can swing the value of an RNG platform by hundreds of millions. |
| **Difficulty to get without KB** | 3 | Analyst reports (Enverus, Stillwater) are individually available to subscribers, but the KB uniquely synthesizes multiple forecasts alongside the actual 3Q2025 deficit data and regulatory mechanism details into a single view. |
| **Realism of PE asking** | 5 | This is question #1 in any RNG acquisition process. Every bidder's IC memo will have an LCFS price deck. |

---

## Question 2: How does the LCFS book-and-claim grandfathering deadline (pre-2030 groundbreaking) create a valuation premium for existing RNG assets vs. greenfield development?

### Why a PE firm would ask this
The 2024 LCFS amendments create a regulatory moat for assets that break ground before January 1, 2030. A PE buyer needs to know exactly what that moat looks like, because it drives a binary distinction in the long-term value of existing vs. new assets.

### What the knowledgebase provides
- Projects breaking ground **before Jan 1, 2030** are "grandfathered" and exempt from new deliverability requirements for their full crediting life (`carbon_credit_markets/book_and_claim_accounting.md`).
- **Post-2029 projects** face: (a) a 50% physical flow-toward-California requirement, (b) phase-out of LCFS crediting for combustion fuel by 2040, and (c) phase-out of avoided methane crediting by 2040 (`carbon_credit_markets/book_and_claim_accounting.md`, `risks/regulatory_changes.md`).
- Avoided methane credits are what give dairy RNG projects deeply **negative CI scores** (e.g., -407 to -630 gCO2e/MJ for Maas Energy dairy projects — `companies/maas_energy_works.md`). Losing these credits would eliminate the most valuable component of dairy RNG economics.
- The 50% flow rule effectively limits participation to projects near California or on major westward pipeline corridors (`carbon_credit_markets/book_and_claim_accounting.md`).

### Ratings

| Criterion | Score (1-5) | Rationale |
|:---|:---:|:---|
| **Value to a PE firm** | 5 | Creates a hard deadline for asset value. An RNG platform with 20 pre-2030 dairy digesters is categorically more valuable than one still in development. This is the kind of structural regulatory advantage PE firms pay premiums for. |
| **Difficulty to get without KB** | 4 | Requires reading multiple CARB Final Regulation Order documents, Vinson & Elkins legal analyses, and CARB response-to-comments PDFs. The KB distills the interplay of grandfathering, deliverability, and avoided methane phase-out into one coherent narrative with specific dates. |
| **Realism of PE asking** | 4 | A PE firm with energy/infrastructure experience would ask this. A generalist PE might miss the nuance of the grandfathering provision and focus only on topline LCFS price. |

---

## Question 3: Can the research agent surface non-obvious gaps between what regulators mandate and what the market has actually delivered — the kind of signal that drives an investment thesis?

### What this question is really about
In any regulated market, the highest-alpha insight is often the delta between what the law *requires* and what has *actually happened*. A human analyst might read the regulation and know the target number. But finding out that the target is almost entirely unmet — that the mandated buyer has signed one contract with zero actual deliveries — requires digging through obscure compliance filings that most people don't even know exist. This is the exact type of needle-in-a-haystack extraction that a research agent should excel at.

### Demo: Q&A as a PE firm would experience it

> **PE firm asks:** "How wide is the gap between mandated utility RNG purchases under SB 1440 and actual procurement? Are these utilities actually buying, or is the mandate just on paper?"

**Knowledgebase answer:**

The gap is enormous — nearly the entire mandate is unfulfilled.

California's SB 1440 requires the state's four largest gas utilities to collectively purchase **17.6 billion cubic feet (Bcf) of biomethane per year by 2025**, ramping to **72.8 Bcf by 2030**. These are binding procurement obligations set by the California Public Utilities Commission (CPUC), allocated by utility based on their emissions footprint [1][2]:

| Utility | Share of Mandate | Short-Term Target (2025) | Medium-Term Target (2030) |
|:---|:---:|:---:|:---:|
| SoCalGas | 49.26% | ~8.7 Bcf/yr | ~35.9 Bcf/yr |
| PG&E | 42.34% | 7.452 Bcf/yr | 27.745 Bcf/yr |
| SDG&E | 6.77% | ~1.2 Bcf/yr | ~4.9 Bcf/yr |
| Southwest Gas | 1.63% | ~0.3 Bcf/yr | ~1.2 Bcf/yr |

Against these targets, actual procurement is essentially zero:

- **SoCalGas** — the single largest obligated buyer — had executed **one biomethane contract** as of the 2024 reporting period and reported **zero actual gas flows** from it [3][5]. Its first competitive solicitation (RFO) was only issued in May 2025, with contract execution targeted for December 2025 [4].
- **PG&E** — the second-largest buyer — had an RNG procurement portal that still listed future solicitations as **"Coming soon"** as of early 2026 [6][7].
- The state's Biomethane Monetary Incentive (BMI) program, designed to subsidize pipeline interconnection for RNG producers, has approved over 17 projects — but **zero projects had received incentive payments** by end of 2024 [3][8].

In short: the law says utilities must buy ~17.6 Bcf/year today, and they've delivered approximately none of it. The 2030 target (72.8 Bcf) is 4x larger. This creates a massive, legally-backed demand signal for any RNG producer that can deliver pipeline-quality gas in California — and it means the solicitation wave is just beginning, not winding down.

*Sources:*
- [1] [CPUC Sets Biomethane Targets](https://www.cpuc.ca.gov/news-and-updates/all-news/cpuc-sets-biomethane-targets-for-utilities)
- [2] [CPUC Decision D.22-02-025 (PDF)](https://docs.cpuc.ca.gov/PublishedDocs/Published/G000/M453/K954/453954308.PDF)
- [3] [Joint Biomethane Annual Combined Report (CPUC Filing)](https://docs.cpuc.ca.gov/PublishedDocs/Efile/G000/M565/K498/565498849.PDF)
- [4] [SoCalGas SB 1440 Solicitation](https://www.socalgas.com/sustainability/renewable-gas/rng-procurement/sb1440-solicitation)
- [5] [SoCalGas RNG Procurement Overview](https://www.socalgas.com/sustainability/renewable-gas/rng-procurement)
- [6] [PG&E Renewable Gas Procurement Plan (CPUC Filing)](https://docs.cpuc.ca.gov/PublishedDocs/Efile/G000/M500/K435/500435651.PDF)
- [7] [PG&E RNG Solicitation Portal](https://www.pge.com/en/about/doing-business-with-pge/core-gas-supply.html#rng)
- [8] [SoCalGas Rate-Basing Proposal / BMI Program (CPUC Filing)](https://docs.cpuc.ca.gov/PublishedDocs/Efile/G000/M585/K813/585813710.PDF)

---

### Why this matters to a VC evaluating the agent

This insight demonstrates three capabilities that define a high-value research agent:

1. **Cross-document synthesis, not just retrieval.** The mandate lives in a CPUC decision. The compliance data lives in a separate annual report filing. The interconnection payment data is in yet another filing. No single document contains the full picture. The agent stitched them together.

2. **Signal extraction from low-accessibility sources.** The "one contract, zero flows" data point comes from a Joint Biomethane Annual Combined Report filed at the CPUC — not a press release, not an analyst report, not a headline. It's the kind of primary-source regulatory filing that a junior analyst would need days to locate and parse. The agent surfaced it alongside the relevant context automatically.

3. **Contrarian framing that drives action.** The headline narrative in this industry is "California has aggressive renewable gas mandates." That's table stakes — everyone knows it. The agent's contribution is flipping that into: "The mandates exist but are almost entirely unfulfilled, creating an immediate and quantifiable market opportunity." That reframe is what turns research into an investment decision.

### Ratings (reframed for agent evaluation)

| Criterion | Score (1-5) | Rationale |
|:---|:---:|:---|
| **Value of the insight to an end user (PE/hedge fund)** | 5 | Directly quantifies an unfilled, legally-mandated demand pipeline. This is the kind of data point that goes on slide 1 of an IC deck. |
| **How hard this is to find without the agent** | 4 | The mandate is in public CPUC decisions, but the compliance gap (one contract, zero flows) is buried in a specific CPUC filing that most market participants haven't read. An analyst would need to know where to look and then manually cross-reference across documents. |
| **Does this showcase differentiated agent capability?** | 5 | Yes — it demonstrates cross-source synthesis, primary-source regulatory mining, and contrarian insight generation. This is not "summarize an article." This is "connect dots across obscure filings to surface an actionable signal." |

---

## Question 4: What is the carbon intensity (CI) score differential between dairy-sourced and landfill-sourced RNG, and how does this affect per-unit credit economics for the acquisition target?

### Why a PE firm would ask this
Not all RNG is created equal. The feedstock source determines the CI score, which determines how many LCFS credits each unit of gas generates. A PE firm comparing two targets — one with dairy digesters, one with landfill gas plants — needs to understand the order-of-magnitude difference in credit value per MMBtu.

### What the knowledgebase provides
- **Dairy RNG CI scores** from Maas Energy Works certified LCFS pathways: **-407 to -630 gCO2e/MJ** (`companies/maas_energy_works.md`). These deeply negative scores are driven by avoided methane crediting from dairy manure.
- **Landfill RNG** projects (e.g., Montauk's Bowerman facility) generate RECs and LCFS credits, but Montauk itself notes that LCFS credits from dairy/livestock projects are expected to be a **"significant future revenue driver"** due to more attractive CI scores vs. landfill projects (`companies/montauk_renewables.md`).
- Clean Energy Fuels' dairy-sourced "Redeem" fuel can achieve **negative carbon intensity**, while its broader portfolio achieves up to 90% CI reduction (`companies/clean_energy_fuels.md`).
- The **avoided methane crediting phase-out** (post-2029 projects, by 2040) would eliminate the most valuable CI component for new dairy projects (`carbon_credit_markets/book_and_claim_accounting.md`).

### Ratings

| Criterion | Score (1-5) | Rationale |
|:---|:---:|:---|
| **Value to a PE firm** | 4 | Important for understanding relative asset quality, but it's a technical input to the broader credit revenue model rather than a standalone strategic question. Still, the difference between -50 and -600 CI scores is a ~12x multiplier in credit generation per unit of gas — impossible to ignore. |
| **Difficulty to get without KB** | 3 | Individual CI pathway scores are public on CARB's website. However, the KB compiles actual certified scores for specific companies alongside the regulatory context of why they matter and when they might change. |
| **Realism of PE asking** | 4 | A specialized energy/infrastructure PE would probe this. A generalist PE would likely rely on management projections and miss the granularity of pathway-level CI economics. |

---

## Question 5: Given that RNG already accounts for 86% of California's NGV fuel market, what demand diversification pathways exist beyond the saturating transportation segment?

### Why a PE firm would ask this
PE firms care about TAM (total addressable market) trajectory. If the primary market for the product is already 86% penetrated and faces long-term displacement by electric vehicles, the investment thesis depends entirely on whether credible alternative demand vectors exist.

### What the knowledgebase provides

**The saturation problem:**
- RNG accounts for **86% of California's on-road NGV fuel** (666M GGE out of 774M GGE in 2024) (`risks/market_saturation.md`).
- Maximum displacement of total HDV fuel demand is projected at only **8.9% by 2030** (`risks/market_saturation.md`).
- CARB's Advanced Clean Truck rule and updated LCFS increasingly prioritize ZEVs over RNG-powered NZEVs (`risks/market_saturation.md`).

**Diversification vector 1 — Utility procurement (SB 1440):**
- 72.8 Bcf/year mandated by 2030, currently near-zero actual procurement (`regulations/sb_1440_procurement.md`) — see Question 3 above.

**Diversification vector 2 — Hydrogen (ARCHES hub):**
- ARCHES awarded **$1.2 billion** in federal funding; RNG is identified as a critical bridge feedstock for clean hydrogen production via steam methane reformation (`opportunities/hydrogen_production.md`).
- Maas Energy Works has a JV with Utility Global for a dairy digester-to-hydrogen mobility project (`companies/maas_energy_works.md`).
- Kompogas SLO is expanding into green hydrogen production with Char Tech (`companies/hitachi_zosen_inova.md`).

**Diversification vector 3 — Voluntary corporate procurement:**
- AstraZeneca signed a **15-year, 650,000 MMBtu/year** contract with Vanguard Renewables (`opportunities/voluntary_carbon_markets.md`).
- UC System has a 20-year RNG contract at ~$13.73/MMBTU (`opportunities/voluntary_carbon_markets.md`).
- Corporations must match or exceed compliance market pricing to secure RNG supply (`opportunities/voluntary_carbon_markets.md`).

### Ratings

| Criterion | Score (1-5) | Rationale |
|:---|:---:|:---|
| **Value to a PE firm** | 5 | This is the bear/bull pivot for the entire thesis. If the answer is "there's nowhere else for RNG to go," it's a pass. If the answer is "there are three large, credible demand vectors opening up," it's a buy. |
| **Difficulty to get without KB** | 3 | The individual data points (86% saturation, SB 1440 targets, ARCHES, voluntary deals) are scattered across government reports, press releases, and trade publications. The KB's value is synthesizing them into a coherent demand diversification narrative with specific numbers. |
| **Realism of PE asking** | 5 | "What's the TAM and where is it going?" is the most fundamental question in any PE acquisition process. |

---

## Summary Rating Table

| # | Question | PE Value | Difficulty w/o KB | PE Realism | Total |
|:--|:---------|:--------:|:------------------:|:----------:|:-----:|
| 1 | LCFS credit price recovery timeline | 5 | 3 | 5 | 13 |
| 2 | Book-and-claim grandfathering premium | 5 | 4 | 4 | 13 |
| 3 | SB 1440 procurement gap vs. mandates | 5 | 4 | 5 | 14 |
| 4 | Dairy vs. landfill CI score economics | 4 | 3 | 4 | 11 |
| 5 | Demand diversification beyond transport | 5 | 3 | 5 | 13 |

**Highest-rated question: #3 (SB 1440 procurement gap)** — It scores highest because it combines maximum PE value (guaranteed regulatory buyer), high difficulty without the KB (actual compliance data is buried in CPUC filings), and maximum realism (PE always asks about contracted revenue). The KB's unique contribution here is the stark juxtaposition of 17.6 Bcf mandated procurement against one contract and zero gas flows — a finding that would take significant regulatory research to uncover independently.
