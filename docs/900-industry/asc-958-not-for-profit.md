# ASC 958: Not-for-Profit Entities

> The comprehensive standard for accounting and financial reporting by not-for-profit organizations.

## Overview

ASC 958 provides guidance on accounting and financial reporting for not-for-profit entities, including the presentation of financial statements, revenue recognition for contributions, and accounting for split-interest agreements. The standard was significantly updated by ASU 2016-14, which improved the usefulness of financial statements.

**Core Principle:**
> "Not-for-profit financial statements should provide information about the amount and nature of net assets, how resources are used, and how an organization obtains and spends cash."

---

## Scope

### Applies To:
- Charitable organizations
- Foundations
- Religious organizations
- Trade associations
- Labor unions
- Professional associations
- Cultural institutions
- Social welfare organizations
- Most private colleges and universities
- Voluntary health and welfare organizations

### Does NOT Apply To:
- Governmental not-for-profits (GASB)
- For-profit entities
- Employee benefit plans

---

## Financial Statements Required

### Statement of Financial Position (Balance Sheet)

**Net Asset Classifications (ASU 2016-14):**

| Classification | Definition | Examples |
|----------------|------------|----------|
| **Without donor restrictions** | Not subject to donor-imposed restrictions | Unrestricted contributions, investment returns, program service fees |
| **With donor restrictions** | Subject to donor-imposed restrictions | Time-restricted gifts, purpose-restricted gifts, endowments |

**Note:** Previous three-category system (unrestricted, temporarily restricted, permanently restricted) was simplified to two categories.

### Statement of Activities (Income Statement)

Shows changes in net assets by classification:
- Revenues, gains, and other support
- Expenses (by function and nature)
- Change in net assets
- Reclassifications (releases from restrictions)

### Statement of Cash Flows

Same as for-profit entities under ASC 230:
- Operating activities
- Investing activities
- Financing activities

### Statement of Functional Expenses

**Required for:** All not-for-profits (expanded by ASU 2016-14)

**Presentation:** Matrix format showing expenses by:
- **Function** (columns): Program services, management/general, fundraising
- **Nature** (rows): Salaries, benefits, occupancy, supplies, etc.

---

## Contributions

### Definition

An unconditional transfer of cash or other assets to an entity, or settlement/cancellation of its liabilities, in a voluntary nonreciprocal transfer.

### Conditional vs. Unconditional

| Type | Characteristics | Recognition |
|------|-----------------|-------------|
| **Unconditional** | No barrier to entitlement | Recognize when promise received |
| **Conditional** | Barrier + right of return/release | Recognize when conditions met |

### Barriers (Indicators)

| Barrier Indicator |
|-------------------|
| Measurable performance-related requirement |
| Stipulated limited discretion over conduct of activities |
| Requirement to follow specific guidelines |
| Requirement to meet specified deliverables |

### Contribution Revenue Recognition

**Unconditional Contributions:**
```
Dr. Contributions Receivable (or Cash)    $XXX
    Cr. Contribution Revenue                      $XXX
```

**Conditional Contributions (before conditions met):**
```
Dr. Cash                                  $XXX
    Cr. Refundable Advance                        $XXX
```

**When conditions subsequently met:**
```
Dr. Refundable Advance                    $XXX
    Cr. Contribution Revenue                      $XXX
```

### Donor Restrictions

| Restriction Type | Net Asset Class | When Released |
|------------------|-----------------|---------------|
| **Purpose** | With donor restrictions | When purpose accomplished |
| **Time** | With donor restrictions | When time period elapses |
| **Perpetual (endowment)** | With donor restrictions | Never (principal); earnings may be released |

### Release from Restrictions

When restriction is satisfied:
```
Dr. Net Assets—With Donor Restrictions    $XXX
    Cr. Net Assets—Without Donor Restrictions     $XXX
```

**Presentation in Statement of Activities:**
- Show as reclassification between net asset classes
- Or show as release in "with restrictions" column

---

## Contributed Services

### Recognition Criteria

Recognize contributed services **only if** they:

