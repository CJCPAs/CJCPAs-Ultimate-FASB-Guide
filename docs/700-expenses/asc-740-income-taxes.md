# ASC 740: Income Taxes

> The comprehensive standard for accounting for income taxes using the asset and liability method.

## Overview

ASC 740 establishes the framework for recognizing, measuring, presenting, and disclosing income taxes in financial statements. It requires the asset and liability method, which focuses on the balance sheet and recognizes deferred taxes for the future tax consequences of events recognized in the financial statements.

**Core Principle:**
> "A deferred tax liability or asset shall be recognized for the estimated future tax effects attributable to temporary differences and carryforwards."

---

## Scope

### Applies To:
- Domestic and foreign operations
- Interim and annual financial statements
- All entities subject to income taxes
- Deferred tax effects of uncertain tax positions

### Does NOT Apply To:
- Franchise taxes based on capital
- Taxes based on gross receipts
- State and local taxes not based on income
- Tax credits (except to extent they reduce taxes payable)

---

## Effective Dates

| Standard/Update | Entity Type | Effective Date |
|-----------------|-------------|----------------|
| ASC 740 (original) | All entities | Already effective |
| ASU 2019-12 (Simplification) | Public entities | Fiscal years beginning after 12/15/2020 |
| ASU 2019-12 (Simplification) | All other entities | Fiscal years beginning after 12/15/2021 |
| ASU 2023-09 (Disclosure) | Public entities | Annual periods beginning after 12/15/2024 |
| ASU 2023-09 (Disclosure) | All other entities | Annual periods beginning after 12/15/2025 |

---

## Key Definitions

### Temporary Differences

**Definition:** Differences between the tax basis of an asset or liability and its reported amount in the financial statements that will result in taxable or deductible amounts in future years.

| Type | Definition | Result |
|------|------------|--------|
| **Taxable temporary difference** | Reported amount > Tax basis (for assets) or Reported amount < Tax basis (for liabilities) | Deferred tax liability |
| **Deductible temporary difference** | Reported amount < Tax basis (for assets) or Reported amount > Tax basis (for liabilities) | Deferred tax asset |

### Common Temporary Differences

| Item | Book vs. Tax Treatment | Type |
|------|------------------------|------|
| **Depreciation** | Book straight-line vs. MACRS accelerated | Usually taxable |
| **Bad debt reserves** | Book accrual vs. Tax direct write-off | Deductible |
| **Warranty reserves** | Book accrual vs. Tax when paid | Deductible |
| **Prepaid expenses** | Book amortized vs. Tax deducted when paid | Taxable |
| **Revenue recognition** | Book ASC 606 vs. Tax when received | Usually taxable |
| **Stock compensation** | Book expense over vesting vs. Tax at exercise | Deductible |
| **Lease liabilities** | Book ASC 842 vs. Tax as paid | Deductible |
| **ROU assets** | Book ASC 842 vs. Tax (none) | Taxable |

### Permanent Differences

Differences that will **never** reverse—do not create deferred taxes.

| Example | Description |
|---------|-------------|
| Municipal bond interest | Tax-exempt income |
| 50% meals limitation | Non-deductible expense |
| Key-person life insurance | Premiums non-deductible, proceeds tax-free |
| Fines and penalties | Non-deductible expense |
| Goodwill amortization (book only) | Book impairment not tax deductible (if no tax basis) |

---

## The Asset and Liability Method

### Step-by-Step Approach

**Step 1: Identify Temporary Differences**
- Compare book basis and tax basis of all assets and liabilities
- Determine if difference is taxable or deductible

**Step 2: Measure Deferred Taxes**
- Apply enacted tax rates expected to apply when differences reverse
- Consider graduated rates if applicable

**Step 3: Assess Need for Valuation Allowance**
- Evaluate realizability of deferred tax assets
- Reduce DTAs by valuation allowance if "more likely than not" (>50%) some portion won't be realized

**Step 4: Present and Disclose**
- Classify as noncurrent on balance sheet
- Provide required disclosures

---

## Deferred Tax Liabilities (DTL)

### Recognition

Recognize a DTL for all taxable temporary differences, except:
- Goodwill if amortization is not deductible for tax purposes
- Initial recognition of an asset or liability that does not affect book or tax income at transaction date
- Undistributed earnings of foreign subsidiaries (indefinite reinvestment assertion)

### Measurement

**DTL = Taxable Temporary Difference × Enacted Tax Rate**

### Example

**Facts:**
- Equipment book basis: $100,000 (cost $200,000 less accumulated depreciation $100,000)
- Equipment tax basis: $60,000 (cost $200,000 less MACRS depreciation $140,000)
- Enacted tax rate: 21%

