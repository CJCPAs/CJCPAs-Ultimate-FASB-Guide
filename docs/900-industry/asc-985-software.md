# ASC 985: Software

> The comprehensive standard for accounting for software revenue and development costs.

## Overview

ASC 985 provides guidance on accounting for costs of computer software developed or obtained for internal use and the sale, lease, or licensing of computer software. The standard has been significantly impacted by ASC 606 for revenue recognition, with ASC 985-20 (costs of software sold/licensed) and ASC 350-40 (internal-use software) providing cost accounting guidance.

**Core Principle:**
> "Costs of developing software for sale should be capitalized after technological feasibility is established, while internal-use software costs should be capitalized during the application development stage."

---

## Scope

### ASC 985-20 (Software to Be Sold, Leased, or Marketed)

**Applies To:**
- Software developed for sale, lease, or licensing
- Purchased software for resale
- Software components of products
- Cloud-based software sold to customers

**Does NOT Apply To:**
- Internal-use software (ASC 350-40)
- Software developed under contract for others
- Website development costs (ASC 350-50)

### ASC 350-40 (Internal-Use Software)

**Applies To:**
- Software developed or obtained for internal use
- Software components of internal systems
- Cloud computing arrangements (hosting)

---

## Software Costs—To Be Sold, Leased, or Marketed (ASC 985-20)

### Development Phase Model

| Phase | Treatment |
|-------|-----------|
| **Planning and design** | Expense as incurred |
| **Before technological feasibility** | Expense as incurred |
| **After technological feasibility** | Capitalize |
| **General release to customers** | Stop capitalization |

### Technological Feasibility

**Established when either:**

| Criterion | Description |
|-----------|-------------|
| **Detail program design** | Completed and documented |
| **OR Working model** | Completed and confirmed consistent with design |

**For most entities:** Working model criterion is used.

### Costs to Capitalize After Technological Feasibility

| Capitalize | Expense |
|------------|---------|
| Coding and testing | Research and development |
| Documentation for users | Marketing and training |
| Software production masters | General and administrative |
| Preparing for release | Maintenance and support |

### Journal Entry—Capitalize Software Costs

```
Dr. Capitalized Software Costs          $XXX
    Cr. Cash/Accounts Payable                  $XXX
```

### Amortization

**Begin when:** Product available for general release

**Method:** Greater of:
1. **Straight-line** over estimated useful life
2. **Revenue-based** (current period revenue ÷ total expected revenue)

**Formula:**
```
Amortization = MAX(Straight-line, Revenue-based)

Straight-line: Capitalized cost ÷ Useful life
Revenue-based: (Current revenue ÷ Total estimated revenue) × Capitalized cost
```

### Journal Entry—Amortization

```
Dr. Cost of Sales (or Amortization Expense)  $XXX
    Cr. Accumulated Amortization—Software         $XXX
```

### Impairment

At each balance sheet date:
- Compare carrying amount to **net realizable value (NRV)**
- NRV = Estimated future gross revenue less costs to complete/sell
- Write down if carrying amount > NRV
- **No recovery of previously written-off amounts**

### Journal Entry—Impairment

```
Dr. Impairment Loss—Software            $XXX
    Cr. Capitalized Software Costs             $XXX
```

---

## Internal-Use Software (ASC 350-40)

### Development Stage Model

| Stage | Treatment | Examples |
|-------|-----------|----------|
| **Preliminary project** | Expense | Conceptual design, vendor selection, requirements |
| **Application development** | Capitalize | Coding, configuration, testing, interfaces |
| **Post-implementation** | Expense | Training, maintenance, minor upgrades |

### Costs to Capitalize (Application Development Stage)

| Capitalize |
|------------|
| External direct costs (consultants, contractors) |
| Payroll costs for employees directly involved |
| Interest costs during development (if applicable) |
| Testing and quality assurance during development |
| Data conversion costs for new system |

### Costs to Expense

| Expense |
|---------|
| Training costs |
| Data conversion for ongoing operations |
| General and administrative overhead |
| Maintenance and minor enhancements |
| Preliminary project stage activities |

### Journal Entry—Capitalize Internal-Use Software

```
Dr. Internal-Use Software               $XXX
    Cr. Cash/Accounts Payable                  $XXX
```

### Upgrades and Enhancements

| Type | Treatment |
|------|-----------|
| **Additional functionality** | Capitalize if criteria met |
| **Maintenance** | Expense |
| **Repairs** | Expense |
| **Minor enhancements** | Generally expense |

### Amortization

**Begin when:** Software ready for intended use
**Method:** Straight-line (typically)
**Period:** Estimated useful life

### Journal Entry—Amortization

