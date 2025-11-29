# ASC 323: Investments—Equity Method and Joint Ventures

> The comprehensive standard for accounting for investments with significant influence.

## Overview

ASC 323 provides guidance on accounting for investments in common stock and similar interests when the investor has significant influence over the investee. The equity method recognizes that the investor has the ability to exercise influence over the operating and financial policies of the investee.

**Core Principle:**
> "Under the equity method, an investment is initially recognized at cost and adjusted thereafter for the post-acquisition change in the investor's share of the investee's net assets."

---

## Scope

### Applies To:
- Investments in common stock with significant influence
- Investments in limited partnerships and LLCs (where more than minor influence)
- Joint ventures (typically)
- Corporate joint ventures

### Does NOT Apply To:
- Investments requiring consolidation (ASC 810)
- Investments without significant influence (ASC 321)
- Investments where fair value option elected (ASC 825)

---

## Significant Influence

### Definition

The ability to participate in the financial and operating policy decisions of the investee but not control or jointly control those policies.

### Ownership Presumptions

| Ownership Level | Presumption |
|-----------------|-------------|
| **< 20%** | No significant influence (rebuttable) |
| **20% - 50%** | Significant influence exists (rebuttable) |
| **> 50%** | Control exists (consolidation required) |

### Indicators of Significant Influence

| Indicator |
|-----------|
| Board representation |
| Participation in policy-making processes |
| Material intercompany transactions |
| Interchange of managerial personnel |
| Technological dependency |
| Extent of ownership relative to other investors |

### Rebutting the Presumption

**20%+ but no significant influence:**
- Investee opposes investor's influence
- Investor signs agreement limiting rights
- Majority ownership concentrated elsewhere
- Investor unable to obtain adequate information
- Investor fails to obtain board representation

**< 20% but significant influence:**
- Board representation achieved
- Other indicators strongly present
- No other large investor blocks influence

---

## Initial Measurement

### Cost Basis

**Investment = Cash paid + Fair value of other consideration**

### Components of Initial Cost

| Component | Treatment |
|-----------|-----------|
| Cash paid | Include |
| Fair value of stock issued | Include |
| Direct acquisition costs | Generally expense (ASC 805 guidance) |
| Contingent consideration | Include at fair value |

### Journal Entry—Initial Investment

```
Dr. Investment in Equity Method Investee  $XXX
    Cr. Cash                                      $XXX
```

---

## Subsequent Measurement

### Equity Method Adjustments

| Event | Adjustment |
|-------|------------|
| Investee net income | Increase investment, recognize income |
| Investee net loss | Decrease investment, recognize loss |
| Dividends received | Decrease investment (not income) |
| Amortization of basis difference | Adjust income |
| Impairment | Decrease investment, recognize loss |
| Other comprehensive income | Adjust AOCI |

### Basic Formula

```
Ending Investment = Beginning Investment
                  + Share of Net Income
                  − Dividends Received
                  ± Amortization of Basis Difference
                  ± Other Adjustments
```

### Journal Entries

**Share of Investee Income:**
```
Dr. Investment in Equity Method Investee  $XXX
    Cr. Equity in Earnings of Investee          $XXX
```

**Share of Investee Loss:**
```
Dr. Equity in Loss of Investee           $XXX
    Cr. Investment in Equity Method Investee    $XXX
```

**Dividends Received:**
```
Dr. Cash                                 $XXX
    Cr. Investment in Equity Method Investee    $XXX
```

---

## Basis Difference

### Definition

Difference between:
- Cost of investment
- Investor's share of book value of investee's net assets

### Components

| Component | Treatment |
|-----------|-----------|
| **Fair value > Book value of assets** | Amortize to income over asset lives |
| **Goodwill** | Not amortized; test for impairment |
| **Bargain purchase** | Recognize gain (rare) |

### Example: Basis Difference Allocation

**Facts:**
- Purchase 30% of investee for $1,000,000
- Investee book value of net assets: $2,500,000
- Investor's share of book value: $750,000 (30% × $2,500,000)
- Basis difference: $250,000

