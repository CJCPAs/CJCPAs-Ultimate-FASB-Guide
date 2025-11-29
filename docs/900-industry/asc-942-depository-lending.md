# ASC 942: Financial Services—Depository and Lending

> Specialized accounting guidance for banks, credit unions, and other depository and lending institutions.

## Overview

ASC 942 provides accounting guidance specific to depository and lending institutions including banks, savings institutions, credit unions, and other financial institutions. These entities have unique accounting considerations for loan portfolios, deposits, interest income, and regulatory capital requirements.

**Core Principle:**
> "Depository and lending institutions account for their primary activities—accepting deposits and making loans—with specialized guidance for interest recognition, credit losses, and regulatory compliance."

---

## Scope

### Applies To:
- Banks (national, state, savings banks)
- Savings and loan associations
- Credit unions
- Bank holding companies
- Mortgage companies (lending aspects)
- Finance companies

### Does NOT Apply To:
- Broker-dealers (ASC 940)
- Insurance companies (ASC 944)
- Investment companies (ASC 946)
- Non-financial lending entities (use general GAAP)

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Depository Institution** | Entity that accepts deposits subject to withdrawal |
| **Loan** | Contractual right to receive money from a borrower |
| **Nonaccrual Loan** | Loan on which interest recognition is suspended |
| **Troubled Debt Restructuring (TDR)** | Modification granted to borrower in financial difficulty (eliminated under ASU 2022-02 for CECL adopters) |
| **Regulatory Capital** | Capital as defined by banking regulators |
| **Net Interest Margin** | Interest income less interest expense as % of earning assets |

---

## Regulatory Framework

### Primary Regulators

| Regulator | Jurisdiction |
|-----------|--------------|
| **OCC** | National banks |
| **Federal Reserve** | State member banks, BHCs |
| **FDIC** | State non-member banks |
| **NCUA** | Credit unions |
| **State regulators** | State-chartered institutions |

### Key Regulations

| Regulation | Description |
|------------|-------------|
| **Basel III** | Capital adequacy framework |
| **Regulation W** | Transactions with affiliates |
| **Regulation O** | Loans to insiders |
| **Call Reports** | Quarterly regulatory filings |
| **CRA** | Community Reinvestment Act |

---

## Financial Statement Presentation

### Balance Sheet Presentation

Banks typically use a **liquidity-ordered** balance sheet:

```
FIRST NATIONAL BANK
Consolidated Balance Sheet
December 31, 20X1
(in thousands)

ASSETS
Cash and due from banks                   $   50,000
Interest-bearing deposits                     25,000
Securities:
  Available for sale                         150,000
  Held to maturity (fair value $82,000)       80,000
Loans, net of allowance of $12,000          800,000
Premises and equipment, net                   35,000
Goodwill and intangibles                      15,000
Other assets                                  20,000
                                          ----------
    Total assets                          $1,175,000
                                          ==========

LIABILITIES
Deposits:
  Noninterest-bearing                     $  200,000
  Interest-bearing                           750,000
                                          ----------
    Total deposits                           950,000
Federal funds purchased                       50,000
Other borrowings                              30,000
Other liabilities                             15,000
                                          ----------
    Total liabilities                      1,045,000

STOCKHOLDERS' EQUITY
Common stock                                  10,000
Surplus                                       50,000
Retained earnings                             72,000
Accumulated OCI                               (2,000)
                                          ----------
    Total stockholders' equity               130,000
                                          ----------
    Total liabilities and equity          $1,175,000
                                          ==========
```

---

## Loan Accounting

### Loan Recognition

**Initial Recognition:**
```
Dr. Loans Receivable                  $100,000
    Cr. Cash                                   $100,000
```

**With Origination Fees and Costs:**
```
Dr. Loans Receivable                  $100,000
Dr. Deferred Loan Costs                 $1,500
    Cr. Cash                                  $100,000
    Cr. Deferred Loan Fees                      $1,500
```

### Interest Income Recognition

**Accrual Method (Performing Loans):**
```
Dr. Interest Receivable               $500
    Cr. Interest Income                        $500

Dr. Deferred Loan Fees                $50
    Cr. Interest Income                        $50
(Fee amortization using interest method)
```

