# ASC 360: Property, Plant, and Equipment

> The comprehensive standard for accounting for long-lived tangible assets, impairment, and disposal.

## Overview

ASC 360 provides guidance on the accounting for property, plant, and equipment (PP&E), including initial recognition, depreciation, impairment testing, and disposal. The standard also covers assets held for sale and discontinued operations.

**Core Principle:**
> "Long-lived assets should be depreciated over their useful lives and tested for impairment when events or circumstances indicate the carrying amount may not be recoverable."

---

## Scope

### Applies To:
- Land, buildings, and improvements
- Machinery and equipment
- Furniture and fixtures
- Vehicles
- Leasehold improvements
- Construction in progress
- Assets held for sale

### Does NOT Apply To:
- Goodwill (ASC 350)
- Intangible assets (ASC 350)
- Financial instruments
- Deferred tax assets (ASC 740)
- Right-of-use assets (ASC 842)

---

## Initial Recognition

### Capitalizable Costs

| Cost Type | Include | Exclude |
|-----------|---------|---------|
| **Purchase price** | Invoice, import duties, non-refundable taxes | Trade discounts, rebates |
| **Direct costs** | Site preparation, delivery, installation | Admin/overhead (generally) |
| **Professional fees** | Directly attributable legal, architectural | General professional fees |
| **Testing costs** | Testing for proper function | Costs after ready for use |
| **Borrowing costs** | Interest during construction (qualifying) | Interest after in service |

### Interest Capitalization (ASC 835-20)

**Qualifying Assets:**
- Assets constructed or produced for own use
- Assets intended for sale/lease constructed as discrete projects

**Calculation:**
Capitalize interest on weighted-average accumulated expenditures during construction period.

**Rate:**
- Specific borrowing rate (if specific financing)
- Weighted-average rate on other borrowings

**Limit:** Cannot exceed interest incurred during period

### Example: Interest Capitalization

**Facts:**
- Construction project cost: $2,000,000 (expenditures evenly throughout year)
- Construction loan: $1,500,000 at 6%
- Other debt: $5,000,000 at 5%
- Construction period: 12 months

**Weighted-average expenditures:** $2,000,000 × 0.5 = $1,000,000

**Interest capitalized:**
- From construction loan: $1,000,000 × 6% = $60,000
- (Capped at $1,500,000 × 6% = $90,000 actual interest)

**Journal Entry:**
```
Dr. Construction in Progress       $60,000
    Cr. Interest Expense                    $60,000
```

---

## Asset Acquisition Methods

### Cash Purchase

**Entry:**
```
Dr. Equipment                      $100,000
    Cr. Cash                                $100,000
```

### Lump-Sum Purchase

**Rule:** Allocate total cost based on relative fair values

**Example:**
- Total purchase price: $500,000
- Land fair value: $200,000
- Building fair value: $400,000
- Total fair value: $600,000

| Asset | Allocation |
|-------|----------:|
| Land | $500,000 × ($200,000/$600,000) = $166,667 |
| Building | $500,000 × ($400,000/$600,000) = $333,333 |

### Noncash Exchange (ASC 845)

**Commercial Substance (gains/losses recognized):**
- Record asset received at fair value
- Recognize gain/loss on exchange

**No Commercial Substance:**
- Record at carrying amount of asset given up
- No gain recognized; loss recognized if indicated

**Commercial Substance Exists If:**
- Future cash flows change significantly in timing, amount, or risk

### Deferred Payment

Record at present value of future payments (or cash price equivalent).

---

## Depreciation

### Methods

| Method | Formula | Pattern |
|--------|---------|---------|
| **Straight-line** | (Cost − Salvage) / Useful life | Equal annual amounts |
| **Declining balance** | Book value × Rate (often 2× SL rate) | Accelerated |
| **Units of production** | (Cost − Salvage) × (Units used / Total units) | Activity-based |
| **Sum-of-years'-digits** | (Cost − Salvage) × (Remaining life / SYD) | Accelerated |