**Calculation:**
- Taxable temporary difference: $100,000 - $60,000 = $40,000
- DTL: $40,000 × 21% = $8,400

---

## Deferred Tax Assets (DTA)

### Recognition

Recognize a DTA for:
- Deductible temporary differences
- Tax credit carryforwards
- Net operating loss (NOL) carryforwards

### Measurement

**DTA = Deductible Temporary Difference × Enacted Tax Rate**

### Valuation Allowance

**When Required:** If it is more likely than not (>50%) that some portion of the DTA will not be realized.

**Assessment Framework—Sources of Taxable Income:**

| Source | Description | Weight |
|--------|-------------|--------|
| **1. Reversing taxable temporary differences** | Future taxable amounts from existing DTLs | Strong (objective) |
| **2. Future taxable income exclusive of reversing differences** | Projected operating income | Moderate (subjective) |
| **3. Taxable income in carryback years** | If carryback available | Strong (objective) |
| **4. Tax planning strategies** | Actions entity would take to realize DTA | Must be prudent and feasible |

**Positive and Negative Evidence:**

| Positive Evidence | Negative Evidence |
|-------------------|-------------------|
| Strong earnings history | Cumulative losses in recent years |
| Existing contracts/backlog | History of NOL/credit expiration |
| Valuable appreciated assets | Unsettled circumstances |
| Excess of FV over tax basis | Carryforward expires before likely utilization |

**Weight of Evidence:** Negative evidence—especially cumulative losses—is difficult to overcome.

### Example: Valuation Allowance

**Facts:**
- DTA for NOL carryforward: $500,000
- Company has cumulative losses for 3 years
- No taxable temporary differences exist
- Limited visibility into future profitability

**Analysis:**
- Cumulative losses = significant negative evidence
- No objective sources of future taxable income
- More likely than not full DTA will not be realized

**Conclusion:** Record valuation allowance of $500,000

```
Dr. Income Tax Expense (or OCI)     $500,000
    Cr. Valuation Allowance                  $500,000
```

---

## Current Tax Provision

### Calculation

**Current Tax Expense = Taxable Income × Current Enacted Rate**

### Taxable Income Calculation

| Starting Point | Book income before taxes |
|----------------|--------------------------|
| **Add:** | Permanent differences (non-deductible items) |
| **Subtract:** | Permanent differences (non-taxable items) |
| **Add:** | Taxable temporary differences originating |
| **Subtract:** | Taxable temporary differences reversing |
| **Add:** | Deductible temporary differences reversing |
| **Subtract:** | Deductible temporary differences originating |
| **= Taxable income** | |

---

## Deferred Tax Provision

### Calculation

**Deferred Tax Expense = Change in Net Deferred Tax Liability (or Asset)**

### Total Tax Provision

**Total Tax Expense = Current Tax Expense + Deferred Tax Expense**

---

## Rate Reconciliation

### Requirement

Reconcile the statutory rate to the effective tax rate.

### Format (Public Companies)

| Item | Rate |
|------|------|
| U.S. federal statutory rate | 21.0% |
| State taxes, net of federal benefit | 4.5% |
| Permanent differences—meals | 0.3% |
| Permanent differences—tax-exempt income | (0.5%) |
| Stock compensation (excess tax benefits) | (2.0%) |
| R&D credits | (1.5%) |
| Valuation allowance change | 1.0% |
| Other | 0.2% |
| **Effective tax rate** | **23.0%** |

---

## Net Operating Losses (NOLs)

### Current Rules (Post-TCJA)

| Aspect | Pre-2018 NOLs | Post-2017 NOLs |
|--------|---------------|----------------|
| Carryback | 2 years | None (generally) |
| Carryforward | 20 years | Indefinite |
| Limitation | None | 80% of taxable income |

### Accounting Treatment

**DTA Recognition:**
- Recognize DTA at enacted rate
- Apply 80% limitation when scheduling deferred taxes
- Assess valuation allowance

### Example

**Facts:**
- 2024 NOL generated: $1,000,000
- Enacted federal rate: 21%
- No state taxes
- Company has strong earnings history

**Entry:**
```
Dr. Deferred Tax Asset             $210,000
    Cr. Income Tax Benefit                   $210,000
```

**Note:** The 80% limitation affects when the NOL can be utilized, not the DTA amount.

---

## Tax Credits

### Types

| Credit | Description |
|--------|-------------|
| **R&D Credit** | Research & development activities |
| **Work Opportunity Tax Credit** | Hiring targeted groups |
| **Low-Income Housing Credit** | Affordable housing investments |
| **Foreign Tax Credit** | Taxes paid to foreign jurisdictions |

