# ASC 330: Inventory

> The comprehensive standard for inventory measurement, costing, and valuation.

## Overview

ASC 330 provides guidance on the measurement and recognition of inventory costs, including capitalization, cost flow assumptions, and subsequent measurement at the lower of cost or net realizable value. Proper inventory accounting directly impacts both the balance sheet and income statement.

**Core Principle:**
> "Inventory should be stated at the lower of cost or net realizable value, with cost determined using an appropriate cost flow assumption consistently applied."

---

## Scope

### Applies To:
- Raw materials
- Work in process
- Finished goods
- Merchandise inventory
- Supplies that are consumed in operations

### Does NOT Apply To:
- Long-term contracts (ASC 606, 340-40)
- Agricultural products at NRV (ASC 905)
- Minerals and mineral products at NRV (ASC 930)
- Broker-dealers in securities at fair value (ASC 940)
- Inventory held at fair value less costs to sell (limited circumstances)

---

## Inventory Cost Components

### Capitalizable Costs

| Cost Type | Examples | Treatment |
|-----------|----------|-----------|
| **Purchase costs** | Invoice price, import duties, freight-in | Capitalize |
| **Conversion costs** | Direct labor, production overhead | Capitalize |
| **Other costs** | Costs to bring inventory to present location/condition | Capitalize |

### Non-Capitalizable Costs

| Cost Type | Examples | Treatment |
|-----------|----------|-----------|
| **Abnormal waste** | Spoilage exceeding normal levels | Expense |
| **Storage costs** | Unless required in production process | Expense |
| **Selling costs** | Marketing, distribution | Expense |
| **Admin overhead** | General corporate costs | Expense |

### Freight Costs

| Type | Treatment |
|------|-----------|
| **Freight-in** | Capitalize as part of inventory cost |
| **Freight-out** | Expense as selling cost |

---

## Cost Flow Assumptions

### FIFO (First-In, First-Out)

**Concept:** Oldest inventory sold first; ending inventory reflects most recent costs.

**Characteristics:**
- Ending inventory approximates current cost
- In rising prices: Lower COGS, higher net income
- Best matches physical flow for perishables

### LIFO (Last-In, First-Out)

**Concept:** Most recent inventory sold first; ending inventory reflects oldest costs.

**Characteristics:**
- COGS approximates current cost
- In rising prices: Higher COGS, lower net income, tax deferral
- Permitted under U.S. GAAP only (not IFRS)
- Requires LIFO conformity rule for tax purposes

### Weighted-Average Cost

**Concept:** Average cost of all units available during period.

**Calculation:**
```
Weighted-Average Cost = Total Cost of Goods Available / Total Units Available
```

**Variations:**
- **Periodic:** Calculate once at period end
- **Perpetual (moving average):** Recalculate after each purchase

### Specific Identification

**Concept:** Track actual cost of each specific item.

**Appropriate For:**
- High-value items
- Unique/distinguishable inventory
- Low-volume, high-cost goods (jewelry, art, autos)

### Comparison of Methods

| Method | Rising Prices Effect | Best For |
|--------|---------------------|----------|
| **FIFO** | Higher income, higher ending inventory | Perishables, high turnover |
| **LIFO** | Lower income (tax benefit), lower ending inventory | Commodities, inflation hedge |
| **Weighted-average** | Moderate—between FIFO and LIFO | Fungible goods |
| **Specific ID** | Depends on selection | Unique items |

---

## LIFO Considerations

### LIFO Reserve

**Definition:** Difference between inventory at LIFO and what it would be under FIFO.

**Disclosure Required:** LIFO reserve amount

**Conversion to FIFO:**
```
FIFO Inventory = LIFO Inventory + LIFO Reserve
FIFO COGS = LIFO COGS − Change in LIFO Reserve
```

### LIFO Layers

When quantities increase, new layer added at current costs.
When quantities decrease (LIFO liquidation), older layers are matched to sales.

### LIFO Liquidation

