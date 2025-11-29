# ASC 815: Derivatives and Hedging

> The comprehensive standard for accounting for derivative instruments and hedging activities.

## Overview

ASC 815 requires all derivatives to be recognized on the balance sheet at fair value. Depending on the purpose for which the derivative is held and whether it qualifies for hedge accounting, changes in fair value are recognized either in earnings or in other comprehensive income.

**Core Principle:**
> "All derivative instruments shall be recognized as either assets or liabilities in the statement of financial position and measured at fair value."

---

## Scope

### Applies To:
- All derivative instruments
- Certain contracts with derivative-like features
- Hedging relationships

### Does NOT Apply To (Scope Exceptions):
- Regular-way security trades (normal purchase/sale with customary settlement)
- Normal purchases and normal sales of nonfinancial assets
- Certain insurance contracts (ASC 944)
- Certain financial guarantee contracts (ASC 460)
- Certain contracts indexed to entity's own stock (ASC 815-40)
- Certain loan commitments (ASC 825)

---

## Key Definitions

### Derivative Instrument

A financial instrument or contract with **ALL THREE** characteristics:

| Characteristic | Description |
|----------------|-------------|
| **Underlying** | Has one or more underlyings (price, rate, index, etc.) AND one or more notional amounts or payment provisions |
| **Initial net investment** | Requires no initial investment, or an initial net investment smaller than required for direct exposure to underlying |
| **Net settlement** | Can be net settled, OR underlying is readily convertible to cash |

### Common Derivatives

| Type | Description | Underlying |
|------|-------------|------------|
| **Interest rate swap** | Exchange fixed for floating rate payments | Interest rate |
| **Forward contract** | Agreement to buy/sell at future date at specified price | Commodity price, FX rate |
| **Futures contract** | Standardized forward traded on exchange | Various |
| **Option** | Right (not obligation) to buy/sell | Stock price, index, rate |
| **Currency swap** | Exchange currencies at specified terms | Exchange rate |

### Notional Amount

The specified quantity (units, dollars, shares, etc.) that determines the settlement amount.

**Example:** Interest rate swap with $1,000,000 notional—parties exchange interest based on $1M, not the principal itself.

---

## General Accounting (No Hedge Designation)

### Recognition

- Recognize derivative as asset or liability at fair value
- Changes in fair value → Current earnings

### Journal Entry—Mark to Market

**If derivative increases in value:**
```
Dr. Derivative Asset               $XXX
    Cr. Gain on Derivative (Income)         $XXX
```

**If derivative decreases in value:**
```
Dr. Loss on Derivative (Income)    $XXX
    Cr. Derivative Liability                $XXX
```

---

## Hedge Accounting Overview

### Purpose

Reduce income statement volatility by matching the timing of gains/losses on derivatives with gains/losses on hedged items.

### Hedge Types

| Type | What is Hedged | Accounting Effect |
|------|----------------|-------------------|
| **Fair Value Hedge** | Changes in fair value of recognized asset/liability or firm commitment | Both derivative and hedged item at fair value through earnings |
| **Cash Flow Hedge** | Variability in cash flows of forecasted transaction or floating-rate asset/liability | Derivative gains/losses in OCI until hedged item affects earnings |
| **Net Investment Hedge** | Foreign currency exposure of investment in foreign operation | Derivative gains/losses in OCI (CTA) |

---

## Hedge Accounting Requirements

### Documentation Requirements (At Inception)

Formal documentation must include:

| Element | Description |
|---------|-------------|
| **Hedging relationship** | Identification of derivative and hedged item |
| **Risk management objective** | Why entity is hedging |
| **Nature of risk** | Specific risk being hedged |
| **Hedge effectiveness** | How effectiveness will be assessed |
| **Assessment methods** | Qualitative or quantitative approach |

### Effectiveness Assessment

**At Inception:**
- Prospective assessment that hedge will be highly effective

**Ongoing:**
- Assess at each reporting date (or when financial statements issued)
- If hedge ceases to be highly effective → Discontinue hedge accounting

### Qualifying Hedged Items

| Fair Value Hedge | Cash Flow Hedge |
|------------------|-----------------|
| Recognized asset or liability | Forecasted transaction |
| Firm commitment | Forecasted purchase/sale |
| Identified portion of asset/liability | Variable cash flows on recognized item |