### Component Depreciation

**When Required:** When component has different useful life or depreciation method from overall asset.

**Example:**
- Building: 40 years
- HVAC system: 20 years
- Roof: 25 years

### Depreciation Factors

| Factor | Description |
|--------|-------------|
| **Depreciable base** | Cost less salvage value |
| **Useful life** | Estimated period of benefit |
| **Salvage value** | Estimated residual value at end of life |
| **Method** | Pattern reflecting economic benefit consumption |

### Useful Life Estimates (Common)

| Asset | Typical Life |
|-------|--------------|
| Buildings | 25-40 years |
| Building improvements | 10-25 years |
| Machinery | 7-15 years |
| Vehicles | 3-7 years |
| Furniture/fixtures | 5-10 years |
| Computer equipment | 3-5 years |
| Leasehold improvements | Shorter of lease term or useful life |

### Changes in Estimates

**Treatment:** Prospective (change in accounting estimate)

**New depreciation = (Carrying amount − Revised salvage) / Revised remaining life**

---

## Impairment of Long-Lived Assets

### When to Test

Test when events or circumstances indicate carrying amount may not be recoverable.

### Triggering Events

| Category | Examples |
|----------|----------|
| **Significant decrease in market price** | Economic downturn, industry decline |
| **Adverse change in use** | Idled asset, change in manner of use |
| **Adverse change in business climate** | Regulatory changes, loss of key customer |
| **Accumulation of costs** | Significantly more than originally expected |
| **Operating/cash flow losses** | History or projection of losses |
| **Expected disposal** | Plan to sell or dispose before end of life |

### Impairment Test—Two Steps

**Step 1: Recoverability Test**

Is carrying amount > Sum of undiscounted future cash flows?

| Result | Action |
|--------|--------|
| No (carrying ≤ undiscounted CF) | No impairment—stop |
| Yes (carrying > undiscounted CF) | Proceed to Step 2 |

**Step 2: Measure Impairment**

**Impairment Loss = Carrying amount − Fair value**

### Cash Flow Estimation

**Include:**
- Cash inflows from use
- Cash outflows necessary to obtain inflows
- Proceeds from eventual disposal

**Characteristics:**
- Based on entity's own assumptions
- Reasonable and supportable
- Probability-weighted if multiple scenarios

### Asset Grouping

**Rule:** Group at lowest level with identifiable cash flows largely independent of other asset groups.

**Approach:**
1. Identify asset group
2. Calculate recoverability at group level
3. Allocate impairment to group assets (pro rata based on carrying amounts)
4. Don't reduce asset below fair value

### Journal Entry—Impairment

```
Dr. Impairment Loss                $XXX
    Cr. Accumulated Depreciation            $XXX
```

**Or:**
```
Dr. Impairment Loss                $XXX
    Cr. Asset (directly reduce)             $XXX
```

### Impairment Reversal

**U.S. GAAP:** Prohibited. Once impaired, cannot be restored.

---

## Assets Held for Sale

### Classification Criteria (ALL must be met)

| Criterion | Description |
|-----------|-------------|
| **1. Management commitment** | Authorized, committed to plan to sell |
| **2. Available for immediate sale** | Asset ready in present condition |
| **3. Active program initiated** | Actively locating buyer, marketing |
| **4. Sale probable** | Within one year (generally) |
| **5. Actively marketed** | At reasonable price relative to fair value |
| **6. Unlikely changes** | Plan unlikely to be withdrawn or significantly changed |

### Measurement

**Measure at:** Lower of carrying amount or fair value less costs to sell

### Presentation

- Classify separately on balance sheet
- Not in property, plant, and equipment
- Cease depreciation when classified as held for sale

### Journal Entry—Held for Sale Classification

