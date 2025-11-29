# ASC 320: Investments—Debt Securities

> The comprehensive standard for accounting for investments in debt securities.

## Overview

ASC 320 provides guidance on accounting for investments in debt securities. Debt securities must be classified into one of three categories based on management's intent and ability, with each category having different measurement and income recognition requirements.

**Core Principle:**
> "Investments in debt securities shall be classified as held-to-maturity, trading, or available-for-sale, and measured accordingly."

---

## Scope

### Applies To:
- Investments in debt securities
- Treasury securities
- Corporate bonds
- Municipal bonds
- Mortgage-backed securities
- Asset-backed securities
- Redeemable preferred stock

### Does NOT Apply To:
- Equity securities (ASC 321)
- Equity method investments (ASC 323)
- Derivative instruments (ASC 815)
- Loans and receivables originated by the entity (ASC 310)
- Investments in consolidated subsidiaries

---

## Classification Categories

### Overview

| Category | Measurement | Unrealized Gains/Losses | Intent |
|----------|-------------|-------------------------|--------|
| **Held-to-Maturity (HTM)** | Amortized cost | Not recognized | Positive intent and ability to hold |
| **Trading** | Fair value | Income statement | Active trading |
| **Available-for-Sale (AFS)** | Fair value | OCI | Neither HTM nor trading |

---

## Held-to-Maturity (HTM)

### Classification Criteria

Must have **both**:
1. **Positive intent** to hold to maturity
2. **Ability** to hold to maturity

### Measurement

**Initial:** Fair value plus transaction costs
**Subsequent:** Amortized cost (using effective interest method)

### Income Recognition

- Interest income using effective interest method
- Amortization of premium/discount to interest income

### Tainting the Portfolio

**Selling HTM securities (before maturity) may "taint" the portfolio:**

If sale is not due to one of the permitted reasons, entity may be precluded from using HTM classification for a period.

### Permitted Sales

| Permitted Reason |
|------------------|
| Significant credit deterioration |
| Tax law change eliminating tax-exempt status |
| Major business combination or disposition |
| Regulatory change significantly increasing capital requirements |
| Significant increase in risk weights for regulatory capital |
| Within 3 months of maturity (sales price ≈ amortized cost) |

### Journal Entry—HTM Purchase

```
Dr. Investment in HTM Securities    $XXX
    Cr. Cash                                $XXX
```

### Journal Entry—Interest Income (Premium)

```
Dr. Cash                            $XXX  (stated interest)
    Cr. Investment in HTM Securities        $XXX  (premium amortization)
    Cr. Interest Income                     $XXX  (effective interest)
```

---

## Trading Securities

### Classification Criteria

Securities bought and held **principally for selling in the near term**.

### Characteristics

- Frequent buying and selling
- Generating profits from short-term price changes
- Typically held by dealers or active traders

### Measurement

**Initial:** Fair value (transaction costs expensed)
**Subsequent:** Fair value

### Income Recognition

- Interest income
- Unrealized gains/losses → **Income statement**
- Realized gains/losses → Income statement

### Journal Entry—Mark to Market (Trading)

**If fair value increases:**
```
Dr. Investment in Trading Securities  $XXX
    Cr. Unrealized Gain—Trading (Income)    $XXX
```

**If fair value decreases:**
```
Dr. Unrealized Loss—Trading (Income)  $XXX
    Cr. Investment in Trading Securities    $XXX
```

---

## Available-for-Sale (AFS)

### Classification Criteria

Securities not classified as HTM or trading—the **default** category.

### Measurement

**Initial:** Fair value plus transaction costs
**Subsequent:** Fair value

### Income Recognition

- Interest income using effective interest method
- Unrealized gains/losses → **OCI** (Accumulated OCI on balance sheet)
- Realized gains/losses → Income statement (reclassified from AOCI)

### Journal Entry—Mark to Market (AFS)

**If fair value increases:**
```
Dr. Investment in AFS Securities     $XXX
    Cr. OCI—Unrealized Gain                 $XXX
```