### Qualifying Hedging Instruments

- Written options only if combined with purchased options or if time value excluded
- Proportion of derivative may be designated (but not partial term)
- Compound derivatives may qualify

---

## Fair Value Hedges

### Mechanics

1. Record derivative at fair value (changes in earnings)
2. Adjust carrying amount of hedged item for changes in fair value due to hedged risk (changes in earnings)
3. Net effect: Earnings impact of derivative and hedged item offset

### Example: Fair Value Hedge of Fixed-Rate Debt

**Facts:**
- Company issues $10,000,000 fixed-rate debt at 5%
- Company enters interest rate swap: pay floating/receive fixed
- Objective: Convert fixed-rate exposure to floating-rate
- Year 1: Interest rates rise; swap fair value = $200,000 asset

**Journal Entries—Year 1:**

*Record swap at fair value:*
```
Dr. Derivative Asset—Swap          $200,000
    Cr. Gain on Hedge (Income)              $200,000
```

*Adjust hedged item (debt) for change in fair value:*
```
Dr. Loss on Hedge (Income)         $200,000
    Cr. Debt (Adjustment)                   $200,000
```

**Net Income Impact:** $0 (offsetting gains and losses)

### Basis Adjustment

The adjustment to the hedged item becomes part of its carrying amount and is:
- Amortized over remaining life (for debt/assets with finite lives)
- Considered in impairment testing (for equity securities, inventory)

---

## Cash Flow Hedges

### Mechanics

1. Record derivative at fair value
2. Effective portion of gain/loss → OCI
3. Ineffective portion → Earnings immediately
4. Reclassify from OCI to earnings when hedged item affects earnings

### Example: Cash Flow Hedge of Forecasted Purchase

**Facts:**
- Company will purchase inventory in 6 months
- Enters forward contract to lock in price
- Forward contract fair value increases by $50,000
- Hedge is 100% effective

**Journal Entry—During Hedge Period:**
```
Dr. Derivative Asset—Forward       $50,000
    Cr. OCI—Cash Flow Hedge                 $50,000
```

**When Inventory Purchased:**
```
Dr. Inventory                      $XXX
    Cr. Cash                                $XXX

Dr. OCI—Cash Flow Hedge            $50,000
    Cr. Inventory                           $50,000
```

**Result:** Inventory recorded at locked-in price

### Discontinued Cash Flow Hedges

| Reason for Discontinuance | Accounting |
|---------------------------|------------|
| Hedge no longer effective | OCI remains until forecasted transaction affects earnings |
| Forecasted transaction no longer probable | Immediately reclassify OCI to earnings |
| Hedging relationship dedesignated | OCI remains until forecasted transaction affects earnings |

---

## Net Investment Hedges

### Mechanics

1. Hedge of foreign currency exposure of net investment in foreign operation
2. Effective portion → CTA (component of OCI)
3. Reclassify to earnings upon sale or substantial liquidation of foreign operation

### Qualifying Instruments

- Derivatives (forwards, options, cross-currency swaps)
- Non-derivative instruments (foreign currency-denominated debt)

### Example: Net Investment Hedge

**Facts:**
- U.S. parent has €50,000,000 investment in German subsidiary
- Parent borrows €30,000,000 to hedge portion of investment
- Euro weakens; translation loss on investment = $2,000,000
- Gain on euro-denominated debt = $1,200,000

**Journal Entry:**
```
Dr. Debt (reduced)                 $1,200,000
    Cr. CTA—Net Investment Hedge (OCI)      $1,200,000
```

**Result:** $1,200,000 of translation loss offset in OCI

---

## Hedge Effectiveness Methods

### Quantitative Methods

| Method | Description | Use |
|--------|-------------|-----|
| **Dollar-offset** | Compare dollar changes in derivative vs. hedged item | Simple but strict (80-125% test) |
| **Regression analysis** | Statistical correlation | More sophisticated, allows more variability |
| **Volatility reduction** | Compare hedged vs. unhedged volatility | Less common |

### Qualitative Methods (Critical Terms Match)

If critical terms of hedging instrument and hedged item match:
- May assume hedge is perfectly effective
- Skip quantitative testing
- Document that terms are matched

**Critical Terms:**
- Notional amounts
- Maturity dates
- Underlying variables
- Payment dates

