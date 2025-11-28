# ASC 718: Compensation—Stock Compensation

> Accounting for share-based payment transactions with employees and nonemployees.

## Overview

ASC 718 requires entities to recognize compensation cost for all share-based payment arrangements based on the fair value of the awards at the grant date. This includes stock options, restricted stock, restricted stock units (RSUs), stock appreciation rights (SARs), employee stock purchase plans (ESPPs), and other equity-based compensation.

**Core Principle:**
The cost of employee services received in exchange for an award of equity instruments should be measured based on the grant-date fair value of the award and recognized over the requisite service period.

---

## Scope

### Applies To:
- Stock options
- Restricted stock awards
- Restricted stock units (RSUs)
- Stock appreciation rights (SARs)
- Performance shares/units
- Employee stock purchase plans (ESPPs)
- Phantom stock (if settled in equity)
- Profits interests (per ASU 2024-01)

### Does NOT Apply To:
- Transactions with stockholders in their capacity as stockholders
- Contributions to employee benefit plans subject to ASC 960-965
- Awards under deferred compensation plans covered by ASC 710

---

## Effective Dates

| Standard | Entity Type | Effective Date |
|----------|-------------|----------------|
| Original ASC 718 | Public entities | Fiscal years beginning after 6/15/2005 |
| | Nonpublic entities | Fiscal years beginning after 12/15/2005 |
| ASU 2024-01 (Profits interests) | All entities | Fiscal years beginning after 12/15/2024 |

---

## Key Concepts

### Grant Date

The date at which:
1. The employer and employee have a mutual understanding of the key terms and conditions of the award
2. The employer is contingently obligated to issue equity instruments or transfer assets

**If approval required:**
- Board approval → grant date is date of board meeting
- Shareholder approval → grant date is date of shareholder approval (if required)

### Measurement Date

| Award Type | Measurement Date |
|------------|------------------|
| Equity awards | Grant date (fixed) |
| Liability awards | Each reporting date until settlement (remeasured) |

### Service Period

The requisite service period is the period during which an employee is required to provide service in exchange for an award. It's often the vesting period, but may differ based on:
- Explicit service periods
- Derived service periods (for market conditions)
- Non-substantive vesting conditions

---

## Award Classification

### Equity vs. Liability

| Classification | Characteristics |
|----------------|-----------------|
| **Equity** | Settlement in equity instruments; generally fixed at grant date |
| **Liability** | Settlement in cash (or issuer option to settle in cash); remeasured each period |

### Key Distinctions

| Feature | Equity-Classified | Liability-Classified |
|---------|------------------|---------------------|
| Settlement | Shares issued | Cash paid |
| Fair value | Fixed at grant date | Remeasured each reporting date |
| Contra-equity | APIC | Liability |
| Total cost | Known at grant | Known at settlement |

---

## Fair Value Measurement

### Stock Options

**Valuation Models:**

| Model | Description | Considerations |
|-------|-------------|----------------|
| **Black-Scholes-Merton** | Closed-form model | Assumes European-style exercise; simpler |
| **Binomial/lattice** | Multi-step model | Allows for American-style early exercise; more complex |
| **Monte Carlo** | Simulation | For complex features (market conditions) |

**Key Inputs:**

| Input | Description | Source |
|-------|-------------|--------|
| Exercise price | Strike price | Award terms |
| Current stock price | Price at grant date | Market |
| Expected term | Expected time to exercise | Historical data, models |
| Expected volatility | Stock price volatility | Historical volatility, implied volatility |
| Risk-free rate | US Treasury rate matching expected term | Published rates |
| Expected dividends | Dividend yield | Company's dividend policy |

### Restricted Stock/RSUs

**Fair Value** = Stock price at grant date

**Adjustments:**
- Reduce for dividends not paid during vesting (if non-participating)
- Adjust for market conditions using pricing models

### Market Conditions

For awards with market conditions (e.g., stock price must reach $X):
- Include probability of achieving condition in fair value (via Monte Carlo)
- Recognize compensation cost regardless of whether condition is achieved
- Only reverse if service/performance condition not met

---

## Recognition of Compensation Cost

