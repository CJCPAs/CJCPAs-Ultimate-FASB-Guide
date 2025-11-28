# ASC 842: Leases

> The comprehensive lease accounting standard requiring recognition of most leases on the balance sheet.

## Overview

ASC 842 fundamentally changed lease accounting by requiring lessees to recognize most leases on the balance sheet as a right-of-use (ROU) asset and lease liability. This provides more transparency about lease obligations.

**Core Principle:**
A lessee should recognize assets and liabilities for leases with a term of more than 12 months.

---

## Scope

### Applies To:
- Leases of property, plant, and equipment
- Subleases
- Sale and leaseback transactions

### Does NOT Apply To:
- Leases of intangible assets (ASC 350)
- Leases to explore for or use natural resources (ASC 930, 932)
- Leases of biological assets (ASC 905)
- Leases of inventory (ASC 330)
- Leases of assets under construction (ASC 360)
- Service concession arrangements (ASC 853)

---

## Effective Dates

| Entity Type | Effective Date |
|-------------|----------------|
| Public business entities | Fiscal years beginning after 12/15/2018 |
| All other entities | Fiscal years beginning after 12/15/2021 |

---

## Key Definitions

### Lease Definition

A contract (or part of a contract) that conveys the right to control the use of identified property, plant, or equipment (an identified asset) for a period of time in exchange for consideration.

**Two Key Questions:**

| Question | Consideration |
|----------|---------------|
| Is there an identified asset? | Explicitly or implicitly specified; supplier cannot have substantive substitution right |
| Does customer control use? | Right to obtain substantially all economic benefits AND right to direct use |

### Lease Term

The non-cancelable period plus:
- Periods covered by renewal options the lessee is reasonably certain to exercise
- Periods covered by termination options the lessee is reasonably certain NOT to exercise
- Periods where landlord has option to extend (if reasonably certain to exercise)

### Lease Payments

Include:
- Fixed payments (less lease incentives)
- Variable payments based on index or rate
- Exercise price of purchase option (if reasonably certain)
- Payments for penalties for terminating (if lease term reflects termination)
- Residual value guarantees expected to be paid

---

## Lessee Accounting

### Recognition

At commencement date, recognize:
1. **Right-of-Use (ROU) Asset** = Lease liability + Initial direct costs + Prepaid lease payments - Lease incentives received
2. **Lease Liability** = Present value of lease payments

### Classification

| Type | Criteria (any ONE) |
|------|-------------------|
| **Finance Lease** | Transfer of ownership at end |
| | Purchase option reasonably certain to be exercised |
| | Lease term is major part of remaining economic life (≈75%) |
| | Present value of payments is substantially all of fair value (≈90%) |
| | Asset is specialized with no alternative use to lessor |
| **Operating Lease** | Does not meet any finance lease criteria |

### Subsequent Measurement

**Finance Lease:**

| Component | Measurement |
|-----------|-------------|
| ROU Asset | Amortize (typically straight-line) |
| Lease Liability | Effective interest method |
| Expense Pattern | Front-loaded (interest + amortization) |

**Operating Lease:**

| Component | Measurement |
|-----------|-------------|
| ROU Asset | Calculated to achieve straight-line expense |
| Lease Liability | Effective interest method |
| Expense Pattern | Straight-line single lease expense |

### Journal Entries

**At Commencement (Operating Lease):**
```
Dr. Right-of-Use Asset           $XXX
    Cr. Lease Liability                  $XXX
```

**Monthly Payment (Operating Lease):**
```
Dr. Lease Expense                $XXX
    Cr. Lease Liability                  $XXX (principal)
    Cr. Cash                             $XXX (payment)
```

**Note:** For operating leases, the ROU asset is adjusted so that lease expense is straight-line.

---

## Lessor Accounting

### Classification

