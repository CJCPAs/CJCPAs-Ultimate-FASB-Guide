# ASC 321: Investments—Equity Securities

> The comprehensive standard for accounting for investments in equity securities.

## Overview

ASC 321 provides guidance on accounting for investments in equity securities and other ownership interests, except those accounted for under the equity method or consolidation. The standard generally requires equity securities to be measured at fair value with changes recognized in net income.

**Core Principle:**
> "Equity securities shall be measured at fair value with changes in fair value recognized in net income, unless a practicability exception applies."

---

## Scope

### Applies To:
- Common stock
- Preferred stock (unless classified as debt)
- Stock warrants, rights, and options (unless derivatives)
- Ownership interests in partnerships, LLCs, and unincorporated JVs
- Investments in mutual funds, hedge funds, and similar entities

### Does NOT Apply To:
- Equity method investments (ASC 323)
- Investments in consolidated subsidiaries
- Derivative instruments (ASC 815)
- Federal Home Loan Bank stock (specific guidance)
- Interests in variable interest entities where investor is primary beneficiary

---

## Classification Framework

### Ownership Threshold Guidance

| Ownership Level | Presumption | Accounting |
|-----------------|-------------|------------|
| **< 20%** | No significant influence | ASC 321 (this standard) |
| **20% - 50%** | Significant influence | Equity method (ASC 323) |
| **> 50%** | Control | Consolidation (ASC 810) |

**Note:** Ownership percentage is a guide—actual influence determines accounting method.

---

## Measurement

### General Rule: Fair Value Through Net Income

**Measurement:** Fair value at each reporting date
**Changes in Fair Value:** Recognized in **net income**

### Journal Entry—Purchase

```
Dr. Investment in Equity Securities  $XXX
    Cr. Cash                                 $XXX
```

### Journal Entry—Fair Value Increase

```
Dr. Investment in Equity Securities  $XXX
    Cr. Unrealized Gain (Income)            $XXX
```

### Journal Entry—Fair Value Decrease

```
Dr. Unrealized Loss (Income)         $XXX
    Cr. Investment in Equity Securities     $XXX
```

### Dividends

```
Dr. Cash (or Dividends Receivable)   $XXX
    Cr. Dividend Income                     $XXX
```

---

## Measurement Alternative (Without Readily Determinable FV)

### Eligibility

Equity securities **without readily determinable fair value** (typically private company investments).

### Alternative Measurement

**Measure at:** Cost minus impairment, plus or minus observable price changes for identical or similar investments.

### Observable Price Changes

When observable transactions occur:
- Adjust carrying amount to observed price
- Recognize adjustment in income

### Impairment

**Qualitative assessment** each reporting period:
- Is impairment indicator present?
- If yes, estimate fair value and recognize impairment

### Impairment Indicators

| Indicator |
|-----------|
| Significant deterioration in earnings or cash flows |
| Significant adverse change in business climate |
| Bona fide offer to purchase at below carrying amount |
| Significant adverse legal or regulatory factors |
| Going concern issues |

### Journal Entry—Measurement Alternative Impairment

```
Dr. Impairment Loss (Income)         $XXX
    Cr. Investment in Equity Securities     $XXX
```

### Journal Entry—Observable Price Change

```
Dr. Investment in Equity Securities  $XXX
    Cr. Gain on Investment (Income)         $XXX
```

---

## Fair Value Measurement

### Readily Determinable Fair Value

Fair value is **readily determinable** if:

| Criterion |
|-----------|
| Sales prices or bid-and-ask quotes available on securities exchange (NYSE, NASDAQ, etc.) |
| Prices or quotes available from multiple dealers |
| Prices published by trade association |
| For mutual funds: NAV published and basis for transactions |

### Fair Value Hierarchy (ASC 820)

| Level | Inputs | Examples |
|-------|--------|----------|
| **Level 1** | Quoted prices in active markets | NYSE-listed stock |
| **Level 2** | Observable inputs | Restricted stock with discount |
| **Level 3** | Unobservable inputs | Private company stock |

---

## Practical Examples

### Example 1: Publicly Traded Stock

**Facts:**
- Purchase 1,000 shares of ABC Corp at $50/share
- Transaction costs: $500
- Year-end price: $55/share
- Dividend received: $1,000

**Initial Entry (transaction costs expensed):**
```
Dr. Investment in Equity Securities  $50,000
Dr. Investment Expense                  $500
    Cr. Cash                                $50,500
```

**Dividend:**
```
Dr. Cash                             $1,000
    Cr. Dividend Income                     $1,000
```

**Year-End Mark to Market:**
```
Fair value: 1,000 × $55 = $55,000
Carrying amount: $50,000
Gain: $5,000

Dr. Investment in Equity Securities  $5,000
    Cr. Unrealized Gain (Income)            $5,000
```

