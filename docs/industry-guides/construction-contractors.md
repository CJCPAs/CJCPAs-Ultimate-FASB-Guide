# Construction Contractors — Complete Industry Guide

[← Back to Main Guide](../../README.md) | [← Industry Guides](README.md)

---

## Table of Contents

1. [Overview](#overview)
2. [Applicable Standards](#applicable-standards)
3. [Revenue Recognition (ASC 606)](#revenue-recognition-asc-606)
4. [Contract Costs (ASC 340-40)](#contract-costs-asc-340-40)
5. [Balance Sheet Presentation](#balance-sheet-presentation)
6. [Loss Contracts](#loss-contracts)
7. [Change Orders and Claims](#change-orders-and-claims)
8. [Joint Ventures](#joint-ventures)
9. [Equipment and Fixed Assets](#equipment-and-fixed-assets)
10. [Bonding and Surety](#bonding-and-surety)
11. [Work-in-Progress (WIP) Schedules](#work-in-progress-wip-schedules)
12. [Financial Statement Presentation](#financial-statement-presentation)
13. [Disclosure Requirements](#disclosure-requirements)
14. [Tax vs. GAAP Differences](#tax-vs-gaap-differences)
15. [Key Financial Ratios](#key-financial-ratios)
16. [Common Audit Issues](#common-audit-issues)
17. [Private Company Considerations](#private-company-considerations)
18. [Sample Journal Entries](#sample-journal-entries)
19. [Sample Disclosures](#sample-disclosures)
20. [External Resources](#external-resources)

---

## Overview

Construction accounting is one of the most complex areas in U.S. GAAP due to the long-term nature of contracts, multiple performance obligations, variable consideration, and the need for significant estimates.

### What Makes Construction Unique

| Factor | Impact on Accounting |
|--------|---------------------|
| Long-term contracts | Revenue recognized over time |
| Progress billings | Billings often differ from revenue earned |
| Retainage | Portion of billings held until project completion |
| Change orders | Variable consideration requiring estimation |
| Claims | Complex recognition criteria |
| Joint ventures | Consolidation and equity method considerations |
| Bonding requirements | Financial statement presentation matters |
| Heavy equipment | Significant fixed asset accounting |

### Types of Construction Contracts

| Contract Type | Description | Risk Profile |
|--------------|-------------|--------------|
| **Fixed-Price (Lump Sum)** | Set price regardless of actual costs | High risk to contractor |
| **Cost-Plus** | Reimbursement of costs plus markup | Low risk to contractor |
| **Time and Materials** | Labor rates plus materials at cost | Medium risk |
| **Unit Price** | Fixed price per unit of work | Medium risk |
| **Guaranteed Maximum Price (GMP)** | Cost-plus with ceiling | Medium-high risk |

---

## Applicable Standards

| Standard | Topic | Key Relevance |
|----------|-------|---------------|
| **ASC 606** | Revenue from Contracts with Customers | Primary revenue recognition guidance |
| **ASC 340-40** | Contracts with Customers | Capitalizing contract costs |
| **ASC 310-10** | Receivables | Retainage accounting |
| **ASC 323** | Equity Method Investments | Joint venture accounting |
| **ASC 360** | Property, Plant, and Equipment | Heavy equipment |
| **ASC 410** | Asset Retirement Obligations | Environmental remediation |
| **ASC 420** | Exit or Disposal Costs | Project wind-down |
| **ASC 450** | Contingencies | Claims and litigation |
| **ASC 460** | Guarantees | Performance bonds |
| **ASC 842** | Leases | Equipment leases |
| **ASC 910** | Contractors—Construction | Industry-specific guidance |

---

## Revenue Recognition (ASC 606)

### The Five-Step Model Applied to Construction

#### Step 1: Identify the Contract

**Contract Criteria (ALL must be met):**
- [ ] Parties have approved the contract
- [ ] Rights of each party are identifiable
- [ ] Payment terms are identifiable
- [ ] Contract has commercial substance
- [ ] Collection is probable

**Construction-Specific Considerations:**

```
Common Contract Forms:
- AIA (American Institute of Architects) contracts
- ConsensusDocs
- EJCDC (Engineers Joint Contract Documents Committee)
- Custom owner-contractor agreements

Red Flags for Contract Existence:
- Unsigned contracts with work already begun
- Verbal agreements for "extra work"
- Letters of intent without binding terms
- Contracts with customers having significant credit risk
```

#### Step 2: Identify Performance Obligations

**Single vs. Multiple Performance Obligations:**

Most construction contracts contain a **single performance obligation** because:
- The contractor provides a significant integration service
- Goods and services are highly interdependent
- The customer contracted for a combined output (the completed project)

**When Multiple Performance Obligations May Exist:**

| Scenario | Likely Separate? | Rationale |
|----------|-----------------|-----------|
| Building + parking structure | Maybe | Depends on integration |
| Construction + 2-year maintenance | Yes | Maintenance is distinct |
| Design + build | Maybe | Depends on contract terms |
| Multiple buildings, same site | Maybe | Depends on interdependence |
| Phased construction | Usually No | Continuous integration |

**Example Analysis:**

```
Contract: Build office building with 5-year HVAC maintenance agreement

Analysis:
1. Construction of building
   - Highly integrated service
   - Single performance obligation

2. HVAC maintenance
   - Customer could purchase separately
   - Does not significantly modify building
   - Separate performance obligation

Result: TWO performance obligations
- Allocate transaction price between construction and maintenance
- Recognize construction revenue over time
- Recognize maintenance revenue over 5 years
```

#### Step 3: Determine the Transaction Price

**Components of Transaction Price:**

| Component | Description | Construction Example |
|-----------|-------------|---------------------|
| Fixed consideration | Base contract price | $10,000,000 lump sum |
| Variable consideration | Amounts that may vary | Incentives, penalties, claims |
| Constraining variable consideration | Limit on variable amounts | Only include amounts "highly probable" |
| Significant financing | Time value of money | Rare in construction |
| Noncash consideration | Non-monetary items | Land, equipment |
| Consideration payable to customer | Amounts paid to customer | Liquidated damages |

**Variable Consideration in Construction:**

```
Common Sources of Variable Consideration:
├── Incentive payments (early completion bonuses)
├── Penalty clauses (liquidated damages)
├── Performance bonuses (LEED certification)
├── Award fees
├── Claims
├── Unpriced change orders
└── Price escalation clauses

Estimation Methods:
1. Expected Value: Probability-weighted amounts (multiple outcomes)
2. Most Likely Amount: Single most likely outcome (binary outcomes)
```

**Example — Estimating Variable Consideration:**

```
Contract Details:
- Base contract: $5,000,000
- Early completion bonus: $200,000 if done by March 1
- Late penalty: $10,000/day after April 1

Management Assessment (as of December 31):
- 70% probability of completion by March 1 (bonus)
- 25% probability of completion March 2-31 (no bonus, no penalty)
- 5% probability of completion after April 1 (assume 15 days late)

Expected Value Calculation:
  $200,000 × 70%     = $140,000 (bonus)
  $0 × 25%           = $0
  ($150,000) × 5%    = ($7,500) (penalty)
                       --------
  Net variable       = $132,500

Constraint Analysis:
Is $132,500 "highly probable" of not reversing?
- History of similar projects suggests yes
- Include $132,500 in transaction price

Total Transaction Price: $5,132,500
```

#### Step 4: Allocate the Transaction Price

When multiple performance obligations exist, allocate based on **relative standalone selling prices**.

**Methods for Estimating Standalone Selling Price:**

| Method | Description | When to Use |
|--------|-------------|-------------|
| Adjusted market assessment | Market price for similar services | Competitive market exists |
| Expected cost plus margin | Cost + reasonable margin | Customized services |
| Residual approach | Transaction price less other SSPs | Highly variable pricing |

**Example — Allocation:**

```
Contract: Build hospital ($50M) + 3-year maintenance ($3M stated)

Standalone Selling Prices:
- Hospital construction: $50,000,000 (expected cost + margin)
- 3-year maintenance: $2,400,000 (market rate is $800K/year)

Total SSP: $52,400,000
Total Transaction Price: $53,000,000

Allocation:
- Hospital: $53M × ($50M ÷ $52.4M) = $50,572,519
- Maintenance: $53M × ($2.4M ÷ $52.4M) = $2,427,481
```

#### Step 5: Recognize Revenue

**Over Time Recognition (Most Construction Contracts)**

Construction contracts typically qualify for **over time** recognition because:

| Criterion | Test | Construction Application |
|-----------|------|-------------------------|
| **ASC 606-10-25-27(a)** | Customer simultaneously receives and consumes benefits | Rarely applies |
| **ASC 606-10-25-27(b)** | Contractor's performance creates/enhances asset customer controls | **Usually applies** — building on customer's land |
| **ASC 606-10-25-27(c)** | Asset has no alternative use + enforceable right to payment | Often applies for custom construction |

**Measuring Progress — Input vs. Output Methods**

| Method | Description | Pros | Cons |
|--------|-------------|------|------|
| **Cost-to-Cost (Input)** | Costs incurred ÷ Total estimated costs | Most common, objective | Front-loaded if materials purchased early |
| **Units of Delivery (Output)** | Units delivered ÷ Total units | Direct measure | May not reflect effort |
| **Surveys/Appraisals (Output)** | Third-party assessment | Independent | Costly, subjective |
| **Milestones (Output)** | Milestones achieved | Simple | May not reflect continuous progress |

### Cost-to-Cost Method (Most Common)

**Formula:**

```
                    Costs Incurred to Date
Percent Complete = ─────────────────────────────
                   Total Estimated Contract Costs

Revenue to Date = Percent Complete × Total Transaction Price

Current Period Revenue = Revenue to Date − Revenue Previously Recognized
```

**Comprehensive Example:**

```
ABC Construction — Highway Project
Contract Price: $10,000,000
Estimated Total Costs: $8,500,000
Contract Duration: 3 years

                          Year 1      Year 2      Year 3
                          ──────      ──────      ──────
Costs Incurred (Year)     $2,550,000  $3,400,000  $2,890,000
Cumulative Costs          $2,550,000  $5,950,000  $8,840,000
Est. Total Costs          $8,500,000  $8,500,000  $8,840,000

Percent Complete:
  $2,550,000 ÷ $8,500,000     30%
  $5,950,000 ÷ $8,500,000                70%
  $8,840,000 ÷ $8,840,000                           100%

Revenue Recognized:
  $10,000,000 × 30%       $3,000,000
  $10,000,000 × 70%                   $7,000,000
  $10,000,000 × 100%                              $10,000,000

Revenue (Current Period):
  Year 1: $3,000,000 − $0             = $3,000,000
  Year 2: $7,000,000 − $3,000,000     = $4,000,000
  Year 3: $10,000,000 − $7,000,000    = $3,000,000

Gross Profit:
  Year 1: $3,000,000 − $2,550,000     = $450,000
  Year 2: $4,000,000 − $3,400,000     = $600,000
  Year 3: $3,000,000 − $2,890,000     = $110,000
                                        ────────
  Total Gross Profit                  = $1,160,000

Verification: $10,000,000 − $8,840,000 = $1,160,000 ✓
```

### Costs to Exclude from Progress Measurement

**ASC 606-10-55-21** requires exclusion of costs that do not depict progress:

| Cost Type | Treatment | Example |
|-----------|-----------|---------|
| **Uninstalled materials** | Exclude from progress; recognize revenue equal to cost | Steel delivered but not erected |
| **Inefficiencies** | Expense as incurred | Rework, wasted materials |
| **Unexpected costs** | May indicate contract loss | Weather delays |
| **Subcontractor mobilization** | May need allocation | Payments before work |

**Example — Uninstalled Materials:**

```
Facts:
- Contract price: $5,000,000
- Total estimated costs: $4,000,000
- At year-end: $1,500,000 costs incurred
- Includes $400,000 of uninstalled materials (steel beams)

Calculation WITH Adjustment:
Costs for progress: $1,500,000 − $400,000 = $1,100,000
Percent complete: $1,100,000 ÷ ($4,000,000 − $400,000) = 30.56%

Revenue from progress: $5,000,000 × 30.56% = $1,527,778
Revenue from materials (at cost): $400,000
Total revenue: $1,927,778

Journal Entry:
Dr. Contract Asset                    $427,778
Dr. Accounts Receivable (if billed)   $XXX,XXX
    Cr. Contract Revenue                        $1,927,778
```

---

## Contract Costs (ASC 340-40)

### Costs to Obtain a Contract

| Cost Type | Capitalize? | Rationale |
|-----------|-------------|-----------|
| Bid preparation costs | **No** | Incurred regardless of winning |
| Sales commissions | **Yes** | Incremental to obtaining contract |
| Legal fees for contract | **Yes** | Incremental to obtaining contract |
| Travel to bid | **No** | Would have been incurred anyway |

**Practical Expedient:** If amortization period would be ≤1 year, may expense as incurred.

### Costs to Fulfill a Contract

**Capitalize if ALL criteria are met:**
1. Costs relate directly to a contract
2. Costs generate/enhance resources to satisfy future performance obligations
3. Costs are expected to be recovered

**Construction Cost Categories:**

| Cost Category | Examples | Capitalize? |
|--------------|----------|-------------|
| **Direct materials** | Lumber, concrete, steel | Yes |
| **Direct labor** | Carpenters, electricians | Yes |
| **Subcontractor costs** | Plumbing sub, electrical sub | Yes |
| **Equipment costs** | Crane rental, equipment depreciation | Yes (allocated) |
| **Insurance** | Builder's risk, workers comp | Yes (job-specific) |
| **Permits** | Building permits | Yes |
| **Engineering/architecture** | Plan review, as-built drawings | Yes |
| **Site supervision** | Project manager, superintendent | Yes |
| **Job office costs** | Trailers, utilities on site | Yes |
| **G&A overhead** | Corporate office | **No** |
| **Selling costs** | Marketing | **No** |
| **Abnormal waste** | Rework from negligence | **No** |

### Pre-Contract Costs

```
Timing of Cost Recognition:

        Contract           Contract
        Pursuit            Award
           │                 │
           ▼                 ▼
    ───────┼─────────────────┼──────────────────►
           │                 │
    [Bid Costs]        [Project Costs]
    Expense as         Capitalize as
    incurred           contract costs

Exception: If contract award is "probable" BEFORE incurring costs,
those costs may be capitalized if they meet fulfillment criteria.
```

---

## Balance Sheet Presentation

### Contract Assets and Liabilities

**Definitions:**

| Term | Definition | Common Name |
|------|------------|-------------|
| **Contract Asset** | Right to consideration that is conditional | Costs in excess of billings; Underbillings |
| **Contract Liability** | Obligation to transfer goods/services for consideration received | Billings in excess of costs; Overbillings |
| **Receivable** | Unconditional right to consideration | Accounts receivable |
| **Retainage Receivable** | Amounts billed but held by customer | Retention receivable |

### Balance Sheet Presentation Example

```
                        ABC CONSTRUCTION COMPANY
                            BALANCE SHEET
                         December 31, 20X5

ASSETS
Current Assets:
  Cash and cash equivalents                    $   850,000
  Accounts receivable                            2,400,000
  Retainage receivable                           1,200,000
  Contract assets (costs in excess of billings)  1,850,000
  Inventory - construction materials               450,000
  Prepaid expenses                                 125,000
                                               ───────────
    Total current assets                         6,875,000

Property and Equipment:
  Construction equipment                         8,500,000
  Vehicles                                       1,200,000
  Office equipment                                 150,000
  Less: accumulated depreciation                (4,100,000)
                                               ───────────
    Total property and equipment, net            5,750,000

Other Assets:
  Retainage receivable - noncurrent                800,000
                                               ───────────
    TOTAL ASSETS                               $13,425,000
                                               ===========

LIABILITIES AND STOCKHOLDERS' EQUITY
Current Liabilities:
  Accounts payable - trade                     $ 1,650,000
  Accounts payable - retainage                     620,000
  Contract liabilities (billings in excess)      1,100,000
  Accrued expenses                                 380,000
  Current portion of equipment loans               450,000
                                               ───────────
    Total current liabilities                    4,200,000

Long-term Liabilities:
  Equipment loans, net of current portion        2,100,000
                                               ───────────
    Total liabilities                            6,300,000

Stockholders' Equity:
  Common stock                                     100,000
  Retained earnings                              7,025,000
                                               ───────────
    Total stockholders' equity                   7,125,000
                                               ───────────
    TOTAL LIABILITIES AND EQUITY               $13,425,000
                                               ===========
```

### Project-Level Presentation

**Important:** Contract assets/liabilities are determined at the **contract level**, not aggregated across all contracts.

```
Contract Analysis at Year-End:

Contract    Costs      Estimated    Revenue     Billings    Asset/
            to Date    Profit       to Date     to Date     (Liability)
────────    ────────   ─────────    ─────────   ─────────   ───────────
Project A   $2,000,000 $500,000     $2,500,000  $2,200,000  $300,000 Asset
Project B   $1,500,000 $300,000     $1,800,000  $2,100,000  ($300,000) Liab
Project C   $800,000   $200,000     $1,000,000  $900,000    $100,000 Asset
Project D   $3,000,000 $600,000     $3,600,000  $3,800,000  ($200,000) Liab
                                                            ───────────
                                                Contract Assets:  $400,000
                                                Contract Liabs:  ($500,000)

DO NOT net to ($100,000) liability!
Present gross on balance sheet.
```

### Retainage

**What is Retainage?**

Retainage (or retention) is a portion of billings (typically 5-10%) withheld by the customer until project completion or satisfaction of conditions.

**Classification:**

| Condition | Classification |
|-----------|---------------|
| Due within operating cycle (typically 1 year) | Current asset |
| Due beyond operating cycle | Noncurrent asset |

**Journal Entries:**

```
Billing with 10% Retainage:
Dr. Accounts Receivable            $900,000
Dr. Retainage Receivable           $100,000
    Cr. Billings on Contract                  $1,000,000

Collection of Retainage at Completion:
Dr. Cash                           $100,000
    Cr. Retainage Receivable                  $100,000
```

**Retainage Payable:**

Contractors often withhold retainage from subcontractors:

```
Subcontractor Invoice with 10% Retention:
Dr. Subcontractor Costs            $100,000
    Cr. Accounts Payable - Subs              $90,000
    Cr. Retainage Payable - Subs             $10,000
```

---

## Loss Contracts

### When to Recognize a Loss

**ASC 605-35-25-45:** When current estimates indicate a loss will be incurred on a contract, the **entire loss** must be recognized **immediately** — not spread over the contract term.

### Calculating Contract Loss

```
Formula:
Total Expected Loss = Total Estimated Costs − Total Contract Revenue

If loss is expected:
1. Continue recognizing revenue based on percent complete
2. Adjust cost of revenue to recognize TOTAL loss
3. Record "provision for loss" or adjust gross profit

Example:

Contract price: $5,000,000
Original estimated costs: $4,200,000
Original expected profit: $800,000

Year 1: 40% complete, $1,680,000 costs incurred
Revenue: $2,000,000 | Cost: $1,680,000 | Gross profit: $320,000

Year 2: Revised estimate - total costs now $5,400,000
Total expected loss: $5,400,000 − $5,000,000 = ($400,000)

Calculation:
Revenue to date (60% complete): $3,000,000
Costs recognized to provide $400,000 loss:
  Revenue to date + Loss = Costs to date
  $3,000,000 + $400,000 = $3,400,000

Year 2 Journal Entry:
Dr. Contract Costs                $1,720,000
    Cr. Various (actual costs)              $1,320,000
    Cr. Provision for Contract Loss           $400,000

Alternative Presentation:
Dr. Contract Costs (actual)       $1,320,000
Dr. Loss on Contract                $400,000
    Cr. Various                              $1,320,000
    Cr. Provision for Contract Loss            $400,000
```

### Balance Sheet Presentation of Loss Provision

```
If costs incurred < estimated costs to complete:
  - Record "Provision for Contract Losses" as liability

If costs incurred + loss > billings to date:
  - May result in contract asset with embedded loss provision

Best Practice: Disclose loss contracts separately
```

---

## Change Orders and Claims

### Change Orders

**Definition:** Modifications to scope, price, or both.

**Types of Change Orders:**

| Type | Description | Revenue Recognition |
|------|-------------|---------------------|
| **Approved and priced** | Customer approved scope and price | Include in contract price |
| **Approved, not priced** | Scope approved, price TBD | Estimate as variable consideration |
| **Unapproved** | Neither approved | Careful evaluation needed |

**Accounting for Unapproved Change Orders:**

```
Decision Tree:

Is the change order approved?
├── YES → Include approved amount in contract price
└── NO → Is approval probable?
         ├── YES → Is the amount estimable?
         │         ├── YES → Include estimated amount (constrained)
         │         └── NO → Exclude until estimable
         └── NO → Exclude from contract price
                  (but may need to include costs in estimate)
```

**Example — Unapproved Change Order:**

```
Facts:
- Original contract: $8,000,000
- Change order submitted: $500,000 for additional foundation work
- Customer disputes amount, offers $350,000
- Costs already incurred: $420,000
- Legal review: 80% probability of recovering at least $400,000

Analysis:
1. Approval is probable (work was directed by customer)
2. Variable consideration estimate: $400,000 (constrained)
3. Costs of $420,000 added to total estimated costs

Journal Entry:
Dr. Contract Asset/Receivable     $400,000
    Cr. Contract Revenue                     $400,000

Note: $20,000 cost overrun reduces profit margin
```

### Claims

**Definition:** Amounts sought from the customer for costs not included in the original contract price (delays, errors in specifications, disputed change orders).

**Recognition Criteria (very restrictive):**

Per **ASC 606-10-32-11**, include claim amounts only when it is **highly probable** that a significant reversal will NOT occur.

**Factors to Consider:**

| Factor | Positive Indicator | Negative Indicator |
|--------|-------------------|-------------------|
| Legal basis | Strong contractual/legal right | Weak or unclear rights |
| Evidence | Detailed documentation | Limited support |
| Customer relationship | History of settling claims | History of disputes |
| Negotiation status | Advanced negotiations | Early stages |
| Similar claims | History of successful claims | Claims often denied |

**Claim Accounting Example:**

```
Facts:
- Claim submitted: $1,200,000 for owner-caused delays
- Actual costs incurred for delays: $1,100,000
- Legal counsel: "More likely than not" to prevail
- No settlement discussions yet

Year 1 Analysis:
- "More likely than not" ≠ "Highly probable"
- Significant uncertainty remains
- Recognition: $0

Year 1 Entry:
Dr. Contract Costs                $1,100,000
    Cr. Cash/Payables                       $1,100,000
(No revenue recognized for claim)

Year 2:
- Mediation yields $900,000 settlement offer
- Management expects to settle at $950,000

Year 2 Analysis:
- Settlement highly probable
- Amount reasonably estimable
- Constraint: Use $900,000 (more conservative)

Year 2 Entry:
Dr. Contract Asset                $900,000
    Cr. Contract Revenue                     $900,000
```

---

## Joint Ventures

### Common Joint Venture Structures

| Structure | Accounting | When Used |
|-----------|-----------|-----------|
| **Corporate JV** | Equity method or consolidation | Large projects, liability protection |
| **Partnership/LLC** | Equity method typically | Flexible profit allocation |
| **Contractual JV** | Proportionate share | No separate entity, just agreement |
| **Consortium** | Separate contract accounting | Each party has separate scope |

### Equity Method Accounting (Most Common)

**When to Use:**

- JV partner has significant influence (typically 20-50% ownership)
- Not controlled (would require consolidation)

**Key Journal Entries:**

```
Initial Investment:
Dr. Investment in JV              $500,000
    Cr. Cash                                 $500,000

Share of JV Income:
Dr. Investment in JV              $75,000
    Cr. Equity in Earnings of JV            $75,000

Distribution from JV:
Dr. Cash                          $50,000
    Cr. Investment in JV                     $50,000

Share of JV Loss:
Dr. Equity in Loss of JV          $30,000
    Cr. Investment in JV                     $30,000
```

### Sponsor Accounting for JVs

When the contractor is the "sponsor" (managing partner):

| Item | Treatment |
|------|-----------|
| Management fees | Revenue when earned |
| Equipment rentals to JV | Revenue (eliminate in consolidation if consolidated) |
| Intercompany profit | Eliminate proportionate share |
| Guarantees of JV debt | Disclosure; possible liability |

### Disclosure Requirements

```
Joint Venture Disclosures:
- Name and description of each significant JV
- Percentage of ownership
- Summarized financial information
- Carrying amount of investment
- Commitments and contingencies
- Related party transactions
```

---

## Equipment and Fixed Assets

### Capitalization Policies

**Typical Construction Equipment:**

| Asset Type | Useful Life | Depreciation Method |
|-----------|-------------|---------------------|
| Cranes | 10-15 years | Straight-line or units of production |
| Excavators | 7-10 years | Straight-line or units of production |
| Trucks | 5-7 years | Straight-line |
| Scaffolding | 5-10 years | Straight-line |
| Small tools | Expense or 3 years | May expense if < threshold |

### Equipment Costing to Jobs

**Methods for Allocating Equipment Costs:**

| Method | Description | Best For |
|--------|-------------|----------|
| **Owned equipment rates** | Internal hourly/daily rates | Diverse fleet |
| **Depreciation allocation** | Based on usage | Dedicated equipment |
| **Operating cost plus depreciation** | Full cost allocation | Cost-type contracts |

**Example — Equipment Allocation:**

```
Equipment: CAT 320 Excavator
Purchase price: $350,000
Useful life: 10,000 hours
Annual operating costs: $25,000

Hourly Rate Calculation:
Depreciation: $350,000 ÷ 10,000 hours = $35/hour
Operating: $25,000 ÷ 1,500 hours/year = $16.67/hour
Total internal rate: $51.67/hour (may add markup)

Job Cost Entry:
Dr. Job Costs - Project Alpha      $5,167
    Cr. Equipment Allocation                 $5,167
(100 hours × $51.67)
```

### Idle Equipment

```
Treatment of Idle Equipment:

During normal business slowdowns:
- Continue depreciation
- Charge to overhead (not specific jobs)

Extended idle periods:
- Evaluate for impairment (ASC 360)
- Consider "held for sale" classification if applicable
- Disclose significant idle assets
```

---

## Bonding and Surety

### Types of Construction Bonds

| Bond Type | Purpose | Who is Protected |
|-----------|---------|-----------------|
| **Bid Bond** | Guarantees contractor will accept contract if awarded | Owner |
| **Performance Bond** | Guarantees completion of work | Owner |
| **Payment Bond** | Guarantees payment to subs and suppliers | Subs, suppliers |
| **Maintenance Bond** | Guarantees against defects | Owner |

### Financial Statement Impact

```
Bond Premiums:
- Typically 1-3% of contract value
- Capitalize as contract cost
- Allocate over contract period

Bond Capacity:
- Sureties limit total bonded work
- Typically 10-20x working capital
- Financial statement quality matters!

Formula (simplified):
Bonding Capacity = Working Capital × Multiplier (10-20x)

Example:
Working capital: $2,000,000
Multiplier: 15x
Capacity: $30,000,000 in bonded work
```

### Indemnity Agreements

**Personal Guarantees:**

Most sureties require personal indemnification from shareholders.

- Disclosed as contingent liability
- May require disclosure of personal financial statements

---

## Work-in-Progress (WIP) Schedules

### Purpose and Importance

The WIP schedule is the **most critical document** for construction contractors because it:
- Summarizes all contracts in progress
- Shows over/underbillings
- Identifies profit fade or loss contracts
- Is scrutinized by banks, bonding companies, and auditors

### Standard WIP Format

```
                              ABC CONSTRUCTION COMPANY
                         WORK IN PROGRESS SCHEDULE
                            December 31, 20X5

                                                          COSTS &
Contract  Contract   Total    Costs    Total    %      Est. Profit  Billings    Over/
Number    Price      Est.Cost Incurred Revenue  Compl  to Date      to Date    (Under)
───────── ───────── ──────── ──────── ──────── ────── ──────────── ────────── ────────
20X5-001  $2,500,000 $2,100,000 $1,680,000 $2,000,000  80%  $1,680,000 $1,850,000 $150,000
20X5-002  $4,200,000 $3,600,000 $1,800,000 $2,100,000  50%  $1,800,000 $1,700,000 ($100,000)
20X5-003  $1,800,000 $1,500,000 $750,000   $900,000   50%  $750,000   $950,000   $200,000
20X5-004  $6,000,000 $5,200,000 $4,160,000 $4,800,000  80%  $4,160,000 $4,500,000 $340,000
20X5-005  $3,100,000 $2,850,000 $2,137,500 $2,325,000  75%  $2,137,500 $2,000,000 ($137,500)
───────── ───────── ──────── ──────── ──────── ────── ──────────── ────────── ────────
TOTALS    $17,600,000 $15,250,000 $10,527,500 $12,125,000      $10,527,500 $11,000,000

Summary:
  Billings in excess of costs (Overbillings):   $690,000
  Costs in excess of billings (Underbillings): ($237,500)
                                               ─────────
  Net Overbilling Position:                     $452,500
```

### WIP Analysis Procedures

**Key Metrics to Review:**

| Metric | Formula | Red Flag |
|--------|---------|----------|
| **Gross profit %** | (Revenue - Costs) ÷ Revenue | Declining from bid |
| **Profit fade** | Original GP% - Current GP% | > 3-5% decline |
| **Over/underbilling %** | Over(under) ÷ Revenue to date | > 10-15% |
| **Backlog** | Contract price - Revenue to date | Declining without new work |

**Profit Fade Analysis:**

```
Contract 20X5-002 Analysis:

Original Estimate:
  Contract price:     $4,200,000
  Estimated costs:    $3,500,000
  Expected profit:    $700,000 (16.7% GP)

Current Estimate:
  Contract price:     $4,200,000
  Estimated costs:    $3,600,000
  Expected profit:    $600,000 (14.3% GP)

Profit Fade: 16.7% - 14.3% = 2.4%
Investigate: Why did costs increase by $100,000?
```

---

## Financial Statement Presentation

### Income Statement Formats

**Percentage-of-Completion Method (Over Time Revenue):**

```
                        ABC CONSTRUCTION COMPANY
                          INCOME STATEMENT
                   Year Ended December 31, 20X5

Contract revenues earned                        $24,500,000
Cost of revenues earned                         (20,825,000)
                                               ────────────
Gross profit                                      3,675,000

Selling, general & administrative expenses       (1,850,000)
                                               ────────────
Operating income                                  1,825,000

Other income (expense):
  Interest expense                                 (185,000)
  Equity in earnings of joint ventures               95,000
  Gain on sale of equipment                          35,000
                                               ────────────
Income before income taxes                        1,770,000
Income tax expense                                 (425,000)
                                               ────────────
Net income                                      $ 1,345,000
                                               ============
```

### Statement of Cash Flows Considerations

**Operating Activities (Indirect Method):**

```
Cash Flows from Operating Activities:
  Net income                                    $ 1,345,000
  Adjustments to reconcile net income:
    Depreciation                                    685,000
    Gain on sale of equipment                       (35,000)
    Equity in earnings of JV                        (95,000)
    Distributions from JV                            50,000
  Changes in operating assets and liabilities:
    (Increase) in accounts receivable              (350,000)
    (Increase) in retainage receivable             (180,000)
    (Increase) in contract assets                  (225,000)
    Decrease in inventory                            75,000
    Increase in accounts payable                    420,000
    Increase in contract liabilities                135,000
    Increase in accrued expenses                     85,000
                                               ────────────
Net cash provided by operating activities       $ 1,910,000
```

---

## Disclosure Requirements

### ASC 606 Required Disclosures

**1. Disaggregation of Revenue:**

```
The Company disaggregates revenue by contract type and geography:

                              Year Ended December 31,
                              20X5          20X4
                              ────          ────
By Contract Type:
  Fixed-price contracts       $15,500,000   $14,200,000
  Cost-plus contracts          7,200,000     6,800,000
  Time and materials           1,800,000     1,500,000
                              ───────────   ───────────
                              $24,500,000   $22,500,000

By Geography:
  Southeast region            $18,000,000   $16,500,000
  Northeast region             6,500,000     6,000,000
                              ───────────   ───────────
                              $24,500,000   $22,500,000
```

**2. Contract Balances:**

```
The following table provides information about contract assets and liabilities:

                              December 31,  December 31,
                              20X5          20X4          Change
                              ────          ────          ──────
Contract assets              $ 1,850,000   $ 1,625,000   $ 225,000
Contract liabilities           1,100,000       965,000     135,000

Revenue recognized during 20X5 that was included in contract
liabilities at December 31, 20X4: $890,000
```

**3. Remaining Performance Obligations (Backlog):**

```
As of December 31, 20X5, the Company had $42,500,000 of remaining
performance obligations (backlog). The Company expects to recognize
approximately:
  - 65% within the next 12 months ($27,625,000)
  - 30% in 13-24 months ($12,750,000)
  - 5% thereafter ($2,125,000)
```

**4. Significant Judgments:**

```
Revenue Recognition Timing:
The Company recognizes revenue over time using the cost-to-cost input
method. This method requires management to estimate total contract costs,
which includes assumptions about labor productivity, material costs, and
subcontractor performance.

Variable Consideration:
The Company includes variable consideration in the transaction price
when it is highly probable that a significant reversal will not occur.
Variable consideration primarily consists of incentive fees, penalties,
and claims. As of December 31, 20X5, the Company has included $1,200,000
of variable consideration in contract prices, of which $800,000 relates
to pending claims.
```

### Other Important Disclosures

**Related Party Transactions:**

```
The Company leases its office facility from XYZ Properties LLC, an
entity owned by the Company's majority shareholder. Rent expense
under this lease was $180,000 for the year ended December 31, 20X5.
```

**Commitments and Contingencies:**

```
The Company is contingently liable under standby letters of credit
totaling $2,500,000 at December 31, 20X5.

The Company has guaranteed the debt of ABC Joint Venture in the
amount of $1,000,000 (its proportionate 50% share of JV debt).

The Company is party to various legal proceedings. Management believes
the ultimate resolution will not have a material impact on the
financial statements.
```

---

## Tax vs. GAAP Differences

### Key Differences

| Item | GAAP Treatment | Tax Treatment |
|------|---------------|---------------|
| **Revenue method** | Over time (% complete) | May elect completed contract if < $25M avg. receipts |
| **Long-term contracts** | ASC 606 | IRC §460 |
| **Home construction** | Over time | Exempt from §460 |
| **Contract costs** | Capitalize direct + allocated | Capitalize per §263A (UNICAP) |
| **Retainage** | Recognize when earned | Typically when received |
| **Equipment depreciation** | GAAP useful lives | MACRS accelerated |
| **Warranty reserves** | Accrue when probable | Deduct when paid |

### Completed Contract Method (Tax)

**Eligibility:**
- Average annual gross receipts ≤ $25 million (2022+)
- Contract must be "long-term" (not completed in same year started)

**Tax Deferral Benefit:**

```
Example:
3-year contract, $10M price, $8.5M costs

GAAP (% Complete):           Tax (Completed Contract):
Year 1: $3.0M revenue        Year 1: $0 revenue
Year 2: $4.0M revenue        Year 2: $0 revenue
Year 3: $3.0M revenue        Year 3: $10.0M revenue

Deferred Tax Liability builds up in Years 1-2 under GAAP,
then reverses in Year 3.
```

### Book-Tax Reconciliation

```
Net Income per Books (GAAP)                    $1,345,000

Additions:
  Contract revenue (GAAP > Tax)                   850,000
  Warranty expense (GAAP accrual)                 125,000
  Depreciation (GAAP > Tax)                            —
                                               ──────────
                                                  975,000

Deductions:
  Contract revenue (Tax > GAAP)                        —
  Warranty payments (Tax deduction)               (95,000)
  Depreciation (Tax > GAAP - §179, bonus)        (420,000)
                                               ──────────
                                                 (515,000)

Taxable Income                                 $1,805,000
                                               ==========
```

---

## Key Financial Ratios

### Bonding Company Metrics

| Ratio | Formula | Target |
|-------|---------|--------|
| **Working Capital** | Current Assets − Current Liabilities | Positive, trending up |
| **Current Ratio** | Current Assets ÷ Current Liabilities | > 1.2 |
| **Debt to Equity** | Total Liabilities ÷ Equity | < 3.0 |
| **Backlog to Working Capital** | Backlog ÷ Working Capital | < 15-20x |

### Profitability Metrics

| Ratio | Formula | Benchmark |
|-------|---------|-----------|
| **Gross Profit Margin** | Gross Profit ÷ Revenue | 15-25% (varies by type) |
| **Net Profit Margin** | Net Income ÷ Revenue | 3-8% |
| **Return on Equity** | Net Income ÷ Avg. Equity | > 15% |
| **Revenue per Employee** | Revenue ÷ FTE Employees | Varies by trade |

### Operational Metrics

| Ratio | Formula | What It Tells You |
|-------|---------|-------------------|
| **Underbilling %** | Underbillings ÷ Total Revenue | Cash flow stress indicator |
| **Overbilling %** | Overbillings ÷ Total Revenue | Advance billing position |
| **Backlog Months** | Backlog ÷ (Annual Revenue ÷ 12) | Work pipeline |
| **Bid Success Rate** | Contracts Won ÷ Bids Submitted | Estimating accuracy |

### Example Ratio Analysis

```
ABC Construction Company — Ratio Analysis

                              20X5      20X4      Benchmark
                              ────      ────      ─────────
Liquidity:
  Current ratio               1.64      1.52      > 1.2 ✓
  Working capital             $2.68M    $2.25M    Positive ✓

Leverage:
  Debt to equity              0.88      0.95      < 3.0 ✓

Profitability:
  Gross profit margin         15.0%     14.2%     15-25% ✓
  Net profit margin           5.5%      5.1%      3-8% ✓

Operations:
  Underbilling %              1.5%      2.1%      < 5% ✓
  Backlog months              8.2       7.5       6-18 mos ✓

Assessment: Strong financial position, improving metrics
```

---

## Common Audit Issues

### High-Risk Areas

| Area | Risk | Audit Procedures |
|------|------|-----------------|
| **Cost estimates** | Understated costs = overstated profit | Test estimate changes, compare to actual |
| **Percent complete** | Manipulation affects revenue | Independent verification, job site visits |
| **Unapproved change orders** | Overstated revenue | Review documentation, confirmation |
| **Claims** | Premature recognition | Legal letters, constraint analysis |
| **Job cost cutoff** | Wrong period | Test around period end |
| **Related party transactions** | Undisclosed or mispriced | Inquiry, review ownership |
| **Joint ventures** | Improper equity method | Confirm investment, review JV financials |

### Audit Procedures Checklist

```
Revenue Recognition:
☐ Review all contracts over $X threshold
☐ Test contract price to signed agreement
☐ Verify estimated costs with project manager interviews
☐ Compare original estimates to current estimates (profit fade)
☐ Test cost-to-cost percentage calculations
☐ Verify billings to approved applications
☐ Perform WIP analytical procedures

Contract Assets/Liabilities:
☐ Agree to WIP schedule
☐ Test for proper over/underbilling presentation
☐ Evaluate collectibility of contract assets
☐ Review for loss contracts

Change Orders & Claims:
☐ List all significant change orders and claims
☐ Evaluate recognition criteria
☐ Review legal correspondence
☐ Assess variable consideration constraint

Backlog:
☐ Obtain backlog schedule
☐ Agree to signed contracts
☐ Test for contract existence (approval, commercial substance)
```

### Common Peer Review Findings

| Finding | Issue | Prevention |
|---------|-------|------------|
| Inadequate cost estimate documentation | Cannot support estimates | Monthly estimate reviews |
| Change order revenue recognized prematurely | Not "highly probable" | Document approval probability |
| Related party leases not disclosed | Missing disclosure | Related party questionnaires |
| WIP schedules not reconciled | Out of balance | Monthly reconciliations |
| Improper contract asset/liability netting | Overstated balance sheet | Present at contract level |

---

## Private Company Considerations

### PCC Alternatives Applicable to Construction

| Alternative | Application to Construction |
|-------------|---------------------------|
| **Goodwill amortization** | Useful for acquisitions of other contractors |
| **VIE exemption** | Real estate holding company structures |
| **Common control leases** | Equipment or property leased from related parties |
| **Simplified hedge accounting** | Interest rate swaps on equipment loans |

### Practical Expedients

**Small Contract Expedients:**

- Contracts < $X may use completed contract method (if contracts typically complete within operating cycle)
- Simplified disclosure for non-public companies

### Financial Statement Considerations for Bonding

```
What Sureties Look For:
├── Audited financial statements (preferred)
├── Working capital adequacy
├── Consistent profitability
├── Clean WIP with limited profit fade
├── Reasonable backlog
├── Low debt levels
├── Experienced management
└── Personal financial statements of owners

Private Company Challenges:
- May not have audited financials
- Owner compensation can distort profits
- Related party transactions common
- May need to normalize financials
```

---

## Sample Journal Entries

### Basic Contract Accounting

```
1. Incur Contract Costs:
Dr. Construction Costs - WIP         $500,000
    Cr. Cash/Accounts Payable                   $500,000

2. Record Billings:
Dr. Accounts Receivable              $450,000
Dr. Retainage Receivable              $50,000
    Cr. Billings on Construction Contract       $500,000

3. Recognize Revenue and Costs:
Dr. Construction Costs Expense       $500,000
Dr. Billings on Construction Contract $550,000
    Cr. Construction Costs - WIP                $500,000
    Cr. Contract Revenue                        $550,000

4. Collect Receivable:
Dr. Cash                             $450,000
    Cr. Accounts Receivable                     $450,000
```

### Loss Contract Recognition

```
Facts:
- Contract: 60% complete
- Costs to date: $600,000
- Revised total estimated costs: $1,100,000
- Contract price: $1,000,000
- Expected loss: $100,000

Entry to Recognize Total Loss:
Dr. Contract Costs Expense           $640,000
    Cr. Construction Costs - WIP               $600,000
    Cr. Provision for Contract Losses          $40,000

Calculation:
Revenue at 60%: $600,000 (cost recovery, no profit)
Costs expensed: $640,000 ($600,000 actual + $40,000 future loss)
Loss recognized: $40,000 (remaining loss to complete)
Total loss: $100,000 ($600,000 costs - $600,000 revenue + $40,000 provision)
```

### Equipment Depreciation Allocation

```
Allocate Depreciation to Jobs:
Dr. Construction Costs - Job A       $15,000
Dr. Construction Costs - Job B       $10,000
Dr. Construction Costs - Job C       $5,000
Dr. Equipment Overhead               $5,000
    Cr. Accumulated Depreciation - Equipment    $35,000
```

### Joint Venture Entries

```
1. Initial Investment in JV:
Dr. Investment in ABC JV             $250,000
    Cr. Cash                                    $250,000

2. Share of JV Income:
Dr. Investment in ABC JV             $45,000
    Cr. Equity in Earnings of JV               $45,000

3. Equipment Rental to JV:
Dr. Due from ABC JV                  $20,000
    Cr. Equipment Rental Revenue               $20,000

4. Eliminate Proportionate Profit (50% ownership):
Dr. Equipment Rental Revenue         $10,000
    Cr. Investment in ABC JV                   $10,000
(Elimination of 50% of intercompany profit)
```

---

## Sample Disclosures

### Revenue Recognition Policy

```
Note X — Revenue Recognition

The Company recognizes revenue from construction contracts over time
using the cost-to-cost input method. Under this method, the percentage
of completion is calculated by dividing total costs incurred to date
by total estimated costs. Revenue is then recognized by applying this
percentage to the total contract price (including approved change
orders and estimated variable consideration).

The Company includes variable consideration in the transaction price
when it is highly probable that a significant revenue reversal will
not occur. Variable consideration consists primarily of incentive
payments, penalty provisions, and claims. The Company estimates variable
consideration using the expected value method for incentives and
penalties, and the most likely amount method for claims.

Contract modifications are accounted for as a separate contract when
the scope increases by distinct goods or services at standalone selling
prices. Other modifications are accounted for as part of the existing
contract on a cumulative catch-up basis.

The Company does not adjust transaction prices for significant financing
components when the period between performance and payment is expected
to be one year or less.
```

### Contract Assets and Liabilities

```
Note X — Contract Assets and Liabilities

Contract assets represent revenue recognized in excess of billings
on contracts in progress. Contract liabilities represent billings in
excess of revenue recognized. Contract assets and liabilities are
reported on a contract-by-contract basis at the end of each reporting
period and are classified as current based on the Company's operating
cycle.

Significant changes in contract assets and liabilities during the
period are as follows:

                                         Contract    Contract
                                         Assets      Liabilities
                                         ────────    ───────────
Balance, December 31, 20X4               $1,625,000  $  965,000
Revenue recognized                       24,500,000          —
Cash received                                   —     5,200,000
Billings                                (23,875,000)        —
Transfer to receivables                  (1,500,000)        —
Recognized from beginning liability             —      (890,000)
Transferred to revenue                          —    (4,175,000)
                                         ────────    ───────────
Balance, December 31, 20X5               $1,850,000  $1,100,000
                                         ========    ==========

The Company recognized $890,000 of revenue during 20X5 that was
included in the contract liability balance at December 31, 20X4.
```

### Remaining Performance Obligations

```
Note X — Remaining Performance Obligations

The Company's remaining performance obligations represent the
transaction price of firm orders for which work has not been
performed (backlog). As of December 31, 20X5, the Company had
remaining performance obligations of approximately $42,500,000.

The Company expects to recognize revenue from these obligations as follows:

    Within 1 year                        $27,625,000     65%
    1 - 2 years                           12,750,000     30%
    Thereafter                             2,125,000      5%
                                         ───────────    ───
                                         $42,500,000    100%

The Company does not disclose information about remaining performance
obligations for contracts with an original expected duration of one
year or less.
```

---

## External Resources

### Authoritative Guidance

| Resource | Description |
|----------|-------------|
| [ASC 606](https://asc.fasb.org/606) | Revenue from Contracts with Customers |
| [ASC 340-40](https://asc.fasb.org/340-40) | Contracts with Customers |
| [ASC 910](https://asc.fasb.org/910) | Contractors—Construction |
| [IRC §460](https://www.law.cornell.edu/uscode/text/26/460) | Tax rules for long-term contracts |

### Industry Resources

| Resource | Description |
|----------|-------------|
| [CFMA](https://www.cfma.org/) | Construction Financial Management Association |
| [AGC of America](https://www.agc.org/) | Associated General Contractors |
| [AICPA Construction Guide](https://www.aicpa.org/) | Audit & Accounting Guide |
| [Surety Association](https://www.surety.org/) | Bonding information |

### Big Four Publications

| Firm | Guide |
|------|-------|
| Deloitte | A Roadmap to Applying ASC 606 |
| EY | Revenue from contracts with customers (ASC 606) |
| KPMG | Handbook: Revenue Recognition |
| PwC | Revenue from contracts with customers (ASC 606) |

---

## Quick Reference Checklist

### Monthly Close Procedures

- [ ] Update cost estimates on all active contracts
- [ ] Calculate percent complete for each contract
- [ ] Prepare WIP schedule
- [ ] Reconcile WIP to general ledger
- [ ] Review for loss contracts
- [ ] Accrue costs for work performed not yet billed
- [ ] Review change order and claim status
- [ ] Reconcile billings to project manager reports

### Year-End Procedures

- [ ] Obtain signed contracts for all jobs in WIP
- [ ] Document cost estimate methodology
- [ ] Perform profit fade analysis
- [ ] Review contract assets for collectibility
- [ ] Evaluate variable consideration constraints
- [ ] Prepare revenue disaggregation
- [ ] Calculate remaining performance obligations
- [ ] Review related party transactions
- [ ] Update disclosure checklist

---

[← Back to Main Guide](../../README.md) | [← Industry Guides](README.md)
