# McKinsey AI Prompt & Framework Vault
## Prompts #14–#20: Advanced Enterprise-Grade Consulting Prompts

---

## PROMPT #14: Customer Segmentation & Targeting Strategy

**Use Case**: Build a McKinsey-style segmentation, prioritize target segments, and define how to win in each.

```
Develop a Customer Segmentation & Targeting Strategy for [COMPANY/PRODUCT].

CONTEXT:
- Company/Product: [NAME]
- Industry: [INDUSTRY]
- Current Revenue: $[X]
- Primary Markets: [GEOS/INDUSTRIES]
- Current Segmentation (if any): [DESCRIBE]
- Strategic Goal: [e.g., increase revenue by 30% in 24 months]

## STEP 1: DEFINE SEGMENTATION DIMENSIONS

Segment the market using a MECE set of dimensions:

1. Firmographics:
   - Company size (revenue, employees)
   - Industry/vertical
   - Geography/region

2. Economics:
   - Average deal size / ARPA
   - Willingness to pay
   - Margin profile / cost-to-serve

3. Needs/Use Cases:
   - Primary jobs-to-be-done
   - Compliance/complexity requirements
   - Integration needs

4. Behavior:
   - Digital maturity level
   - Buying process (self-serve vs. high-touch)
   - Price sensitivity vs. value sensitivity

List 4–7 distinct segments that are internally coherent and externally differentiated.

Example:
- Segment A: Mid-market tech (100–1,000 employees), high digital maturity
- Segment B: Traditional industries (manufacturing/logistics), low digital maturity
- Segment C: Large enterprise (>5,000 employees), highly regulated
- Segment D: Startups (Seed–Series B), high growth, low budget

## STEP 2: SIZE EACH SEGMENT (TAM/SAM/SOM)

For each segment, estimate:

- TAM (Total Addressable Market): All potential revenue in segment
- SAM (Serviceable Addressable Market): Portion you can serve given product, geography
- SOM (Serviceable Obtainable Market): Realistic 3-year share target

Create a table:

| Segment | # Customers | TAM ($) | SAM ($) | SOM ($) (3-year) |
|---------|------------|---------|---------|-------------------|
| A | 10,000 | $2B | $800M | $80M |
| B | 8,000 | $1.2B | $500M | $50M |
| C | 1,000 | $1.5B | $600M | $60M |
| D | 20,000 | $500M | $200M | $20M |

## STEP 3: ATTRACTIVENESS vs. FIT SCORECARD

Score each segment on:

1. Segment Attractiveness:
   - Market size & growth
   - Profitability (margin potential)
   - Competitive intensity
   - Ease of acquisition (CAC)
   - Expansion potential (LTV)

2. Company Fit:
   - Product fit (feature alignment)
   - Sales motion fit (self-serve vs. enterprise)
   - Referenceability (logos, case studies)
   - Strategic importance (alignment with long-term vision)

Use a 1–5 scale.

Example:

| Segment | Attractiveness (1–5) | Fit (1–5) | Composite Priority (Attractiveness × Fit) |
|---------|----------------------|-----------|-------------------------------------------|
| A | 4 | 5 | 20 |
| B | 3 | 3 | 9 |
| C | 5 | 3 | 15 |
| D | 2 | 4 | 8 |

Prioritize segments by composite score.

## STEP 4: IDEAL CUSTOMER PROFILE (ICP) PER PRIORITY SEGMENT

For top 1–3 segments, define a crisp ICP:

- Firmographics:
  - Industry:
  - Size:
  - Region:
- Buyer:
  - Primary decision maker (title, reporting line)
  - Influencers (IT, Finance, Ops)
- Pain Points (ranked):
  - Pain 1:
  - Pain 2:
  - Pain 3:
- Success Metrics:
  - What KPIs they care about (e.g., CAC, churn, uptime)
- Buying Triggers:
  - Events that trigger purchase (funding, regulation, churn spike)
- Objections:
  - Top 3 concerns about you / category

## STEP 5: POSITIONING & OFFER BY SEGMENT

For each priority segment, define:

1. Value Proposition:
   - One-line promise tailored to this segment.
   - Example: "For mid-market SaaS companies, [PRODUCT] reduces churn by 30% in 90 days with AI-driven health scoring."

2. Product Configuration:
   - Which features matter most?
   - Which can be deprioritized or hidden?

3. Pricing & Packaging:
   - Recommended tier (Starter/Pro/Enterprise)
   - Discount guidance
   - Contract length, payment terms

4. Channel Strategy:
   - Direct sales vs. partners vs. self-serve
   - Key partners (SIs, resellers, ISVs)

5. Proof & Content:
   - Relevant case studies
   - Benchmarks and ROI numbers
   - Industry-specific messaging

## STEP 6: GO-TO-MARKET PLAYBOOK BY SEGMENT

Design a focused GTM plan per segment:

| Segment | Primary Channel | Outreach Motions | Key Content | Quarterly Targets |
|---------|-----------------|------------------|-------------|-------------------|
| A | SDR + AE | Outbound + inbound | Case studies, ROI calculator | $5M pipeline |
| C | Enterprise | Executive ABM | Whitepapers, workshops | 10 target accounts |

Define:

- Lead sources (events, paid, content)
- SDR scripts & email sequences (segment-specific)
- Segment-level OKRs

## STEP 7: 12-MONTH EXECUTION ROADMAP

Phase implementation:

- Q1:
  - Finalize segmentation model & ICPs
  - Align sales, marketing, product
  - Build segment dashboards
- Q2:
  - Launch segment-specific campaigns for Segment A
  - Pilot for Segment C
- Q3:
  - Scale segment A campaigns
  - Expand to segment C fully
- Q4:
  - Review, adjust weighting
  - Consider new segments or sub-segmentation

## STEP 8: METRICS & FEEDBACK LOOP

Track per segment:

- Pipeline created
- Win rates
- Sales cycle length
- ARPA / LTV
- CAC payback
- NRR (net revenue retention)

Set up a quarterly review to refine segmentation and focus.
```