```
Dr. Amortization Expense                $XXX
    Cr. Accumulated Amortization—Software    $XXX
```

### Impairment

Apply ASC 360 (long-lived assets):
- Test when indicators present
- Recoverability test (undiscounted cash flows)
- If impaired, measure at fair value

---

## Cloud Computing Arrangements (ASC 350-40)

### Hosting Arrangements

**Key Question:** Does the customer have a software license?

| Arrangement | Customer Control? | Accounting |
|-------------|-------------------|------------|
| **License + Hosting** | Yes—takes possession or runs on own hardware | Capitalize as software |
| **Hosting only (SaaS)** | No—vendor operates software | Service contract |

### Implementation Costs (ASU 2018-15)

For hosting arrangements **without software license**:

| Stage | Treatment |
|-------|-----------|
| **Preliminary project** | Expense |
| **Application development** | Capitalize as prepaid |
| **Post-implementation** | Expense |

### Journal Entry—Capitalize SaaS Implementation

```
Dr. Prepaid Implementation Costs        $XXX
    Cr. Cash/Accounts Payable                  $XXX
```

### Amortization of Implementation Costs

**Period:** Term of hosting arrangement (including reasonably certain renewals)
**Method:** Straight-line
**Presentation:** Same line as hosting fees

### Journal Entry—Amortize Implementation Costs

```
Dr. Hosting Expense                     $XXX
    Cr. Prepaid Implementation Costs          $XXX
```

---

## Software Revenue Recognition (ASC 606)

### Integration with ASC 606

Software revenue follows ASC 606's five-step model with specific application guidance.

### Performance Obligations

**Common software arrangements:**

| Element | Separate Obligation? |
|---------|---------------------|
| **Software license** | Yes, if distinct |
| **Implementation services** | Depends on significance |
| **Post-contract support (PCS)** | Yes, if distinct |
| **Hosting services** | Yes, if distinct |
| **Training** | Generally yes |

### License vs. Service

| Nature of Promise | Classification | Recognition |
|-------------------|----------------|-------------|
| **Right to use** (point-in-time) | License | At transfer of license |
| **Right to access** (over time) | Service | Over the access period |
| **SaaS arrangement** | Service | Ratably over service period |

### Determining License Type

| Indicator | Right to Use | Right to Access |
|-----------|--------------|-----------------|
| IP nature at grant | Significant standalone functionality | Requires ongoing support |
| Significant updates | Not expected | Expected and customer entitled |
| Customer benefit | From existing functionality | From ongoing activities |

### Practical Example—License Revenue

**Software license with standalone functionality:**
```
Dr. Accounts Receivable                 $500,000
    Cr. Software License Revenue              $500,000
```
Recognition: At point-in-time when license delivered.

### Practical Example—SaaS Revenue

**Annual SaaS subscription:**
```
Dr. Cash                                $120,000
    Cr. Deferred Revenue—SaaS                 $120,000

Monthly recognition:
Dr. Deferred Revenue—SaaS               $10,000
    Cr. SaaS Subscription Revenue             $10,000
```

---

## Practical Examples

### Example 1: Software Development Costs (ASC 985-20)

**Facts:**
- Company develops software product for sale
- Planning and design costs: $200,000
- Coding before technological feasibility: $400,000
- Technological feasibility achieved June 1
- Coding after feasibility: $500,000
- Testing and documentation: $150,000
- General release September 1
- Estimated useful life: 3 years
- Estimated total revenue: $5,000,000
- Year 1 revenue: $2,000,000

**Capitalization:**
```
Capitalize after technological feasibility:
  Coding after feasibility:     $500,000
  Testing and documentation:    $150,000
  Total capitalized:           $650,000
```

**Expense:**
```
Planning and design:           $200,000
Coding before feasibility:     $400,000
Total expensed:               $600,000
```

**Amortization (Year 1—4 months of sales):**
```
Straight-line: $650,000 ÷ 3 years × 4/12 = $72,222
Revenue-based: ($2,000,000 ÷ $5,000,000) × $650,000 = $260,000

Use greater: $260,000
```

**Journal Entry:**
```
Dr. Cost of Sales                       $260,000
    Cr. Accumulated Amortization              $260,000
```

---

### Example 2: Internal-Use Software (ASC 350-40)

**Facts:**
- Company implements new ERP system
- Preliminary stage (vendor selection): $50,000
- Application development (configuration): $800,000
- Data conversion (one-time): $100,000
- Training: $75,000
- Post-implementation support: $40,000
- Go-live date: January 1
- Estimated useful life: 7 years

**Capitalize:**
```
Application development:       $800,000
Data conversion (new system):  $100,000
Total capitalized:            $900,000
```

