# ASC 730: Research and Development

> Accounting for costs incurred in research and development activities.

## Overview

ASC 730 establishes the accounting for research and development (R&D) costs. The fundamental principle is that R&D costs are expensed as incurred due to the uncertainty of future benefits. This topic covers what constitutes R&D, how to account for various types of R&D costs, and special considerations for arrangements with third parties.

**Core Principle:**
> "Research and development costs shall be charged to expense when incurred, except for certain software development costs and acquired R&D in business combinations."

---

## Scope

### Applies To:
- Research activities
- Development activities
- Materials, equipment, and facilities used in R&D
- Personnel costs for R&D activities
- Purchased intangibles for R&D
- Contract services for R&D

### Does NOT Apply To:
- Extractive industries' costs (ASC 930, 932)
- Computer software development (ASC 985-20, 350-40)
- Routine product testing
- Quality control during production
- Adaptation for specific customer requirements

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Research** | Planned search or critical investigation aimed at discovery of new knowledge |
| **Development** | Translation of research findings into a plan or design for a new product or process |
| **R&D Costs** | All costs of materials, personnel, and services used in R&D activities |
| **Alternative Future Use** | Use of asset in other R&D projects or otherwise |

---

## What Is R&D?

### R&D Activities Include

| Activity | Example |
|----------|---------|
| **Laboratory research** | Basic research for new knowledge |
| **Design of new products** | Conceptual design and testing |
| **Design of new processes** | Manufacturing process development |
| **Prototype testing** | Construction and testing of prototypes |
| **Pilot plant operations** | Pre-commercial scale testing |
| **Engineering activity** | Not routine—required for product design |

### R&D Activities Exclude

| Activity | Accounting Treatment |
|----------|---------------------|
| **Routine engineering** | Expense as incurred (production cost) |
| **Quality control testing** | Expense as incurred (production cost) |
| **Troubleshooting** | Expense as incurred |
| **Seasonal design changes** | Expense as incurred |
| **Routine product improvement** | Expense as incurred |
| **Customer adaptation** | Expense as incurred |
| **Legal work on patents** | Capitalize if successful (ASC 350) |
| **Market research** | Expense as incurred |

---

## Accounting Treatment

### General Rule: Expense as Incurred

All R&D costs are expensed when incurred:

```
Dr. R&D Expense                      $500,000
    Cr. Cash/Payables                        $500,000
```

### Exceptions

| Exception | Treatment |
|-----------|-----------|
| **Materials with alternative future use** | Capitalize, then expense as used |
| **Equipment with alternative future use** | Capitalize, depreciate over useful life |
| **Acquired R&D in business combination** | Capitalize as intangible (ASC 805) |
| **Software development (ASC 985-20)** | Capitalize after technological feasibility |
| **Internal-use software (ASC 350-40)** | Capitalize during application development |

---

## Components of R&D Costs

### Materials and Supplies

| Situation | Treatment |
|-----------|-----------|
| **No alternative future use** | Expense as incurred |
| **Has alternative future use** | Capitalize as inventory, expense when used |

**Example—Materials with alternative use:**
```
Dr. Inventory—R&D Materials          $50,000
    Cr. Cash                                   $50,000
(Purchase of materials usable in multiple projects)

Dr. R&D Expense                      $30,000
    Cr. Inventory—R&D Materials               $30,000
(When used in R&D project)
```

### Equipment and Facilities

| Situation | Treatment |
|-----------|-----------|
| **No alternative future use** | Expense as incurred |
| **Has alternative future use** | Capitalize and depreciate |
| **Depreciation allocation** | Allocate to R&D expense |

**Example—Equipment with alternative use:**
```
Dr. Equipment                        $200,000
    Cr. Cash                                  $200,000
(Equipment usable in R&D and production)

Dr. R&D Expense                       $15,000
    Cr. Accumulated Depreciation              $15,000
(Depreciation allocated to R&D activities)
```

### Personnel Costs

