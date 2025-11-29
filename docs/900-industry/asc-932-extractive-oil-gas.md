# ASC 932: Extractive Activities—Oil and Gas

> Specialized accounting for oil and gas exploration, development, and production.

## Overview

ASC 932 provides industry-specific guidance for oil and gas producing companies, addressing the unique accounting challenges of exploration, development, and production activities. The standard allows two primary accounting methods: **full cost** and **successful efforts**.

> **Core Principle:** Oil and gas companies must consistently apply either the full cost method or successful efforts method to account for costs associated with finding and developing oil and gas reserves.

---

## Scope

### Applies To

- Oil and gas exploration companies
- Production companies
- Integrated oil companies
- Independent producers
- Royalty owners (certain aspects)

### Activities Covered

| Activity | Description |
|----------|-------------|
| **Acquisition** | Mineral rights, leases |
| **Exploration** | Geological studies, drilling exploratory wells |
| **Development** | Drilling production wells, facilities |
| **Production** | Lifting, gathering, processing |

---

## Two Accounting Methods

### Full Cost Method

**All costs capitalized** to a cost center (typically by country):
- Successful and unsuccessful exploration
- Acquisition costs
- Development costs

**Subject to ceiling test for impairment**

### Successful Efforts Method

**Only successful exploration capitalized:**
- Unsuccessful exploration expensed
- Only costs of successful wells capitalized
- Property-by-property accounting

### Comparison

| Aspect | Full Cost | Successful Efforts |
|--------|-----------|-------------------|
| Dry holes | Capitalize | Expense |
| Geological costs | Capitalize | Expense |
| Cost center | Country/large pools | Property/field |
| Earnings volatility | Lower | Higher |
| Commonly used by | Smaller companies | Major oil companies |

---

## Acquisition Costs

### Unproved Properties

**Both methods:** Capitalize costs to acquire mineral interests in unproved properties:
- Lease bonuses
- Lease rentals (before drilling)
- Brokers' fees

**Journal Entry:**
```
Dr. Unproved Oil & Gas Properties       $1,000,000
    Cr. Cash                                   $1,000,000
```

### Proved Properties

Costs to acquire proved reserves:
- Purchase price allocated to reserves
- Fair value of proved reserves acquired

---

## Exploration Costs

### Types of Costs

| Cost Type | Full Cost | Successful Efforts |
|-----------|-----------|-------------------|
| Geological studies | Capitalize | Expense |
| Geophysical costs (seismic) | Capitalize | Expense |
| Carrying costs (delay rentals) | Capitalize | Expense |
| Exploratory drilling | Capitalize | Capitalize initially |

### Successful Efforts—Exploratory Wells

**Initially capitalize all drilling costs:**
```
Dr. Exploratory Wells in Progress       $5,000,000
    Cr. Cash                                   $5,000,000
```

**If successful (proved reserves found):**
```
Dr. Proved Oil & Gas Properties         $5,000,000
    Cr. Exploratory Wells in Progress          $5,000,000
```

**If unsuccessful (dry hole):**
```
Dr. Dry Hole Expense                    $5,000,000
    Cr. Exploratory Wells in Progress          $5,000,000
```

### Wells in Progress

**Continue to capitalize** exploratory well costs while:
1. Drilling continues
2. Sufficient reserves found, but classification pending
3. Active work ongoing to assess commerciality

---

## Development Costs

### Both Methods—Capitalize

Development costs are capitalized under both methods:
- Development wells (productive or dry)
- Platforms, facilities
- Equipment
- Enhanced recovery systems

**Journal Entry:**
```
Dr. Oil & Gas Properties—Development   $10,000,000
    Cr. Cash                                  $10,000,000
```

---

## Depreciation, Depletion, and Amortization (DD&A)

### Unit-of-Production Method

**Formula:**
```
DD&A Rate = (Capitalized Costs + Future Development Costs) / (Proved Reserves)

Period DD&A = DD&A Rate × Production
```

### Example Calculation

| Item | Amount |
|------|--------|
| Capitalized costs | $100,000,000 |
| Estimated future development | $20,000,000 |
| Proved reserves | 10,000,000 barrels |
| Period production | 500,000 barrels |

**DD&A Rate:** ($100M + $20M) / 10M = $12 per barrel

**Period DD&A:** 500,000 × $12 = $6,000,000

**Journal Entry:**
```
Dr. DD&A Expense                        $6,000,000
    Cr. Accumulated DD&A                       $6,000,000
```

---

## Full Cost Ceiling Test

### Purpose

Prevent carrying costs in excess of value of reserves.

### Ceiling Calculation

```
Ceiling = PV of Future Net Revenues (proved reserves, 10% discount)
        + Cost of unproved properties excluded from amortization
        + Lower of cost or FV of unproved properties included
        − Income tax effects
```

### Impairment Test

**If Net Capitalized Costs > Ceiling:**
- Write down to ceiling
- Impairment is permanent (no reversal)

