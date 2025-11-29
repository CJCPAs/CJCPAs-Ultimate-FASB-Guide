# ASC 944: Financial Services—Insurance

> Specialized accounting guidance for insurance and reinsurance entities.

## Overview

ASC 944 provides comprehensive accounting guidance for insurance entities, covering life and property/casualty insurance contracts, reinsurance, and related activities. Insurance accounting is highly specialized with unique concepts for loss reserving, premium recognition, and deferred acquisition costs.

**Core Principle:**
> "Insurance contracts create obligations to provide coverage and services, with premiums recognized over the coverage period and liabilities established for future policy benefits and claims."

---

## Scope

### Applies To:
- Life insurance contracts
- Property and casualty insurance contracts
- Reinsurance contracts
- Title insurance
- Mortgage guaranty insurance
- Financial guarantee insurance

### Does NOT Apply To:
- Self-insurance (ASC 720)
- Product warranties (ASC 460)
- Service contracts accounted for under ASC 606
- Investments (ASC 320, 321)

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Insurance Contract** | Agreement that transfers insurance risk |
| **Premium** | Consideration paid for insurance coverage |
| **Loss Reserve** | Estimated liability for unpaid claims |
| **IBNR** | Incurred But Not Reported—claims reserve |
| **DAC** | Deferred Acquisition Costs |
| **Reinsurance** | Transfer of risk from one insurer to another |
| **Ceding Company** | Insurer that transfers risk |
| **Assuming Company** | Reinsurer that accepts risk |

---

## Insurance Contract Classification

### Short-Duration Contracts

| Characteristic | Description |
|----------------|-------------|
| **Coverage period** | Fixed, usually one year or less |
| **Cancellation** | Either party can cancel |
| **Repricing** | Premiums can change at renewal |
| **Examples** | Auto, homeowners, commercial property |

### Long-Duration Contracts

| Characteristic | Description |
|----------------|-------------|
| **Coverage period** | Extended, often lifetime |
| **Cancellation** | Generally not cancelable by insurer |
| **Pricing** | Generally fixed or guaranteed |
| **Examples** | Whole life, term life, annuities |

---

## Premium Revenue Recognition

### Short-Duration Contracts

**Earned ratably over coverage period:**

```
Dr. Cash/Premium Receivable        $12,000
    Cr. Unearned Premium                    $12,000
(Annual premium received)

Dr. Unearned Premium                $1,000
    Cr. Premium Revenue                      $1,000
(Monthly recognition)
```

### Long-Duration Contracts

**Recognition varies by contract type:**

| Contract Type | Recognition |
|---------------|-------------|
| **Traditional life** | Over premium-paying period |
| **Universal life** | As amounts assessed |
| **Annuities (deferred)** | Not revenue (deposit) |
| **Annuities (immediate)** | Over payout period |

---

## Loss Reserves (Short-Duration)

### Components

| Reserve Type | Description |
|--------------|-------------|
| **Case reserves** | Known claims, estimated amounts |
| **IBNR** | Incurred but not reported |
| **LAE** | Loss adjustment expenses |
| **Salvage/subrogation** | Recoveries to offset |

### Recognition

```
Dr. Loss and LAE Expense          $500,000
    Cr. Loss and LAE Reserve               $500,000
(Accrual for incurred losses)
```

### Estimation Methods

| Method | Description |
|--------|-------------|
| **Case-by-case** | Individual claim estimates |
| **Loss development** | Historical patterns |
| **Expected loss ratio** | Based on earned premium |
| **Bornhuetter-Ferguson** | Combination method |

---

## Policy Liabilities (Long-Duration)

### Benefit Reserves

For traditional contracts:
```
Liability = PV of Future Benefits - PV of Future Net Premiums
```

### Policyholder Account Balances

For universal life and similar:
```
Balance = Premiums + Interest Credits - Charges - Withdrawals
```

### Journal Entry

```
Dr. Benefit Expense               $100,000
    Cr. Policy Benefit Liability          $100,000
(Increase in long-duration reserve)
```

---

## Deferred Acquisition Costs (DAC)

### What Is Capitalized

| Cost Type | Capitalize? |
|-----------|-------------|
| **Agent commissions** | Yes |
| **Underwriting costs** | Yes (direct) |
| **Policy issuance** | Yes (direct) |
| **Advertising** | Generally no |
| **General overhead** | No |

### Amortization

**Short-Duration:**
```
Amortize over policy coverage period (with premium)
```

**Long-Duration:**
```
Amortize over benefit period or premium-paying period
```

### Journal Entries

**Capitalize:**
```
Dr. Deferred Acquisition Costs    $50,000
    Cr. Cash/Payables                      $50,000
```

**Amortize:**
```
Dr. Amortization Expense          $10,000
    Cr. Deferred Acquisition Costs         $10,000
```

---

## Reinsurance

### Types of Reinsurance

| Type | Description |
|------|-------------|
| **Treaty** | Automatic coverage for defined risks |
| **Facultative** | Individual risk placement |
| **Quota share** | Proportional sharing |
| **Excess of loss** | Non-proportional; covers above retention |

### Ceding Company Accounting

**Ceded premiums:**
```
Dr. Ceded Premium Expense         $100,000
    Cr. Reinsurance Payable               $100,000
```

**Ceded losses:**
```
Dr. Reinsurance Recoverable       $75,000
    Cr. Ceded Losses Recovered            $75,000
```

### Presentation

| Item | Presentation |
|------|--------------|
| **Reinsurance recoverable** | Asset (not offset against reserves) |
| **Ceded premiums** | Reduction of premium revenue |
| **Ceded losses** | Reduction of loss expense |

---

