# ASC 700-799: Expenses

> Accounting for costs, expenses, and cost allocation across various categories.

## Topic Overview

The 700 series covers accounting for various types of expenses and costs.

| Topic | Title | Key Standards |
|-------|-------|---------------|
| ASC 705 | Cost of Sales and Services | Cost of goods sold |
| ASC 710 | Compensation—General | Salaries, bonuses, benefits |
| ASC 712 | Compensation—Nonretirement Postemployment Benefits | Severance, disability |
| ASC 715 | Compensation—Retirement Benefits | Pensions, OPEB |
| ASC 718 | Compensation—Stock Compensation | (See [ASC 500s](../500-equity/README.md)) |
| ASC 720 | Other Expenses | Advertising, start-up costs |
| ASC 730 | Research and Development | R&D costs |
| [ASC 740](asc-740-income-taxes.md) | **Income Taxes** | Deferred taxes, uncertain positions |

---

## Key Standards

### ASC 715: Compensation—Retirement Benefits

**Defined Benefit Plans:**

Employers recognize:
- **Net periodic pension cost** — Service cost, interest cost, expected return, amortization
- **Funded status** — Plan assets minus benefit obligation (on balance sheet)

**Components of Net Periodic Pension Cost:**

| Component | Description | Income Statement Location |
|-----------|-------------|---------------------------|
| Service cost | Benefits earned this period | Operating expense |
| Interest cost | Benefit obligation growth | Non-operating |
| Expected return on assets | Reduces expense | Non-operating |
| Amortization of prior service cost | Plan amendments | Non-operating |
| Amortization of net actuarial gain/loss | Experience differences | Non-operating |

**Plain English:** Only service cost is shown in operating income; everything else is non-operating.

---

### ASC 720: Other Expenses

**Advertising Costs:**
- Generally expense as incurred or when advertising first occurs
- Exception: Direct-response advertising may be capitalized if criteria met

**Start-Up Costs:**
- Expense as incurred (no capitalization)
- Includes pre-opening costs, organization costs

**Internal-Use Software (ASC 350-40):**

| Phase | Treatment |
|-------|-----------|
| Preliminary project stage | Expense |
| Application development stage | Capitalize |
| Post-implementation stage | Expense |

---

### ASC 730: Research and Development

**Core Principle:** R&D costs are expensed as incurred.

**What's R&D?**
- **Research** — Discovering new knowledge
- **Development** — Translating research into plan/design for new product/process

**Includes:**
- Materials, equipment, facilities (if no alternative future use)
- Personnel costs
- Intangibles purchased from others (if no alternative future use)
- Contract services
- Indirect costs reasonably allocable

**Excludes:**
- Routine quality control
- Routine engineering
- Market research
- Legal costs of patents

**Software Development Costs (ASC 985-20):**
- **External-use software:** Capitalize after technological feasibility established
- **Internal-use software:** See ASC 350-40 above

---

### ASC 740: Income Taxes

📌 **Major Standard — Complex area requiring careful analysis**

See detailed guide: [ASC 740: Income Taxes](asc-740-income-taxes.md)

**Overview:**

ASC 740 addresses financial reporting for income taxes, including:
- Current tax expense/benefit
- Deferred tax assets/liabilities
- Uncertain tax positions

**Key Concepts:**

**Deferred Taxes:**

| Item | Creates | Example |
|------|---------|---------|
| **Deferred Tax Liability (DTL)** | Taxable temporary difference | Accelerated tax depreciation |
| **Deferred Tax Asset (DTA)** | Deductible temporary difference | Accrued vacation, allowance for bad debts |

**Formula:**
```
Deferred Tax = Temporary Difference × Tax Rate
```

**Valuation Allowance:**
- Reduce DTA if "more likely than not" (>50%) won't be realized
- Consider positive and negative evidence

**Uncertain Tax Positions (FIN 48):**

| Step | Description |
|------|-------------|
| Recognition | Recognize only if "more likely than not" position will be sustained |
| Measurement | Largest amount with >50% likelihood of realization |

---

## Recent Updates (2024-2025)

| ASU | Topic | Effective Date | Summary |
|-----|-------|----------------|---------|
| ASU 2023-09 | Income Tax Disclosures | Dec 2025 (public), Dec 2026 (private) | Enhanced rate reconciliation and cash taxes paid |
| ASU 2019-12 | Income Taxes Simplification | 2021 | Simplifies accounting for income taxes |
| ASU 2018-02 | Reclassification of Tax Effects | 2019 | Stranded tax effects from TCJA |