**If write-down required:**
```
Dr. Loss on Assets Held for Sale   $XXX
    Cr. Assets Held for Sale                $XXX
```

### Subsequent Increases in Fair Value

Recognize gain for increases in fair value less costs to sell, but:
- Only to extent of cumulative losses previously recognized
- For held-for-sale assets (not for sold assets)

---

## Disposal of PP&E

### Upon Sale

**Gain or Loss = Proceeds − Carrying amount (cost less accumulated depreciation)**

**Journal Entry—Sale at Gain:**
```
Dr. Cash                           $50,000
Dr. Accumulated Depreciation       $80,000
    Cr. Equipment                           $100,000
    Cr. Gain on Disposal                    $30,000
```

**Journal Entry—Sale at Loss:**
```
Dr. Cash                           $10,000
Dr. Accumulated Depreciation       $80,000
Dr. Loss on Disposal               $10,000
    Cr. Equipment                           $100,000
```

### Retirement (No Proceeds)

```
Dr. Accumulated Depreciation       $100,000
Dr. Loss on Retirement             $15,000
    Cr. Equipment                           $115,000
```

### Trade-In (With Commercial Substance)

```
Dr. Equipment (new)                $150,000
Dr. Accumulated Depreciation       $70,000
    Cr. Equipment (old)                     $100,000
    Cr. Cash                                $100,000
    Cr. Gain on Exchange                    $20,000
```

---

## Discontinued Operations (ASC 205-20)

### Definition

A component of an entity that either:
- Has been disposed of, OR
- Is classified as held for sale

AND represents a strategic shift with major effect on operations and financial results.

### Examples of Strategic Shift

- Disposal of major geographic area
- Disposal of major line of business
- Disposal of major equity method investment
- Disposal of subsidiary

### Presentation

**Income Statement:**
- Report separately, net of tax, below continuing operations
- Include results of operations and gain/loss on disposal
- EPS for discontinued operations

**Prior Periods:**
- Recast to present comparable discontinued operations

### Disclosure Requirements

- Description of facts and circumstances
- Gain or loss recognized
- Revenue and pretax income/loss if not separately presented
- Segment in which component was reported

---

## Practical Examples

### Example 1: Impairment Test

**Facts:**
- Manufacturing equipment carrying amount: $500,000
- Remaining useful life: 5 years
- Estimated future undiscounted cash flows: $420,000
- Fair value: $380,000

**Step 1: Recoverability Test**

Carrying amount ($500,000) > Undiscounted cash flows ($420,000)

→ Asset NOT recoverable; proceed to Step 2

**Step 2: Measure Impairment**

| Component | Amount |
|-----------|-------:|
| Carrying amount | $500,000 |
| Fair value | $380,000 |
| **Impairment loss** | **$120,000** |

**Journal Entry:**
```
Dr. Impairment Loss                $120,000
    Cr. Accumulated Depreciation            $120,000
```

**New carrying amount:** $380,000
**New annual depreciation:** $380,000 / 5 = $76,000

---

### Example 2: Asset Group Impairment

**Facts:**
Asset group (retail store) contains:

| Asset | Carrying Amount |
|-------|----------------:|
| Land | $200,000 |
| Building | $500,000 |
| Equipment | $100,000 |
| **Total** | **$800,000** |

- Undiscounted cash flows: $700,000
- Fair value of group: $600,000

**Step 1:** $800,000 > $700,000 → Not recoverable

**Step 2:** Impairment = $800,000 − $600,000 = $200,000

**Allocation:**

| Asset | Carrying | % | Impairment | New Carrying |
|-------|----------:|-----:|----------:|-------------:|
| Land | $200,000 | 25% | $50,000 | $150,000 |
| Building | $500,000 | 62.5% | $125,000 | $375,000 |
| Equipment | $100,000 | 12.5% | $25,000 | $75,000 |
| **Total** | **$800,000** | 100% | **$200,000** | **$600,000** |