| Type | Criteria |
|------|----------|
| **Sales-Type Lease** | Meets ANY finance lease criterion from lessee perspective |
| **Direct Financing Lease** | Does not meet sales-type criteria BUT present value of payments + residual = substantially all of fair value AND probable collection |
| **Operating Lease** | Does not meet sales-type or direct financing criteria |

### Accounting Treatment

**Sales-Type Lease:**
- Derecognize asset
- Recognize net investment in lease (receivable + unguaranteed residual)
- Recognize selling profit/loss upfront
- Recognize interest income over lease term

**Direct Financing Lease:**
- Derecognize asset
- Recognize net investment in lease
- Defer selling profit in net investment
- Recognize interest income over lease term

**Operating Lease:**
- Continue to recognize asset
- Depreciate asset
- Recognize lease income (generally straight-line)

---

## Short-Term Lease Exception

### Policy Election

Lessees may elect to not recognize ROU assets and lease liabilities for leases with:
- Lease term of 12 months or less at commencement
- No purchase option the lessee is reasonably certain to exercise

**Apply:** By class of underlying asset

**If Elected:** Recognize lease payments as expense (generally straight-line)

---

## Practical Expedients

### Transition Practical Expedients (Package)

Entities may elect to not reassess:
1. Whether expired/existing contracts are or contain leases
2. Lease classification for expired/existing leases
3. Initial direct costs for existing leases

### Ongoing Practical Expedients

| Expedient | Description | Available To |
|-----------|-------------|--------------|
| **Combine lease and non-lease components** | Account for as single lease component | Lessees (by class) and lessors |
| **Risk-free discount rate** | Use risk-free rate instead of incremental borrowing rate | Private companies and nonprofits |
| **Portfolio approach** | Apply to portfolio of leases with similar characteristics | All entities |

---

## Variable Lease Payments

### Types

| Type | Treatment |
|------|-----------|
| **Based on index or rate** | Include in lease liability using rate at commencement |
| **Based on usage or performance** | Recognize in expense when incurred |

### Common Examples

- **CPI adjustments** — Include in lease liability (based on index)
- **Percentage of sales** — Expense as incurred (performance-based)
- **Property taxes/insurance passed through** — Often non-lease components

---

## Lease Modifications

### Definition

A change not part of original terms—e.g., adding space, extending term, changing payments.

### Accounting

| Scenario | Treatment |
|----------|-----------|
| Adds right of use for separate lease | Account for as separate lease |
| Other modifications | Remeasure lease liability and adjust ROU asset |

### Remeasurement Events

- Change in lease term (reassess options)
- Change in probability of purchase option exercise
- Change in amounts probable of being owed under residual value guarantee
- Change in payments resulting from index or rate changes

---

## Sale and Leaseback Transactions

### If Sale Qualifies (Transfer of Control Under ASC 606)

**Seller-Lessee:**
- Derecognize asset
- Recognize ROU asset (based on retained right)
- Recognize lease liability
- Recognize gain/loss only on rights transferred

**Buyer-Lessor:**
- Apply acquisition guidance
- Apply lessor accounting

### If Sale Does NOT Qualify

**Seller-Lessee:**
- Continue to recognize asset
- Account for proceeds as financing liability

---

## Disclosure Requirements

### Lessees

**Qualitative:**
- Nature of leases (description, basis for variable payments, existence of options)
- Significant assumptions and judgments

**Quantitative:**
- Finance lease cost (amortization, interest)
- Operating lease cost
- Short-term lease cost
- Variable lease cost
- Sublease income
- Cash paid for leases
- ROU assets obtained in exchange for lease liabilities
- Weighted-average remaining lease term
- Weighted-average discount rate
- Maturity analysis of lease liabilities

### Lessors

- Nature of leases
- Significant assumptions and judgments
- Table of lease income by component
- Maturity analysis of lease receivables
- Information about residual assets

---

## Practical Examples

### Example 1: Operating Lease Recognition