**Expense:**
```
Preliminary stage:            $50,000
Training:                     $75,000
Post-implementation:          $40,000
Total expensed:              $165,000
```

**Annual Amortization:**
```
$900,000 ÷ 7 years = $128,571

Dr. Amortization Expense                $128,571
    Cr. Accumulated Amortization              $128,571
```

---

### Example 3: Cloud Computing Implementation (ASU 2018-15)

**Facts:**
- Company implements SaaS HR system
- Contract term: 3 years
- Annual subscription fee: $200,000
- Implementation costs:
  - Preliminary project: $25,000
  - Configuration and integration: $180,000
  - Training: $30,000
  - Data migration (new system): $45,000

**Capitalize (as prepaid):**
```
Configuration and integration: $180,000
Data migration:                $45,000
Total capitalized:            $225,000
```

**Expense:**
```
Preliminary project:          $25,000
Training:                     $30,000
Total expensed:              $55,000
```

**Amortization (annual):**
```
$225,000 ÷ 3 years = $75,000

Dr. Operating Expense (same line as SaaS fees)  $75,000
    Cr. Prepaid Implementation Costs                   $75,000
```

---

### Example 4: Multi-Element Software Arrangement

**Facts:**
- Total contract: $1,000,000
- Components:
  - Software license (SSP: $600,000)
  - Implementation services (SSP: $250,000)
  - 2-year PCS (SSP: $200,000)
- Implementation integrated with software

**Analysis:**

| Element | Distinct? | Recognition |
|---------|-----------|-------------|
| Software license | Yes | Point-in-time |
| Implementation | No (integrated) | Combined with license |
| PCS | Yes | Over 2 years |

**Allocation:**
```
Combined license + implementation SSP: $850,000
PCS SSP: $200,000
Total SSP: $1,050,000

License + implementation: $1,000,000 × ($850,000 ÷ $1,050,000) = $809,524
PCS: $1,000,000 × ($200,000 ÷ $1,050,000) = $190,476
```

**Journal Entries:**

*At delivery (license + implementation):*
```
Dr. Accounts Receivable                 $809,524
    Cr. Software Revenue                      $809,524
```

*Monthly PCS recognition:*
```
Dr. Accounts Receivable                 $7,936
    Cr. PCS Revenue                           $7,936
    ($190,476 ÷ 24 months)
```

---

## Disclosure Requirements

### ASC 985-20 Disclosures

| Disclosure |
|------------|
| Unamortized software costs |
| Total amortization for period |
| Amount written down (if any) |

### Internal-Use Software Disclosures

| Disclosure |
|------------|
| Capitalized amounts |
| Amortization method and period |
| Accumulated amortization |

### Cloud Implementation Disclosures

| Disclosure |
|------------|
| Nature of hosting arrangement |
| Capitalized implementation costs |
| Amortization period |
| Line item presentation |

---

## Common Implementation Issues

### 1. Technological Feasibility Determination
- Subjective judgment required
- Documenting the milestone
- Different for agile development

### 2. Internal-Use vs. Commercial Software
- Dual-use situations
- Change in intended use
- Proper allocation

### 3. Cloud Arrangement Classification
- License vs. service determination
- Identifying implementation components
- Renewal periods

### 4. Revenue Recognition Timing
- License type (right to use vs. access)
- Performance obligation identification
- Variable consideration (usage-based)

### 5. Impairment Assessment
- NRV estimation
- Market condition changes
- Technology obsolescence

---

## Private Company Considerations

### Practical Expedients

Private companies should consider:
- Materiality of software costs
- Complexity vs. benefit of capitalization
- Consistency in application

### Common Approaches

| Approach | Consideration |
|----------|---------------|
| Expense all development | Simplicity (if immaterial) |
| Shorter useful lives | Conservative, less tracking |
| Detailed tracking | Required for significant investments |

---

## Recent Developments

### Agile Development

Traditional technological feasibility model challenging for agile:
- Continuous development cycles
- Minimum viable product approach
- Consider working model criterion

### Artificial Intelligence/Machine Learning

| Component | Treatment |
|-----------|-----------|
| Training data acquisition | Generally expense |
| Algorithm development | Follow software guidance |
| Ongoing training | Generally expense |

---

## External Resources

- [FASB ASC 985-20](https://asc.fasb.org/)
- [FASB ASC 350-40](https://asc.fasb.org/)
- [AICPA Software Revenue Recognition Guide](https://www.aicpa.org/)
- [PwC: Software Revenue Recognition Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Software Revenue Recognition](https://www.iasplus.com/en-us)

---

## Navigation

← [Back to Industry (900s)](README.md) | [Back to Main Guide](../../README.md)