---

## PROMPT #15: Revenue Model & Pricing Optimization

**Use Case**: Redesign pricing and revenue model to maximize growth, profitability, and alignment with value.

```
Design a Revenue Model & Pricing Optimization strategy for [COMPANY/PRODUCT].

CONTEXT:
- Current Revenue Model: [e.g., flat subscription, per-seat, usage-based]
- ARPA / ACV: $[X]
- Gross Margin: [X]%
- Churn: [X]%
- Competitive Price Benchmarks: [SUMMARY]
- Strategic Goal: [e.g., increase NRR, move upmarket, improve margins]

## STEP 1: DIAGNOSE CURRENT REVENUE MODEL

Assess:

- How you charge:
  - Per user / per account / per volume / flat
- What you charge for:
  - Core product, modules, services, support
- Discounting patterns:
  - Average discount %, frequency
- Churn & expansion:
  - Logo churn, contraction, expansion

Build a simple revenue bridge:

| Metric | Current |
|--------|---------|
| # Customers | X |
| ARPA | $Y |
| ARR | $X×Y |
| Gross Margin | Z% |
| NRR | N% |

Identify pain points:

- Under-monetized heavy users?
- Overpriced for low-value users?
- Too complex/confusing?

## STEP 2: MAP VALUE DRIVERS

Identify what actually drives value for customers:

- Value metric candidates:
  - Seats/users
  - Data volume (GB, records)
  - Transactions / API calls
  - Outcomes (leads, savings, revenue uplift)

For each candidate, rate:

| Value Metric | Correlates with Customer Value? | Measurable? | Simple to Explain? | Scalable? |
|-------------|----------------------------------|-------------|--------------------|----------|
| # users | Medium | Yes | Yes | Yes |
| API calls | High | Yes | Medium | Yes |
| Revenue uplift | High | Hard | Low | Medium |

Choose 1 primary + optional secondary metric.

## STEP 3: DESIGN ALTERNATIVE PRICING MODELS

Consider 3–4 model options:

1. **Tiered Subscription (per seat)**:
   - Starter / Pro / Enterprise
   - Simple but may misalign with value for varying usage.

2. **Usage-Based (consumption)**:
   - Pay per API call / transaction / GB, possibly with minimums.
   - Highly aligned to usage; can be volatile.

3. **Hybrid**:
   - Base platform fee + usage overage.
   - Smooths revenue, aligns to value.

4. **Outcome-Based / Value Sharing**:
   - % of savings / uplift.
   - Hard to measure but powerful.

Outline each model:

| Model | Pros | Cons | Suitable For |
|-------|------|------|--------------|
| Tiered | Simple | Misaligned for power users | SMB |
| Usage | Aligned | Hard to forecast | API customers |

Pick 1–2 to test.

## STEP 4: BUILD TIER STRUCTURE & PACKAGING

For the chosen model (e.g., tiered + usage):

Define:

- Tier 1 (Starter):
  - Target: SMB / teams
  - Features: Core only
  - Limits: X users, Y volume
  - Price: $[X]/month

- Tier 2 (Pro):
  - Target: Mid-market
  - Features: Core + advanced analytics
  - Limits: More users, more volume
  - Price: $[Y]/month

- Tier 3 (Enterprise):
  - Target: Large accounts
  - Features: All + SSO, custom SLA, dedicated support
  - Price: Custom

Ensure:

- Clear upgrade path
- Meaningful fences between tiers
- Add-ons (e.g., extra volume, modules)

## STEP 5: FINANCIAL MODELING & SCENARIO ANALYSIS

Build a simple model comparing:

- Current model vs. new model
- For small, medium, large customers

Example for a medium customer:

| Scenario | Users | Volume | Current Price | New Price | Delta |
|----------|-------|--------|---------------|-----------|-------|
| Now | 50 | 100k events | $2k/mo | - | - |
| New Tier 2 | 50 | 100k | - | $2.5k/mo | +25% |

Do this for:

- 3–4 representative customer profiles
- Low, mid, high usage

Estimate impact on:

- ARPA
- NRR
- Gross margin

## STEP 6: DISCOUNT & COMMERCIAL POLICY

Set guardrails:

- Target discount band by segment (e.g., SMB: <10%, Enterprise: <25%)
- Floor price per segment
- Rules for:
  - Multi-year deals
  - Prepayment
  - Volume commitments

Document in a **Commercial Policy** so sales has clarity.

## STEP 7: MIGRATION STRATEGY (EXISTING CUSTOMERS)

Define how to move existing customers:

- Grandfathering decisions:
  - For how long?
  - For which cohorts?
- Upgrade incentives:
  - Extra features, discounts, extended contracts
- Risk management:
  - Identify accounts that will see large price jumps
  - Pre-empt with tailored offers

Plan communication milestones and account-by-account ops.

## STEP 8: EXPERIMENTATION PLAN

Pilot new pricing:

- Select:
  - A segment (e.g., new logos only)
  - A channel (e.g., inbound only)
- A/B test:
  - Old vs. new pricing page
  - Different value propositions
- Track:
  - Conversion rates
  - ARPA
  - Close rates
  - Sales feedback

Iterate based on empirical data.

## STEP 9: METRICS & TARGETS

Define success:

- ARPA uplift target: +[X]%
- NRR improvement: +[Y]pp
- Gross margin improvement: +[Z]pp
- Churn not increased
- Win rate not decreased materially

Review monthly for first 6 months, then quarterly.
```

