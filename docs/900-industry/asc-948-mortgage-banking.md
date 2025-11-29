# ASC 948: Financial Services—Mortgage Banking

> Specialized accounting for mortgage banking activities including loan origination, sales, and servicing.

## Overview

ASC 948 provides industry-specific guidance for mortgage banking activities, addressing the accounting for mortgage loan origination, acquisition, sale, and servicing. This guidance is critical for understanding the complex economics of the mortgage industry.

> **Core Principle:** Mortgage bankers must properly account for loans held for sale at fair value or lower of cost or fair value, and recognize servicing rights as assets when retained in loan sales.

---

## Scope

### Applies To

- Mortgage banks
- Commercial banks (mortgage operations)
- Savings institutions
- Credit unions
- Non-bank mortgage lenders

### Key Activities

| Activity | Key Issues |
|----------|------------|
| **Loan origination** | Fees, costs, classification |
| **Loans held for sale** | Measurement, fair value option |
| **Loan sales** | Gain/loss, servicing rights |
| **Servicing** | Asset recognition, amortization |

---

## Loan Origination

### Classification at Origination

| Intent | Classification |
|--------|---------------|
| Sell in secondary market | Held for sale |
| Hold to maturity | Held for investment |
| Trading portfolio | Trading |

### Origination Fees and Costs

**Direct loan origination costs:**
- Loan officer compensation
- Credit evaluation costs
- Appraisal costs

**Treatment depends on classification:**

| Classification | Fee/Cost Treatment |
|----------------|-------------------|
| Held for sale | Include in loan basis |
| Held for investment | Defer, amortize over loan life |

---

## Loans Held for Sale

### Measurement Options

| Method | Description |
|--------|-------------|
| **Lower of cost or fair value (LOCOM)** | Traditional approach |
| **Fair value option (ASC 825)** | Elect at origination |

### LOCOM Method

**Measure at lower of:**
- Amortized cost basis
- Fair value

**If FV < Cost, record valuation allowance:**
```
Dr. Loss on Loans Held for Sale         $100,000
    Cr. Valuation Allowance—LHFS              $100,000
```

### Fair Value Option

**Elect at origination:**
- All changes in fair value through earnings
- No valuation allowance needed

**Journal Entry—Fair value change:**
```
Dr. Loans Held for Sale                 $50,000
    Cr. Gain on Loans Held for Sale            $50,000
```

---

## Loan Sales

### Sale Recognition

**Qualify as sale under ASC 860 when:**
1. Transferred assets isolated from transferor
2. Transferee has right to pledge or exchange
3. Transferor doesn't maintain effective control

### Gain on Sale Calculation

```
Gain = Sale Proceeds + Servicing Asset − Carrying Amount
```

### Components at Sale

| Component | Treatment |
|-----------|-----------|
| Cash proceeds | Receive |
| Servicing asset | Recognize at FV |
| Recourse liability | Recognize at FV |
| Retained interest | Recognize at FV |

### Example—Loan Sale

**Facts:**
- Loan carrying amount: $10,000,000
- Sale price: $10,200,000
- Servicing asset FV: $150,000
- Recourse liability FV: $50,000

**Gain calculation:**
```
$10,200,000 + $150,000 − $50,000 − $10,000,000 = $300,000
```

**Journal Entry:**
```
Dr. Cash                               $10,200,000
Dr. Mortgage Servicing Rights             $150,000
    Cr. Loans Held for Sale                   $10,000,000
    Cr. Recourse Liability                        $50,000
    Cr. Gain on Sale of Loans                    $300,000
```

---

## Mortgage Servicing Rights (MSRs)

### Recognition

**Recognize MSR when:**
- Loans sold with servicing retained
- Servicing acquired separately
- Assumption of servicing

### Initial Measurement

**At fair value** based on:
- Expected servicing income
- Adequate compensation comparison
- Market pricing if available

### Subsequent Measurement Options

| Method | Treatment |
|--------|-----------|
| **Amortization method** | Amortize over service period; test for impairment |
| **Fair value method** | Mark to FV each period; changes in earnings |

### Amortization Method

**Amortize in proportion to net servicing income:**

```
Dr. Amortization Expense—MSR           $25,000
    Cr. Accumulated Amortization—MSR          $25,000
```

**Impairment testing:**
- Compare carrying amount to fair value
- Recognize impairment if FV < carrying amount
- Stratify by risk characteristics

### Fair Value Method

**Mark to fair value each period:**

*If FV increases:*
```
Dr. Mortgage Servicing Rights           $30,000
    Cr. Gain on MSR Valuation                  $30,000
```

*If FV decreases:*
```
Dr. Loss on MSR Valuation               $40,000
    Cr. Mortgage Servicing Rights              $40,000
```

---

## Servicing Liabilities

