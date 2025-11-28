# ASC 500-599: Equity

> Accounting for stockholders' equity, stock compensation, and related transactions.

## Topic Overview

The 500 series covers accounting for equity instruments, stock-based compensation, and transactions affecting stockholders' equity.

| Topic | Title | Key Standards |
|-------|-------|---------------|
| ASC 505 | Equity | Stock issuances, treasury stock, dividends |
| [ASC 718](asc-718-stock-compensation.md) | **Compensation—Stock Compensation** | Fair value of share-based payments |

---

## Key Standards

### ASC 718: Stock Compensation

📌 **Major Standard — Critical for entities issuing equity-based compensation**

See detailed guide: [ASC 718: Stock Compensation](asc-718-stock-compensation.md)

**Overview:**

ASC 718 requires entities to recognize compensation cost for share-based payment arrangements based on fair value at grant date.

**Scope:**
- Stock options
- Restricted stock/units
- Employee stock purchase plans (ESPPs)
- Performance shares
- Stock appreciation rights (SARs)
- Profits interests (clarified by ASU 2024-01)

**Key Principle:**
Recognize compensation cost equal to fair value of equity instruments granted, measured at grant date, over the requisite service period.

**Measurement:**

| Award Type | Measurement |
|------------|-------------|
| Equity-classified | Fair value at grant date (fixed) |
| Liability-classified | Fair value each reporting date (remeasured) |

**Fair Value Methods:**
- **Stock options** — Black-Scholes or binomial models
- **Restricted stock** — Stock price at grant date
- **Performance awards** — Monte Carlo simulation (if market conditions)

---

### ASC 505: Equity

**Stock Issuances:**
- Record at fair value of consideration received
- Excess over par value → Additional Paid-In Capital (APIC)

**Treasury Stock:**

| Method | Balance Sheet Treatment |
|--------|------------------------|
| **Cost Method** | Debit treasury stock at cost; reduces total equity |
| **Par Value Method** | Reduces common stock and APIC |

**Dividends:**

| Type | Treatment |
|------|-----------|
| Cash dividends | Reduce retained earnings when declared |
| Stock dividends (small, <20-25%) | Transfer fair value from retained earnings |
| Stock dividends (large, ≥20-25%) | Transfer par value from retained earnings |
| Stock splits | No journal entry (adjust par value) |

---

## Recent Updates (2024-2025)

| ASU | Topic | Effective Date | Summary |
|-----|-------|----------------|---------|
| ASU 2024-01 | Profits Interest Awards | Jan 2024 | Clarifies when profits interests are in scope of ASC 718 |
| ASU 2021-07 | Stock Compensation | 2022 | Practical expedient for expected term |
| ASU 2018-07 | Stock Compensation to Nonemployees | 2019 | Aligns employee and nonemployee accounting |

### ASU 2024-01: Profits Interest Awards

**Key Clarification:** A profits interest award should be accounted for under ASC 718 if:
1. The entity would account for a substantively similar stock option under ASC 718, AND
2. The profits interest is denominated in shares of the entity

**Effective Date:** Fiscal years beginning after December 15, 2024 (all entities)

---

## Practical Examples

### Stock Option Grant

**Scenario:** Company grants 10,000 options to employees with fair value of $5 per option. Vesting period: 3 years.

**Total Compensation Cost:** $50,000

**Annual Journal Entry (Years 1-3):**
```
Dr. Compensation Expense          $16,667
    Cr. Additional Paid-In Capital        $16,667
```

### Restricted Stock Unit (RSU) Grant

**Scenario:** Company grants 1,000 RSUs to employee when stock price is $20. 4-year cliff vesting.

**Total Compensation Cost:** $20,000

**Annual Journal Entry (Years 1-4):**
```
Dr. Compensation Expense          $5,000
    Cr. Additional Paid-In Capital        $5,000
```

### Treasury Stock Purchase (Cost Method)

**Scenario:** Company repurchases 5,000 shares at $30 per share.

**Journal Entry:**
```
Dr. Treasury Stock               $150,000
    Cr. Cash                             $150,000
```

### Cash Dividend Declaration

**Scenario:** Company declares $0.50 per share dividend on 100,000 outstanding shares.

**At Declaration:**
```
Dr. Retained Earnings            $50,000
    Cr. Dividends Payable                $50,000
```

**At Payment:**
```
Dr. Dividends Payable            $50,000
    Cr. Cash                             $50,000
```

---

## Private Company Considerations

### PCC Alternatives

| Topic | Private Company Alternative |
|-------|---------------------------|
| **Stock Options** | Can use practical expedient for expected term (ASU 2021-07) |
| **Nonemployee Awards** | Same accounting as employee awards |
| **Fair Value** | Can use calculated value (volatility of similar public companies) |

### Practical Expedient for Expected Term

Private companies can estimate expected term as:
- **Vesting period + Contractual term** ÷ 2 (simplified method), OR
- **Midpoint of vesting date and contractual term**

---

## Stock Compensation: Step-by-Step Process

### 1. Determine Award Type
- Options, RSUs, performance shares, etc.

### 2. Identify Vesting Conditions

| Condition Type | Impact on Accounting |
|----------------|---------------------|
| **Service** | Recognize over service period |
| **Performance** | Recognize when probable of achievement |
| **Market** | Always recognize (probability built into fair value) |

### 3. Measure Fair Value
- Grant date for equity awards
- Each reporting date for liability awards

### 4. Recognize Compensation Cost
- Straight-line over requisite service period (if no performance conditions)
- Graded vesting approach (if distinct vesting tranches)

### 5. Handle Forfeitures
- Estimate expected forfeitures at grant, OR
- Elect to recognize forfeitures as they occur

---

## Common Audit Issues

1. **Grant Date Determination** — Award terms not finalized
2. **Fair Value Inputs** — Inappropriate volatility or expected term assumptions
3. **Performance Conditions** — Not reassessing probability each period
4. **Modifications** — Failure to recognize incremental compensation cost
5. **Forfeiture Estimates** — Significant true-ups when actuals differ

---

## Disclosure Requirements

### ASC 718 Requires Disclosure Of:

1. **Method and assumptions** for fair value estimates
2. **Compensation cost** recognized during the period
3. **Unrecognized compensation cost** and weighted-average recognition period
4. **Award activity** (grants, exercises, forfeitures)
5. **Cash flows** from tax benefits and share repurchases

---

## External Resources

- [FASB ASC 500 Topics](https://asc.fasb.org/)
- [FASB Stock Compensation Implementation Guidance](https://www.fasb.org/)
- [KPMG: Handbook—Share-based Payment](https://frv.kpmg.us/)
- [PwC: Stock-based Compensation Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Accounting for Share-Based Payment Awards](https://www.iasplus.com/en-us)

---

## Navigation

← [Previous: Liabilities (400s)](../400-liabilities/README.md) | [Back to Main Guide](../../README.md) | [Next: Revenue (600s) →](../600-revenue/README.md)