---

## PROMPT #16: Enterprise Risk Assessment & Mitigation Plan

**Use Case**: Identify, quantify, and prioritize strategic, operational, financial, and compliance risks, then create a mitigation roadmap.

```
Perform a comprehensive Enterprise Risk Assessment & Mitigation Plan for [COMPANY].

CONTEXT:
- Company: [NAME]
- Industry: [INDUSTRY]
- Revenue: $[X]
- Geographies: [LIST]
- Known Major Risks: [e.g., single large customer, regulatory change, key person risk]

## STEP 1: RISK IDENTIFICATION (RISK REGISTER)

Use categories:

1. Strategic:
   - Market disruption, new entrants, technology shifts
2. Operational:
   - Process failures, outages, supplier issues
3. Financial:
   - Liquidity, FX, credit, concentration
4. Compliance/Legal:
   - Regulatory non-compliance, data privacy, litigation
5. Cyber/IT:
   - Security breaches, data loss, downtime
6. People:
   - Talent shortages, key person risk, culture

Create a risk register:

| Risk ID | Category | Description | Root Cause | Owner |
|--------|----------|-------------|-----------|-------|
| R1 | Strategic | New AI-native competitor entering market | Low barriers + high funding | CEO |
| R2 | Operational | Single data center failure causing downtime | No geo-redundancy | CTO |
| R3 | Financial | 40% revenue from top 3 customers | Concentration | CFO |

Aim for 20–40 risks, then focus on top 10–15.

## STEP 2: RISK SCORING (LIKELIHOOD × IMPACT)

For each risk, define:

- Likelihood (1–5): From rare (1) to almost certain (5)
- Impact (1–5): From negligible to existential
- Time horizon: Short (<1 year), Medium (1–3), Long (>3)

Score:

| Risk ID | Likelihood (L) | Impact (I) | Risk Score (L×I) | Horizon |
|--------|-----------------|------------|-------------------|---------|
| R1 | 3 | 5 | 15 | 1–3 yrs |
| R2 | 4 | 4 | 16 | <1 yr |
| R3 | 3 | 4 | 12 | <1 yr |

Segment into:

- Red Zone: Score ≥ 16
- Amber Zone: 9–15
- Green Zone: ≤ 8

## STEP 3: QUANTIFY RISK EXPOSURE

Where possible, quantify in financial terms:

- For R2 (data center failure):
  - Downtime cost: $X per hour
  - MTTR currently: Y hours
  - Expected frequency: once every 2 years
  - Annualized expected loss = (X × Y) / 2

- For R3 (customer concentration):
  - 40% revenue from top 3 customers
  - If 1 leaves: revenue drop of ~15–20%
  - Likelihood of churn: [estimate: e.g., 10–15% per year]
  - Annualized risk = Probability × Impact

Focus on top-5 risks by potential $ impact.

## STEP 4: MITIGATION & CONTINGENCY PLANS

For each high/medium risk:

Define:

1. Prevention / Mitigation:
   - Actions to reduce likelihood or impact.

2. Contingency:
   - What you will do if it happens.

Example (R2 – data center failure):

- Mitigation:
  - Move to multi-region cloud deployment
  - Implement automated failover
- Contingency:
  - Incident response plan
  - Customer communication templates
  - SLAs and credits

Document:

| Risk ID | Mitigation Actions | Owner | Timeline | Residual Risk Score |
|--------|---------------------|-------|----------|---------------------|
| R2 | Cloud migration, redundancy | CTO | 6 months | L=2, I=4, Score=8 |

## STEP 5: RISK APPETITE & THRESHOLDS

Define risk appetite per category:

- Strategic: Willing to take moderate risk for growth
- Operational: Low tolerance for downtime beyond X hours/year
- Financial: Max concentration per customer = Y%; leverage limit
- Compliance: Zero tolerance for intentional violations

Set thresholds:

- Revenue concentration cap
- Maximum acceptable downtime
- Minimum cash runway
- Cyber SLAs

## STEP 6: EMBED INTO GOVERNANCE

Propose governance mechanisms:

- Quarterly risk review in exec meeting
- Risk owner per major risk
- Risk committee for critical categories (e.g., cyber, AI ethics)
- KPIs and early warning indicators

Define reporting:

- Risk dashboard with traffic-light status
- Top-10 risks with trends
- New/emerging risks

## STEP 7: 12-MONTH RISK REDUCTION ROADMAP

Prioritize:

- Q1:
  - Address 2–3 red-zone operational/cyber risks
- Q2:
  - Reduce customer concentration via diversification plan
- Q3:
  - Build contingency and incident management exercises
- Q4:
  - Review and recalibrate risk register

## STEP 8: TRACKING & REVIEW

Monitor:

- Residual risk scores
- Incidents and near-misses
- Risk mitigation completion %
- Change in expected annualized loss

Conduct an annual full refresh of the risk register.
```

