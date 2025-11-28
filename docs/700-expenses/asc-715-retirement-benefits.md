# ASC 715: Compensation—Retirement Benefits

> The comprehensive standard for accounting for defined benefit pension plans and other postretirement benefits.

## Overview

ASC 715 establishes the accounting and reporting requirements for employers that sponsor defined benefit pension plans and other postretirement benefit plans (OPEB). The standard requires recognition of the funded status of defined benefit plans on the balance sheet.

**Core Principle:**
> "An employer shall recognize the funded status of a benefit plan—measured as the difference between plan assets at fair value and the benefit obligation—as an asset or liability in its statement of financial position."

---

## Scope

### Applies To:
- Single-employer defined benefit pension plans
- Other postretirement benefit plans (OPEB)—retiree health, life insurance
- Multiemployer plan disclosures
- Defined contribution plan expense

### Does NOT Apply To:
- Employee benefit plan financial statements (ASC 960, 962, 965)
- Stock compensation (ASC 718)
- Deferred compensation (ASC 710)

---

## Key Definitions

### Plan Types

| Type | Employer Obligation | Risk Bearer |
|------|---------------------|-------------|
| **Defined benefit** | Pay specified benefit at retirement | Employer bears investment and actuarial risk |
| **Defined contribution** | Make specified contributions | Employee bears investment risk |

### Defined Benefit Plan Components

| Term | Definition |
|------|------------|
| **Projected Benefit Obligation (PBO)** | Present value of benefits earned, considering future salary increases |
| **Accumulated Benefit Obligation (ABO)** | Present value of benefits earned, using current salaries |
| **Vested Benefit Obligation (VBO)** | Present value of vested benefits only |
| **Plan Assets** | Assets held by the plan at fair value |
| **Funded Status** | Plan assets minus PBO (or ABO for OPEB) |

### Relationship of Benefit Obligations

```
VBO ≤ ABO ≤ PBO

VBO: Benefits employee is entitled to if they leave today
ABO: Benefits earned to date at current salaries
PBO: Benefits earned to date considering future salary increases
```

---

## Net Periodic Pension Cost

### Components

| Component | Description | I/S Classification |
|-----------|-------------|-------------------|
| **Service cost** | Present value of benefits earned during current period | Operating |
| **Interest cost** | Growth of PBO due to passage of time | Non-operating |
| **Expected return on plan assets** | Reduces expense (shown as negative) | Non-operating |
| **Amortization of prior service cost** | Plan amendments—spread over remaining service | Non-operating |
| **Amortization of net gain/loss** | Experience differences—corridor approach | Non-operating |

### Presentation (ASU 2017-07)

**Only service cost** is presented with other employee compensation costs in operating income. All other components are presented below operating income (often in "Other income/expense").

### Basic Formula

```
Net Periodic Pension Cost =
    Service Cost
  + Interest Cost
  − Expected Return on Plan Assets
  + Amortization of Prior Service Cost
  + Amortization of Net Loss (or − Net Gain)
```

---

## Interest Cost

### Calculation

**Interest Cost = Beginning PBO × Discount Rate**

(Adjusted for benefit payments, if significant)

### Discount Rate

- High-quality corporate bond rate
- Matches timing and amount of expected benefit payments
- Often use bond indices (e.g., Aa corporate bond yields)

---

## Expected Return on Plan Assets

### Calculation

**Expected Return = Beginning Fair Value of Plan Assets × Expected Long-Term Rate of Return**

### Expected Rate of Return

- Based on long-term expectations
- Consider asset allocation and historical returns
- Should be consistent with actuarial assumptions

### Actual vs. Expected Return

| Component | Treatment |
|-----------|-----------|
| Expected return | Reduces pension expense |
| Actual return | Not directly used in expense |
| Difference (gain/loss) | Goes to OCI, subject to amortization |

---

## Prior Service Cost

### Definition

Cost of retroactive benefits granted by plan amendments (plan initiation or change increasing benefits).

### Recognition

- Recognize in OCI at amendment date
- Amortize from OCI to expense over future service periods of active employees

### Amortization Methods

| Method | Description |
|--------|-------------|
| **Straight-line** | Over average remaining service period |
| **Years-of-service** | Weighted by expected years of service |

---

## Actuarial Gains and Losses

### Sources

| Source | Description |
|--------|-------------|
| **Assumption changes** | Changes in discount rate, mortality, turnover |
| **Experience adjustments** | Actual experience differs from assumptions |
| **Asset performance** | Actual return differs from expected return |

### Recognition—Corridor Approach