### Nonaccrual Loans

**When to Place on Nonaccrual:**
- Principal or interest 90+ days past due
- Full collection of principal/interest doubtful
- Loan meets regulatory nonaccrual criteria

**Nonaccrual Treatment:**
```
Dr. Interest Income                   $500
    Cr. Interest Receivable                    $500
(Reverse accrued interest)
```

**Cash Payments Received:**
| Method | Application |
|--------|-------------|
| **Cost recovery** | Apply to principal until recovered |
| **Cash basis** | Recognize as income if collectible |

---

## Allowance for Credit Losses (CECL)

### Overview

Under ASC 326 (CECL), institutions estimate lifetime expected credit losses at origination.

### Allowance Calculation Components

| Component | Description |
|-----------|-------------|
| **Collective assessment** | Pool loans with similar risk characteristics |
| **Individual assessment** | Evaluate significant loans separately |
| **Qualitative factors** | Economic conditions, portfolio changes |
| **Historical loss rates** | Adjusted for current conditions |

### Methodology Options

| Method | Description |
|--------|-------------|
| **PD/LGD** | Probability of default × Loss given default |
| **Migration analysis** | Movement between risk ratings |
| **Vintage analysis** | Losses by origination year |
| **Discounted cash flows** | For individually assessed loans |

### Journal Entries

**Initial Allowance (at origination):**
```
Dr. Provision for Credit Losses       $1,500
    Cr. Allowance for Credit Losses           $1,500
```

**Charge-Off:**
```
Dr. Allowance for Credit Losses       $5,000
    Cr. Loans Receivable                      $5,000
```

**Recovery:**
```
Dr. Cash                              $1,000
    Cr. Allowance for Credit Losses           $1,000
```

---

## Deposit Accounting

### Types of Deposits

| Type | Characteristics |
|------|-----------------|
| **Demand deposits** | Checking accounts, no maturity |
| **Savings deposits** | Limited transactions, no maturity |
| **Time deposits (CDs)** | Fixed maturity, penalty for early withdrawal |
| **NOW accounts** | Interest-bearing checking |
| **Money market** | Higher rates, limited checks |

### Deposit Recognition

**Customer Deposit:**
```
Dr. Cash                             $10,000
    Cr. Deposits—Savings                     $10,000
```

**Interest Expense:**
```
Dr. Interest Expense                    $50
    Cr. Interest Payable                        $50
```

### Brokered Deposits

Special considerations:
- May be more volatile
- Regulatory restrictions if undercapitalized
- Higher rates typically
- Disclose separately

---

## Securities Portfolio

### Classification

| Category | Measurement | Interest | Fair Value Changes |
|----------|-------------|----------|-------------------|
| **Held to Maturity (HTM)** | Amortized cost | Interest method | N/A (disclose FV) |
| **Available for Sale (AFS)** | Fair value | Interest method | OCI |
| **Trading** | Fair value | As earned | Earnings |

### AFS Securities

**Purchase:**
```
Dr. AFS Securities                   $100,000
    Cr. Cash                                  $100,000
```

**Interest Accrual:**
```
Dr. Interest Receivable               $2,500
Dr. AFS Securities (premium amort.)     (200)
    Cr. Interest Income                        $2,300
```

**Fair Value Adjustment:**
```
Dr. OCI—Unrealized Gain               $3,000
    Cr. AFS Securities—FV Adjustment          $3,000
```

### HTM Securities—Credit Losses

Under CECL, HTM securities also subject to credit loss allowance:
```
Dr. Provision for Credit Losses       $500
    Cr. Allowance for Credit Losses—HTM       $500
```

---

## Interest Rate Risk Management

### Common Hedging Strategies

| Strategy | Purpose |
|----------|---------|
| **Interest rate swaps** | Convert fixed to floating (or vice versa) |
| **Caps/floors** | Protect against rate movements |
| **Forward rate agreements** | Lock in future rates |

### Fair Value Hedges