**Facts:**
- 5-year building lease
- Annual payments: $100,000 (paid at year-end)
- Lessee's incremental borrowing rate: 5%
- No purchase option, renewal option, or residual guarantee

**Calculate Lease Liability:**

Present value of 5 payments of $100,000 at 5%:
$100,000 × 4.3295 = $432,948

**At Commencement:**
```
Dr. Right-of-Use Asset           $432,948
    Cr. Lease Liability                  $432,948
```

**Year 1:**

| Period | Beginning Liability | Interest (5%) | Payment | Ending Liability |
|--------|--------------------:|-------------:|--------:|----------------:|
| Year 1 | $432,948 | $21,647 | $100,000 | $354,595 |

Annual Lease Expense (straight-line): $100,000

**Year 1 Entry:**
```
Dr. Lease Expense                $100,000
    Cr. Lease Liability                  $78,353
    Cr. Right-of-Use Asset               $21,647
```

**Note:** The ROU asset adjustment ensures straight-line expense.

---

### Example 2: Finance Lease Recognition

**Facts:**
- 5-year equipment lease
- Annual payments: $50,000 (paid at year-end)
- Purchase option at end: $5,000 (reasonably certain to exercise)
- Lessee's incremental borrowing rate: 6%
- Fair value of equipment: $230,000

**Calculate Lease Liability:**

Present value at 6%:
- 5 payments of $50,000: $50,000 × 4.2124 = $210,618
- Purchase option: $5,000 × 0.7473 = $3,737
- **Total:** $214,355

**At Commencement:**
```
Dr. Right-of-Use Asset           $214,355
    Cr. Lease Liability                  $214,355
```

**Year 1:**

Interest: $214,355 × 6% = $12,861
Amortization: $214,355 / 5 years = $42,871

```
Dr. Interest Expense             $12,861
Dr. Amortization Expense         $42,871
    Cr. Lease Liability                  $37,139
    Cr. Accumulated Amortization         $42,871
    Cr. Cash                             $50,000
```

---

## Private Company Considerations

### Risk-Free Rate Practical Expedient

Private companies may use a risk-free discount rate (e.g., US Treasury rate) instead of incremental borrowing rate.

**Considerations:**
- Simpler to determine
- Generally results in higher lease liability (lower discount rate)
- Apply by class of underlying asset

### Common Control Lease Arrangements (ASU 2023-01)

Private companies can:
- Use written terms and conditions to determine whether lease exists
- Account for leasehold improvements over useful life (rather than shorter of useful life and lease term) if certain criteria met

### Related-Party Leases

Key considerations:
- Determine if arrangement is a lease
- Use written terms (not legally enforceable terms) per ASU 2023-01
- Consider if terms are at arm's length

---

## Common Implementation Issues

1. **Lease Identification** — Missing embedded leases in service contracts
2. **Discount Rate** — Using wrong rate or inconsistent rates
3. **Lease Term** — Not properly evaluating renewal options
4. **Lease vs. Non-Lease Components** — Improper allocation
5. **Variable Payments** — Including usage-based payments in liability
6. **Modifications** — Not remeasuring when required

---

## Embedded Leases

### When Service Contract May Contain Lease

Evaluate if supplier provides use of identified asset that customer controls.

**Examples:**
- Dedicated equipment in outsourcing arrangements
- Specified data center space
- Vehicle in transportation contract

**If Embedded Lease Exists:**
- Separate lease and non-lease components
- Apply ASC 842 to lease component

---

## External Resources

- [FASB ASC 842](https://asc.fasb.org/)
- [FASB Lease Implementation Q&As](https://www.fasb.org/)
- [KPMG: Handbook—Leases](https://frv.kpmg.us/)
- [PwC: Leases Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Applying the New Leasing Standard](https://www.iasplus.com/en-us)
- [EY: Lease Accounting Guide](https://www.ey.com/)

---

## Navigation

← [Back to Liabilities (400s)](README.md) | [Back to Main Guide](../../README.md)
