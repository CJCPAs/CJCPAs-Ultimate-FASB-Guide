# ASC 954: Health Care Entities

> The comprehensive standard for accounting and financial reporting by healthcare organizations.

## Overview

ASC 954 provides guidance on accounting and financial reporting specific to healthcare entities, including hospitals, nursing homes, continuing care retirement communities (CCRCs), managed care organizations, and other healthcare providers. The standard addresses unique aspects of healthcare operations including charity care, third-party payor settlements, and malpractice claims.

**Core Principle:**
> "Healthcare entities should present financial statements that reflect the unique nature of healthcare services and the various sources of payment for those services."

---

## Scope

### Applies To:
- Hospitals
- Nursing homes and long-term care facilities
- Home health agencies
- Health maintenance organizations (HMOs)
- Continuing care retirement communities (CCRCs)
- Physician practices and clinics
- Ambulatory surgery centers
- Rehabilitation facilities
- Other healthcare service providers

### Does NOT Apply To:
- Pharmaceutical companies (general GAAP)
- Medical device manufacturers (general GAAP)
- Health insurance companies (ASC 944)
- Entities that do not provide healthcare services

---

## Revenue Recognition

### Patient Service Revenue (ASC 606 Integration)

Healthcare entities apply ASC 606 for revenue from contracts with patients/third-party payors.

**Key Considerations:**

| Element | Healthcare Application |
|---------|----------------------|
| **Contract identification** | Patient registration, insurance verification |
| **Performance obligation** | Healthcare services (often combined) |
| **Transaction price** | Expected amount to collect (variable consideration) |
| **Allocation** | Typically single performance obligation |
| **Recognition** | Generally over time as services provided |

### Variable Consideration

Healthcare revenue is highly variable due to:
- Contractual adjustments (insurance discounts)
- Charity care policies
- Self-pay discounts
- Bad debt expectations

### Presentation of Revenue

**Net Revenue Presentation:**

| Component | Treatment |
|-----------|-----------|
| Gross charges | Not presented separately |
| Contractual adjustments | Implicit price concession |
| Bad debt (implicit price concession) | Reduce revenue |
| **Net patient service revenue** | Report on statement of operations |

**Example Revenue Calculation:**
```
Gross patient charges:              $10,000,000
Less: Contractual adjustments:      (4,500,000)
Less: Implicit price concessions:     (500,000)
Net patient service revenue:        $5,000,000
```

### Journal Entry—Patient Services

```
Dr. Accounts Receivable             $5,000,000
    Cr. Net Patient Service Revenue        $5,000,000
```

---

## Charity Care

### Definition

Healthcare services provided free or at reduced charge to patients who meet the entity's financial assistance criteria.

### Measurement

Charity care is **NOT revenue**—it represents services provided without expectation of payment.

### Disclosure Requirements

| Required Disclosure |
|--------------------|
| Description of charity care policy |
| Level of charity care provided (at cost) |
| Method for determining costs |
| Funds received to offset charity care |

### Calculating Charity Care at Cost

**Cost-to-Charge Ratio Method:**
```
Charity care at cost = Charity care charges × Cost-to-charge ratio

Example:
Charity care charges: $2,000,000
Cost-to-charge ratio: 45%
Charity care at cost: $2,000,000 × 45% = $900,000
```

### Charity Care vs. Bad Debt

| Charity Care | Bad Debt |
|--------------|----------|
| Patient qualifies for financial assistance | Patient expected to pay but doesn't |
| Known at time of service | Determined after billing efforts |
| Never recorded as revenue | Under ASC 606, implicit price concession |
| Disclosed at cost | Reduces transaction price |

---

## Third-Party Payor Arrangements

### Types of Payors

| Payor Type | Reimbursement Method |
|------------|---------------------|
| **Medicare** | Prospective payment (DRG), fee schedules |
| **Medicaid** | State-specific, often cost-based or fee schedule |
| **Commercial insurance** | Negotiated rates, % of charges |
| **Self-pay** | Charges less self-pay discounts |

### Contractual Adjustments

Difference between gross charges and amounts expected from third-party payors.

**Example:**
```
Gross charges:                  $50,000
Medicare allowed amount:        $35,000
Contractual adjustment:         $15,000
```

### Settlement Estimates

Many government programs subject to retrospective adjustment:
- Cost report settlements
- Audit adjustments
- Rate changes

**Journal Entry—Estimated Settlement Payable:**
```
Dr. Net Patient Service Revenue         $XXX
    Cr. Estimated Third-Party Settlements     $XXX
```

**Journal Entry—Settlement Receivable:**
```
Dr. Estimated Third-Party Settlements   $XXX
    Cr. Net Patient Service Revenue           $XXX
```