**If fair value decreases:**
```
Dr. OCI—Unrealized Loss              $XXX
    Cr. Investment in AFS Securities        $XXX
```

### Journal Entry—Sale of AFS

```
Dr. Cash                             $XXX
Dr. or Cr. OCI—Reclassification      $XXX
    Cr. Investment in AFS Securities        $XXX
    Cr. or Dr. Realized Gain/Loss (Income)  $XXX
```

---

## Impairment—Credit Losses (ASC 326)

### Overview

ASC 326 (CECL) applies to AFS debt securities with modifications for the credit loss model.

### AFS Debt Securities Impairment

**When FV < Amortized Cost:**

**Step 1:** Determine if any decline is due to credit loss

**Step 2:** If credit loss exists:
- Recognize credit loss through allowance (limited to amount FV < amortized cost)
- Recognize in income statement

**Step 3:** Non-credit portion:
- Remains in OCI

### Credit Loss Indicators

| Indicator |
|-----------|
| Downgrade in credit rating |
| Adverse changes in issuer's financial condition |
| Failure to make scheduled payments |
| Adverse changes in economic conditions affecting issuer |

### Allowance for Credit Losses (AFS)

**Limited to:** Amount by which fair value is less than amortized cost

**Recovery:** Reverse through income (up to amounts previously recognized)

### Journal Entry—Credit Loss (AFS)

```
Dr. Credit Loss Expense              $XXX
    Cr. Allowance for Credit Losses—AFS     $XXX
```

### HTM Credit Losses

For HTM securities, apply full CECL model (ASC 326):
- Measure expected credit losses
- Record allowance for credit losses
- No fair value adjustment

---

## Transfers Between Categories

### Permitted Transfers

| From | To | Accounting |
|------|-----|------------|
| **Trading → AFS** | Rare—requires change in intent | FV at transfer; unrealized G/L stays in income |
| **Trading → HTM** | Rare | FV becomes new cost basis |
| **AFS → Trading** | Rare | FV at transfer; unrealized G/L from AOCI → income |
| **AFS → HTM** | Intent/ability changes | FV becomes new cost basis; OCI amortized over remaining life |
| **HTM → AFS** | May taint | FV at transfer; unrealized G/L → OCI |
| **HTM → Trading** | May taint | FV at transfer; unrealized G/L → income |

### Journal Entry—AFS to HTM Transfer

**Facts:** AFS security with amortized cost $100,000, FV $105,000, unrealized gain in AOCI $5,000

```
Dr. Investment in HTM Securities    $105,000
    Cr. Investment in AFS Securities        $105,000
```

The $5,000 in AOCI is amortized as yield adjustment over remaining life.

---

## Practical Examples

### Example 1: HTM Bond Investment

**Facts:**
- Purchase $100,000 face value bond for $95,000
- Stated rate: 5%
- Effective rate: 6%
- Term: 5 years
- Fair value at year-end: $97,000

**Initial Entry:**
```
Dr. Investment in HTM Securities    $95,000
    Cr. Cash                                $95,000
```

**Year 1 Interest:**
```
Interest income: $95,000 × 6% = $5,700
Cash received: $100,000 × 5% = $5,000
Discount amortization: $700

Dr. Cash                            $5,000
Dr. Investment in HTM Securities      $700
    Cr. Interest Income                     $5,700
```

**Year-End:**
- No adjustment to fair value (HTM carried at amortized cost)
- Carrying amount: $95,700

---

### Example 2: AFS Bond with Fair Value Change

**Facts:**
- Purchase $50,000 bond at par (fair value)
- Year-end fair value: $48,000
- Decline is temporary (no credit loss)

**Initial Entry:**
```
Dr. Investment in AFS Securities    $50,000
    Cr. Cash                                $50,000
```

**Year-End—Mark to Market:**
```
Dr. OCI—Unrealized Loss             $2,000
    Cr. Investment in AFS Securities        $2,000
```

