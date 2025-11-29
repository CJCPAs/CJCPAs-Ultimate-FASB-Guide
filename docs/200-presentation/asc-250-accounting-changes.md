# ASC 250: Accounting Changes and Error Corrections

> The comprehensive standard for accounting for and reporting changes in accounting principles, estimates, and corrections of errors.

## Overview

ASC 250 provides guidance on accounting for and reporting different types of accounting changes and error corrections. The standard ensures that financial statements provide useful information about an entity's financial position and results by requiring appropriate treatment and disclosure of these items.

**Core Principle:**
> "Retrospective application is the preferred method for reporting a change in accounting principle, while changes in estimates are accounted for prospectively."

---

## Scope

### Applies To:
- Changes in accounting principle
- Changes in accounting estimate
- Changes in reporting entity
- Corrections of errors in previously issued financial statements

### Related Standards:
- ASC 855: Subsequent Events
- SEC Regulation S-X, Rule 3-01 (for public companies)

---

## Types of Changes

### Overview Comparison

| Type | Treatment | Prior Periods |
|------|-----------|---------------|
| **Change in accounting principle** | Retrospective (generally) | Restate |
| **Change in accounting estimate** | Prospective | No restatement |
| **Change in estimate effected by change in principle** | Prospective | No restatement |
| **Change in reporting entity** | Retrospective | Restate |
| **Error correction** | Retrospective (restatement) | Restate |

---

## Change in Accounting Principle

### Definition

A change from one generally accepted accounting principle to another generally accepted accounting principle when:
- Two or more principles apply, OR
- The principle previously used is no longer accepted

### Examples

| From | To |
|------|-----|
| FIFO inventory | LIFO inventory |
| Completed contract | Percentage of completion |
| Cost model | Fair value model (if permitted) |
| One depreciation method | Another depreciation method* |

*May be considered change in estimate if useful life also changed.

### Treatment: Retrospective Application

**Step 1:** Calculate cumulative effect as of beginning of earliest period presented

**Step 2:** Adjust beginning retained earnings of earliest period for cumulative effect

**Step 3:** Recast all prior periods presented as if new principle had always been used

**Step 4:** Disclose nature and reason for change

### Journal Entry (Cumulative Effect)

**Example:** Change from FIFO to weighted-average cost

**Cumulative effect:** $50,000 increase to beginning inventory (after tax: $37,500)

```
Dr. Inventory                       $50,000
    Cr. Deferred Tax Liability              $12,500
    Cr. Retained Earnings                   $37,500
```

### Retrospective Application Impracticable

**When Impracticable:**
- Cannot determine period-specific effects
- Requires significant estimates of past conditions
- Cannot objectively verify assumptions

**If Impracticable:**
- Apply to earliest period practicable
- If cannot apply retrospectively at all, apply prospectively from earliest date practicable

### New Accounting Standards

**Follow transition guidance in the new standard:**
- Some require retrospective (full or modified)
- Some require prospective (cumulative catch-up)
- Modified retrospective may not require full restatement

---

## Change in Accounting Estimate

### Definition

A change that occurs as a result of new information or experience. Does not result from correction of an error.

### Examples

| Estimate |
|----------|
| Useful lives of depreciable assets |
| Salvage values |
| Allowance for doubtful accounts |
| Warranty obligations |
| Obsolete inventory |
| Fair value estimates |
| Contingent liabilities |
| Revenue recognition (variable consideration) |

### Treatment: Prospective Application

- Account for change in current period and future periods
- Do not restate prior periods
- No cumulative adjustment

### Example: Change in Useful Life

**Facts:**
- Equipment cost: $100,000
- Original useful life: 10 years, no salvage
- After 4 years, useful life revised to 8 years total
- Accumulated depreciation: $40,000
- Carrying amount: $60,000

**New Depreciation:**
```
Remaining carrying amount: $60,000
Remaining useful life: 4 years (8 - 4)
New annual depreciation: $60,000 / 4 = $15,000
```

**No adjustment to prior depreciation recorded.**

### Disclosure Requirements

If material, disclose:
- Nature of change
- Effect on current period income
- Effect on EPS (if applicable)
- Effect on future periods (if estimable and material)

---