---

## Malpractice Claims

### Self-Insurance

Many healthcare entities self-insure for professional liability (malpractice).

### Liability Recognition (ASC 450)

| Criterion | Recognition |
|-----------|-------------|
| **Probable and estimable** | Accrue liability |
| **Reasonably possible** | Disclose in notes |
| **Remote** | No accrual or disclosure required |

### Components of Malpractice Liability

| Component | Description |
|-----------|-------------|
| **Reported claims** | Claims filed, estimate individually |
| **IBNR (Incurred but not reported)** | Actuarial estimate of unreported claims |
| **Claims expenses** | Legal and administrative costs |

### Journal Entry—Malpractice Liability

```
Dr. Malpractice Expense                 $XXX
    Cr. Estimated Malpractice Liability       $XXX
```

### Discounting

May discount to present value if:
- Timing of payments reasonably determinable
- Applied consistently
- Disclosed

---

## Continuing Care Retirement Communities (CCRCs)

### Overview

CCRCs provide housing and various levels of healthcare to residents, typically involving:
- Independent living
- Assisted living
- Skilled nursing care

### Entrance Fees

| Type | Recognition |
|------|-------------|
| **Refundable** | Liability until refund obligation expires |
| **Nonrefundable** | Deferred and amortized over resident life expectancy |
| **Partially refundable** | Split accounting |

### Journal Entry—Nonrefundable Entrance Fee

**At Move-in:**
```
Dr. Cash                                $300,000
    Cr. Deferred Revenue—Entrance Fees        $300,000
```

**Monthly Amortization (20-year expected stay):**
```
Dr. Deferred Revenue—Entrance Fees      $1,250
    Cr. Entrance Fee Revenue                   $1,250
```

### Obligation to Provide Future Services

**Liability Recognition:**
When present value of future costs exceeds:
- Present value of future revenues, plus
- Unamortized deferred entrance fees

**Journal Entry—Future Service Obligation:**
```
Dr. Operating Expense                   $XXX
    Cr. Obligation to Provide Future Services $XXX
```

### Refundable Entrance Fees

If refundable upon death or withdrawal:
- Record as liability
- Reduce as refund obligation decreases
- Amortize portion earned over expected stay

---

## Capitation Arrangements

### Definition

Fixed payment per member per period, regardless of services provided.

### Revenue Recognition

**Premium Revenue:**
```
Dr. Cash (or Receivable)               $XXX
    Cr. Premium Revenue                       $XXX
```

### Medical Claims Expense

Recognize as services are provided to members:
- Paid claims
- Unpaid claims liability (IBNR)

**Journal Entry—Medical Claims:**
```
Dr. Medical Claims Expense              $XXX
    Cr. Cash                                   $XXX
    Cr. Medical Claims Payable                 $XXX
```

### Medical Loss Ratio

Key metric for managed care:
```
Medical Loss Ratio = Medical Claims Expense ÷ Premium Revenue
```

---

## Grants and Contributions

### Government Grants

| Grant Type | Recognition |
|------------|-------------|
| **Conditional** | Recognize when conditions met |
| **Unconditional** | Recognize when grant awarded |
| **Cost-reimbursement** | Recognize as costs incurred |

### Journal Entry—Conditional Grant

**At Award (conditions not met):**
```
Dr. Cash                                $500,000
    Cr. Refundable Advance                    $500,000
```

**As Conditions Met:**
```
Dr. Refundable Advance                  $100,000
    Cr. Grant Revenue                         $100,000
```

### Contributions (Not-for-Profit Healthcare)

Apply ASC 958 contribution guidance for not-for-profit healthcare entities.

---

## Practical Examples

### Example 1: Hospital Revenue Recognition

**Facts:**
- Patient admitted for surgery
- Gross charges: $75,000
- Medicare patient
- Medicare allowed amount: $45,000
- Medicare pays 80%: $36,000
- Patient responsible for 20%: $9,000
- Patient qualifies for charity care on copay

**Analysis:**
```
Transaction price:
- Medicare portion: $36,000 (expected to collect)
- Patient portion: $0 (charity care)
Total transaction price: $36,000
```

**Journal Entry:**
```
Dr. Accounts Receivable—Medicare        $36,000
    Cr. Net Patient Service Revenue           $36,000
```

**Charity Care Disclosure:**
- Charges forgiven: $9,000
- Cost of charity care: $9,000 × 50% = $4,500

---

### Example 2: Malpractice Self-Insurance

**Facts:**
- Hospital self-insures for malpractice
- Three pending claims with probable liability
- Claim estimates: $500,000, $300,000, $200,000
- IBNR estimate (actuarial): $1,500,000
- Legal costs estimate: $250,000

