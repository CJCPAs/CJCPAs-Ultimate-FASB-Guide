# ASC 710: Compensation—General

> Foundational guidance on employer accounting for various forms of employee compensation.

## Overview

ASC 710 provides guidance on compensation arrangements other than retirement benefits (ASC 715), stock compensation (ASC 718), and nonretirement postemployment benefits (ASC 712). This topic covers general compensation matters including deferred compensation, compensated absences, and sabbatical leaves.

**Core Principle:**
> "Compensation expense shall be recognized in the period the employee provides services, with liabilities accrued when the obligation is probable and reasonably estimable."

---

## Scope

### Applies To:
- Deferred compensation arrangements
- Compensated absences (vacation, sick leave)
- Sabbatical leave
- Bonus and incentive arrangements
- Lump-sum payments under union contracts

### Does NOT Apply To:
- Retirement benefits (ASC 715)
- Stock-based compensation (ASC 718)
- Postemployment benefits (termination, disability—ASC 712)
- Exit/disposal activities (ASC 420)

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Compensated Absences** | Employee absences (vacation, illness, holidays) for which employees are paid |
| **Vested Rights** | Employee entitled to payment even upon termination |
| **Accumulated Rights** | Rights that can be carried forward if not used |
| **Deferred Compensation** | Compensation earned currently but paid in future |
| **Rabbi Trust** | Irrevocable trust to fund deferred compensation (not protected from creditors) |

---

## Compensated Absences

### Recognition Criteria

Accrue a liability for compensated absences when **ALL** of the following are met:

| Criterion | Description |
|-----------|-------------|
| **1. Services already rendered** | Obligation relates to past services |
| **2. Rights vest or accumulate** | Employees can carry forward or receive payment |
| **3. Payment is probable** | Likelihood of future use/payment |
| **4. Amount is estimable** | Can reasonably estimate |

### Vacation Pay

**Typically meets all criteria—ACCRUE**

| Feature | Treatment |
|---------|-----------|
| Vests | Accrued (paid upon termination) |
| Accumulates | Accrued (carries forward) |
| Non-vesting, non-accumulating | Generally not accrued |

### Sick Pay

**May not meet all criteria—analyze carefully**

| Type | Accrue? | Reason |
|------|---------|--------|
| **Vesting sick pay** | Yes | Paid if unused |
| **Accumulating, paid upon termination** | Yes | Will be paid |
| **Accumulating, use-it-or-lose-it** | Maybe | Payment not certain |
| **Non-accumulating** | No | Relates to future absence |

---

## Journal Entries—Compensated Absences

### Accrual of Vacation Pay

**Year-End Accrual:**
```
Dr. Compensation Expense             $150,000
    Cr. Accrued Vacation Liability           $150,000
```

**Components:**
- Number of unused vacation days/hours
- Current pay rates (or expected future rates)
- Employer-paid payroll taxes and benefits

### When Vacation Taken

```
Dr. Accrued Vacation Liability       $1,200
    Cr. Cash/Wages Payable                    $1,200
(No additional expense if previously accrued)
```

### Vacation Paid Upon Termination

```
Dr. Accrued Vacation Liability       $3,000
    Cr. Cash                                   $3,000
```

---

## Sabbatical Leave

### Types of Sabbatical

| Type | Purpose | Accrual |
|------|---------|---------|
| **Benefit sabbatical** | Employee benefit (no service requirement during) | Accrue over period leading to sabbatical |
| **Research sabbatical** | Compensated for specific activities during leave | Expense during sabbatical period |

### Benefit Sabbatical

**Example:** After 7 years of service, employee receives 1 month paid leave.

**Annual Accrual:**
```
Dr. Compensation Expense              $2,000
    Cr. Sabbatical Liability                   $2,000
(Annual accrual = 1 month pay / 7 years)
```

### Research Sabbatical

**Example:** Professor receives sabbatical to write book.

**During Sabbatical Period:**
```
Dr. Compensation Expense              $8,000
    Cr. Cash/Wages Payable                    $8,000
(Expense during leave period—service being provided)
```

---

## Deferred Compensation

### Overview

