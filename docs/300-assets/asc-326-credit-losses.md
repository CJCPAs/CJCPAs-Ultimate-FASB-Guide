# ASC 326: Credit Losses (CECL)

> The Current Expected Credit Loss model for measuring expected credit losses on financial assets.

## Overview

ASC 326 introduced the Current Expected Credit Loss (CECL) model, fundamentally changing how entities measure credit losses. Unlike the previous "incurred loss" model (which required a probable loss before recognition), CECL requires immediate recognition of lifetime expected credit losses.

**Core Principle:**
Financial assets measured at amortized cost should be presented at the net amount expected to be collected, reflecting management's current estimate of expected credit losses.

---

## Scope

### Applies To:
- Financial assets measured at amortized cost (loans, trade receivables, held-to-maturity debt securities)
- Net investments in leases (lessor)
- Off-balance-sheet credit exposures (loan commitments, standby letters of credit, financial guarantees)
- Reinsurance receivables
- Receivables from repurchase agreements and securities lending

### Does NOT Apply To:
- Available-for-sale debt securities (separate model under ASC 326-30)
- Loans measured at fair value through earnings
- Receivables between entities under common control
- Policy loan receivables of insurance entities

---

## Effective Dates

| Entity Type | Effective Date |
|-------------|----------------|
| SEC filers (excluding SRCs) | Fiscal years beginning after 12/15/2019 |
| Public business entities (SRCs, other) | Fiscal years beginning after 12/15/2020 |
| Private companies, nonprofits, and other | Fiscal years beginning after 12/15/2022 |

**SRC** = Smaller Reporting Company

---

## Key Concepts

### Incurred Loss vs. CECL

| Aspect | Incurred Loss (Old) | CECL (New) |
|--------|--------------------:|:-----------|
| Recognition threshold | Loss must be probable | Day 1 recognition |
| Losses considered | Incurred as of reporting date | Lifetime expected losses |
| Forward-looking info | Generally not considered | Must consider reasonable forecasts |
| Allowance timing | Delayed | Earlier, more proactive |

### Expected Credit Loss Components

The allowance for credit losses reflects management's estimate of:

1. **Historical loss experience** — Actual losses on similar assets
2. **Current conditions** — Factors as of the reporting date
3. **Reasonable and supportable forecasts** — Future economic conditions

---

## Measurement

### General Principles

| Principle | Description |
|-----------|-------------|
| **Collective basis** | Measure on pool basis when assets share similar risk characteristics |
| **Individual basis** | Measure individually when assets don't share risk characteristics with pool |
| **Relevant information** | Consider historical loss experience, current conditions, and forecasts |
| **Reversion** | Revert to historical loss information beyond the reasonable and supportable forecast period |

### Methods for Estimating Expected Credit Losses

| Method | Description | Common Use |
|--------|-------------|------------|
| **Discounted cash flow (DCF)** | PV of expected cash flows vs. amortized cost | Large loans, troubled debt |
| **Loss-rate method** | Historical loss rates adjusted for current/forecast conditions | Trade receivables, homogeneous loans |
| **Roll-rate method** | Movement between delinquency buckets | Credit cards, consumer loans |
| **Probability of default/loss given default** | PD × LGD × EAD | Large loan portfolios |
| **Vintage analysis** | Losses by origination period | Homogeneous loan pools |

### Reasonable and Supportable Forecast Period

- No bright-line guidance on length
- Must be supportable based on available information
- Common practice: 1-3 years, depending on asset type and economic visibility
- **Reversion:** Beyond forecast period, revert to historical loss experience (may be immediate or gradual)

---

## Trade Receivables Practical Expedient

### Aging Schedule Method

Entities with trade receivables may use a simplified approach based on aging categories.

**Example Aging Schedule:**

| Aging Bucket | Receivable Balance | Historical Loss Rate | Adjustment Factor | Adjusted Loss Rate | Expected Loss |
|--------------|-------------------:|--------------------|-------------------|-------------------:|--------------:|
| Current | $500,000 | 0.5% | 1.1x | 0.55% | $2,750 |
| 1-30 days | $100,000 | 2.0% | 1.1x | 2.20% | $2,200 |
| 31-60 days | $50,000 | 5.0% | 1.1x | 5.50% | $2,750 |
| 61-90 days | $25,000 | 15.0% | 1.1x | 16.50% | $4,125 |
| Over 90 days | $10,000 | 50.0% | 1.1x | 55.00% | $5,500 |
| **Total** | **$685,000** | | | | **$17,325** |