**Allocation:**

| Item | Book Value | Fair Value | Difference | Investor Share (30%) | Life | Annual Amort |
|------|----------:|----------:|-----------:|--------------------:|-----:|-------------:|
| Inventory | $500,000 | $600,000 | $100,000 | $30,000 | 1 yr | $30,000 |
| Equipment | $1,000,000 | $1,200,000 | $200,000 | $60,000 | 10 yr | $6,000 |
| Land | $400,000 | $500,000 | $100,000 | $30,000 | N/A | $0 |
| Goodwill | — | — | — | $130,000 | N/A | $0 |
| **Total** | | | | **$250,000** | | **$36,000** |

### Journal Entry—Basis Difference Amortization

```
Dr. Equity in Earnings of Investee       $36,000
    Cr. Investment in Equity Method Investee    $36,000
```

---

## Intercompany Transactions

### Elimination Required

Eliminate unrealized profit/loss from:
- Sales of inventory (upstream and downstream)
- Sales of fixed assets
- Other intercompany transactions

### Upstream vs. Downstream

| Type | Direction | Elimination |
|------|-----------|-------------|
| **Upstream** | Investee → Investor | Reduce equity pickup by % ownership |
| **Downstream** | Investor → Investee | Reduce equity pickup by % ownership |

### Example: Upstream Inventory Sale

**Facts:**
- Investor owns 40% of investee
- Investee sells inventory to investor for $100,000
- Investee cost: $70,000
- Investor still holds inventory at year-end

**Unrealized Profit:**
```
Sale price: $100,000
Cost: $70,000
Gross profit: $30,000
Investor's share: $30,000 × 40% = $12,000
```

**Adjustment:**
```
Dr. Equity in Earnings of Investee       $12,000
    Cr. Investment in Equity Method Investee    $12,000
```

When inventory is sold to third party, reverse the adjustment.

---

## Impairment

### Impairment Indicators

| Indicator |
|-----------|
| Investee's market value significantly below carrying amount |
| Significant adverse change in investee's business |
| Severe operating losses of investee |
| Investee's going concern issues |
| Intent to sell investment |

### Impairment Measurement

**Loss = Carrying amount − Fair value**

### Key Difference from CECL

Equity method investments use an "other-than-temporary" impairment model:
- Decline must be other than temporary
- Once impaired, new cost basis (no recovery)

### Journal Entry—Impairment

```
Dr. Impairment Loss                      $XXX
    Cr. Investment in Equity Method Investee    $XXX
```

---

## Investment Below Zero

### General Rule

Do not reduce investment below zero.

### When Investee Has Losses

If share of losses exceeds investment:
1. Reduce investment to zero
2. Stop recognizing additional losses
3. **Unless:** Investor has guaranteed obligations or committed additional support

### Subsequent Recoveries

When investee becomes profitable:
1. First, recover unrecognized losses
2. Then, resume normal equity method

### Journal Entry—Loss When Investment Near Zero

**Facts:** Investment balance: $50,000; Share of loss: $80,000

```
Dr. Equity in Loss of Investee           $50,000
    Cr. Investment in Equity Method Investee    $50,000
```

Remaining $30,000 loss is not recognized (memorandum entry to track).

---

## Changes in Ownership

### Acquiring Additional Interest

**Scenarios:**

| From | To | Action |
|------|-----|--------|
| < 20% (ASC 321) | 20%+ | Apply equity method; adjust for fair value changes already in income |
| 20-50% (Equity) | > 50% | Consolidate; remeasure to fair value at control date |

### Disposing of Interest

| From | To | Action |
|------|-----|--------|
| 20%+ (Equity) | < 20% | Stop equity method; measure at fair value |
| > 50% (Consolidation) | 20-50% | Deconsolidate; apply equity method to retained interest |

### Step Acquisition to Equity Method

When moving from ASC 321 to equity method:
- Remeasure existing investment to fair value
- Recognize gain/loss
- Apply equity method prospectively

---

## Practical Examples