**Hedging Fixed-Rate Loans:**
```
Dr. Derivative Asset                  $5,000
    Cr. Gain on Derivative                    $5,000

Dr. Loss on Hedged Item               $5,000
    Cr. Loans Receivable (basis adjustment)   $5,000
```

### Cash Flow Hedges

**Hedging Variable-Rate Deposits:**
```
Dr. Derivative Asset                  $3,000
    Cr. OCI—Cash Flow Hedge                   $3,000
```

---

## Regulatory Capital

### Capital Components

| Tier | Components |
|------|------------|
| **CET1** | Common stock, retained earnings, AOCI (opt-out available) |
| **Additional Tier 1** | Non-cumulative preferred stock, qualifying instruments |
| **Tier 2** | Subordinated debt, allowance (limited), other |

### Capital Ratios

| Ratio | Minimum | Well-Capitalized |
|-------|---------|------------------|
| **CET1 Ratio** | 4.5% | 6.5% |
| **Tier 1 Ratio** | 6.0% | 8.0% |
| **Total Capital** | 8.0% | 10.0% |
| **Leverage Ratio** | 4.0% | 5.0% |

### AOCI Opt-Out

Non-advanced approaches banks may elect to exclude AOCI from CET1:
- One-time irrevocable election
- Reduces capital volatility from AFS securities

---

## Practical Examples

### Example 1: Loan with Fees and Costs

**Facts:**
- $1,000,000 loan, 5-year term
- 6% interest rate
- Origination fee: $20,000
- Direct origination costs: $5,000
- Net fee: $15,000

**Initial Recognition:**
```
Dr. Loans Receivable                $1,000,000
Dr. Deferred Loan Costs                $5,000
    Cr. Cash                                $1,000,000
    Cr. Deferred Loan Fees                     $20,000
```

**Interest and Fee Amortization (Year 1):**
```
Effective yield calculation: ~6.3%

Dr. Cash                              $60,000
Dr. Deferred Loan Fees                 $3,000
    Cr. Deferred Loan Costs                    $1,000
    Cr. Interest Income                       $62,000
```

---

### Example 2: CECL Allowance Calculation

**Facts—Commercial Loan Portfolio:**
- Total loans: $100,000,000
- Risk segments:
  - Pass: $80,000,000 (1.2% expected loss)
  - Watch: $15,000,000 (3.0% expected loss)
  - Substandard: $5,000,000 (10.0% expected loss)
- Qualitative adjustment: +0.2% (economic uncertainty)

**Calculation:**

| Segment | Balance | Loss Rate | Allowance |
|---------|---------|-----------|-----------|
| Pass | $80M | 1.4% | $1,120,000 |
| Watch | $15M | 3.2% | $480,000 |
| Substandard | $5M | 10.2% | $510,000 |
| **Total** | **$100M** | | **$2,110,000** |

**Journal Entry:**
```
Dr. Provision for Credit Losses     $2,110,000
    Cr. Allowance for Credit Losses         $2,110,000
```

---

### Example 3: Nonaccrual and Charge-Off

**Facts:**
- $500,000 loan placed on nonaccrual
- Accrued interest: $25,000
- Subsequent charge-off: $200,000 (collateral value $300,000)

**Place on Nonaccrual:**
```
Dr. Interest Income                   $25,000
    Cr. Interest Receivable                   $25,000
(Reverse previously accrued interest)
```

**Partial Charge-Off:**
```
Dr. Allowance for Credit Losses      $200,000
    Cr. Loans Receivable                     $200,000
```

**Remaining loan balance: $300,000 (collateral value)**

---

### Example 4: AFS Securities with Impairment

**Facts:**
- AFS bond: Amortized cost $100,000
- Fair value: $85,000
- Decline: $15,000
  - Credit-related: $5,000
  - Non-credit: $10,000

**Journal Entry (under CECL):**
```
Dr. Provision for Credit Losses       $5,000
    Cr. Allowance for Credit Losses—AFS      $5,000

Dr. OCI—Unrealized Loss              $10,000
    Cr. AFS Securities—FV Adjustment        $10,000
```

---

## Income Statement Presentation

### Net Interest Income Focus