**Definition:** Reduction in LIFO inventory quantities that causes older, lower-cost layers to flow to COGS.

**Effect:** Artificially low COGS, higher income (if prices have risen)

**Disclosure:** If material, disclose effect on income

### Dollar-Value LIFO

**Concept:** Measure inventory in dollars rather than units; use price indices.

**Steps:**
1. Convert ending inventory to base-year dollars
2. Determine layer changes
3. Apply indices to each layer

---

## Lower of Cost or Net Realizable Value

### General Rule (Non-LIFO Inventory)

Measure inventory at **lower of cost or net realizable value (NRV)**.

**Net Realizable Value = Estimated selling price − Estimated costs to complete and sell**

### LIFO and Retail Inventory Method

Measure at **lower of cost or market (LCM)**.

**Market = Replacement cost**, constrained by:
- Ceiling: NRV (cannot exceed)
- Floor: NRV minus normal profit margin (cannot be below)

### LCM Floor and Ceiling

```
        Ceiling (NRV)
            ↑
        Market = Replacement Cost (if between floor and ceiling)
            ↓
        Floor (NRV − Normal Profit)
```

### Write-Down Entries

**Direct Method:**
```
Dr. Cost of Goods Sold             $XXX
    Cr. Inventory                           $XXX
```

**Allowance Method:**
```
Dr. Loss on Inventory Write-Down   $XXX
    Cr. Allowance for Inventory Write-Down  $XXX
```

### Write-Down Reversal

**U.S. GAAP:** Prohibited for most inventory. Once written down, new cost basis established.

**Exception:** Agricultural and mineral products reported at NRV can be adjusted.

---

## Retail Inventory Method

### Concept

Estimate ending inventory by applying a cost-to-retail ratio.

### Calculation

**Step 1:** Calculate cost-to-retail ratio
```
Cost-to-Retail Ratio = Cost of Goods Available / Retail Value of Goods Available
```

**Step 2:** Apply ratio to ending inventory at retail
```
Ending Inventory at Cost = Ending Inventory at Retail × Cost-to-Retail Ratio
```

### Variations

| Method | Treatment of Markdowns | Effect |
|--------|------------------------|--------|
| **Conventional (LCM)** | Exclude markdowns from ratio | Lower ratio, conservative |
| **Average cost** | Include markdowns in ratio | Higher ratio |
| **LIFO retail** | Special calculation with layers | LIFO cost flow |

### Markups and Markdowns

| Term | Definition |
|------|------------|
| **Original retail** | Initial selling price |
| **Markup** | Increase above original retail |
| **Markup cancellation** | Reversal of markup |
| **Markdown** | Decrease below original retail |
| **Markdown cancellation** | Reversal of markdown |

---

## Practical Examples

### Example 1: FIFO vs. LIFO Calculation

**Inventory Data:**

| Transaction | Units | Cost/Unit | Total Cost |
|-------------|------:|----------:|-----------:|
| Beginning inventory | 100 | $10 | $1,000 |
| Purchase 1 | 200 | $12 | $2,400 |
| Purchase 2 | 150 | $14 | $2,100 |
| **Available for sale** | **450** | | **$5,500** |
| Units sold | (300) | | |
| **Ending inventory** | **150** | | |

**FIFO Calculation:**
Ending inventory = 150 units at most recent costs

| Layer | Units | Cost | Total |
|-------|------:|-----:|------:|
| From Purchase 2 | 150 | $14 | $2,100 |
| **Ending inventory** | **150** | | **$2,100** |

COGS = $5,500 − $2,100 = $3,400

**LIFO Calculation:**
Ending inventory = 150 units at oldest costs

| Layer | Units | Cost | Total |
|-------|------:|-----:|------:|
| From Beginning | 100 | $10 | $1,000 |
| From Purchase 1 | 50 | $12 | $600 |
| **Ending inventory** | **150** | | **$1,600** |

COGS = $5,500 − $1,600 = $3,900

**Comparison:**