---

## PROMPT #17: Cost Reduction & Procurement Optimization

**Use Case**: Identify, quantify, and capture cost savings across spend categories and suppliers.

```
Develop a Cost Reduction & Procurement Optimization plan for [COMPANY].

CONTEXT:
- Annual Spend: $[TOTAL]
- Major Categories: [e.g., cloud, marketing, contractors, travel, facilities]
- Savings Target: $[X] or Y% over [TIMEFRAME]
- Constraints: [e.g., no layoffs, preserve NPS]

## STEP 1: SPEND BASELINE & VISIBILITY

Create a spend cube:

- By category (IT, Marketing, HR, etc.)
- By supplier
- By BU/region

Table:

| Category | Annual Spend | # Suppliers | Top 3 Suppliers (share) | Contracted vs. Ad-Hoc |
|----------|--------------|------------|--------------------------|------------------------|
| Cloud | $2M | 2 | AWS 80%, GCP 20% | 100% contracted |
| Marketing | $3M | 15 | Agency A 40%, B 20% | 60% contracted |

Identify:

- Fragmented categories
- Maverick spend (off-contract)
- High-growth spend lines

## STEP 2: SAVINGS LEVERS BY CATEGORY

For each category, consider:

1. Demand Management:
   - Do we need this at current volume?
2. Specification Optimization:
   - Are we over-specifying quality/features?
3. Supplier Rationalization:
   - Too many suppliers? Consolidate for discounts.
4. Rate Reduction:
   - Benchmark vs. market, negotiate.
5. Process Improvement:
   - Automate P2P, reduce errors, avoid late fees.

Example (Cloud):

- Right-size instances
- Use reserved/savings plans
- Remove idle resources
- Negotiate rate card

Estimate lever potential:

| Category | Lever | Potential Savings | Difficulty | Timeline |
|----------|-------|-------------------|-----------|----------|
| Cloud | Right-sizing | 10–20% | Medium | 3 months |
| Cloud | Negotiation | 5–10% | Low | 1–2 months |

## STEP 3: SUPPLIER STRATEGY & NEGOTIATION

For top suppliers:

- Analyze:
  - Annual spend
  - Contract terms (renewal date, SLAs)
  - Dependency/risk
- Strategy:
  - Consolidate volume into fewer suppliers
  - Use competitive bidding (RFP)
  - Offer longer-term commitments in exchange for lower rates

Build a supplier prioritization:

| Supplier | Category | Annual Spend | Strategic/Critical? | Savings Potential | Strategy |
|----------|----------|-------------|---------------------|-------------------|----------|
| AWS | Cloud | $1.6M | Critical | 15% | Right-size + reserved + negotiation |

## STEP 4: COST–VALUE FILTER (DON'T CUT BLINDLY)

Before cutting:

- Evaluate impact on:
  - Customer experience
  - Growth
  - Employee engagement
- Avoid:
  - Cutting high-ROI spend (e.g., top-performing channels)
  - Short-termism that harms long-term competitiveness

Implement a simple filter:

- Must-pass test for cuts:
  - "Will this materially damage CX/growth/brand?"
  - If yes → consider optimization, not cut.

## STEP 5: BUILD SAVINGS INITIATIVES PORTFOLIO

For each initiative:

- Description
- Owner
- Savings estimate (low/base/high)
- One-time costs (tools, consulting)
- Time to realize

Example:

| Initiative | Category | Owner | Est. Annual Savings | One-time Cost | Net Y1 | Timeline |
|-----------|----------|-------|----------------------|---------------|--------|----------|
| Cloud optimization | IT | CTO | $400k | $50k | $350k | 3–6 months |
| Agency consolidation | Marketing | CMO | $500k | $0 | $500k | 3–9 months |

Prioritize by:

- Impact
- Ease
- Risk

## STEP 6: EXECUTION ROADMAP (12 MONTHS)

Phase:

- Q1:
  - Quick wins (no-regret moves)
  - Launch cloud optimization
- Q2:
  - Supplier consolidation & RFPs
- Q3:
  - Process & policy changes (e.g., travel, approvals)
- Q4:
  - Embed new governance & controls

## STEP 7: GOVERNANCE & CONTROL

Implement:

- Spend approval thresholds
- Category managers
- Quarterly procurement reviews
- Compliance monitoring (off-contract spend)

Track:

- Savings realized vs. plan
- Category budget adherence
- Supplier performance

## STEP 8: SUSTAINABLE SAVINGS

Ensure savings are not one-off:

- Lock in via contracts
- Adjust budgets (don't allow "savings leakage")
- Embed processes & tools (e.g., P2P system, catalogs)
```