**Adjustment Factor:** Reflects current conditions and reasonable forecasts (e.g., economic downturn increases losses)

---

## Pool-Based Approach

### Pooling Criteria

Group assets with similar risk characteristics:
- Risk ratings or credit scores
- Type of receivable
- Size of receivable
- Geographic location
- Industry of borrower
- Collateral type
- Vintage/origination date

### When NOT to Pool

Measure individually when:
- Asset does not share risk characteristics with any pool
- Asset has unique circumstances (e.g., individual large loan in distress)

---

## Held-to-Maturity Debt Securities

### Measurement

Apply CECL model to HTM debt securities.

**Key Considerations:**
- Consider credit rating, sector, geography
- Zero expected credit loss may be appropriate for high-quality securities (e.g., US Treasuries)
- Historical default data by rating and maturity may be useful

### Presentation

Present at amortized cost, net of allowance for credit losses.

---

## Available-for-Sale Debt Securities

### Separate Model (ASC 326-30)

| If Fair Value < Amortized Cost | Analysis |
|--------------------------------|----------|
| Credit-related | Recognize allowance (limited to difference between FV and amortized cost) |
| Non-credit-related | Recognize in OCI |

**Indicators of Credit Loss:**
- Issuer default on interest or principal
- Credit rating downgrade
- Adverse changes in borrower's financial condition

**Key Difference:** AFS impairment remains an individual security analysis, not a pool approach.

---

## Off-Balance-Sheet Credit Exposures

### Scope

- Unfunded loan commitments
- Standby letters of credit
- Financial guarantees

### Measurement

Estimate expected credit losses over the contractual period (unless entity expects earlier termination).

### Presentation

Recognize as a liability (not contra-asset).

**Journal Entry:**
```
Dr. Credit Loss Expense          $XXX
    Cr. Liability for Off-Balance-Sheet 
        Credit Exposures                 $XXX
```

---

## Purchased Credit-Deteriorated (PCD) Assets

### Definition

Financial assets that at acquisition have experienced more-than-insignificant credit deterioration since origination.

### Initial Recognition

| Component | Measurement |
|-----------|-------------|
| Purchase price | Amount paid |
| Allowance for credit losses | Expected credit losses at acquisition |
| **Amortized cost basis** | Purchase price + allowance |

**Key:** No credit loss expense recognized at acquisition for PCD assets (allowance is "grossed up").

### Subsequent Measurement

- Recognize changes in expected credit losses in earnings
- Accrete non-credit discount into interest income

---

## Collateral-Dependent Financial Assets

### Definition

Assets where repayment is expected to be provided substantially through the sale or operation of collateral.

### Measurement Options

| Method | Description |
|--------|-------------|
| **Fair value of collateral** | If expect to sell collateral |
| **Fair value of collateral less costs to sell** | If foreclosure probable |

### Practical Expedient

For collateral-dependent assets, may measure expected credit losses based on fair value of collateral less costs to sell (if applicable).

---

## Transition

### Transition Method

Modified retrospective approach (cumulative-effect adjustment to retained earnings at adoption date).

**NOT permitted:** Full retrospective restatement

### Transition Entries

**Day 1 Adjustment:**
```
Dr. Retained Earnings            $XXX
    Cr. Allowance for Credit Losses      $XXX
```

**For PCD Assets:**
```
Dr. Financial Asset (gross up)   $XXX
    Cr. Allowance for Credit Losses      $XXX
```

---

## Disclosure Requirements

### Quantitative Disclosures

1. **Roll-forward of allowance** — Beginning balance, provisions, write-offs, recoveries, ending balance
2. **Credit quality indicators** — Risk ratings, past-due status
3. **Amortized cost by vintage** — Year of origination
4. **Collateral-dependent loans** — Information about significant changes in collateral

### Qualitative Disclosures

1. **Policies and methodology** — How estimates are developed
2. **Factors** — What factors influence estimates
3. **Changes** — Significant changes in estimates or methodology
4. **Risk characteristics** — How receivables are grouped

---

## Practical Examples