| Method | Ending Inventory | COGS | Gross Profit |
|--------|----------------:|-----:|-------------:|
| FIFO | $2,100 | $3,400 | Higher |
| LIFO | $1,600 | $3,900 | Lower |
| **Difference (LIFO Reserve)** | **$500** | **$500** | |

---

### Example 2: Lower of Cost or NRV

**Facts:**
- Inventory item cost: $100
- Estimated selling price: $120
- Estimated selling costs: $30

**NRV Calculation:**
```
NRV = $120 − $30 = $90
```

**Comparison:**
- Cost: $100
- NRV: $90

**Inventory value:** $90 (lower of cost or NRV)

**Write-down:** $100 − $90 = $10

**Journal Entry:**
```
Dr. Cost of Goods Sold             $10
    Cr. Inventory                           $10
```

---

### Example 3: Lower of Cost or Market (LCM) for LIFO

**Facts:**
- Item cost (LIFO): $50
- Replacement cost: $42
- NRV (ceiling): $48
- NRV minus normal profit (floor): $40
- Normal profit margin: $8

**Step 1: Determine Market**

| Value | Amount | Analysis |
|-------|-------:|----------|
| Replacement cost | $42 | Between floor and ceiling |
| Ceiling (NRV) | $48 | |
| Floor (NRV − profit) | $40 | |

**Market = $42** (replacement cost, within constraints)

**Step 2: Compare Cost to Market**
- Cost: $50
- Market: $42

**Inventory value:** $42 (lower)

**Write-down:** $50 − $42 = $8

---

### Example 4: Weighted-Average Cost (Perpetual)

**Transactions:**

| Date | Transaction | Units | Cost | Total | Avg Cost |
|------|-------------|------:|-----:|------:|---------:|
| 1/1 | Beginning | 100 | $10 | $1,000 | $10.00 |
| 1/15 | Purchase | 50 | $12 | $600 | |
| | *New average* | 150 | | $1,600 | $10.67 |
| 1/20 | Sale | (80) | $10.67 | ($853) | |
| | *Balance* | 70 | | $747 | $10.67 |
| 1/25 | Purchase | 100 | $14 | $1,400 | |
| | *New average* | 170 | | $2,147 | $12.63 |

**Ending inventory:** 170 units × $12.63 = $2,147

---

### Example 5: Retail Inventory Method (Conventional)

**Data:**

| | Cost | Retail |
|-|-----:|-------:|
| Beginning inventory | $20,000 | $30,000 |
| Purchases | $80,000 | $120,000 |
| Markups (net) | | $10,000 |
| Markdowns (net) | | ($5,000) |
| Sales | | ($105,000) |

**Step 1: Calculate Goods Available**

| | Cost | Retail |
|-|-----:|-------:|
| Beginning inventory | $20,000 | $30,000 |
| Purchases | $80,000 | $120,000 |
| Net markups | — | $10,000 |
| **Goods available (before markdowns)** | **$100,000** | **$160,000** |

**Step 2: Cost-to-Retail Ratio (Conventional Method—exclude markdowns)**
```
Ratio = $100,000 / $160,000 = 62.5%
```

**Step 3: Ending Inventory at Retail**
```
Retail available after markdowns: $160,000 − $5,000 = $155,000
Less: Sales: ($105,000)
Ending inventory at retail: $50,000
```

**Step 4: Ending Inventory at Cost**
```
$50,000 × 62.5% = $31,250
```

---

## Manufacturing Inventory

### Cost Accumulation

| Cost Type | Description |
|-----------|-------------|
| **Direct materials** | Raw materials traceable to product |
| **Direct labor** | Labor directly involved in production |
| **Manufacturing overhead** | Indirect costs (utilities, depreciation, supervision) |

### Overhead Allocation

**Normal Costing:**
- Apply overhead using predetermined rate
- Based on normal capacity
- Allocate variance to COGS (if immaterial)

**Actual Costing:**
- Apply actual overhead incurred
- More accurate but less timely