---

## PROMPT #18: Market Sizing & TAM / SAM / SOM Analysis

**Use Case**: Quantify market size and your realistic share.

```
Perform a Market Sizing (TAM/SAM/SOM) analysis for [PRODUCT/MARKET].

CONTEXT:
- Product: [DESCRIPTION]
- Geography: [REGION(S)]
- Target Customer: [SEGMENT]
- Business Model: [B2B/B2C, SaaS, transactional]

## STEP 1: DEFINE MARKET BOUNDARIES

Clarify:

- What is "in" vs. "out" of scope?
- Use:
  - Customer type
  - Use case
  - Geography
  - Price band (if relevant)

Example:
- "B2B SaaS sales intelligence tools for mid-market and enterprise in North America."

## STEP 2: TOP-DOWN TAM ESTIMATE

Using external data:

- Total # of potential customers:
  - e.g., # of companies with 100–10,000 employees in region
- Average annual spend per customer (in your category)

TAM = (# customers) × (avg spend)

Example:
- 50,000 companies × $20k/year = $1B TAM

## STEP 3: BOTTOM-UP TAM CHECK

Using your own model:

- Average price of your product (by segment)
- Number of potential users or units per customer

Example:
- Typical customer: 50 seats × $50/seat/month × 12 = $30k/year
- Potential customers: 20,000 = $600M bottom-up TAM

Compare top-down vs. bottom-up, reconcile.

## STEP 4: DEFINE SAM (SERVICEABLE)

Constrain TAM by:

- Regions you can sell to today (legal, operational reach)
- Segments you can serve with current product
- Language/regulation limits

Example:
- From $1B global TAM down to $400M SAM in North America mid-market.

## STEP 5: DEFINE SOM (OBTAINABLE, 3–5 YEARS)

Estimate realistic share:

- Consider:
  - Competitive intensity
  - Win rates
  - Sales capacity
  - Budget

Example:

- SAM = $400M
- Target market share in 5 years: 5–8%
- SOM = $20–32M ARR

Provide both base and stretch scenarios.

## STEP 6: SEGMENTED VIEW

Break TAM/SAM/SOM by:

- Segment (industry, size)
- Geography

Example:

| Segment | TAM | SAM | SOM (3-yr) |
|---------|-----|-----|------------|
| Mid-market Tech | $300M | $150M | $10–15M |
| Enterprise | $500M | $200M | $10–15M |

## STEP 7: IMPLICATIONS FOR STRATEGY

Answer:

- Is the market big enough?
- Where should we focus first?
- Which segments drive most of SOM?
- Do we need product changes to unlock more SAM?

Use this to prioritize GTM and roadmap.
```

