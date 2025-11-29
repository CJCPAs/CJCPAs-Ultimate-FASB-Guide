# ASC 980: Regulated Operations

> Specialized accounting for rate-regulated utilities and other regulated enterprises.

## Overview

ASC 980 provides guidance for entities whose rates are established by regulatory bodies and are designed to recover the entity's costs of providing service. This guidance allows recognition of regulatory assets and liabilities that would not be recognized under general GAAP.

> **Core Principle:** Rate-regulated entities may recognize regulatory assets and liabilities to match the economic effects of rate regulation, reflecting costs and revenues in the periods they are included in rates.

---

## Scope

### Applies To

- Electric utilities
- Gas utilities
- Water utilities
- Telecommunications (certain)
- Transportation (regulated)
- Other rate-regulated entities

### Criteria for Application

**All three criteria must be met:**

| Criterion | Description |
|-----------|-------------|
| **Rates established** | Third-party regulator or board sets rates |
| **Cost-based rates** | Rates designed to recover costs |
| **Rates charged and collected** | Reasonable assumption rates will be collected |

### Discontinuation

**Stop applying ASC 980 when:**
- Deregulation occurs
- Competition makes cost recovery unlikely
- Rate structure changes to non-cost-based

---

## Regulatory Assets

### Definition

Probable future revenue associated with costs incurred that will be recovered through rates charged to customers.

### Types of Regulatory Assets

| Type | Description |
|------|-------------|
| **Deferred costs** | Costs incurred, to be recovered later |
| **Deferred losses** | Losses deferred for rate recovery |
| **Under-recovered costs** | Current costs exceeding current rates |
| **Other** | Regulatory-directed deferrals |

### Recognition Criteria

Recognize regulatory asset when:
1. Costs incurred
2. Regulator has allowed or will allow recovery
3. Recovery is probable

### Journal Entry—Regulatory Asset

**Deferred storm damage costs allowed for recovery:**
```
Dr. Regulatory Asset—Storm Costs        $5,000,000
    Cr. Storm Damage Expense (or various)      $5,000,000
```

### Amortization

**When recovered through rates:**
```
Dr. Storm Damage Expense (or Regulatory Asset Amortization)  $500,000
    Cr. Regulatory Asset—Storm Costs                               $500,000
```

---

## Regulatory Liabilities

### Definition

Obligations to refund amounts to customers through reduced future rates or to incur costs in the future.

### Types of Regulatory Liabilities

| Type | Description |
|------|-------------|
| **Over-collected costs** | Collections exceeding costs |
| **Deferred gains** | Gains to be passed to customers |
| **Cost of removal** | Amounts collected for future removal costs |
| **Other** | Regulatory-directed deferrals |

### Journal Entry—Regulatory Liability

**Excess depreciation collected (cost of removal):**
```
Dr. Depreciation Expense               $1,000,000
    Cr. Accumulated Depreciation               $800,000
    Cr. Regulatory Liability—Cost of Removal   $200,000
```

---

## Rate-Making Process

### Key Concepts

| Term | Definition |
|------|------------|
| **Rate base** | Investment on which return is allowed |
| **Rate of return** | Allowed percentage return on rate base |
| **Test year** | Period used to determine rates |
| **Revenue requirement** | Total revenue needed to cover costs plus return |

### Revenue Requirement Formula

```
Revenue Requirement = Operating Expenses + Depreciation + Taxes + (Rate Base × Rate of Return)
```

---

## Accounting vs. Rate-Making Differences

### Timing Differences

| Item | GAAP Timing | Rate Recovery Timing |
|------|-------------|---------------------|
| **Pension costs** | Current expense | Future rate recovery |
| **Environmental costs** | Accrue when incurred | Recover when spent |
| **Major maintenance** | Expense as incurred | Amortized recovery |
| **Income taxes** | Current provision | Flow-through or normalize |

### Example—Pension Costs

**GAAP pension expense exceeds amount in rates:**
```
Dr. Pension Expense                    $2,000,000
    Cr. Pension Liability                      $2,000,000

Dr. Regulatory Asset—Deferred Pension    $500,000
    Cr. Pension Expense                          $500,000
```
*(Portion expected to be recovered in future rates)*

---

## Intercompany Profits

### Rate-Making Treatment

Profits on sales between regulated affiliates may be:
- Eliminated for rate-making
- Deferred as regulatory liability
- Allowed depending on regulatory rules

### Accounting

**If eliminated for rate-making:**
```
Dr. Intercompany Profit (Income)        $100,000
    Cr. Regulatory Liability                   $100,000
```

---

## Impairment and Discontinuation

### Impairment of Regulatory Assets

**Test when:**
- Regulatory changes
- Competition increases
- Cost recovery becomes uncertain

**If not probable of recovery:**
```
Dr. Regulatory Asset Impairment Loss   $10,000,000
    Cr. Regulatory Asset                      $10,000,000
```