### Accounting Methods

| Method | Treatment |
|--------|-----------|
| **Flow-through method** | Reduce current tax expense |
| **Deferral method** | Amortize over life of asset (investment credits) |

**Note:** Most entities use flow-through for operating credits.

---

## Uncertain Tax Positions (ASC 740-10-25)

### Two-Step Approach

**Step 1: Recognition**
Determine if tax position is "more likely than not" (>50%) to be sustained based on technical merits.

| Result | Action |
|--------|--------|
| >50% likely | Recognize benefit |
| ≤50% likely | Do not recognize benefit |

**Step 2: Measurement**
Measure at largest amount with >50% likelihood of being realized upon settlement.

### Example

**Facts:**
- Tax position reduces taxes by $100,000
- 60% probability of full benefit
- 25% probability of $60,000 benefit
- 15% probability of no benefit

**Analysis:**
- Cumulative probability analysis:

| Amount | Individual Probability | Cumulative |
|--------|----------------------:|----------:|
| $100,000 | 60% | 60% |
| $60,000 | 25% | 85% |
| $0 | 15% | 100% |

**Measurement:** $100,000 (largest amount with cumulative probability >50%)

### Balance Sheet Presentation

| Classification | Criteria |
|----------------|----------|
| Current liability | Expected to be settled within 12 months |
| Noncurrent liability | All other uncertain tax positions |
| Reduce DTA | If would reduce NOL, carryforward, or credit |

### Interest and Penalties

- **Policy election:** Classify as income tax expense or other expense
- Must disclose policy
- Accrue interest on unpaid balances

---

## Intraperiod Tax Allocation

### Requirement

Allocate total tax expense to different components of comprehensive income.

### Components

| Component | Allocation |
|-----------|------------|
| Continuing operations | Primary component |
| Discontinued operations | Tax on discontinued items |
| Other comprehensive income | Tax on OCI items |
| Prior period adjustments | Tax on adjustments |
| Capital transactions | Tax on equity transactions |

### Special Rule for OCI

Tax rate used for OCI items depends on whether entity uses:
- **Portfolio approach:** Apply incremental tax rate
- **Securities-specific approach:** Apply specific rate to each item

---

## Interim Reporting (ASC 740-270)

### Estimated Annual Effective Tax Rate (EAETR)

**Calculate:** Estimated annual tax expense ÷ Estimated annual pretax income

**Apply:** EAETR to year-to-date income, then subtract prior quarters' expense

### Discrete Items

Recognize separately in the quarter they occur:
- Effects of enacted tax rate changes
- Changes in valuation allowance
- Tax effects of unusual or infrequent items
- Effects of uncertain tax positions
- Tax benefits from stock compensation

---

## ASU 2023-09: Enhanced Disclosures

### Key Changes (Effective 2025 for public, 2026 for private)

**Rate Reconciliation:**
- Disaggregate into specific categories:
  - State and local taxes
  - Foreign taxes
  - Tax credits
  - Stock compensation
  - Nontaxable/nondeductible items
  - Changes in valuation allowance
  - Changes in unrecognized tax benefits
- Quantitative threshold for "other" category

**Taxes Paid:**
- Disclose income taxes paid (net of refunds) by:
  - Federal
  - State
  - Foreign (by jurisdiction if significant)

### Example Disclosure Format

**Rate Reconciliation:**

| Category | Amount | Percent |
|----------|-------:|--------:|
| Income tax at statutory rate | $2,100,000 | 21.0% |
| State income tax, net of federal | 400,000 | 4.0% |
| Research and development credits | (150,000) | (1.5%) |
| Stock compensation—excess benefits | (200,000) | (2.0%) |
| Foreign rate differential | 100,000 | 1.0% |
| Nondeductible compensation | 75,000 | 0.8% |
| Other | 25,000 | 0.2% |
| **Total income tax expense** | **$2,350,000** | **23.5%** |

---

## Practical Examples

### Example 1: Comprehensive Deferred Tax Calculation

**Facts:**
- Book income before taxes: $1,000,000
- Depreciation: Book $100,000; Tax $150,000
- Bad debt reserve: Book $50,000 allowance; Tax $0 (direct write-off)
- Prepaid expenses: Book $20,000 asset; Tax $0 (deducted when paid)
- Meals expense (50% limitation): Book $10,000; Tax $5,000
- Enacted tax rate: 25%

**Step 1: Calculate Current Tax**

| Item | Amount |
|------|-------:|
| Book income before taxes | $1,000,000 |
| Add: Excess book depreciation | 50,000 |
| Add: Bad debt reserve (not yet written off) | 50,000 |
| Subtract: Prepaid expenses (tax deducted) | (20,000) |
| Add: Non-deductible meals | 5,000 |
| **Taxable income** | **$1,085,000** |