### ASU 2023-09: Income Tax Disclosures

**Key Requirements:**
1. **Rate Reconciliation** — Disaggregate into categories with specific thresholds
2. **Taxes Paid** — Disclose by jurisdiction (federal, state, foreign) when > 5% of total
3. **Pretax Income** — Disaggregate domestic vs. foreign

**Effective Dates:**
- Public: December 2025
- Private: December 2026

---

## Practical Examples

### Deferred Tax Asset—Allowance for Bad Debts

**Scenario:** Company has $100,000 allowance for bad debts (book expense recognized, not yet tax deductible). Tax rate: 21%.

**DTA Calculation:**
```
DTA = $100,000 × 21% = $21,000
```

**Journal Entry:**
```
Dr. Deferred Tax Asset           $21,000
    Cr. Income Tax Benefit               $21,000
```

### Valuation Allowance

**Scenario:** Company has $500,000 DTA but only $200,000 of projected taxable income.

**Analysis:** Only $200,000 of temporary differences will reverse within the foreseeable period with available income.

**Realizable DTA:** $200,000 × 21% = $42,000
**Total DTA:** $500,000 × 21% = $105,000
**Valuation Allowance:** $105,000 - $42,000 = $63,000

**Journal Entry:**
```
Dr. Income Tax Expense           $63,000
    Cr. Valuation Allowance              $63,000
```

### R&D Expense

**Scenario:** Company incurs $50,000 on research project with uncertain outcome.

**Journal Entry:**
```
Dr. R&D Expense                  $50,000
    Cr. Cash/Payables                    $50,000
```

---

## Private Company Considerations

### Practical Expedients

| Topic | Relief Available |
|-------|-----------------|
| **Pension plans** | May use measurement date up to 3 months prior to year-end |
| **Income taxes** | Same standards apply; complexity similar |

### Common Private Company Issues

1. **Pass-through entities** — No deferred taxes at entity level
2. **S corps/partnerships** — Owner-level tax considerations
3. **State taxes** — Multiple jurisdictions add complexity

---

## Income Tax Provision: Step-by-Step

### 1. Calculate Current Tax Expense
```
Current Tax = Taxable Income × Current Tax Rates
```

### 2. Identify Temporary Differences
- Compare book and tax basis of all assets/liabilities
- Determine if deferred tax asset or liability

### 3. Calculate Deferred Tax Expense
```
Deferred Tax Expense = Change in Net DTL (or DTA) during period
```

### 4. Assess Valuation Allowance
- Evaluate realizability of DTAs
- Consider positive/negative evidence

### 5. Evaluate Uncertain Positions
- Apply two-step process (recognition, measurement)
- Document support for positions

### 6. Calculate Effective Tax Rate
```
ETR = Total Income Tax Expense / Pretax Book Income
```

---

## Common Audit Issues

1. **Valuation Allowance** — Insufficient evidence for conclusions
2. **Rate Changes** — Failure to remeasure deferred taxes when rates change
3. **Uncertain Positions** — Inadequate documentation
4. **State Taxes** — Incorrect apportionment
5. **Intercompany Transactions** — Transfer pricing issues

---

## Disclosure Requirements

### Current Requirements (ASC 740)

1. Components of tax expense (current vs. deferred)
2. Rate reconciliation (tabular format)
3. Significant deferred tax assets/liabilities
4. Valuation allowance changes
5. Uncertain tax positions roll-forward

### Enhanced Requirements (ASU 2023-09)

1. Disaggregated rate reconciliation categories
2. Cash taxes paid by jurisdiction
3. Pretax income split (domestic/foreign)

---

## External Resources

- [FASB ASC 700 Topics](https://asc.fasb.org/)
- [AICPA Income Tax Practice Guide](https://www.aicpa.org/)
- [KPMG: Handbook—Accounting for Income Taxes](https://frv.kpmg.us/)
- [PwC: Income Taxes Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Accounting for Income Taxes](https://www.iasplus.com/en-us)
- [EY: Tax Accounting and Provisions Guide](https://www.ey.com/)

---

## Navigation

← [Previous: Revenue (600s)](../600-revenue/README.md) | [Back to Main Guide](../../README.md) | [Next: Broad Transactions (800s) →](../800-broad-transactions/README.md)