## Long-Duration Contract Updates (ASU 2018-12)

### Key Changes (LDTI)

| Area | Change |
|------|--------|
| **Liability measurement** | Updated assumptions |
| **DAC amortization** | Simplified—straight-line |
| **Market risk benefits** | Fair value |
| **Disclosures** | Enhanced |

### Effective Dates

| Entity Type | Effective |
|-------------|-----------|
| **SEC filers (large)** | 2023 |
| **Other SEC filers** | 2025 |
| **All others** | 2025 |

---

## Practical Examples

### Example 1: Short-Duration Premium Recognition

**Facts:**
- Annual premium: $120,000
- Policy period: January 1 - December 31
- Commission: $15,000 (paid at inception)

**At Inception:**
```
Dr. Cash                          $120,000
Dr. Deferred Acquisition Costs     $15,000
    Cr. Unearned Premium                   $120,000
    Cr. Cash (commission)                   $15,000
```

**Monthly:**
```
Dr. Unearned Premium               $10,000
    Cr. Premium Revenue                     $10,000

Dr. Amortization Expense            $1,250
    Cr. Deferred Acquisition Costs          $1,250
```

---

### Example 2: Loss Reserve Calculation

**Facts—Auto Insurance Portfolio:**

| Development Year | Paid Losses | Case Reserves | Ultimate Est. |
|------------------|-------------|---------------|---------------|
| 2020 | $800,000 | $50,000 | $875,000 |
| 2021 | $1,000,000 | $150,000 | $1,250,000 |
| 2022 | $600,000 | $400,000 | $1,500,000 |

**Loss Reserve Calculation:**
```
2020: $875,000 - $800,000 = $75,000
2021: $1,250,000 - $1,000,000 = $250,000
2022: $1,500,000 - $600,000 = $900,000
Total Reserve: $1,225,000
```

---

### Example 3: Reinsurance Transaction

**Facts:**
- Direct premium written: $5,000,000
- Quota share reinsurance: 30% ceded
- Losses incurred: $3,000,000

**Ceded Premium:**
```
Dr. Ceded Premium Expense        $1,500,000
    Cr. Reinsurance Payable              $1,500,000
($5,000,000 × 30%)
```

**Ceded Losses:**
```
Dr. Reinsurance Recoverable        $900,000
    Cr. Ceded Losses                       $900,000
($3,000,000 × 30%)
```

---

## Financial Statement Presentation

### Balance Sheet—Insurance Company

```
ASSETS
  Investments                          $50,000,000
  Reinsurance recoverable               5,000,000
  Premium receivable                    3,000,000
  Deferred acquisition costs            2,000,000
  Other assets                          2,000,000
                                      -----------
    Total assets                      $62,000,000

LIABILITIES
  Loss and LAE reserves               $25,000,000
  Unearned premium                      8,000,000
  Policy benefit liabilities           10,000,000
  Reinsurance payable                   1,000,000
  Other liabilities                     2,000,000
                                      -----------
    Total liabilities                  46,000,000

EQUITY
  Common stock                          5,000,000
  Retained earnings                    11,000,000
                                      -----------
    Total equity                       16,000,000
                                      -----------
    Total liabilities and equity      $62,000,000
```

---

## Regulatory Accounting (SAP)

### GAAP vs. Statutory

| Item | GAAP | Statutory |
|------|------|-----------|
| **DAC** | Capitalized | Expensed |
| **Investments** | Various | Mostly amortized cost |
| **Reinsurance** | Asset | Offset allowed |
| **Non-admitted assets** | Included | Excluded |
| **Policy reserves** | Net premium | Gross premium |

### Reconciliation Required

Insurance companies typically reconcile GAAP equity to statutory surplus.

---

## Common Audit Issues

### Loss Reserves

| Issue | Consideration |
|-------|---------------|
| **Estimation** | Methodology appropriateness |
| **Data quality** | Completeness and accuracy |
| **Assumptions** | Reasonableness |
| **Trends** | Development patterns |

### DAC

| Issue | Focus |
|-------|-------|
| **Costs capitalized** | Only allowable costs |
| **Amortization** | Proper pattern |
| **Recoverability** | Premium deficiency |

### Reinsurance

| Issue | Consideration |
|-------|---------------|
| **Risk transfer** | Does contract transfer risk? |
| **Collectibility** | Reinsurer credit quality |
| **Cut-through** | Proper recognition |

---

## Disclosure Requirements

### Required Disclosures

| Area | Disclosure |
|------|------------|
| **Loss reserves** | Rollforward, development |
| **Reinsurance** | Concentrations, recoverables |
| **DAC** | Balances, amortization |
| **Investments** | Fair value, credit quality |
| **Risk** | Insurance risk, credit risk |

---

## Recent Updates

| ASU | Topic | Impact |
|-----|-------|--------|
| **ASU 2018-12** | LDTI | Major long-duration changes |
| **ASU 2019-09** | LDTI Effective Date | Deferred adoption |
| **ASU 2020-11** | LDTI Amendments | Targeted improvements |

---

## External Resources

- [FASB ASC 944](https://asc.fasb.org/)
- [NAIC Statutory Accounting Principles](https://www.naic.org/)
- [Casualty Actuarial Society](https://www.casact.org/)
- [Society of Actuaries](https://www.soa.org/)
- [KPMG: Insurance Accounting Guide](https://frv.kpmg.us/)
- [PwC: Insurance Industry Guide](https://viewpoint.pwc.com/)
- [Deloitte: Insurance Industry Updates](https://www.deloitte.com/)

---

## Navigation

← [Back to Industry (900s)](README.md) | [Back to Main Guide](../../README.md)