### Shortcut Method (Limited Availability)

For interest rate swaps hedging debt, may assume perfect effectiveness if **ALL** criteria met:
- Notional = Principal
- Fair value of swap at inception is zero
- Fixed rate on swap = fixed rate on debt
- Other specific criteria in ASC 815

---

## Embedded Derivatives

### Definition

A derivative embedded within a host contract.

### Bifurcation Required When:

| Criterion | Description |
|-----------|-------------|
| **1. Not clearly and closely related** | Economic characteristics of embedded derivative differ from host |
| **2. Hybrid not measured at fair value** | Changes in fair value not in earnings |
| **3. Separate instrument would be derivative** | Meets definition of derivative |

### Examples

| Host Contract | Embedded Derivative | Bifurcate? |
|---------------|---------------------|------------|
| Fixed-rate debt | Interest rate cap | No (related) |
| Debt in functional currency | Conversion to stock | No (indexed to own stock—ASC 815-40) |
| Debt denominated in foreign currency | Currency component | May require analysis |
| Lease with variable rent based on sales | No underlying price/rate risk | No |
| Debt with equity conversion feature | Conversion option | Analyze under ASC 815-40 |

### Accounting When Bifurcated

- Separate embedded derivative from host
- Account for derivative at fair value through earnings
- Account for host under applicable GAAP

---

## Special Topics

### Private Company Practical Expedient

**Receive-Variable, Pay-Fixed Swaps (ASU 2014-03):**

Private companies may elect simplified hedge accounting for swaps that:
- Have specified terms
- Are designated as hedging variable-rate borrowings
- Meet simplified effectiveness requirements

**Benefit:** Combined instrument approach—no bifurcation, simplified measurement

### Last-of-Layer Hedging (ASU 2017-12)

Allows fair value hedging of a stated amount of a closed portfolio of prepayable assets (last layer not expected to be prepaid).

**Benefit:** Hedge bottom layer of portfolio that is unlikely to prepay

### Partial-Term Hedging

May hedge only a portion of the time period of a hedged item (not just full term).

### Excluded Components

May exclude certain components from effectiveness assessment:
- Time value of options
- Forward points
- Cross-currency basis spreads

**Accounting for Excluded Amounts:**
- Amortize to earnings systematically and rationally, OR
- Recognize all changes in fair value in earnings

---

## ASU 2017-12 Hedge Accounting Improvements

### Key Changes

| Area | Change |
|------|--------|
| **Risk component hedging** | Can hedge component of contractual coupon |
| **Effectiveness assessment** | Qualitative ongoing assessment if initially demonstrated |
| **Partial-term hedging** | Explicitly permitted |
| **Presentation** | Derivatives in same line as hedged item |
| **Disclosures** | Enhanced tabular disclosures |

### Presentation Requirements

| Hedge Type | Presentation of Derivative Gains/Losses |
|------------|----------------------------------------|
| Fair value hedge | Same income statement line as hedged item |
| Cash flow hedge | Same line as hedged item when reclassified from OCI |

---

## Practical Examples

### Example 1: Interest Rate Swap—Cash Flow Hedge

**Facts:**
- Company has $5,000,000 variable-rate loan (SOFR + 2%)
- Enters pay-fixed (4%), receive-variable (SOFR) swap
- Notional: $5,000,000; Term: 3 years
- Quarter 1: SOFR = 3%; Swap fair value = ($25,000)

**Analysis:**
- Company pays 4% fixed on swap, receives SOFR (3%)
- Net swap payment: $5M × (4% - 3%) × 1/4 = $12,500
- Total interest: Loan (SOFR + 2%) + Net swap = Fixed 6%
- Swap fair value decline = Loss of $25,000

**Journal Entries—Quarter 1:**

*Record swap payment:*
```
Dr. Interest Expense               $62,500   (5M × 5% × 1/4)
    Cr. Cash—Loan Payment                    $62,500

Dr. Interest Expense               $12,500   (Net swap payment)
    Cr. Cash—Swap Settlement                 $12,500
```

*Record swap fair value change (effective portion to OCI):*
```
Dr. OCI—Cash Flow Hedge            $25,000
    Cr. Derivative Liability—Swap           $25,000
```