## Change in Estimate Effected by Change in Principle

### Definition

A change that is inseparable from a change in accounting principle because the change in estimate is made by changing an accounting principle.

### Examples

| Change | Treatment |
|--------|-----------|
| Depreciation method change (straight-line to declining balance) | Prospective |
| Amortization method change | Prospective |

### Treatment: Prospective (Like Estimate Change)

- Apply the new method prospectively
- No retrospective application
- Disclose as change in estimate

---

## Change in Reporting Entity

### Definition

A change that results in financial statements that are effectively those of a different reporting entity.

### Examples

| Change |
|--------|
| Consolidated statements now include previously excluded subsidiary |
| Change in subsidiaries included in consolidation |
| Change from cost/equity to consolidated statements |

### Treatment: Retrospective

- Restate all prior periods presented
- As if new reporting entity had always existed
- Disclose nature and reason for change

---

## Error Corrections

### Definition

An error in previously issued financial statements resulting from:
- Mathematical mistakes
- Mistakes in applying GAAP
- Oversight or misuse of facts
- Fraud

### Examples

| Type | Example |
|------|---------|
| Mathematical | Calculation error in depreciation |
| GAAP misapplication | Improper revenue recognition |
| Oversight | Failed to accrue expense |
| Fraud | Intentional misstatement |

### Treatment: Retrospective Restatement

**Step 1:** Correct each prior period presented

**Step 2:** Adjust beginning retained earnings if error affects periods prior to earliest presented

**Step 3:** Disclose nature of error and effect on financial statements

### Journal Entry Format

**Correct prior period error discovered in current year:**

**Example:** Failed to record $20,000 depreciation in prior year (tax rate 25%)

```
Dr. Retained Earnings              $15,000
Dr. Deferred Tax Asset              $5,000
    Cr. Accumulated Depreciation            $20,000
```

### Restatement vs. Revision

| Term | Meaning |
|------|---------|
| **Restatement** | Correction of material error; prior periods restated |
| **Revision** | Correction of immaterial error; prior periods may be revised |
| **Out-of-period adjustment** | Correction in current period (when prior period correction impracticable or immaterial) |

### Little r vs. Big R (SEC Registrants)

| Type | Situation | Action |
|------|-----------|--------|
| **Big R Restatement** | Prior period materially misstated | Amend prior filings (10-K/A, 10-Q/A) |
| **Little r Revision** | Prior immaterial, but would be material if corrected in current period | Revise comparatives in current filing |

---

## Practical Examples

### Example 1: Change in Accounting Principle (Retrospective)

**Facts:**
- Company changes inventory method from FIFO to weighted-average
- Two years of comparative statements presented (20X1, 20X2)
- 20X1 beginning inventory: FIFO $100,000, W/A $85,000
- 20X1 ending inventory: FIFO $120,000, W/A $100,000
- 20X2 ending inventory: FIFO $150,000, W/A $125,000
- Tax rate: 25%

**Cumulative Effect (Beginning 20X1):**
```
FIFO beginning inventory: $100,000
W/A beginning inventory: $85,000
Difference: $15,000 (pretax)
After tax: $15,000 × (1 - 0.25) = $11,250
```

**Journal Entry (as of beginning 20X1):**
```
Dr. Retained Earnings              $11,250
Dr. Deferred Tax Asset              $3,750
    Cr. Inventory                           $15,000
```

**Recast 20X1:**
- Reduce COGS by $5,000 (inventory change: $120K - $100K) - ($100K - $85K) = $5,000 less under W/A
- Adjust income tax accordingly

---

### Example 2: Error Correction

**Facts:**
- In 20X2, discovered that 20X1 failed to record accrued wages of $30,000
- Tax rate: 25%
- Currently preparing 20X2 financial statements with 20X1 comparatives

**Analysis:**
- 20X1 wages expense understated by $30,000
- 20X1 net income overstated by $22,500 (after tax)
- 20X1 accrued liabilities understated by $30,000
- 20X1 retained earnings overstated by $22,500

**Restatement Entry:**
```
Dr. Retained Earnings (20X1)       $22,500
Dr. Deferred Tax Asset              $7,500
    Cr. Accrued Wages                       $30,000
```