**Step 1:** Determine corridor
```
Corridor = 10% × Greater of (Beginning PBO or Plan Assets at FV)
```

**Step 2:** Calculate excess
```
Excess = |Net Unamortized Gain/Loss| − Corridor
```

**Step 3:** Amortize excess (if any)
```
Amortization = Excess ÷ Average Remaining Service Period
```

### Example: Corridor Calculation

**Given:**
- Net unamortized loss: $500,000
- Beginning PBO: $3,000,000
- Beginning plan assets: $2,800,000
- Average remaining service: 10 years

**Calculation:**
```
Corridor = 10% × $3,000,000 = $300,000
Excess = $500,000 − $300,000 = $200,000
Amortization = $200,000 ÷ 10 = $20,000
```

---

## Balance Sheet Recognition

### Funded Status

**Net Asset (Overfunded):** Plan assets > PBO
**Net Liability (Underfunded):** PBO > Plan assets

### Classification

| Component | Classification |
|-----------|----------------|
| Funded status | Noncurrent asset or liability (generally) |
| Benefits payable within 12 months | Current liability |

### Amounts in AOCI

| Item | Recorded in |
|------|-------------|
| Net actuarial loss (gain) | AOCI (debit for loss) |
| Prior service cost (credit) | AOCI (debit for cost) |

---

## Practical Example: Complete Pension Accounting

### Year 1 Data

| Item | Amount |
|------|-------:|
| Beginning PBO | $1,000,000 |
| Beginning plan assets (FV) | $900,000 |
| Service cost | $80,000 |
| Discount rate | 5% |
| Expected return rate | 7% |
| Actual return on assets | $72,000 |
| Benefits paid | $50,000 |
| Contributions | $100,000 |
| Prior service cost (unamortized) | $60,000 |
| Avg. remaining service (PSC) | 10 years |
| Net unamortized loss | $150,000 |
| Avg. remaining service (loss) | 15 years |

### Step 1: Calculate Net Periodic Pension Cost

| Component | Calculation | Amount |
|-----------|-------------|-------:|
| Service cost | Given | $80,000 |
| Interest cost | $1,000,000 × 5% | 50,000 |
| Expected return | $900,000 × 7% | (63,000) |
| Prior service cost amortization | $60,000 ÷ 10 | 6,000 |
| Net loss amortization | See below | 0 |
| **Net periodic pension cost** | | **$73,000** |

**Loss Amortization Check:**
- Corridor: 10% × $1,000,000 = $100,000
- Net loss: $150,000
- Excess: $150,000 − $100,000 = $50,000
- Amortization: $50,000 ÷ 15 = $3,333

**Revised Net Periodic Pension Cost:** $73,000 + $3,333 = **$76,333**

### Step 2: Calculate Ending PBO

| Item | Amount |
|------|-------:|
| Beginning PBO | $1,000,000 |
| Service cost | 80,000 |
| Interest cost | 50,000 |
| Benefits paid | (50,000) |
| Actuarial loss (gain) | Assume $20,000 loss |
| **Ending PBO** | **$1,100,000** |

### Step 3: Calculate Ending Plan Assets

| Item | Amount |
|------|-------:|
| Beginning plan assets | $900,000 |
| Actual return | 72,000 |
| Contributions | 100,000 |
| Benefits paid | (50,000) |
| **Ending plan assets** | **$1,022,000** |

### Step 4: Calculate Funded Status

```
Funded status = $1,022,000 − $1,100,000 = ($78,000) underfunded
```

### Step 5: Journal Entries

**Record pension expense:**
```
Dr. Pension Expense—Service Cost        $80,000
Dr. Pension Expense—Other Components    ($3,667)   [Net of other items]
    Cr. Pension Liability                         $76,333
```

**Or broken out:**
```
Dr. Pension Expense (Operating)         $80,000
Dr. Pension Expense (Non-operating)     ($3,667)
    Cr. PBO (increase)                           $130,000
    Cr. Plan Assets (increase for return)         72,000
    Dr. Plan Assets (contributions)              100,000
    [Net effect on liability: $76,333 increase]
```

**Simplied approach—adjust to funded status:**
```
Dr. Pension Expense                     $76,333
Dr. OCI—Net Loss                        $11,000
    Cr. Net Pension Liability                    $78,000
    Cr. OCI—Prior Service Cost                   $6,000
    Cr. OCI—Amortization of Loss                 $3,333
```

---

## Other Postretirement Benefits (OPEB)

### Key Differences from Pensions