### Service Conditions

| Method | Description |
|--------|-------------|
| **Straight-line** | Total fair value recognized ratably over requisite service period |
| **Graded vesting** | Each tranche treated as separate award with own service period |

**Entity can choose** either method for service-condition awards with graded vesting (accounting policy election).

### Performance Conditions

| Probability | Treatment |
|-------------|-----------|
| Probable of achievement | Recognize cost |
| Not probable | Do not recognize cost |
| Reassess each period | Adjust cumulative compensation cost |

**At vest:** True-up to actual outcome

### Market Conditions

- **Always recognize** compensation cost (even if market condition not achieved)
- Fair value at grant date reflects probability of achievement
- Derived service period used if no explicit service period

---

## Modifications

### When Modification Occurs

A modification is a change to any of the terms or conditions of an award.

### Accounting Treatment

1. Calculate fair value of original award immediately before modification
2. Calculate fair value of modified award immediately after modification
3. Recognize any incremental fair value as additional compensation cost

**Types of Modifications:**

| Modification | Treatment |
|--------------|-----------|
| Increase fair value | Recognize incremental cost |
| Decrease fair value | Continue recognizing original cost (no reduction) |
| Equity to liability | Remeasure; recognize incremental value as compensation cost |
| Improbable to probable (performance) | Catch-up adjustment |

---

## Forfeitures

### Two Approaches

| Approach | Description |
|----------|-------------|
| **Estimate at grant** | Estimate expected forfeitures and adjust true-ups when actual differs |
| **Recognize when occur** | Recognize forfeitures as they occur (accounting policy election) |

**Policy Election:** Entity can elect to recognize forfeitures as they occur (simpler approach).

---

## Special Topics

### Reload Features

- Reload options are separate awards
- Recognize when new option is granted (triggering exercise)

### Employee Stock Purchase Plans (ESPPs)

**Non-compensatory if ALL met:**
1. Substantially all employees may participate
2. Plan does not have substantively optional features
3. Discount ≤ 5% of stock price (or justifiable for administrative costs)
4. Purchase price based on stock price at purchase date (with limited look-back)

**If compensatory:** Recognize fair value as compensation cost

### Awards Settled in Cash

- Classify as liability
- Remeasure fair value each reporting period
- Cumulative compensation cost equals cash paid at settlement

### Profits Interests (ASU 2024-01)

**Account for under ASC 718 if:**
1. Entity would account for a substantively similar stock option under ASC 718, AND
2. Profits interest is denominated in shares

---

## Tax Effects

### Book vs. Tax Differences

| Item | Book | Tax |
|------|------|-----|
| Stock options (ISOs) | Deduct at grant | No deduction (unless disqualifying disposition) |
| Stock options (NQSOs) | Deduct at grant | Deduct at exercise |
| RSUs | Deduct at grant | Deduct at vest |

### Excess Tax Benefits/Deficiencies

| Outcome | Treatment |
|---------|-----------|
| Tax deduction > book expense | Excess tax benefit in income tax expense |
| Tax deduction < book expense | Tax deficiency in income tax expense |

**Note:** Per ASU 2016-09, all excess tax benefits and deficiencies are recognized in income tax expense (not APIC).

### Cash Flow Presentation

Cash paid to tax authorities for employee taxes (e.g., withholding on stock vesting) classified as financing activity.

---

## Practical Examples

### Example 1: Stock Option Grant

**Facts:**
- 10,000 options granted on 1/1/Year 1
- Exercise price: $50 (equals grant-date stock price)
- Vesting: 4-year cliff
- Fair value per option (Black-Scholes): $15
- No expected forfeitures

**Total Compensation Cost:** 10,000 × $15 = $150,000

**Annual Entry (Years 1-4):**
```
Dr. Compensation Expense          $37,500
    Cr. Additional Paid-In Capital        $37,500
```

**At Exercise (Year 5, stock price $80):**
Employee pays: 10,000 × $50 = $500,000
```
Dr. Cash                         $500,000
Dr. APIC (from compensation)     $150,000
    Cr. Common Stock                     $10,000
    Cr. APIC                             $640,000
```