Current tax expense: $1,085,000 × 25% = $271,250

**Step 2: Calculate Deferred Taxes**

| Temporary Difference | Book Basis | Tax Basis | Difference | Type | DTA/(DTL) |
|----------------------|-----------:|----------:|-----------:|------|----------:|
| Equipment (depreciation) | 100,000 | 50,000 | 50,000 | Taxable | ($12,500) |
| Bad debt reserve | (50,000) | 0 | (50,000) | Deductible | 12,500 |
| Prepaid expenses | 20,000 | 0 | 20,000 | Taxable | (5,000) |
| **Net** | | | | | **($5,000)** |

**Journal Entry:**
```
Dr. Income Tax Expense—Current       $271,250
Dr. Income Tax Expense—Deferred        5,000
    Cr. Income Taxes Payable                   $271,250
    Cr. Deferred Tax Liability                   $5,000
```

---

### Example 2: Valuation Allowance Assessment

**Facts:**
- DTA from NOL carryforward: $300,000
- DTA from other temporary differences: $100,000
- DTL from depreciation differences: $150,000
- Company has 3-year cumulative loss
- Management projects $200,000 taxable income annually for next 5 years

**Analysis:**

**Negative Evidence:**
- Three-year cumulative loss (significant weight)
- No objective evidence of future income

**Positive Evidence:**
- Management projections (subjective—reduced weight due to losses)
- Reversing DTLs provide $150,000 of future taxable income

**Scheduling:**
| Source | Amount |
|--------|-------:|
| Reversing DTLs | $150,000 |
| Supportable future income | Limited |

**Conclusion:**
- DTL provides objective support for $150,000 of DTA
- Remaining $250,000 DTA ($400,000 total - $150,000) requires valuation allowance

**Entry:**
```
Dr. Income Tax Expense              $250,000
    Cr. Valuation Allowance                  $250,000
```

---

### Example 3: Uncertain Tax Position

**Facts:**
- Company took R&D credit of $500,000
- Tax advisors believe 70% likely to be sustained
- If challenged, possible outcomes:
  - 55% probability: Full $500,000 sustained
  - 30% probability: $350,000 sustained
  - 15% probability: $200,000 sustained

**Step 1: Recognition**
- More likely than not (70% > 50%)? YES
- Recognize benefit

**Step 2: Measurement**

| Amount | Individual | Cumulative |
|-------:|----------:|----------:|
| $500,000 | 55% | 55% |
| $350,000 | 30% | 85% |
| $200,000 | 15% | 100% |

- Largest amount with >50% cumulative probability: $500,000

**Benefit Recognized:** $500,000

---

## Private Company Considerations

### Simplification Opportunities

| Area | Consideration |
|------|---------------|
| **Valuation allowance** | More reliance on objective evidence |
| **State apportionment** | May use simpler allocation methods |
| **Rate changes** | May have less impact (pass-through entities) |
| **Disclosures** | Reduced requirements (non-public) |

### Pass-Through Entities

- S corporations, partnerships, LLCs: Generally no entity-level income tax
- Consider built-in gains tax (S corps)
- State taxes may still apply at entity level
- Owner-level deferred taxes not recorded at entity level

### Tax Basis Financial Statements

Some private companies may prepare tax basis statements:
- No deferred taxes
- Simpler presentation
- Limited GAAP comparability

---

## Common Implementation Issues

### 1. Valuation Allowance Errors
- Not updating quarterly
- Insufficient documentation of positive/negative evidence
- Ignoring cumulative loss requirement

### 2. Rate Changes
- Not using enacted rates
- Failing to remeasure deferred taxes when rates change
- Improper attribution of remeasurement effect

### 3. Uncertain Tax Positions
- Not identifying all positions
- Improper measurement using "best estimate"
- Failing to accrue interest

### 4. Interim Reporting
- Not recalculating EAETR each quarter
- Improper treatment of discrete items
- Valuation allowance changes in wrong period

### 5. Intraperiod Allocation
- Failing to allocate to OCI
- Improper tax rate for OCI items
- Missing discontinued operations allocation

---

## External Resources

- [FASB ASC 740](https://asc.fasb.org/)
- [KPMG: Handbook—Accounting for Income Taxes](https://frv.kpmg.us/)
- [PwC: Income Taxes Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Accounting for Income Taxes](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Income Taxes](https://www.ey.com/)
- [AICPA: Accounting for Income Taxes](https://www.aicpa.org/)

---

## Navigation

← [Back to Expenses (700s)](README.md) | [Back to Main Guide](../../README.md)