| Criterion | Description |
|-----------|-------------|
| **Create or enhance nonfinancial assets** | Construction, improvements |
| **OR** | |
| **Require specialized skills** | Legal, accounting, medical, construction |
| **AND** | |
| **Would typically be purchased** | If not donated, would have been acquired |
| **AND** | |
| **Provided by persons with those skills** | Qualified professionals |

### Journal Entry—Contributed Services

```
Dr. Professional Services Expense         $XXX
    Cr. Contribution Revenue—In-Kind              $XXX
```

### Services NOT Typically Recognized

- General volunteer time
- Board member services
- Fundraising volunteer hours
- General office help

---

## Contributed Nonfinancial Assets (In-Kind)

### ASU 2020-07 Enhanced Disclosures

**Required Disclosures for Each Category:**
- Description of contributed nonfinancial assets
- Qualitative information about whether assets were monetized or used
- Donor restrictions
- Valuation techniques
- Principal market used for valuation

### Categories

| Category | Examples |
|----------|----------|
| Fixed assets | Land, buildings, equipment |
| Use of fixed assets | Office space, equipment use |
| Utilities | Donated utilities |
| Food/clothing | Donated inventory |
| Supplies | Office supplies, medical supplies |
| Advertising/media | PSAs, donated advertising |

### Measurement

**Fair Value** at date of gift

For property: Fair value typically from appraisal

---

## Endowments

### Types

| Type | Principal | Earnings |
|------|-----------|----------|
| **True (donor) endowment** | Permanently restricted | May be restricted or unrestricted |
| **Board-designated endowment** | Unrestricted (board can reverse) | Unrestricted |
| **Term endowment** | Restricted until time/event | May be restricted or unrestricted |

### UPMIFA (Uniform Prudent Management of Institutional Funds Act)

Many states have adopted UPMIFA, which allows spending from endowments based on prudent considerations rather than historical dollar value.

### Underwater Endowments

When fair value < original gift amount:
- Continue to classify as "with donor restrictions"
- Disclose aggregate fair value and original amounts
- Consider spending policy implications

### Endowment Disclosures

- Interpretation of relevant law
- Return objectives and risk parameters
- Spending policy
- Investment policy
- Composition of endowment by net asset class
- Roll-forward of endowment funds

---

## Net Asset Reclassifications

### Board Designations

**Creating Board Designation:**
Not a change in net asset classification—remains "without donor restrictions"

**Disclosure:** Board-designated amounts within unrestricted net assets

### Expirations/Satisfactions

**Time Restriction Expires:**
```
Dr. Net Assets—With Donor Restrictions    $XXX
    Cr. Net Assets—Without Donor Restrictions     $XXX
```

**Purpose Restriction Satisfied:**
Same entry when funds spent for designated purpose

---

## Practical Examples

### Example 1: Multi-Year Pledge

**Facts:**
- Donor pledges $300,000 over 3 years ($100,000/year)
- Unrestricted purpose
- Discount rate: 3%
- Present value: $291,347

**At Pledge Date:**
```
Dr. Pledges Receivable                   $300,000
    Cr. Discount on Pledges Receivable            $8,653
    Cr. Contribution Revenue—With Restrictions   $291,347
```

**Classification:** With donor restrictions (time restriction)

**Year 2—Amortize Discount:**
```
Dr. Discount on Pledges Receivable        $2,740
    Cr. Contribution Revenue                      $2,740
```

**When Cash Received Each Year:**
```
Dr. Cash                                 $100,000
    Cr. Pledges Receivable                       $100,000

Dr. Net Assets—With Donor Restrictions   $100,000
    Cr. Net Assets—Without Donor Restrictions    $100,000
```

---

### Example 2: Conditional Grant

**Facts:**
- Foundation awards $500,000 grant
- Condition: Must provide matched funds of $100,000
- Condition: Must serve 1,000 clients

**At Grant Award (conditions not met):**
```
Dr. Cash                                 $500,000
    Cr. Refundable Advance                       $500,000
```