**Presentation:**
- Restate 20X1 to show correct amounts
- Disclose the error and its effects

---

### Example 3: Change in Estimate

**Facts:**
- Building cost: $1,000,000
- Original life: 40 years, no salvage
- Straight-line depreciation
- After 10 years, remaining life estimated at 20 years (not original 30)

**Original depreciation:** $1,000,000 / 40 = $25,000/year
**Accumulated depreciation after 10 years:** $250,000
**Carrying amount:** $750,000

**New depreciation:**
```
$750,000 / 20 years = $37,500/year
```

**No adjustment to prior periods.**

---

## Disclosure Requirements

### Change in Accounting Principle

| Disclosure |
|------------|
| Nature of change |
| Reasons for change (including why new principle preferable) |
| Method of applying change |
| Effect on current and prior periods (line items affected) |
| Cumulative effect on retained earnings |
| If retrospective application impracticable, reasons why |

### Change in Accounting Estimate

| Disclosure |
|------------|
| Nature of change |
| Effect on income from continuing operations, net income, and EPS (current period) |
| Effect on future periods (if material and estimable) |

### Error Correction

| Disclosure |
|------------|
| Nature of error |
| Effect on each prior period presented |
| Effect on retained earnings at beginning of earliest period |
| Cumulative effect of change |
| If restatement impracticable, reasons why |

---

## Interim Period Considerations

### Change in Accounting Principle

- Apply retrospectively to interim periods of current and prior fiscal years
- Disclose in interim period of change

### Change in Estimate

- Recognize in interim period of change
- If material, disclose nature and amount

### Error Correction

- Restate all interim periods affected
- Disclose nature and effect

---

## SEC Considerations (Public Companies)

### Material Misstatement Disclosure

- File 8-K (Item 4.02) if previously issued statements should not be relied upon
- Discuss with audit committee
- May require restatement

### SAB 99: Materiality

Consider both quantitative and qualitative factors:
- Percentage of pretax income, revenue, assets
- Segment information impact
- Trend analysis
- Analyst expectations
- Management compensation thresholds
- Regulatory compliance

### SAB 108: Error Evaluation

Use dual approach:
- **Rollover method:** Current period impact
- **Iron curtain method:** Balance sheet impact
- Error is material if material under either method

---

## Common Implementation Issues

### 1. Classification of Changes
- Misclassifying estimate change as principle change
- Not recognizing change in estimate effected by principle change
- Treating error as change in estimate

### 2. Retrospective Application
- Not restating all periods presented
- Calculation errors in cumulative effect
- Missing required disclosures

### 3. Materiality Assessment
- Only considering current period
- Ignoring qualitative factors
- Not aggregating similar errors

### 4. Tax Effects
- Forgetting to record deferred tax impact
- Using wrong tax rate
- Ignoring tax carryforwards

### 5. Disclosure
- Insufficient detail about nature of change
- Missing EPS impact
- Not explaining preferability (principle changes)

---

## Decision Tree: Identifying the Type of Change

```
Is there an error in prior financial statements?
├── YES → ERROR CORRECTION (Retrospective restatement)
└── NO → Is there a change from one GAAP to another?
          ├── YES → Is it inseparable from a change in estimate?
          │         ├── YES → CHANGE IN ESTIMATE (Prospective)
          │         └── NO → CHANGE IN PRINCIPLE (Retrospective)
          └── NO → Is it a change in reporting entity?
                    ├── YES → CHANGE IN ENTITY (Retrospective)
                    └── NO → Is there new information or experience?
                              ├── YES → CHANGE IN ESTIMATE (Prospective)
                              └── NO → No accounting change
```

---

## External Resources

- [FASB ASC 250](https://asc.fasb.org/)
- [SEC SAB 99—Materiality](https://www.sec.gov/)
- [SEC SAB 108—Considering the Effects of Prior Year Misstatements](https://www.sec.gov/)
- [KPMG: Handbook—Accounting Changes and Error Corrections](https://frv.kpmg.us/)
- [PwC: Financial Statement Presentation Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Accounting Changes and Error Corrections](https://www.iasplus.com/en-us)

---

## Navigation

← [Back to Presentation (200s)](README.md) | [Back to Main Guide](../../README.md)