**Effective interest rate achieved:** 6% (4% swap + 2% spread)

---

### Example 2: Forward Contract—Fair Value Hedge of Firm Commitment

**Facts:**
- Company commits to sell 10,000 units at $50/unit in 6 months
- Enters forward contract to buy 10,000 units at $48/unit (hedging commodity price risk)
- At settlement date: Market price = $55
- Forward contract gain = 10,000 × ($55 - $48) = $70,000
- Firm commitment loss (locked in at lower price) = 10,000 × ($50 - $55) = ($50,000)

**Note:** Mismatch because hedge ratio not 1:1 (selling 10K, bought forward for 10K but at different strike)

**Journal Entries:**

*At settlement—Forward contract:*
```
Dr. Derivative Asset—Forward       $70,000
    Cr. Gain on Hedge (Income)              $70,000
```

*Firm commitment adjustment:*
```
Dr. Loss on Hedge (Income)         $50,000
    Cr. Firm Commitment Liability           $50,000
```

*Settle forward:*
```
Dr. Inventory                      $480,000  (10K × $48)
Dr. Cash                           $70,000   (Forward settlement)
    Cr. Derivative Asset—Forward            $70,000
    Cr. Cash                                $480,000
```

---

### Example 3: Embedded Derivative Analysis

**Facts:**
- Company issues $1,000,000 convertible debt
- Debt is convertible into 50,000 shares at holder's option
- Conversion feature indexed to company's stock

**Analysis—Is Bifurcation Required?**

| Criterion | Analysis |
|-----------|----------|
| Not clearly and closely related? | Equity conversion in debt host—not related |
| Hybrid not at fair value? | Debt at amortized cost—criterion met |
| Would be a derivative? | Analyze under ASC 815-40... |

**ASC 815-40 Analysis:**
- Is conversion feature indexed to own stock? YES
- Would it be classified in equity if freestanding? Analyze...
- If equity classified → No bifurcation (ASC 815-15 scope exception)
- If liability classified → Bifurcate and measure at fair value

---

## Disclosure Requirements

### Qualitative Disclosures

- Objectives and strategies for using derivatives
- Context for understanding those objectives
- Risk management policies

### Quantitative Disclosures

| Disclosure | Description |
|------------|-------------|
| **Fair values** | Location and fair value of derivatives by category |
| **Gains and losses** | By hedge type and location in statements |
| **Notional amounts** | Volume of derivative activity |
| **Credit-risk contingencies** | Collateral requirements, termination features |

### Tabular Format Required

Present fair value hedge gains/losses, cash flow hedge amounts in OCI, and amounts reclassified from OCI in tabular format.

---

## Common Implementation Issues

### 1. Documentation Failures
- Incomplete or late documentation
- Missing formal designation
- Inadequate description of hedged risk

### 2. Effectiveness Testing
- Not testing at required intervals
- Using inappropriate methods
- Ignoring ineffectiveness

### 3. Forecasted Transaction Issues
- Transaction no longer probable
- Timing changes affecting hedge relationship
- Not monitoring forecast probability

### 4. Embedded Derivatives
- Missing identification of embedded features
- Incorrect bifurcation analysis
- Not updating assessment for modifications

### 5. Presentation Errors
- Gross vs. net presentation
- Wrong income statement location
- Improper OCI reclassification timing

---

## Private Company Considerations

### Simplified Hedge Accounting (ASU 2014-03 and ASU 2017-12)

**Qualifying Swaps:**
- Receive-variable, pay-fixed
- Designated as hedging variable-rate debt
- Certain term requirements

**Benefits:**
- No effectiveness testing
- Combined accounting with debt
- Simplified documentation

### Cost-Benefit of Hedge Accounting

Many private companies choose to:
- Not apply hedge accounting (mark to market through earnings)
- Simplify by matching economic hedges without formal designation
- Use private company alternatives where available

---

## External Resources

- [FASB ASC 815](https://asc.fasb.org/)
- [KPMG: Handbook—Derivatives and Hedging](https://frv.kpmg.us/)
- [PwC: Derivatives and Hedging Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Accounting for Derivative Instruments and Hedging Activities](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Derivatives and Hedging](https://www.ey.com/)

---

## Navigation

← [Back to Broad Transactions (800s)](README.md) | [Back to Main Guide](../../README.md)