**Note:** Don't reduce any asset below its individual fair value.

---

### Example 3: Change in Useful Life Estimate

**Facts:**
- Equipment cost: $100,000
- Original useful life: 10 years
- Salvage value: $10,000
- Accumulated depreciation after 4 years: $36,000
- Revised remaining useful life: 3 years (at end of year 4)

**Analysis:**

| Component | Amount |
|-----------|-------:|
| Carrying amount (end year 4) | $100,000 − $36,000 = $64,000 |
| Revised salvage | $10,000 |
| Remaining depreciable amount | $54,000 |
| New remaining life | 3 years |
| **New annual depreciation** | **$18,000** |

---

### Example 4: Assets Held for Sale

**Facts:**
- Company decides to sell manufacturing plant
- Carrying amount: $2,000,000
- Fair value: $1,700,000
- Estimated costs to sell: $100,000

**Measurement:**

| Component | Amount |
|-----------|-------:|
| Fair value | $1,700,000 |
| Less: Costs to sell | (100,000) |
| Fair value less costs to sell | $1,600,000 |
| Carrying amount | $2,000,000 |
| **Write-down required** | **$400,000** |

**Journal Entry:**
```
Dr. Loss on Assets Held for Sale   $400,000
    Cr. Manufacturing Plant                 $400,000
```

**Balance Sheet Presentation:**
- Report $1,600,000 as "Assets Held for Sale"
- No further depreciation

---

## Private Company Considerations

### Simplified Impairment Approach

No special private company exceptions for PP&E impairment.

### Practical Considerations

| Area | Consideration |
|------|---------------|
| **Triggering events** | Smaller companies may have fewer formal processes to identify triggers |
| **Fair value** | May need external valuations for significant assets |
| **Asset groups** | Simpler operations may have fewer distinct asset groups |
| **Documentation** | Should document impairment analysis even if no impairment |

### Cost-Benefit

For smaller private companies:
- Focus on significant assets
- Use practical expedients for estimating fair value
- Consider materiality in grouping decisions

---

## Disclosure Requirements

### PP&E Disclosures

| Disclosure | Description |
|------------|-------------|
| Depreciation policy | Methods, useful lives |
| Balances by major class | Gross and accumulated depreciation |
| Depreciation expense | For the period |
| Significant additions | Major capital expenditures |
| Commitments | Contracts for future acquisitions |

### Impairment Disclosures

- Description of impaired asset(s)
- Facts and circumstances leading to impairment
- Amount of impairment loss
- Method of determining fair value
- Segment affected (if applicable)
- Asset group affected

### Held-for-Sale Disclosures

- Description of facts and circumstances
- Expected timing of disposal
- Carrying amount
- Gain or loss (if recognized)

---

## Common Implementation Issues

### 1. Capitalization vs. Expense
- Capitalizing repairs that don't extend life
- Expensing costs that add capacity or extend life
- Missing component accounting opportunities

### 2. Useful Life Estimates
- Not updating estimates when circumstances change
- Using tax lives instead of economic lives
- Ignoring salvage value updates

### 3. Impairment Testing
- Not identifying triggering events timely
- Improper asset grouping
- Overly optimistic cash flow projections

### 4. Interest Capitalization
- Overcapitalizing interest
- Including non-qualifying assets
- Errors in weighted-average expenditure calculation

### 5. Disposal Accounting
- Continuing depreciation after held-for-sale classification
- Improper gain/loss calculation
- Missing discontinued operations criteria

---

## External Resources

- [FASB ASC 360](https://asc.fasb.org/)
- [KPMG: Handbook—Long-Lived Assets](https://frv.kpmg.us/)
- [PwC: Property, Plant, Equipment and Other Assets Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Impairment of Long-Lived Assets](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Long-Lived Assets](https://www.ey.com/)

---

## Navigation

← [Back to Assets (300s)](README.md) | [Back to Main Guide](../../README.md)