```
Dr. R&D Expense—Salaries             $300,000
Dr. R&D Expense—Benefits              $75,000
    Cr. Salaries Payable                     $300,000
    Cr. Benefits Payable                      $75,000
```

### Contracted R&D Services

```
Dr. R&D Expense—Contract Services    $100,000
    Cr. Accounts Payable                     $100,000
```

### Indirect Costs

Reasonable allocation of indirect costs to R&D:
```
Dr. R&D Expense—Overhead              $50,000
    Cr. Manufacturing Overhead Applied        $50,000
```

---

## Practical Examples

### Example 1: New Product Development

**Facts—Annual R&D costs for new widget:**
- Scientists' salaries: $400,000
- Lab supplies (consumed): $75,000
- Prototype materials: $50,000
- Equipment depreciation (R&D share): $25,000
- Outside testing services: $30,000
- Allocated overhead: $20,000

**Journal Entry:**
```
Dr. R&D Expense                      $600,000
    Cr. Salaries Payable                     $400,000
    Cr. Supplies Inventory                    $75,000
    Cr. Raw Materials Inventory               $50,000
    Cr. Accumulated Depreciation              $25,000
    Cr. Accounts Payable                      $30,000
    Cr. Overhead Applied                      $20,000
```

---

### Example 2: R&D Equipment Purchase

**Facts:**
- Purchase specialized equipment for $500,000
- No alternative use outside R&D project
- Project expected to last 3 years

**At Purchase:**
```
Dr. R&D Expense                      $500,000
    Cr. Cash                                  $500,000
(Expense immediately—no alternative future use)
```

---

### Example 3: Equipment with Alternative Use

**Facts:**
- Purchase equipment for $300,000
- Can be used in R&D and later in production
- Useful life: 5 years
- First 2 years used in R&D, then production

**At Purchase:**
```
Dr. Equipment                        $300,000
    Cr. Cash                                  $300,000
```

**Annual Depreciation (Years 1-2):**
```
Dr. R&D Expense                       $60,000
    Cr. Accumulated Depreciation              $60,000
```

**Annual Depreciation (Years 3-5):**
```
Dr. Depreciation Expense              $60,000
    Cr. Accumulated Depreciation              $60,000
```

---

## Acquired R&D in Business Combinations

### ASC 805 Treatment

When R&D assets are acquired in a business combination:

| Situation | Treatment |
|-----------|-----------|
| **In-process R&D (IPR&D)** | Capitalize as indefinite-lived intangible |
| **After acquisition** | Continue to expense R&D costs |
| **Upon completion** | Reclassify and begin amortization |
| **If abandoned** | Write off IPR&D |

### Journal Entry—Acquisition

```
Dr. In-Process R&D                 $5,000,000
Dr. Other Assets                  $25,000,000
Dr. Goodwill                       $8,000,000
    Cr. Cash/Stock                          $38,000,000
```

### Post-Acquisition R&D Costs

```
Dr. R&D Expense                      $500,000
    Cr. Cash/Payables                        $500,000
(Costs to complete acquired IPR&D—expensed)
```

### Upon Project Completion

```
Dr. Developed Technology           $5,000,000
    Cr. In-Process R&D                      $5,000,000
(Reclassify and begin amortization)
```

---

## R&D Funding Arrangements

### Types of Arrangements

| Arrangement | Accounting |
|-------------|------------|
| **Entity bears risk** | Expense R&D as incurred |
| **Other party bears risk** | May be contract/consulting revenue |
| **Shared risk** | Analyze substance |

### Repayment Obligations

If entity must repay funding:
- Recognize as liability (not R&D expense)
- Expense when obligation relieved

**Funding Received with Repayment Obligation:**
```
Dr. Cash                           $1,000,000
    Cr. Liability—R&D Funding              $1,000,000
```

**If Repayment Condition Met:**
```
Dr. Liability—R&D Funding          $1,000,000
    Cr. Cash                               $1,000,000
```