**Total Liability:**
```
Reported claims:    $1,000,000
IBNR:              $1,500,000
Legal costs:         $250,000
Total:             $2,750,000
```

**Journal Entry:**
```
Dr. Malpractice Expense                 $2,750,000
    Cr. Estimated Malpractice Liability       $2,750,000
```

---

### Example 3: CCRC Entrance Fee

**Facts:**
- Resident pays $400,000 entrance fee
- 80% refundable upon departure
- 20% nonrefundable
- Expected residency: 10 years

**At Move-in:**
```
Dr. Cash                                $400,000
    Cr. Refundable Entrance Fee Liability     $320,000
    Cr. Deferred Revenue—Entrance Fee          $80,000
```

**Monthly Amortization:**
```
Nonrefundable portion: $80,000
Monthly amortization: $80,000 ÷ 120 months = $667

Dr. Deferred Revenue—Entrance Fee          $667
    Cr. Entrance Fee Revenue                    $667
```

**As Refund Obligation Decreases:**
If contract provides declining refund over 5 years:
```
Monthly reduction: $320,000 ÷ 60 months = $5,333

Dr. Refundable Entrance Fee Liability    $5,333
    Cr. Entrance Fee Revenue                   $5,333
```

---

### Example 4: Medicare Cost Report Settlement

**Facts:**
- Hospital estimates final Medicare settlement
- Prior year cost report under audit
- Expected additional payment: $250,000
- Uncertainty exists regarding allowable costs

**Recording Estimate:**
```
Dr. Estimated Third-Party Settlements   $250,000
    Cr. Net Patient Service Revenue           $250,000
```

**When Settlement Received (actual: $200,000):**
```
Dr. Cash                                $200,000
Dr. Net Patient Service Revenue          $50,000
    Cr. Estimated Third-Party Settlements     $250,000
```

---

## Financial Statement Presentation

### Statement of Operations

**Typical Format:**

| Line Item |
|-----------|
| Net patient service revenue |
| Premium revenue |
| Other operating revenue |
| **Total operating revenue** |
| Operating expenses by function |
| **Operating income** |
| Nonoperating gains (losses) |
| **Excess of revenues over expenses** |

### Performance Indicator

For not-for-profit healthcare entities, analogous to net income:
- "Excess of revenues over expenses"
- "Change in unrestricted net assets from operations"

### Required Disclosures

| Disclosure |
|------------|
| Charity care policy and amount at cost |
| Revenue by major payor class |
| Concentration of credit risk |
| Third-party payor settlements |
| Malpractice insurance coverage and claims |
| Related party transactions |

---

## Common Implementation Issues

### 1. Revenue Recognition Under ASC 606
- Determining implicit price concessions
- Portfolio approach for similar contracts
- Transition from gross to net presentation

### 2. Charity Care vs. Bad Debt
- Proper classification timing
- Consistent policy application
- Documentation requirements

### 3. Third-Party Settlements
- Estimation uncertainty
- Proper revenue adjustment
- Disclosure of contingencies

### 4. CCRC Accounting
- Entrance fee allocation
- Future service obligation calculation
- Actuarial assumptions

### 5. Malpractice Liability
- IBNR estimation
- Adequacy of reserves
- Discounting appropriateness

---

## Private Company Considerations

### Simplified Approaches

Private healthcare entities may:
- Use simplified actuarial methods
- Apply less complex estimation techniques
- Consider cost-benefit of disclosures

### Common Structures

| Structure | Considerations |
|-----------|----------------|
| Physician practices | Less complex revenue arrangements |
| Small hospitals | May lack actuarial resources |
| Nursing homes | Focus on Medicaid/Medicare |

---

## Regulatory Considerations

### Medicare/Medicaid Compliance

- Cost report filing requirements
- Audit adjustments
- Provider enrollment

### State Regulations

- Certificate of need
- Rate setting
- Reporting requirements

### IRS (Tax-Exempt)

- Community benefit reporting
- Charity care documentation
- Form 990 Schedule H

---

## External Resources

- [FASB ASC 954](https://asc.fasb.org/)
- [AICPA Health Care Entities Guide](https://www.aicpa.org/)
- [HFMA (Healthcare Financial Management Association)](https://www.hfma.org/)
- [CMS Medicare Provider Reimbursement Manual](https://www.cms.gov/)
- [Deloitte: Healthcare Industry Accounting Guide](https://www.iasplus.com/en-us)

---

## Navigation

← [Back to Industry (900s)](README.md) | [Back to Main Guide](../../README.md)