**Income Statement Impact:**
- Dividend income: $1,000
- Unrealized gain: $5,000
- Investment expense: $(500)
- Net: $5,500

---

### Example 2: Private Company Investment (Measurement Alternative)

**Facts:**
- Purchase 5% interest in private company for $100,000
- Company elects measurement alternative
- Year 2: Observable sale of similar interest at $120,000 per 5%
- Year 3: Qualitative assessment indicates impairment; fair value estimated at $90,000

**Initial Entry:**
```
Dr. Investment in Equity Securities  $100,000
    Cr. Cash                                $100,000
```

**Year 2—Observable Price Change:**
```
Dr. Investment in Equity Securities  $20,000
    Cr. Gain on Investment (Income)         $20,000
```

**Year 3—Impairment:**
```
Carrying amount: $120,000
Estimated fair value: $90,000
Impairment: $30,000

Dr. Impairment Loss (Income)         $30,000
    Cr. Investment in Equity Securities     $30,000
```

---

### Example 3: Sale of Equity Securities

**Facts:**
- Investment carrying amount: $75,000
- Previously recognized unrealized gain: $10,000
- Sale price: $80,000

**Sale Entry:**
```
Dr. Cash                             $80,000
    Cr. Investment in Equity Securities     $75,000
    Cr. Realized Gain (Income)              $5,000
```

**Note:** The total gain in income over the holding period is the same whether marked to market or sold—the timing differs.

---

## Forward Contracts and Prepaid Shares

### Forward Contracts to Acquire Shares

Generally accounted for as derivatives (ASC 815) unless:
- Physical settlement required
- Company's own stock (equity classification)

### Prepaid Forward Contracts

If prepaid (equity prepay):
- Assess if should be classified as equity security
- May require derivative accounting depending on settlement provisions

---

## Comparison: Previous GAAP vs. Current

### Key Changes from Legacy GAAP

| Aspect | Previous (pre-ASU 2016-01) | Current |
|--------|---------------------------|---------|
| Available-for-sale equity | Fair value through OCI | Fair value through income |
| Cost method equity | Cost with impairment | Fair value or measurement alternative |
| Impairment indicator | Other-than-temporary | Qualitative assessment |

---

## Disclosure Requirements

### General Disclosures

| Disclosure |
|------------|
| Carrying amount by type of security |
| Cost of securities without readily determinable FV |
| Unrealized gains/losses by type |
| Gross realized gains and losses |
| Method for determining cost (specific ID, average, etc.) |

### Measurement Alternative Disclosures

| Disclosure |
|------------|
| Carrying amount of investments using measurement alternative |
| Impairments and adjustments during period |
| Unrealized gains/losses for still-held securities |
| Qualitative information about observable price changes |

---

## Private Company Considerations

### Measurement Alternative Benefits

- Avoids cost of ongoing fair value measurements
- Practical for closely-held investments
- Simpler impairment model

### Considerations

- Must apply consistently to qualifying investments
- One-way election to fair value (cannot revert to alternative)
- Still need to monitor for observable transactions

---

## Common Implementation Issues

### 1. Fair Value vs. Measurement Alternative
- Determining if fair value is readily determinable
- Identifying observable transactions
- Applying qualitative impairment assessment

### 2. Income Statement Volatility
- All fair value changes in income
- Impact on earnings quality discussions
- Management/analyst communication

### 3. Observable Price Adjustments
- Identifying "similar" securities
- Adjusting for differences in rights/terms
- Timing of adjustment recognition

### 4. Classification Errors
- Not considering significant influence indicators
- Ownership changes affecting method
- Missing derivative features

### 5. Disclosure Completeness
- Aggregation vs. disaggregation
- Measurement alternative disclosures
- Fair value hierarchy classification

---

## Investments in Funds

### Mutual Funds

- Generally have readily determinable FV (NAV)
- Fair value through net income

### Hedge Funds / Private Equity Funds

- May not have readily determinable FV
- May use measurement alternative
- Consider NAV practical expedient (ASC 820)

### NAV Practical Expedient

For investments measured at NAV as practical expedient:
- Not categorized in fair value hierarchy
- Additional disclosures required
- Cannot use measurement alternative for same investment

---

## External Resources

- [FASB ASC 321](https://asc.fasb.org/)
- [KPMG: Handbook—Debt and Equity Securities](https://frv.kpmg.us/)
- [PwC: Financial Instruments Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Accounting for Equity Securities](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Equity Securities](https://www.ey.com/)

---

## Navigation

← [Back to Assets (300s)](README.md) | [Back to Main Guide](../../README.md)