### When Recognized

**Recognize liability when:**
- Servicing fee is less than adequate compensation
- Servicing acquired at above-market terms

### Measurement

Same options as servicing assets:
- Amortization method
- Fair value method

---

## Loan Commitments

### Interest Rate Lock Commitments (IRLCs)

**Commitment to originate loan at specified rate:**

| Classification | Treatment |
|----------------|-----------|
| Derivative (ASC 815) | Fair value, changes in earnings |
| Loan commitment | Generally not a derivative |

### IRLC as Derivative

When IRLC meets derivative definition:
```
Dr. IRLC Asset                          $10,000
    Cr. Gain on IRLC                           $10,000
```

### Forward Sale Commitments

**Hedge of IRLCs or loans held for sale:**
- May qualify for hedge accounting
- Or mark to market with offsetting changes

---

## Repurchase and Indemnification Obligations

### Types

| Obligation | Trigger |
|------------|---------|
| **Early payment default** | Loan defaults within initial period |
| **Representation breach** | Underwriting/documentation issues |
| **Indemnification** | Various contractual triggers |

### Accounting

**Estimate and accrue:**
```
Dr. Provision for Repurchases          $200,000
    Cr. Repurchase Liability                   $200,000
```

**When repurchase occurs:**
```
Dr. Repurchase Liability               $50,000
Dr. Loans Held for Investment          $950,000
    Cr. Cash                                  $1,000,000
```

---

## Pipeline and Warehouse Accounting

### Mortgage Pipeline

Loans in process of origination:
- Track commitments
- Monitor IRLC values
- Manage hedge positions

### Warehouse Loans

**Loans held between origination and sale:**
- Typically 15-45 days
- Warehouse line financing
- Fair value or LOCOM measurement

---

## Practical Example: Monthly Cycle

### 1. Loan Originations ($50M)

```
Dr. Loans Held for Sale               $50,000,000
    Cr. Cash (funded)                        $49,000,000
    Cr. Warehouse Line                        $1,000,000
```

### 2. Pipeline Hedge (Forward sales $45M)

```
Dr. Forward Sale Commitment (Asset)       $75,000
    Cr. Gain on Forward Commitment               $75,000
```

### 3. Loan Sales ($48M)

```
Dr. Cash                              $48,500,000
Dr. Mortgage Servicing Rights            $600,000
    Cr. Loans Held for Sale                   $48,000,000
    Cr. Gain on Sale                          $1,100,000
```

### 4. MSR Fair Value Adjustment

```
Dr. Loss on MSR Valuation                $50,000
    Cr. Mortgage Servicing Rights               $50,000
```

---

## Disclosure Requirements

### Required Disclosures

1. **Loans held for sale** accounting policy
2. **Servicing assets/liabilities** by class
3. **Fair value** of servicing rights
4. **Sensitivity analysis** for FV servicing
5. **Risk characteristics** for stratification

### MSR Rollforward

| Activity | Amount |
|----------|--------|
| Beginning balance | $XX |
| Additions (new originations) | $XX |
| Amortization | $(XX) |
| Fair value changes | $XX |
| **Ending balance** | **$XX** |

### Example Disclosure

> **Mortgage Servicing Rights:** The Company recognizes MSRs when loans are sold with servicing retained. MSRs are initially recorded at fair value and subsequently measured using the amortization method. The Company stratifies MSRs based on loan type and interest rate characteristics for impairment testing.

---

## Private Company Considerations

### Applicability

- Community banks with mortgage operations
- Credit unions
- Small mortgage companies

### Practical Issues

1. Fair value determination for MSRs
2. IRLC hedge accounting complexity
3. Pipeline management
4. Repurchase reserve estimation

---

## Common Audit Issues

1. **LOCOM valuation** — Fair value support for loans
2. **MSR valuation** — Model inputs, assumptions
3. **Gain on sale** — Proper allocation of proceeds
4. **Hedge accounting** — Documentation, effectiveness
5. **Repurchase reserves** — Historical loss rates
6. **Classification** — Held for sale vs. investment transfers
7. **Fee income cutoff** — Proper period recognition

---

## Recent Developments

### CECL Impact

- Loans held for investment subject to CECL
- Loans held for sale generally excluded
- Transfer between categories triggers recognition

### Interest Rate Environment

- MSR values sensitive to rates
- Prepayment assumptions critical
- Hedging strategies evolving

---

## External Resources

- [FASB ASC 948](https://asc.fasb.org/)
- [Mortgage Bankers Association](https://www.mba.org/)
- [AICPA Depository and Lending Guide](https://www.aicpa.org/)
- [KPMG: Banking Handbook](https://frv.kpmg.us/)

---

## Navigation

← [Back to Industry (900s)](README.md) | [Main Guide](../../README.md)