**If Repayment Condition NOT Met:**
```
Dr. Liability—R&D Funding          $1,000,000
    Cr. R&D Revenue/Expense Offset         $1,000,000
```

---

## Software Development Costs

### External-Use Software (ASC 985-20)

| Phase | Treatment |
|-------|-----------|
| **Before technological feasibility** | Expense as R&D |
| **After technological feasibility** | Capitalize |
| **Technological feasibility** | Detailed design or working model |

### Internal-Use Software (ASC 350-40)

| Phase | Treatment |
|-------|-----------|
| **Preliminary project stage** | Expense |
| **Application development stage** | Capitalize |
| **Post-implementation stage** | Expense |

---

## R&D Disclosures

### Required Disclosures

| Item | Disclosure |
|------|------------|
| **Total R&D expense** | Charged to expense during period |
| **Government funding** | If significant |
| **Acquired IPR&D** | In business combinations |

### Example Disclosure

```
NOTE X: RESEARCH AND DEVELOPMENT

Research and development costs are expensed as incurred. R&D
expense totaled $12.5 million and $10.8 million for the years
ended December 31, 20X1 and 20X0, respectively.

R&D expense consists primarily of personnel costs, materials
and supplies, and contracted services related to the development
of new products and improvements to existing products.

During 20X1, the Company acquired ABC Inc., which included
$3.5 million of in-process research and development. This IPR&D
is accounted for as an indefinite-lived intangible asset and
tested annually for impairment.
```

---

## Private Company Considerations

### Common Issues

| Issue | Consideration |
|-------|---------------|
| **Definition of R&D** | Clearly distinguish from production |
| **Owner time** | Value if performing R&D |
| **Government grants** | May offset R&D costs |
| **Tax credits** | R&D credit separate from GAAP |

### Documentation

- Define R&D activities clearly
- Track time spent on R&D
- Distinguish R&D from other activities
- Support for alternative use determinations

---

## Common Audit Issues

### Classification

| Issue | Audit Focus |
|-------|-------------|
| **R&D vs. production** | Proper classification |
| **Alternative use** | Support for determination |
| **Capital vs. expense** | Correct treatment |

### Completeness

| Issue | Consideration |
|-------|---------------|
| **All costs included** | Materials, labor, overhead |
| **Proper allocation** | Shared resources |
| **Contract R&D** | All arrangements identified |

### Accuracy

| Issue | Focus |
|-------|-------|
| **Period expense** | Correct timing |
| **Cost accumulation** | Proper tracking |
| **Disclosure** | Complete and accurate |

---

## R&D vs. Other Activities

### Decision Framework

```
Is activity aimed at new knowledge or products?
         ↓
    No → Not R&D (may be production, QC, or routine)
         ↓
    Yes
         ↓
Is it research (discovery) or development (application)?
         ↓
Both are R&D → Expense as incurred
         ↓
Exception: Alternative future use for assets?
         ↓
    Yes → Capitalize asset
         ↓
    No → Expense immediately
```

---

## Recent Updates

| ASU | Topic | Impact |
|-----|-------|--------|
| **ASU 2018-15** | Cloud Computing | Implementation costs |
| **ASU 2017-04** | Goodwill Impairment | May affect IPR&D |
| **ASU 2014-18** | Business Combinations | IPR&D accounting |

---

## External Resources

- [FASB ASC 730](https://asc.fasb.org/)
- [FASB ASC 985-20 (Software—External)](https://asc.fasb.org/)
- [FASB ASC 350-40 (Software—Internal)](https://asc.fasb.org/)
- [IRS R&D Tax Credit Guidance](https://www.irs.gov/)
- [KPMG: Handbook—R&D Costs](https://frv.kpmg.us/)
- [PwC: Technology Industry Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to R&D Costs](https://www.iasplus.com/en-us)

---

## Navigation

← [Back to Expenses (700s)](README.md) | [Back to Main Guide](../../README.md)