### Example 1: Complete Equity Method Accounting

**Facts:**
- January 1: Purchase 25% of Beta Co. for $500,000
- Beta Co. net assets book value: $1,600,000
- Fair value adjustment: Equipment understated by $200,000 (10-year life)
- Beta Co. Year 1 net income: $400,000
- Dividends received: $20,000

**Step 1: Calculate Basis Difference**
```
Cost: $500,000
Share of book value: 25% × $1,600,000 = $400,000
Basis difference: $100,000

Allocation:
Equipment: 25% × $200,000 = $50,000 (amortize over 10 years)
Goodwill: $50,000
```

**Step 2: Journal Entries**

*Initial investment:*
```
Dr. Investment in Beta Co.           $500,000
    Cr. Cash                                 $500,000
```

*Share of net income:*
```
25% × $400,000 = $100,000

Dr. Investment in Beta Co.           $100,000
    Cr. Equity in Earnings of Beta           $100,000
```

*Basis difference amortization:*
```
$50,000 ÷ 10 = $5,000

Dr. Equity in Earnings of Beta        $5,000
    Cr. Investment in Beta Co.               $5,000
```

*Dividends received:*
```
Dr. Cash                             $20,000
    Cr. Investment in Beta Co.               $20,000
```

**Ending Investment Balance:**
```
$500,000 + $100,000 − $5,000 − $20,000 = $575,000
```

**Net Equity Income:**
```
$100,000 − $5,000 = $95,000
```

---

### Example 2: Loss Exceeding Investment

**Facts:**
- Beginning investment balance: $100,000
- Share of investee loss: $150,000
- No guarantees or commitments

**Entry:**
```
Dr. Equity in Loss of Investee       $100,000
    Cr. Investment in Beta Co.               $100,000
```

**Result:**
- Investment balance: $0
- Unrecognized loss: $50,000 (track off balance sheet)

---

## Fair Value Option

### Election

Investors may elect fair value option (ASC 825) for equity method investments:
- Irrevocable at acquisition or when equity method first applies
- Measure at fair value
- Changes in fair value → Net income
- No equity method pickup

### Considerations

- Simplifies accounting
- Removes basis difference tracking
- Results in different income pattern

---

## Disclosure Requirements

### Required Disclosures

| Disclosure |
|------------|
| Name and percentage ownership of significant investees |
| Accounting policies for equity method investments |
| Difference between carrying amount and underlying equity |
| Aggregated financial information for immaterial investees |
| Fair value of publicly traded investments |
| Commitments and contingencies related to investees |

### Significant Investee Disclosures

For individually significant investees:
- Summarized financial information (assets, liabilities, revenue, net income)
- Nature and extent of transactions

---

## Common Implementation Issues

### 1. Determining Significant Influence
- Over-reliance on ownership percentage
- Not considering all indicators
- Missing changes in influence

### 2. Basis Difference
- Incomplete allocation
- Wrong amortization periods
- Missing impairment of goodwill component

### 3. Intercompany Eliminations
- Missing eliminations
- Wrong percentage used
- Not tracking inventory movement

### 4. Timing Differences
- Investee reporting lag
- Inconsistent year-ends
- Missing adjustments for material events

### 5. Investment Below Zero
- Continuing to record losses past zero
- Not tracking unrecognized losses
- Missing guarantee assessment

---

## Private Company Considerations

### Equity Method vs. Measurement Alternative

Private companies may consider:
- Administrative burden of equity method
- Availability of investee financial information
- User needs

### Practical Expedients

- May use investee financials with up to 3-month lag
- Consider cost-benefit of basis difference tracking

---

## External Resources

- [FASB ASC 323](https://asc.fasb.org/)
- [KPMG: Handbook—Equity Method of Accounting](https://frv.kpmg.us/)
- [PwC: Consolidation and Equity Method of Accounting Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Equity Method Investments](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Equity Method](https://www.ey.com/)

---

## Navigation

← [Back to Assets (300s)](README.md) | [Back to Main Guide](../../README.md)