### Example 1: Trade Receivables—Aging Method

**Facts:**
- Total receivables: $1,000,000
- Historical loss rates by aging bucket
- Economy showing signs of slowdown (increase loss rates by 20%)

**Calculation:**

| Bucket | Balance | Historical Rate | Adjusted Rate | Allowance |
|--------|--------:|----------------:|--------------:|----------:|
| Current | $700,000 | 1.0% | 1.2% | $8,400 |
| 31-60 | $150,000 | 3.0% | 3.6% | $5,400 |
| 61-90 | $100,000 | 8.0% | 9.6% | $9,600 |
| 91+ | $50,000 | 25.0% | 30.0% | $15,000 |
| **Total** | **$1,000,000** | | | **$38,400** |

**Journal Entry (if prior balance was $30,000):**
```
Dr. Credit Loss Expense          $8,400
    Cr. Allowance for Credit Losses      $8,400
```

---

### Example 2: Loan Portfolio—Vintage Analysis

**Facts:**
- Commercial loan portfolio
- Track cumulative loss rates by origination year

**Historical Cumulative Loss Rate by Vintage:**

| Year Originated | Year 1 | Year 2 | Year 3 | Year 4 | Year 5 | Lifetime |
|-----------------|-------:|-------:|-------:|-------:|-------:|---------:|
| 2019 | 0.2% | 0.8% | 1.5% | 2.0% | 2.3% | 2.3% |
| 2020 | 0.5% | 1.5% | 2.5% | 3.2% | — | 3.5%* |
| 2021 | 0.3% | 1.0% | 1.8% | — | — | 2.5%* |
| 2022 | 0.2% | 0.7% | — | — | — | 2.0%* |
| 2023 | 0.2% | — | — | — | — | 1.8%* |

*Projected lifetime loss rates based on historical patterns and economic forecasts

---

### Example 3: HTM Debt Securities

**Facts:**
- Portfolio of corporate bonds rated BBB
- Remaining life: 5 years
- Historical 5-year default rate for BBB: 1.5%
- Recovery rate: 40%

**Expected Credit Loss:**
Loss given default = 1 - 40% = 60%
Expected credit loss rate = 1.5% × 60% = 0.9%

For $10,000,000 portfolio:
Allowance = $10,000,000 × 0.9% = $90,000

---

## Private Company Considerations

### Practical Expedients

Private companies may find these approaches helpful:
- **Trade receivables:** Use simplified aging schedule approach
- **Reversion:** Immediate reversion to historical loss rates acceptable if forecast period is supportable
- **Collateral-dependent:** Use fair value of collateral when substantially dependent

### Common Challenges

1. **Data limitations** — May lack historical loss data
2. **Economic forecasts** — Consider publicly available forecasts
3. **Documentation** — Critical to document methodology and judgments

### Solutions

- Use industry data if entity-specific data is limited
- Consider trade association or peer group data
- Engage specialists if needed

---

## Common Implementation Issues

1. **Insufficient historical data** — Consider alternative sources, proxies
2. **Forecast period determination** — Document basis for length chosen
3. **Reversion method** — Straight-line vs. immediate; be consistent
4. **Pooling decisions** — Document risk characteristics used for pooling
5. **Collateral values** — Keep current; document appraisal methodology
6. **Disclosure completeness** — Vintage disclosures commonly missed

---

## Comparison to IFRS 9

| Aspect | ASC 326 (CECL) | IFRS 9 |
|--------|----------------|--------|
| Initial recognition | Lifetime expected losses | 12-month expected losses (Stage 1) |
| Subsequent | Lifetime expected losses | Move to lifetime if credit deteriorates (Stages 2-3) |
| AFS securities | Separate model | Part of general model |

---

## External Resources

- [FASB ASC 326](https://asc.fasb.org/)
- [FASB CECL Transition Resource Group](https://www.fasb.org/)
- [AICPA CECL Practice Aid](https://www.aicpa.org/)
- [KPMG: Handbook—Credit Impairment](https://frv.kpmg.us/)
- [PwC: Loans and Investments Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Accounting for Credit Losses](https://www.iasplus.com/en-us)
- [EY: CECL Implementation Guide](https://www.ey.com/)

---

## Navigation

← [Back to Assets (300s)](README.md) | [Back to Main Guide](../../README.md)