**Balance Sheet:**
- Investment in AFS: $48,000
- AOCI: $(2,000)

---

### Example 3: AFS with Credit Loss

**Facts:**
- AFS bond with amortized cost: $100,000
- Fair value at year-end: $85,000 (decline of $15,000)
- Credit loss determined to be: $8,000
- Non-credit loss: $7,000

**Journal Entries:**

*Record credit loss:*
```
Dr. Credit Loss Expense             $8,000
    Cr. Allowance for Credit Losses—AFS     $8,000
```

*Record non-credit portion in OCI:*
```
Dr. OCI—Unrealized Loss             $7,000
    Cr. Investment in AFS Securities        $7,000
```

**Presentation:**
- Investment in AFS (gross): $100,000
- Allowance: $(8,000)
- Fair value adjustment (OCI): $(7,000)
- Net carrying amount: $85,000

---

### Example 4: Sale of AFS Security

**Facts:**
- Original cost: $40,000
- Accumulated unrealized loss in AOCI: $(3,000)
- Sale price: $37,000

**Journal Entry:**
```
Dr. Cash                            $37,000
Dr. Realized Loss (Income)           $3,000
    Cr. Investment in AFS Securities        $37,000
    Cr. OCI—Reclassification                $3,000
```

Or combined:
```
Dr. Cash                            $37,000
Dr. AOCI—Reclassification           $3,000
    Cr. Investment in AFS Securities        $40,000
```

---

## Fair Value Measurement

### Hierarchy (ASC 820)

| Level | Inputs | Examples |
|-------|--------|----------|
| **Level 1** | Quoted prices in active markets | Treasury securities |
| **Level 2** | Observable inputs | Corporate bonds with dealer quotes |
| **Level 3** | Unobservable inputs | Illiquid securities, model-based |

### Fair Value Option

Entities may elect fair value option (ASC 825) for debt securities:
- Irrevocable election at acquisition
- Changes in fair value → Income statement
- Similar to trading classification

---

## Disclosure Requirements

### Required Disclosures

| Category | Disclosure |
|----------|------------|
| **All categories** | Amortized cost, fair value, unrealized G/L by major type |
| **HTM** | Contractual maturities |
| **AFS** | Gross unrealized gains and losses by major type |
| **Sales** | Proceeds, gross realized gains/losses |
| **Credit losses** | Methodology, allowance roll-forward |
| **Transfers** | Reasons for transfers, amounts |

### Maturity Disclosure

Present by contractual maturity:
- Within 1 year
- After 1 year through 5 years
- After 5 years through 10 years
- After 10 years

---

## Common Implementation Issues

### 1. Classification Judgment
- Not documenting intent and ability
- Frequent sales tainting HTM
- Misclassifying trading securities

### 2. Impairment Analysis
- Not identifying credit losses
- Improper allocation between credit and non-credit
- Missing qualitative factors

### 3. Fair Value Measurement
- Using stale prices
- Improper Level 3 measurements
- Not updating for market changes

### 4. Interest Income
- Wrong effective rate calculation
- Not amortizing premium/discount correctly
- Missing accrued interest

### 5. Transfers
- Not documenting justification
- Improper accounting treatment
- Missing disclosures

---

## Private Company Considerations

### Practical Expedients

Private companies may:
- Use simplified impairment model in some cases
- Have smaller portfolios requiring less complexity
- Apply same standards but with cost-benefit considerations

### Common Issues

- Limited internal resources for fair value measurements
- Less sophisticated tracking systems
- Need for external valuation assistance

---

## External Resources

- [FASB ASC 320](https://asc.fasb.org/)
- [KPMG: Handbook—Debt and Equity Securities](https://frv.kpmg.us/)
- [PwC: Financial Instruments Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Accounting for Debt Securities](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Debt Securities](https://www.ey.com/)

---

## Navigation

← [Back to Assets (300s)](README.md) | [Back to Main Guide](../../README.md)