**When Match Raised and Clients Served:**
```
Dr. Refundable Advance                   $500,000
    Cr. Contribution Revenue—Without Restrictions $500,000
```

---

### Example 3: Contributed Services

**Facts:**
- Attorney provides 50 hours of pro bono legal services
- Normal billing rate: $400/hour

**Recognition Test:**
- Specialized skills? Yes (attorney)
- Would be purchased? Yes
- Qualified provider? Yes

**Journal Entry:**
```
Dr. Legal Services Expense               $20,000
    Cr. Contribution Revenue—In-Kind             $20,000
```

---

### Example 4: Statement of Functional Expenses

**Presentation Format:**

| | Program A | Program B | Management | Fundraising | Total |
|--|----------:|----------:|-----------:|------------:|------:|
| Salaries | $200,000 | $150,000 | $75,000 | $50,000 | $475,000 |
| Benefits | 40,000 | 30,000 | 15,000 | 10,000 | 95,000 |
| Occupancy | 30,000 | 25,000 | 10,000 | 5,000 | 70,000 |
| Supplies | 15,000 | 10,000 | 3,000 | 2,000 | 30,000 |
| Professional fees | 10,000 | 8,000 | 20,000 | 5,000 | 43,000 |
| **Total** | **$295,000** | **$223,000** | **$123,000** | **$72,000** | **$713,000** |

---

## Agency Transactions

### Definition

Organization receives assets from a donor and agrees to transfer them to a specified beneficiary (agency transaction).

### Accounting

**Not a contribution to the agent organization:**
```
Dr. Cash                                 $XXX
    Cr. Liability to Beneficiary                 $XXX
```

### When Organization is NOT Agent

If organization has variance power or discretion:
- Record as contribution to the organization
- Record grant/contribution when transferred out

---

## Split-Interest Agreements

### Types

| Agreement | Description |
|-----------|-------------|
| **Charitable lead trust** | Charity receives income; remainder to donor/beneficiaries |
| **Charitable remainder trust** | Donor receives income; remainder to charity |
| **Charitable gift annuity** | Charity pays fixed annuity; remainder retained |
| **Pooled income fund** | Donor receives proportional income; remainder to charity |

### Accounting (Irrevocable)

**Recognize at Fair Value:**
- Asset received
- Liability for payments to others
- Contribution revenue for remainder interest

---

## Disclosure Requirements

### Required Disclosures (ASU 2016-14)

| Disclosure |
|------------|
| Net asset composition by type of restriction |
| Liquidity disclosures (qualitative and quantitative) |
| Board designations within unrestricted net assets |
| Endowment composition and policies |
| Expenses by function and nature |
| Methods of allocating costs among functions |
| Underwater endowments |
| Contributed nonfinancial assets (ASU 2020-07) |

### Liquidity Disclosure

**Required Information:**
- Qualitative: How organization manages liquidity
- Quantitative: Financial assets available within one year to meet cash needs

---

## Common Implementation Issues

### 1. Conditional vs. Unconditional
- Misidentifying barriers
- Premature revenue recognition
- Not tracking condition satisfaction

### 2. Functional Expense Allocation
- Unreasonable allocation methods
- Not documenting methodology
- Inconsistent application

### 3. Contributed Services
- Recognizing unqualified services
- Missing specialized services
- Improper valuation

### 4. Net Asset Classification
- Misclassifying restrictions
- Missing releases from restrictions
- Improper endowment classification

### 5. Related Party Considerations
- Contributed services from board members
- Related party transactions
- Proper disclosure

---

## External Resources

- [FASB ASC 958](https://asc.fasb.org/)
- [AICPA Not-for-Profit Entities Guide](https://www.aicpa.org/)
- [KPMG: Handbook—Not-for-Profit Entities](https://frv.kpmg.us/)
- [PwC: Not-for-Profit Guide](https://viewpoint.pwc.com/)
- [Deloitte: Not-for-Profit Accounting Resources](https://www.iasplus.com/en-us)

---

## Navigation

← [Back to Industry (900s)](README.md) | [Back to Main Guide](../../README.md)