---

## PROMPT #19: Customer Retention & Churn Analysis

**Use Case**: Diagnose churn, predict risk, and build a retention strategy.

```
Conduct a Customer Retention & Churn Analysis for [COMPANY/PRODUCT].

CONTEXT:
- Current ARR: $[X]
- Logo churn: [Y]% per year
- Net Revenue Retention (NRR): [Z]%
- Segments: [LIST]
- Known churn reasons (if any): [DESCRIBE]

## STEP 1: CHURN BASELINE & COHORTS

Compute:

- Logo churn (customer count)
- Revenue churn (ARR lost)
- Gross vs. net churn
- By:
  - Segment
  - Cohort (start month/quarter)
  - Geography

Example:

| Segment | Logo Churn | Revenue Churn |
|---------|------------|---------------|
| SMB | 15% | 20% |
| Mid-market | 8% | 10% |
| Enterprise | 4% | 5% |

## STEP 2: CHURN DRIVER ANALYSIS

Use data:

- Product usage:
  - Logins, feature usage, frequency
- Support:
  - Ticket volume, satisfaction
- Commercial:
  - Price increases, discounts, contract type
- Relationship:
  - Executive sponsor, QBRs held

Correlate:

- Which variables differ most between:
  - Retained vs. churned
  - High vs. low NRR

Example findings:

- Customers with:
  - No QBR in 2 quarters: churn 3× higher
  - <2 logins/week after month 2: 4× churn risk

## STEP 3: QUALITATIVE CHURN INSIGHTS

Run structured exit interviews:

- Why did you leave?
- What could have changed your mind?
- How do we compare to alternative?

Code themes:

- Product gaps
- UX/friction
- Support quality
- Price/value
- Internal changes at customer

## STEP 4: CUSTOMER HEALTH SCORING MODEL

Build a simple health score combining:

- Product usage (30–40% weight)
- Support sentiment/volume (20–30%)
- Relationship (QBRs, champion presence) (20–30%)
- Commercial (contract term, pricing anomalies) (10–20%)

Score 0–100:

- 80–100 = Healthy
- 60–79 = Watchlist
- <60 = At risk

Define simple rules to start (can be later modeled with ML).

## STEP 5: RETENTION PLAYBOOK

Define actions per risk band:

- Healthy:
  - Upsell opportunities
  - Referral asks
- Watchlist:
  - CS outreach
  - Targeted training
  - Product roadmap discussion
- At risk:
  - Exec outreach
  - Discount + roadmap alignment
  - Expansion freeze until usage improves

Codify playbook by segment.

## STEP 6: STRUCTURAL FIXES

From churn drivers, propose:

- Product investments (fix top 3 gaps causing churn)
- Support improvements (response times, knowledge base)
- Onboarding redesign (improve time-to-value)
- Commercial policies (avoid aggressive increases without value)

Prioritize by impact on churn.

## STEP 7: RETENTION TARGETS & IMPACT

Set goals:

- Reduce logo churn from Y% → Y–Δ%
- Improve NRR from Z% → Z+Δ%

Quantify:

- Value of 1pp churn reduction:
  - 1pp of ARR = $X
- Plan over 12–24 months:

| Metric | Current | Target (12m) | Target (24m) |
|--------|---------|--------------|--------------|
| Logo churn | 12% | 9% | 7% |
| NRR | 105% | 115% | 120% |

## STEP 8: OPERATIONALIZE

Implement:

- Health score in CRM/CS platform
- Weekly "churn standup"
- Monthly retention review
- CS capacity aligned to risk (more time on at-risk/high ARR)

Track results monthly and iterate.
```