```
FIRST NATIONAL BANK
Consolidated Statement of Income
For the Year Ended December 31, 20X1
(in thousands)

Interest income:
  Loans, including fees                    $48,000
  Securities                                 8,500
  Other                                      1,000
                                           -------
    Total interest income                   57,500

Interest expense:
  Deposits                                  18,000
  Borrowings                                 2,500
                                           -------
    Total interest expense                  20,500
                                           -------
Net interest income                         37,000

Provision for credit losses                  3,500
                                           -------
Net interest income after provision         33,500

Noninterest income:
  Service charges on deposits                2,500
  Trust and investment fees                  1,500
  Mortgage banking income                    1,000
  Other                                        500
                                           -------
    Total noninterest income                 5,500

Noninterest expense:
  Salaries and benefits                     12,000
  Occupancy                                  3,000
  Other                                      4,500
                                           -------
    Total noninterest expense               19,500
                                           -------
Income before income taxes                  19,500
Income tax expense                           4,875
                                           -------
Net income                                $14,625
                                           =======
```

---

## Private Company Considerations

### Community Banks

| Consideration | Impact |
|---------------|--------|
| **CECL complexity** | May use simpler methods |
| **Securities portfolio** | Often smaller, less complex |
| **Regulatory burden** | Proportionate to size |
| **S-Corp election** | Tax considerations |

### Credit Unions

| Difference | Impact |
|------------|--------|
| **Not-for-profit** | Member-owned structure |
| **Net worth** | Instead of equity |
| **Retained earnings** | Undivided earnings |
| **NCUA regulation** | Different from bank regulators |

---

## Common Audit Issues

### Loan Portfolio

| Issue | Audit Focus |
|-------|-------------|
| **Allowance adequacy** | Methodology, assumptions |
| **Loan classification** | Nonaccrual identification |
| **Collateral values** | Appraisals, support |
| **TDR identification** | Concession + difficulty (pre-ASU 2022-02) |

### Securities

| Issue | Consideration |
|-------|---------------|
| **Classification** | Intent and ability for HTM |
| **Fair value** | Pricing sources |
| **Impairment** | Credit vs. non-credit |
| **AOCI/capital impact** | Regulatory implications |

### Regulatory Compliance

| Issue | Focus |
|-------|-------|
| **Call report accuracy** | Agrees to GAAP financials |
| **Capital ratios** | Accurate computation |
| **BSA/AML** | Compliance programs |

---

## Disclosure Requirements

### Major Disclosures

| Area | Disclosure |
|------|------------|
| **Loans** | By type, nonaccrual, past due aging |
| **Allowance** | Rollforward, methodology |
| **Securities** | By type, maturity, fair value |
| **Deposits** | By type, maturity schedule |
| **Capital** | Regulatory ratios, requirements |
| **Interest rate risk** | Sensitivity analysis |

---

## Recent Updates

| ASU | Topic | Impact |
|-----|-------|--------|
| **ASU 2022-02** | TDR Elimination/Vintage | Major change for loan modifications |
| **ASU 2020-04** | Reference Rate Reform | LIBOR transition |
| **ASU 2019-04** | CECL Amendments | Clarifications |
| **ASU 2016-13** | CECL | Current expected credit loss model |

---

## External Resources

- [FASB ASC 942](https://asc.fasb.org/)
- [FASB ASC 326 (Credit Losses)](https://asc.fasb.org/)
- [Federal Reserve Supervision Manual](https://www.federalreserve.gov/)
- [OCC Comptroller's Handbook](https://www.occ.gov/)
- [FDIC Risk Management Manual](https://www.fdic.gov/)
- [AICPA Audit and Accounting Guide—Depository and Lending](https://www.aicpa.org/)
- [KPMG: Banking Accounting Guide](https://frv.kpmg.us/)
- [PwC: Banking and Capital Markets Guide](https://viewpoint.pwc.com/)
- [Deloitte: Banking Industry Updates](https://www.deloitte.com/)
- [EY: Banking Accounting Developments](https://www.ey.com/)

---

## Navigation

← [Back to Industry (900s)](README.md) | [Back to Main Guide](../../README.md)