### Discontinuation of ASC 980

**When no longer qualifying:**
1. Write off regulatory assets not recoverable
2. Write off regulatory liabilities
3. Recognize gains/losses in income
4. Apply general GAAP prospectively

**Journal Entry—Discontinuation:**
```
Dr. Loss on Discontinuation of Regulated Operations  $XX
Dr. Regulatory Liabilities                            $XX
    Cr. Regulatory Assets                                  $XX
```

---

## Allowance for Funds Used During Construction (AFUDC)

### Definition

Capitalized cost representing return on capital invested in construction projects.

### Components

| Component | Source |
|-----------|--------|
| **Debt AFUDC** | Interest on borrowed funds |
| **Equity AFUDC** | Return on equity funds |

### Accounting

**Capitalize AFUDC during construction:**
```
Dr. Construction Work in Progress       $500,000
    Cr. AFUDC—Debt (Interest Expense)          $200,000
    Cr. AFUDC—Equity (Other Income)            $300,000
```

### Rate Recovery

AFUDC is included in rate base when asset is placed in service, recovered through depreciation and return.

---

## Deferred Income Taxes

### Normalization vs. Flow-Through

| Method | Description |
|--------|-------------|
| **Normalization** | Deferred taxes recorded; rates reflect normalized taxes |
| **Flow-through** | No deferred taxes; rates reflect actual taxes paid |

### Normalization Requirements

Many regulators require normalization for:
- Accelerated depreciation
- Investment tax credits
- Other timing differences

**Journal Entry—Normalized Taxes:**
```
Dr. Income Tax Expense                 $1,000,000
    Cr. Current Income Tax Payable             $600,000
    Cr. Deferred Income Tax Liability          $400,000
```

### Excess Deferred Income Taxes

**From Tax Cuts and Jobs Act rate reduction:**
```
Dr. Deferred Income Tax Liability      $5,000,000
    Cr. Regulatory Liability—Excess ADIT       $5,000,000
```
*(To be refunded to customers)*

---

## Practical Example: Electric Utility

### Rate Case Filing

**Revenue requirement components:**
| Component | Amount |
|-----------|--------|
| Operating expenses | $50,000,000 |
| Depreciation | $15,000,000 |
| Taxes | $8,000,000 |
| Return (Rate base $200M × 10%) | $20,000,000 |
| **Total revenue requirement** | **$93,000,000** |

### Regulatory Asset Example

**Storm restoration costs ($3M) allowed for 3-year recovery:**

*Year 1—Costs incurred:*
```
Dr. Regulatory Asset—Storm Costs        $3,000,000
    Cr. Various Expense Accounts               $3,000,000
```

*Years 1-3—Recovery:*
```
Dr. Operating Expenses (Storm recovery)  $1,000,000
    Cr. Regulatory Asset—Storm Costs           $1,000,000
```

---

## Disclosure Requirements

### Required Disclosures

1. **Regulatory assets and liabilities** by type
2. **Remaining recovery/refund periods**
3. **Rate actions** affecting amounts
4. **Discontinuation risks**
5. **AFUDC** components and rates

### Example Disclosure

> **Regulatory Assets and Liabilities:** The Company's rates are established by the State Public Utilities Commission based on historical costs. Accordingly, the Company applies the provisions of ASC 980 and records regulatory assets and liabilities that reflect the economic effects of rate regulation.
>
> The following regulatory assets and liabilities were recorded as of December 31, 20XX:
>
> | Regulatory Assets | Amount |
> |-------------------|--------|
> | Deferred storm costs | $X million |
> | Deferred pension costs | $X million |
> | Environmental remediation | $X million |
> | **Total** | **$X million** |

---

## FERC vs. State Regulation

### Federal Energy Regulatory Commission (FERC)

- Regulates interstate transmission
- Wholesale power sales
- Natural gas pipelines

### State Public Utility Commissions

- Retail rate setting
- Distribution rates
- Service territory

### Accounting Implications

Different regulators may require different treatments—must track by jurisdiction.

---

## Common Audit Issues

1. **Probability of recovery** — Support for regulatory asset recognition
2. **Regulatory orders** — Documentation of rate decisions
3. **Impairment** — Assessment when conditions change
4. **AFUDC rates** — Calculations and methodology
5. **Intercompany** — Proper eliminations for rate-making
6. **Deferred taxes** — Normalization requirements
7. **Disclosure completeness** — All significant items disclosed

---

## External Resources

- [FASB ASC 980](https://asc.fasb.org/)
- [Federal Energy Regulatory Commission](https://www.ferc.gov/)
- [National Association of Regulatory Utility Commissioners](https://www.naruc.org/)
- [Edison Electric Institute](https://www.eei.org/)
- [AICPA Utilities Industry Guide](https://www.aicpa.org/)

---

## Navigation

← [Back to Industry (900s)](README.md) | [Main Guide](../../README.md)