Deferred compensation includes:
- Supplemental executive retirement plans (SERPs)
- Non-qualified deferred compensation (NQDC)
- Bonus deferrals
- Performance-based long-term incentives

### Recognition

| Timing | Expense Recognition |
|--------|---------------------|
| **Service-based** | Over requisite service period |
| **Performance-based** | When performance achieved |
| **Fixed payment schedule** | Present value of future payments |

### Measurement

| Approach | Description |
|----------|-------------|
| **Defined benefit approach** | PV of estimated future payments |
| **Defined contribution approach** | Amount contributed/allocated |

---

## Journal Entries—Deferred Compensation

### Defined Contribution Approach

**Employer credits account annually:**
```
Dr. Deferred Compensation Expense     $50,000
    Cr. Deferred Compensation Liability        $50,000
```

### Defined Benefit Approach

**Accrue present value of future obligation:**
```
Dr. Deferred Compensation Expense    $100,000
    Cr. Deferred Compensation Liability       $100,000
(Accrual during service period)
```

### Payment Upon Retirement

```
Dr. Deferred Compensation Liability   $50,000
    Cr. Cash                                   $50,000
```

---

## Rabbi Trusts

### Overview

A rabbi trust is an irrevocable trust established to fund deferred compensation:
- Assets remain subject to creditor claims (in bankruptcy)
- Provides employee security (employer can't access funds)
- NOT a "funded" plan for tax purposes

### Accounting Treatment

**Assets remain on employer's books:**
```
Dr. Rabbi Trust Assets               $500,000
    Cr. Cash                                  $500,000
```

**Liability still recognized:**
```
Dr. Deferred Compensation Expense     $50,000
    Cr. Deferred Compensation Liability        $50,000
```

**Investment earnings in trust:**
```
Dr. Rabbi Trust Assets                $25,000
    Cr. Investment Income                      $25,000
```

### Balance Sheet Presentation

| Item | Presentation |
|------|--------------|
| **Trust assets** | Asset (often "Investments in deferred compensation trust") |
| **Deferred compensation liability** | Liability |
| **Net presentation** | May net if permitted |

---

## Bonus and Incentive Compensation

### Recognition Timing

| Type | When to Accrue |
|------|----------------|
| **Discretionary bonus** | When authorized |
| **Formula-based bonus** | When earned (usually period-end) |
| **Performance bonus** | When performance condition met |
| **Retention bonus** | Over requisite service period |

### Annual Bonus Example

**Year-End Accrual (formula-based):**
```
Dr. Bonus Expense                    $200,000
    Cr. Accrued Bonus                        $200,000
```

**Payment in Following Year:**
```
Dr. Accrued Bonus                    $200,000
    Cr. Cash                                  $200,000
```

### Sign-On Bonus (with Clawback)

**At hire date:**
```
Dr. Prepaid Bonus (Asset)            $25,000
    Cr. Cash                                   $25,000
```

**Amortization over required service period (e.g., 2 years):**
```
Dr. Bonus Expense                     $1,042
    Cr. Prepaid Bonus                          $1,042
(Monthly amortization: $25,000 / 24 months)
```

---

## Lump-Sum Union Contract Payments

### Overview

When a new union contract is signed, sometimes a lump-sum payment is made to employees.

### Accounting

| Arrangement | Treatment |
|-------------|-----------|
| **Payment for past services** | Expense immediately |
| **Payment for future services** | Expense over contract term |
| **Hybrid** | Allocate based on nature |

**Lump-sum for past services:**
```
Dr. Compensation Expense             $300,000
    Cr. Cash/Accrued Liabilities             $300,000
```

---

## Practical Examples

### Example 1: Vacation Accrual Calculation

**Facts:**
- 100 employees
- Average unused vacation: 5 days per employee
- Average daily rate: $200
- Employer payroll taxes: 7.65%
- Employer benefits: 10%

**Calculation:**
```
Base vacation pay: 100 × 5 × $200 = $100,000
Payroll taxes: $100,000 × 7.65% = $7,650
Benefits: $100,000 × 10% = $10,000
Total accrual: $117,650
```

**Journal Entry:**
```
Dr. Compensation Expense            $117,650
    Cr. Accrued Vacation                     $117,650
```

---

### Example 2: Deferred Compensation—Executive SERP

**Facts:**
- Executive hired age 45
- Retires at age 65 (20 years service)
- SERP provides $100,000 annual payments for 10 years starting at retirement
- Discount rate: 5%

**Step 1: PV at Retirement**
```
PV of 10 payments of $100,000 at 5% = $772,173
```

**Step 2: Annual Accrual**
```
$772,173 / 20 years = $38,609 per year
```

**Annual Entry:**
```
Dr. SERP Expense                     $38,609
    Cr. SERP Liability                        $38,609
```

---

### Example 3: Rabbi Trust Accounting

**Facts:**
- Establish rabbi trust with $1,000,000
- Trust invests in mutual funds
- Trust earns $50,000 during year
- Pay $75,000 to retirees from trust

**Establish Trust:**
```
Dr. Rabbi Trust Investments        $1,000,000
    Cr. Cash                                $1,000,000
```

**Investment Earnings:**
```
Dr. Rabbi Trust Investments           $50,000
    Cr. Investment Income                      $50,000
```

**Payments to Retirees:**
```
Dr. Deferred Compensation Liability   $75,000
    Cr. Rabbi Trust Investments               $75,000
```

---

## Private Company Considerations

### Common Issues

| Issue | Consideration |
|-------|---------------|
| **Owner compensation** | Distinguish from distributions |
| **Related party arrangements** | Document terms carefully |
| **Informal arrangements** | May still require accrual |
| **State law** | Vacation payout requirements vary |

### Simplified Approaches

| Area | Approach |
|------|----------|
| **Small workforce** | May calculate individually |
| **Stable workforce** | May use average rates |
| **Immaterial amounts** | Reduced documentation |

---

## Common Audit Issues

### Compensated Absences

| Issue | Audit Focus |
|-------|-------------|
| **Completeness** | All employee types included |
| **Accuracy** | Pay rates, balances correct |
| **Valuation** | Include related costs |
| **Policy compliance** | Follows company policy |

### Deferred Compensation

| Issue | Consideration |
|-------|---------------|
| **Terms** | Review plan documents |
| **Measurement** | Actuarial assumptions |
| **Rabbi trusts** | Proper consolidation |
| **Vesting** | Service requirements |

---

## Disclosure Requirements

### Required Disclosures

| Item | Disclosure |
|------|------------|
| **Policy** | Accounting policy for compensated absences |
| **Deferred compensation** | Terms and amounts |
| **Funding arrangements** | Rabbi trust assets |
| **Payment schedule** | Future payments if determinable |

### Example Disclosure

```
NOTE X: COMPENSATION AND BENEFITS

Compensated Absences
The Company accrues for vacation pay as earned. Employees may
carry over up to 40 hours of unused vacation to the following year.
At December 31, 20X1 and 20X0, accrued vacation totaled $420,000
and $385,000, respectively.

Deferred Compensation
The Company maintains a supplemental executive retirement plan
covering certain officers. The plan provides for benefit payments
upon retirement based on years of service and compensation levels.
The deferred compensation liability was $2,500,000 and $2,200,000
at December 31, 20X1 and 20X0, respectively.

The Company has established a rabbi trust to fund its deferred
compensation obligations. Trust assets of $2,100,000 and $1,900,000
at December 31, 20X1 and 20X0 are included in other assets.
```

---

## Recent Updates

| ASU | Topic | Impact |
|-----|-------|--------|
| **ASU 2020-04** | Reference Rate Reform | May affect discount rates |
| **ASU 2019-01** | Leases and Compensation | Coordination guidance |

---

## External Resources

- [FASB ASC 710](https://asc.fasb.org/)
- [FASB ASC 715 (Retirement Benefits)](https://asc.fasb.org/)
- [FASB ASC 712 (Postemployment Benefits)](https://asc.fasb.org/)
- [IRS Guidance on Deferred Compensation (409A)](https://www.irs.gov/)
- [KPMG: Handbook—Compensation](https://frv.kpmg.us/)
- [PwC: Employee Benefits Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Compensation](https://www.iasplus.com/en-us)

---

## Navigation

← [Back to Expenses (700s)](README.md) | [Back to Main Guide](../../README.md)