| Aspect | Pension | OPEB |
|--------|---------|------|
| Benefit obligation | PBO | APBO (Accumulated Postretirement Benefit Obligation) |
| Salary assumption | Includes future increases | Not applicable (medical costs) |
| Key assumption | Discount rate, salary growth | Healthcare cost trend rate |
| Funding | Often funded | Often unfunded |

### Healthcare Cost Trend Rate

**Definition:** Assumed annual increase in healthcare costs

**Components:**
- Near-term rate (current year)
- Ultimate rate (rate after trend period)
- Years to reach ultimate rate

**Example:**
- Current rate: 7%
- Ultimate rate: 4.5%
- Years to ultimate: 5 years

### Sensitivity Disclosure

Required disclosure of effect on APBO and service cost of:
- 1% increase in healthcare trend rate
- 1% decrease in healthcare trend rate

---

## Multiemployer Plans

### Definition

Plan maintained by two or more unrelated employers, often under collective bargaining agreements.

### Accounting

- Expense = Required contributions for period
- No recognition of funded status on employer's balance sheet

### Disclosure Requirements (ASU 2011-09)

- Total contributions by employer
- Significant plans identified (by name, EIN)
- Funded status and financial health (zone status)
- Expiration dates of CBAs
- Whether surcharges have been paid
- Minimum contributions and funding improvement plans

### Zone Status

| Zone | Funded Status |
|------|---------------|
| **Green** | No funding issues |
| **Yellow** | Endangered (funding concerns) |
| **Orange** | Seriously endangered |
| **Red** | Critical (significant underfunding) |

---

## Private Company Considerations

### Practical Expedient—Measurement Date

Private companies may measure plan assets and obligations as of the month-end closest to fiscal year-end (up to 3 months prior).

**Example:** December 31 year-end may use September 30 measurement date.

### Simplified Approaches

| Area | Private Company Consideration |
|------|-------------------------------|
| Actuarial valuations | May be less frequent for small plans |
| Assumptions | May use standardized rates |
| Disclosures | Same requirements, but often simpler plans |

---

## Settlement and Curtailment

### Settlement

**Definition:** Irrevocable action that relieves employer of primary responsibility for obligation (e.g., lump-sum payment, annuity purchase).

**Accounting:**
- Recognize gain/loss immediately
- Measured as portion of unamortized gain/loss attributable to settled obligation

### Curtailment

**Definition:** Significant reduction in expected future service or accrual of benefits (e.g., plant closing, benefit freeze).

**Accounting:**
- Recognize prior service cost related to eliminated future service
- Recognize gain/loss if PBO decreases/increases

---

## Disclosure Requirements

### Required Disclosures

| Category | Items |
|----------|-------|
| **Benefit obligations** | Reconciliation of beginning to ending PBO |
| **Plan assets** | Reconciliation of beginning to ending fair value |
| **Funded status** | Amounts recognized on balance sheet |
| **AOCI** | Amounts in AOCI (prior service, net gain/loss) |
| **Net periodic cost** | Components of pension expense |
| **Assumptions** | Discount rate, expected return, salary increases |
| **Expected cash flows** | Contributions expected next year; benefit payments for 5+ years |
| **Plan assets** | Fair value by category, hierarchy levels |

### Example Disclosure Note (Excerpt)

> **Pension Plan Assumptions:**
>
> | | 20X2 | 20X1 |
> |--|-----:|-----:|
> | Discount rate | 5.00% | 4.75% |
> | Expected return on plan assets | 6.50% | 7.00% |
> | Rate of compensation increase | 3.00% | 3.00% |

---

## Common Implementation Issues

### 1. Discount Rate Selection
- Not matching rate to plan's payment timing
- Using inappropriate index
- Not updating annually

### 2. Expected Return on Assets
- Overly optimistic assumptions
- Not consistent with asset allocation
- Not adjusting for plan maturity

### 3. Corridor Calculation
- Using wrong base (PBO vs. ABO for OPEB)
- Calculation errors in excess amount
- Wrong service period denominator

### 4. Presentation
- Including non-service cost in operating income
- Incorrect classification of funded status
- Missing AOCI disclosures

### 5. Healthcare Cost Trend
- Not considering Medicare Part D subsidy
- Unrealistic ultimate trend rate
- Missing sensitivity disclosure

---

## External Resources

- [FASB ASC 715](https://asc.fasb.org/)
- [KPMG: Handbook—Retirement Benefits](https://frv.kpmg.us/)
- [PwC: Pension and Other Postretirement Benefits Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Retirement Benefits](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Retirement Benefits](https://www.ey.com/)
- [Society of Actuaries](https://www.soa.org/)

---

## Navigation

← [Back to Expenses (700s)](README.md) | [Back to Main Guide](../../README.md)
