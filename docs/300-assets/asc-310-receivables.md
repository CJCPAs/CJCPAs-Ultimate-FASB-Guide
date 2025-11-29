# ASC 310: Receivables

> Comprehensive guidance on recognition, measurement, and presentation of receivables—one of the most common assets on any balance sheet.

## Overview

ASC 310 provides guidance on the accounting for receivables, including trade receivables, loans, and notes receivable. This topic addresses initial recognition, subsequent measurement, impairment (in conjunction with ASC 326), and derecognition of receivables. For most entities, receivables represent a significant asset requiring careful attention to collectibility and valuation.

**Core Principle:**
> "Receivables should be recognized at their net realizable value—the amount expected to be collected—with appropriate allowances for credit losses and other adjustments."

---

## Scope

### Applies To:
- Trade accounts receivable
- Notes receivable
- Loans receivable
- Financing receivables
- Factored receivables (from transferor's perspective)
- Contract assets (receivable aspects)

### Does NOT Apply To:
- Debt securities (ASC 320)
- Derivatives (ASC 815)
- Lease receivables (lessor—ASC 842)
- Equity securities (ASC 321)
- Contract assets—revenue recognition aspects (ASC 606)

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Receivable** | Right to receive cash or other assets |
| **Trade Receivable** | Amounts due from customers for goods/services sold in ordinary course of business |
| **Financing Receivable** | Contractual right to receive money, either on demand or fixed/determinable dates |
| **Loan** | Extension of money from a lender to a borrower, with repayment obligation |
| **Troubled Debt Restructuring (TDR)** | Creditor grants concession to debtor experiencing financial difficulty (eliminated for ASC 326 adopters) |
| **Nonaccrual Status** | Loans for which recognition of interest income has been suspended |

---

## Initial Recognition and Measurement

### Trade Receivables

**Initial Recognition:** At transaction price per ASC 606

```
Dr. Accounts Receivable              $100,000
    Cr. Revenue                                  $100,000
```

**With Early Payment Discount:**
```
Dr. Accounts Receivable              $100,000
    Cr. Revenue                                  $98,000
    Cr. Refund Liability                          $2,000
(Assuming 2% discount is expected to be taken)
```

### Notes Receivable

**At Fair Value (typically face if at market rate):**
```
Dr. Notes Receivable                 $50,000
    Cr. Cash                                     $50,000
```

**Below-Market Rate Loan:**
```
Dr. Notes Receivable                 $50,000
Dr. Discount on Note Receivable       $5,000
    Cr. Cash                                     $50,000
    Cr. Unearned Interest Revenue                 $5,000
```

### Loans Receivable

**Initial Measurement:** At fair value, which generally equals:
- Cash disbursed PLUS
- Direct loan origination costs LESS
- Loan origination fees

```
Dr. Loans Receivable                 $100,000
Dr. Deferred Loan Costs                $2,000
    Cr. Cash                                    $100,000
    Cr. Deferred Loan Fees                        $2,000
```

---

## Loan Origination Fees and Costs (ASC 310-20)

### Fee and Cost Categories

| Type | Treatment |
|------|-----------|
| **Loan origination fees** | Defer and amortize as yield adjustment |
| **Direct loan origination costs** | Defer and amortize as yield adjustment |
| **Commitment fees** | Defer if commitment exercised; recognize if expired |
| **Syndication fees** | Generally recognize when syndication complete |

### Direct Loan Origination Costs

**Include:**
- Incremental direct costs (credit checks, appraisals)
- Direct personnel costs (time spent on specific loans)

**Exclude:**
- Indirect costs (overhead)
- General administrative costs
- Unsuccessful loan efforts

### Amortization Methods

| Method | When to Use |
|--------|-------------|
| **Interest method (effective yield)** | Required for loans with stated interest |
| **Straight-line** | Acceptable if not materially different |

**Journal Entry—Fee Amortization:**
```
Dr. Deferred Loan Fees               $200
    Cr. Interest Income                          $200
(Monthly amortization of origination fees)
```

---

## Credit Losses and Allowances

### ASC 326—Current Expected Credit Loss (CECL)

**Effective Dates:**
- SEC filers: Already effective
- All other entities: Fiscal years beginning after December 15, 2022

### CECL Model Overview

**Key Principle:** Recognize expected credit losses over the life of the asset at origination/purchase.

| Element | Description |
|---------|-------------|
| **Scope** | Measured at amortized cost (receivables, loans, HTM securities) |
| **Measurement** | Lifetime expected credit losses |
| **When to Record** | At initial recognition and updated each period |
| **Collective Assessment** | Pool similar risk characteristics |

### Estimating Expected Credit Losses

**Methods Include:**

| Method | Description | When to Use |
|--------|-------------|-------------|
| **Discounted cash flow** | Present value of expected collections | Complex loans |
| **Loss rate** | Historical loss percentage × outstanding balance | Trade receivables |
| **Roll rate** | Migration analysis across aging buckets | Consumer loans |
| **Probability of default** | PD × LGD × EAD | Sophisticated portfolios |
| **Vintage analysis** | Losses by origination cohort | Homogeneous pools |

### Allowance for Credit Losses

**Recording Initial Allowance:**
```
Dr. Credit Loss Expense              $15,000
    Cr. Allowance for Credit Losses            $15,000
```

**Write-Off:**
```
Dr. Allowance for Credit Losses      $5,000
    Cr. Accounts Receivable                     $5,000
```

**Recovery:**
```
Dr. Accounts Receivable              $1,000
    Cr. Allowance for Credit Losses             $1,000
Dr. Cash                             $1,000
    Cr. Accounts Receivable                     $1,000
```

---

## Trade Receivables Specifics

### Aging Analysis

| Age Bucket | Balance | Loss Rate | Expected Loss |
|------------|---------|-----------|---------------|
| Current | $500,000 | 0.5% | $2,500 |
| 1-30 days past due | $100,000 | 2% | $2,000 |
| 31-60 days past due | $50,000 | 5% | $2,500 |
| 61-90 days past due | $25,000 | 15% | $3,750 |
| Over 90 days | $15,000 | 50% | $7,500 |
| **Total** | **$690,000** | | **$18,250** |

### Concentration Risk

**Disclosure Required:** Significant concentrations of credit risk

**Example Factors:**
- Geographic concentration
- Industry concentration
- Major customer concentration

### Sales with Right of Return

Per ASC 606:
- Estimate returns using expected value or most likely amount
- Record refund liability (not contra A/R)
- Record asset for right to recover goods

---

## Notes Receivable

### Interest Recognition

**Interest Method:**
```
Interest Income = Carrying Amount × Effective Interest Rate
```

**Example:**
- Note face value: $100,000
- Discount: $5,000
- Effective rate: 6%
- Term: 3 years

**Year 1 Entry:**
```
Dr. Cash                              $4,000
Dr. Discount on Note Receivable       $1,700
    Cr. Interest Income                         $5,700
($95,000 × 6% = $5,700)
```

### Imputed Interest (ASC 835-30)

**When Required:** Receivables with:
- No stated interest rate, or
- Stated rate unreasonable, or
- Face amount materially different from cash price

**Not Required For:**
- Trade receivables ≤ 1 year
- Security deposits
- Customer advances
- Intercompany transactions (may impute)

---

## Loan Impairment (Pre-CECL Entities)

### Incurred Loss Model (if CECL not yet adopted)

**Recognition:** When probable that creditor won't collect all amounts due

**Measurement Options:**
1. Present value of expected future cash flows
2. Loan's observable market price
3. Fair value of collateral (if collateral-dependent)

### Impairment Entry

```
Dr. Bad Debt Expense/Provision        $10,000
    Cr. Allowance for Loan Losses              $10,000
```

---

## Troubled Debt Restructuring (Historical—Pre-ASU 2022-02)

**Note:** For entities that have adopted ASU 2022-02, TDR guidance is eliminated. Below is historical reference.

### Types of Modifications

| Type | Accounting Treatment |
|------|---------------------|
| **Transfer of assets** | Record at fair value; recognize gain/loss |
| **Equity interest** | Record at fair value of equity |
| **Modification of terms** | Compare cash flows; possible gain |

---

## Transfers and Servicing (ASC 860)

### Sale vs. Secured Borrowing

**Sale Criteria (ALL must be met):**
1. Assets isolated from transferor
2. Transferee can pledge or exchange
3. Transferor does not maintain effective control

### Factoring/Selling Receivables

**Sale Treatment:**
```
Dr. Cash                              $95,000
Dr. Loss on Sale                       $5,000
    Cr. Accounts Receivable                    $100,000
```

**Secured Borrowing:**
```
Dr. Cash                              $95,000
    Cr. Loan Payable                           $95,000
(Receivables remain on balance sheet)
```

### Servicing Assets/Liabilities

When retaining servicing after sale:
- Fair value servicing at transfer
- Subsequently measure at fair value or amortized cost

---

## Pledged and Assigned Receivables

### Pledging Receivables as Collateral

- Receivables remain on balance sheet
- Disclose pledging arrangement
- Note nature and carrying amount pledged

### Assignment

| Type | Control | Balance Sheet Treatment |
|------|---------|------------------------|
| **Notification basis** | High transferor control | Keep on balance sheet |
| **Non-notification** | Moderate control | Analyze for sale criteria |

---

## Practical Examples

### Example 1: CECL Allowance Calculation

**Facts:**
- Trade receivables: $1,000,000
- Historical loss rate: 2%
- Economic forecast: Recession expected
- Qualitative adjustment: +0.5%

**Calculation:**
```
Base expected loss ($1,000,000 × 2%)      $20,000
Qualitative adjustment ($1,000,000 × 0.5%)   5,000
                                          -------
Total expected credit loss               $25,000
```

**Journal Entry:**
```
Dr. Credit Loss Expense               $25,000
    Cr. Allowance for Credit Losses           $25,000
```

---

### Example 2: Note Receivable with Below-Market Rate

**Facts:**
- Loaned employee $50,000
- 0% interest note, due in 2 years
- Market rate: 5%

**Present Value Calculation:**
- PV = $50,000 ÷ (1.05)² = $45,351
- Discount = $50,000 - $45,351 = $4,649

**Initial Entry:**
```
Dr. Note Receivable                   $50,000
    Cr. Cash                                   $50,000

Dr. Compensation Expense               $4,649
    Cr. Discount on Note Receivable            $4,649
```

**Year 1 Interest Accrual:**
```
Dr. Discount on Note Receivable        $2,268
    Cr. Interest Income                        $2,268
($45,351 × 5% = $2,268)
```

---

### Example 3: Factoring with Recourse

**Facts:**
- Factored $200,000 receivables
- Received $185,000 cash
- Retained recourse obligation (estimated $5,000)
- Transaction qualifies as sale

**Journal Entry:**
```
Dr. Cash                              $185,000
Dr. Loss on Sale of Receivables        $20,000
    Cr. Accounts Receivable                   $200,000
    Cr. Recourse Liability                      $5,000
```

---

### Example 4: Loan Modification (Post-ASU 2022-02)

**Facts:**
- Commercial loan: $500,000
- Borrower in financial difficulty
- Terms modified: Rate reduced from 6% to 4%, term extended 2 years

**Under ASU 2022-02 (TDR eliminated):**
- Evaluate whether modification is new loan or continuation
- Generally, account as continuation with prospective yield adjustment
- No special TDR accounting

**Analysis:** If substantially similar to original loan terms, continue accounting with new effective rate.

---

## Private Company Considerations

### Practical Expedients

| Area | Private Company Alternative |
|------|---------------------------|
| **CECL timing** | Delayed effective date (now effective) |
| **Fair value option** | Generally not elected |
| **Complexity** | Simpler estimation methods acceptable |

### Common Private Company Issues

1. **Related party receivables** — Evaluate collectibility carefully
2. **Shareholder advances** — May be equity in substance
3. **Concentration risk** — Often higher with fewer customers
4. **Documentation** — Support for allowance estimates

---

## Disclosure Requirements

### ASC 310 Disclosures

| Item | Required Disclosure |
|------|---------------------|
| **Major categories** | Disaggregation of receivables |
| **Allowance method** | Accounting policy |
| **Credit quality indicators** | Age, risk rating, etc. |
| **Nonaccrual policy** | When placed on nonaccrual |
| **Past due policy** | Definition of past due |
| **Charge-off policy** | When receivables are written off |

### ASC 326 CECL Disclosures

| Item | Required Disclosure |
|------|---------------------|
| **Allowance rollforward** | Beginning, provisions, write-offs, recoveries, ending |
| **Credit quality** | By risk characteristic |
| **Vintage disclosure** | For public entities |
| **Methodology** | How expected losses estimated |
| **Significant assumptions** | Forecasts used |

### Credit Risk Concentration

Disclose:
- Nature of concentration
- Maximum loss exposure
- Collateral or guarantees

---

## Common Audit Issues

### Allowance for Credit Losses

| Issue | Audit Response |
|-------|---------------|
| Inadequate allowance | Analyze aging, test historical losses |
| Unsupported assumptions | Evaluate management's methodology |
| Missing write-offs | Review aged receivables for collectibility |
| Forecast adjustments | Assess reasonableness of economic forecasts |

### Revenue Recognition Interface

| Issue | Risk |
|-------|------|
| Fictitious receivables | Revenue overstatement |
| Bill-and-hold | Premature recognition |
| Channel stuffing | Collectibility concerns |
| Side agreements | Contingent terms |

### Documentation

**Retain documentation for:**
- Allowance methodology
- Historical loss analysis
- Economic forecast support
- Individual account assessments
- Write-off approvals

---

## Recent Updates

| ASU | Topic | Impact |
|-----|-------|--------|
| **ASU 2022-02** | TDR and Vintage | Eliminated TDR, added vintage disclosures |
| **ASU 2022-03** | FV Option Equity | Not for receivables, but related |
| **ASU 2020-04** | Reference Rate Reform | LIBOR transition for loans |
| **ASU 2019-11** | CECL Amendments | Clarifications to ASC 326 |
| **ASU 2016-13** | CECL | Fundamental change to impairment model |

---

## External Resources

- [FASB ASC 310](https://asc.fasb.org/)
- [FASB ASC 326 (Credit Losses)](https://asc.fasb.org/)
- [FASB ASC 860 (Transfers and Servicing)](https://asc.fasb.org/)
- [SEC Staff Bulletin on CECL](https://www.sec.gov/)
- [AICPA Credit Losses Toolkit](https://www.aicpa.org/)
- [KPMG: Handbook—Credit Impairment](https://frv.kpmg.us/)
- [PwC: Loans and Investments Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to CECL](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Credit Losses](https://www.ey.com/)

---

## Navigation

← [Back to Assets (300s)](README.md) | [Back to Main Guide](../../README.md)