---

### Example 2: Restricted Stock Units (RSUs)

**Facts:**
- 1,000 RSUs granted on 1/1/Year 1
- Grant-date stock price: $30
- Vesting: 3-year graded (1/3 each year)
- No dividends during vesting
- Entity uses graded vesting attribution

**Fair Value per RSU:** $30

**Compensation Schedule:**

| Tranche | Shares | Service Period | Annual Expense |
|---------|-------:|----------------|---------------:|
| 1 | 333 | 1 year | $9,990 |
| 2 | 333 | 2 years | $4,995 |
| 3 | 334 | 3 years | $3,340 |

**Year 1 Total:** $9,990 + $4,995 + $3,340 = $18,325
**Year 2 Total:** $4,995 + $3,340 = $8,335
**Year 3 Total:** $3,340

---

### Example 3: Performance-Based Award

**Facts:**
- 5,000 shares granted on 1/1/Year 1
- Vesting: 3 years, contingent on achieving 15% revenue growth
- Grant-date fair value: $20 per share
- Year 1: Probability of achievement is 70%
- Year 2: Probability increases to 90%
- Year 3: Target is met

**Year 1:**
Cumulative cost recognized: $100,000 × 70% × 1/3 = $23,333
```
Dr. Compensation Expense          $23,333
    Cr. APIC                             $23,333
```

**Year 2:**
Cumulative cost: $100,000 × 90% × 2/3 = $60,000
Expense: $60,000 - $23,333 = $36,667
```
Dr. Compensation Expense          $36,667
    Cr. APIC                             $36,667
```

**Year 3:**
Cumulative cost: $100,000 × 100% × 3/3 = $100,000
Expense: $100,000 - $60,000 = $40,000
```
Dr. Compensation Expense          $40,000
    Cr. APIC                             $40,000
```

---

## Private Company Considerations

### Practical Expedients

| Topic | Expedient |
|-------|-----------|
| **Expected term** | May use simplified method (vesting period + contractual term) / 2 |
| **Volatility** | May use calculated value (volatility of similar public companies) |
| **Forfeitures** | May elect to recognize as occur |

### Calculated Value Method

Private companies can estimate expected term using:
- Simplified method: (Vesting period + Contractual term) ÷ 2

For volatility, use an appropriate industry sector index or peer group.

### Common Private Company Awards

1. **Phantom stock** — Often liability-classified
2. **Profits interests** — Per ASU 2024-01, evaluate if in scope
3. **Book value awards** — May be liability or equity

---

## Disclosure Requirements

### Required Disclosures

1. **Method and significant assumptions** for fair value determination
2. **Total compensation cost** recognized during period
3. **Total compensation cost** related to nonvested awards not yet recognized
4. **Weighted-average period** over which unrecognized cost will be recognized
5. **Description of awards** (types, vesting requirements, terms)
6. **Activity tables:**
   - Options: Outstanding, exercisable, granted, exercised, forfeited
   - RSUs: Nonvested shares, weighted-average grant-date fair value

### Tax-Related Disclosures

1. Total tax benefit recognized related to stock compensation
2. Cash received from exercise of options
3. Tax benefit realized from exercise/vesting

---

## Common Implementation Issues

1. **Grant date determination** — Awards with approval contingencies
2. **Fair value inputs** — Inappropriate volatility or expected term
3. **Performance conditions** — Not reassessing probability each period
4. **Modifications** — Failure to recognize incremental cost
5. **Forfeitures** — Large true-ups indicating poor estimates
6. **Classification changes** — Not recognizing incremental cost when converting equity to liability

---

## External Resources

- [FASB ASC 718](https://asc.fasb.org/)
- [FASB Stock Compensation Implementation Guidance](https://www.fasb.org/)
- [KPMG: Handbook—Share-based Payment](https://frv.kpmg.us/)
- [PwC: Stock-based Compensation Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Accounting for Share-Based Payment Awards](https://www.iasplus.com/en-us)
- [EY: Stock-based Compensation Guide](https://www.ey.com/)

---

## Navigation

← [Back to Equity (500s)](README.md) | [Back to Main Guide](../../README.md)