### Under/Over-Applied Overhead

| Situation | Adjustment |
|-----------|------------|
| **Under-applied** | Increase COGS (or allocate to inventory/COGS) |
| **Over-applied** | Decrease COGS (or allocate to inventory/COGS) |

**Journal Entry—Under-Applied (immaterial):**
```
Dr. Cost of Goods Sold             $XXX
    Cr. Manufacturing Overhead              $XXX
```

---

## Purchase Commitments

### Non-Cancellable Commitments

If contracted purchase price > Current market price:

**Recognition:**
- Recognize loss when decline occurs (if material)
- Accrue liability for expected loss

**Journal Entry:**
```
Dr. Loss on Purchase Commitment    $XXX
    Cr. Accrued Loss on Purchase Commitment $XXX
```

### When Inventory Received

**Entry to Reverse Accrual:**
```
Dr. Accrued Loss on Purchase Commitment $XXX
Dr. Inventory (at market)              $XXX
    Cr. Cash/Accounts Payable                   $XXX
```

---

## Consignment Inventory

### Consignor Accounting

- Inventory remains on consignor's books
- Not recorded as sale until sold by consignee
- May reclassify to "Inventory on Consignment"

### Consignee Accounting

- Does not record inventory
- Only records commission when sold
- Liability to consignor until remittance

---

## Private Company Considerations

### Practical Expedients

| Area | Consideration |
|------|---------------|
| **Overhead allocation** | Simplified methods acceptable if reasonable |
| **LCM/NRV testing** | May test at category or aggregate level |
| **Cost flow assumptions** | LIFO less common (complexity vs. benefit) |

### Common Issues

- Inadequate overhead allocation methods
- Missing obsolescence reserves
- Inconsistent cost flow application
- Poor cut-off procedures

---

## Disclosure Requirements

### Required Disclosures

| Disclosure | Description |
|------------|-------------|
| **Basis of stating inventories** | Cost flow assumption (FIFO, LIFO, etc.) |
| **Composition** | Major categories (raw materials, WIP, finished goods) |
| **LIFO reserve** | If LIFO used, excess of FIFO over LIFO |
| **LIFO liquidation** | If material effect on income |
| **Write-downs** | Significant losses from LCM/NRV adjustments |
| **Pledged inventory** | If inventory used as collateral |

### Example Note Disclosure

> **Inventories**
> Inventories are stated at the lower of cost or net realizable value. Cost is determined using the first-in, first-out (FIFO) method. Inventories consist of the following at December 31:
>
> | | 20X2 | 20X1 |
> |--|-----:|-----:|
> | Raw materials | $500,000 | $450,000 |
> | Work in process | 300,000 | 275,000 |
> | Finished goods | 700,000 | 625,000 |
> | **Total** | **$1,500,000** | **$1,350,000** |

---

## Common Implementation Issues

### 1. Cost Capitalization Errors
- Including period costs in inventory
- Excluding freight-in
- Improper overhead allocation

### 2. Cost Flow Consistency
- Switching methods without proper accounting change treatment
- Different methods for similar inventory
- LIFO conformity violations

### 3. Obsolescence Recognition
- Not establishing adequate reserves
- Delayed recognition of slow-moving inventory
- Improper write-down reversals

### 4. Physical Inventory
- Poor count procedures
- Cut-off errors
- Not reconciling book to physical

### 5. LCM/NRV Application
- Testing at wrong level (item vs. category)
- Improper NRV calculation
- Missing market decline indicators

---

## External Resources

- [FASB ASC 330](https://asc.fasb.org/)
- [KPMG: Handbook—Inventory](https://frv.kpmg.us/)
- [PwC: Inventory and Cost of Sales](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Inventory](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Inventory](https://www.ey.com/)
- [AICPA: Audit Guide—Inventory](https://www.aicpa.org/)

---

## Navigation

← [Back to Assets (300s)](README.md) | [Back to Main Guide](../../README.md)