---

## PROMPT #20: Supplier Relationship & Supply Chain Risk Assessment

**Use Case**: Assess supplier base, concentration risk, and supply chain resilience; design mitigation.

```
Perform a Supplier Relationship & Supply Chain Risk Assessment for [COMPANY].

CONTEXT:
- Industry: [INDUSTRY]
- Key Products/Services: [LIST]
- Supply Chain Footprint: [Regions, # suppliers, key tiers]
- Recent Issues: [e.g., stockouts, delays, quality]

## STEP 1: SUPPLIER MAPPING & CRITICALITY

List:

- Tier-1 suppliers (direct)
- Tier-2+ (if possible)

Table:

| Supplier | Location | Category | Annual Spend | Single-Sourced? | Criticality (1–5) |
|----------|----------|----------|--------------|------------------|-------------------|
| S1 | China | Component A | $5M | Yes | 5 |
| S2 | India | Component B | $3M | No | 4 |

Criticality based on:

- Revenue impact if disrupted
- Lead time
- Substitutability

## STEP 2: RISK ASSESSMENT PER SUPPLIER

Dimensions:

- Financial health
- Geopolitical risk
- Operational reliability (OTIF – on-time-in-full)
- Quality performance
- Capacity constraints

Score 1–5 per dimension.

Example:

| Supplier | Financial | Geo | OTIF | Quality | Overall Risk |
|----------|-----------|-----|------|---------|--------------|
| S1 | 3 | 4 | 2 | 2 | High |
| S2 | 4 | 2 | 4 | 4 | Low |

## STEP 3: CONCENTRATION & SINGLE-SOURCE RISK

Identify:

- % of spend per supplier
- % of critical components single-sourced
- Time-to-replace critical supplier

Example:

- Component A: 100% from S1 (single-source)
- No qualified alternative
- Lead time: 8 weeks
- If interrupted, production stops.

## STEP 4: SCENARIO & STRESS TESTING

Stress scenarios:

- S1 down for 3 months
- Port closure
- FX swings
- Regulatory change

Estimate impact:

- Revenue at risk
- Delay cost
- Penalties

Identify most dangerous combinations.

## STEP 5: MITIGATION OPTIONS

Options:

- Dual-sourcing critical components
- Geographic diversification
- Strategic inventory buffers
- Long-term contracts with critical suppliers
- Supplier development (help them invest/upgrade)

For each high-risk item:

| Component | Current Supplier | Risk | Mitigation | Cost | Timeline |
|-----------|------------------|------|-----------|------|----------|
| A | S1 | High | Qualify S3 in new region | $200k | 9 months |

## STEP 6: SUPPLIER COLLABORATION & SRM

Implement Supplier Relationship Management (SRM):

- Segment suppliers:
  - Strategic
  - Preferred
  - Transactional
- Governance:
  - Quarterly business reviews with strategic suppliers
  - Joint improvement plans
- KPIs:
  - OTIF, quality, cost, innovation

## STEP 7: SUPPLY CHAIN VISIBILITY & DIGITAL TOOLS

Recommend:

- End-to-end visibility tools
- Risk monitoring feeds (geo, weather, political)
- Alerts for:
  - Lead time changes
  - Quality excursions
  - Financial distress

## STEP 8: RESILIENCE KPIs

Track:

- % single-sourced critical items
- Average risk score per critical supplier
- Inventory days for critical components
- Time to recover from disruption

Set targets (e.g., "No more than 30% of any critical component from a single supplier").
```

---

**Version**: 1.0 | **Last Updated**: December 2025 | **Scope**: Prompts #14–#20 (Customer Segmentation, Pricing, Risk, Cost Reduction, Market Sizing, Retention, Supply Chain)