**Journal Entry:**
```
Dr. Ceiling Test Write-Down            $20,000,000
    Cr. Oil & Gas Properties                  $20,000,000
```

### Pricing for Ceiling Test

Use **12-month average prices** (first-day-of-month prices for prior 12 months)

---

## Successful Efforts Impairment

### Unproved Properties

Test for impairment when:
- Lease about to expire
- No planned drilling
- Adverse geological information

### Proved Properties

Apply ASC 360 impairment model:
1. **Triggering event** occurs
2. **Recoverability test** (undiscounted cash flows)
3. **Measure impairment** (FV if not recoverable)

---

## Asset Retirement Obligations (ARO)

### Applicability

Oil and gas companies have significant AROs for:
- Well plugging and abandonment
- Platform removal
- Site restoration

### Accounting (ASC 410)

**Initial Recognition:**
```
Dr. Oil & Gas Properties (ARO asset)    $5,000,000
    Cr. Asset Retirement Obligation            $5,000,000
```

**Accretion Expense:**
```
Dr. Accretion Expense                   $250,000
    Cr. Asset Retirement Obligation            $250,000
```

**Depreciation of ARO Asset:**
- Include in DD&A base
- Amortize using unit-of-production

---

## Revenue Recognition

### Types of Revenue

| Type | Recognition |
|------|-------------|
| Oil and gas sales | When delivered and title transfers |
| Royalties | As underlying production occurs |
| Gas imbalances | Various methods |

### Gas Balancing Methods

When partners take more/less than entitled share:

| Method | Treatment |
|--------|-----------|
| **Sales method** | Revenue when sold |
| **Entitlement method** | Revenue based on ownership interest |

---

## Joint Interest Operations

### Common in Industry

Most properties operated through joint ventures:
- One operator, multiple working interest owners
- Operator bills partners (joint interest billing)

### Accounting

**As operator:**
```
Dr. Oil & Gas Properties               $1,000,000
Dr. Joint Interest Receivable          $4,000,000
    Cr. Cash                                   $5,000,000
```
*(Operator has 20% interest)*

**As non-operator:**
```
Dr. Oil & Gas Properties               $1,000,000
    Cr. Cash                                   $1,000,000
```

---

## Disclosure Requirements

### Required Disclosures

1. **Method used** (full cost or successful efforts)
2. **Capitalized costs** by category
3. **Costs incurred** during period
4. **Results of operations** for O&G activities
5. **Reserve quantities** (proved reserves)
6. **Standardized measure** of discounted future cash flows

### Supplementary Information

| Disclosure | Description |
|------------|-------------|
| Reserve quantities | Beginning, revisions, discoveries, production, ending |
| Standardized measure | PV of future cash flows at 10% discount |
| Changes in standardized measure | Reconciliation |

---

## Practical Example

### Successful Efforts Company—Year 1

**Activities:**
- Acquired lease: $500,000
- Geological studies: $100,000
- Drilled 3 exploratory wells: $15,000,000
- 2 successful, 1 dry

**Journal Entries:**

*Lease acquisition:*
```
Dr. Unproved Properties                  $500,000
    Cr. Cash                                    $500,000
```

*Geological studies:*
```
Dr. Exploration Expense                  $100,000
    Cr. Cash                                    $100,000
```

*Drilling costs (initially):*
```
Dr. Wells in Progress                 $15,000,000
    Cr. Cash                                  $15,000,000
```

*Reclassification after results:*
```
Dr. Proved Properties ($5M × 2)        $10,000,000
Dr. Dry Hole Expense                    $5,000,000
    Cr. Wells in Progress                     $15,000,000
```

---

## Common Audit Issues

1. **Reserve estimates** — Support for proved reserve quantities
2. **Ceiling test** — Price calculations, cost inclusions
3. **Well status** — Proved vs. unproved classification
4. **Impairment timing** — Delayed recognition of dry holes
5. **ARO estimates** — Assumptions, discount rates
6. **DD&A rates** — Reserve revisions, cost pool accuracy
7. **Joint interest** — Billing accuracy, cutoff

---

## Regulatory Considerations

### SEC Requirements

- Definition of proved reserves
- Oil and gas reserve estimation rules
- Supplementary disclosures required
- Ceiling test pricing rules

### FASB vs. SEC

Some guidance originates from SEC (Regulation S-X Rule 4-10) rather than FASB.

---

## External Resources

- [FASB ASC 932](https://asc.fasb.org/)
- [SEC Regulation S-X, Rule 4-10](https://www.sec.gov/)
- [Society of Petroleum Engineers](https://www.spe.org/)
- [AICPA Oil and Gas Entities Guide](https://www.aicpa.org/)
- [KPMG: Oil and Gas Handbook](https://frv.kpmg.us/)

---

## Navigation

← [Back to Industry (900s)](README.md) | [Main Guide](../../README.md)
