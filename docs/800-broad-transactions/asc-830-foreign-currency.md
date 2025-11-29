# ASC 830: Foreign Currency Matters

> Comprehensive guidance on accounting for foreign currency transactions and translating foreign subsidiary financial statements.

## Overview

ASC 830 provides guidance on accounting for foreign currency transactions and translating foreign entity financial statements into the reporting currency. This topic addresses exchange rate changes, functional currency determination, transaction gains and losses, and translation adjustments. As businesses increasingly operate globally, foreign currency accounting has become essential knowledge.

**Core Principle:**
> "Foreign currency transactions should be remeasured into the functional currency, and foreign operations should be translated into the reporting currency, with appropriate recognition of exchange gains and losses."

---

## Scope

### Applies To:
- Foreign currency transactions (purchases, sales, borrowings in foreign currency)
- Translation of foreign subsidiary/investee financial statements
- Foreign currency forward contracts (non-derivative aspects)
- Hedges of net investments in foreign operations

### Does NOT Apply To:
- Derivatives (hedge accounting under ASC 815)
- Highly inflationary economies (special rules within ASC 830)
- Crypto assets (ASC 350)

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Functional Currency** | Currency of the primary economic environment in which an entity operates |
| **Reporting Currency** | Currency in which the entity prepares financial statements |
| **Local Currency** | Currency of the country where the foreign entity is located |
| **Exchange Rate** | Ratio for converting one currency to another |
| **Spot Rate** | Exchange rate for immediate delivery |
| **Translation** | Expressing functional currency amounts in reporting currency |
| **Remeasurement** | Measuring transactions in functional currency |

---

## Functional Currency Determination

### The Critical First Step

Determining functional currency is the foundation of foreign currency accounting:

| Factor | Indicates Local Currency | Indicates Parent's Currency |
|--------|-------------------------|----------------------------|
| **Cash flows** | Primarily local | Primarily parent's currency |
| **Sales prices** | Responsive to local market | Responsive to exchange rate/parent pricing |
| **Sales market** | Active local market | Export sales dominate |
| **Expenses** | Primarily local | Primarily from parent country |
| **Financing** | Denominated in local | Denominated in parent's |
| **Intercompany transactions** | Low volume | High volume with parent |

### Management Judgment

If indicators are mixed:
- Management must apply judgment
- Consider which economy predominantly affects the entity
- Document rationale
- Once determined, change only if significant change in circumstances

### Functional Currency Examples

| Scenario | Likely Functional Currency |
|----------|---------------------------|
| Manufacturing subsidiary with local sales | Local currency |
| Sales office of U.S. parent | U.S. dollar |
| Self-sustaining foreign subsidiary | Local currency |
| Extension/integral operation of parent | Parent's currency |

---

## Foreign Currency Transactions

### Overview

A foreign currency transaction occurs when an entity:
- Buys or sells goods/services with prices denominated in foreign currency
- Borrows or lends with amounts denominated in foreign currency
- Acquires or disposes of assets/liabilities denominated in foreign currency

### Initial Recognition

**Record at spot rate on transaction date:**

**Example—Foreign Currency Purchase:**
```
Purchase: €100,000 equipment
Spot rate: €1 = $1.10

Dr. Equipment                        $110,000
    Cr. Accounts Payable (€)                  $110,000
```

### Subsequent Measurement

**At Each Balance Sheet Date:**
- Monetary items (receivables, payables, debt): Remeasure at current rate
- Non-monetary items (inventory, PP&E, prepaid): Remain at historical rate

**Example—A/P at Year-End:**
```
Original payable: $110,000 (€100,000 at $1.10)
Year-end spot rate: €1 = $1.15
New carrying amount: €100,000 × $1.15 = $115,000

Dr. Foreign Currency Transaction Loss   $5,000
    Cr. Accounts Payable (€)                    $5,000
```

### Settlement

**At Settlement Date:**
```
Settlement rate: €1 = $1.12
Payable at year-end: $115,000
Cash paid: €100,000 × $1.12 = $112,000

Dr. Accounts Payable (€)             $115,000
    Cr. Cash                                   $112,000
    Cr. Foreign Currency Transaction Gain       $3,000
```

---

## Translation of Foreign Operations

### Translation Process

**Step 1:** Determine functional currency
**Step 2:** Remeasure to functional currency (if needed)
**Step 3:** Translate to reporting currency

### Translation Method (Functional Currency = Local Currency)

When foreign entity's functional currency is its local currency:

| Item | Exchange Rate |
|------|---------------|
| **Assets** | Current rate (balance sheet date) |
| **Liabilities** | Current rate (balance sheet date) |
| **Equity—contributed capital** | Historical rate |
| **Equity—retained earnings** | Composite historical |
| **Revenues and expenses** | Average rate (or rates at transaction dates) |

**Result:** Translation adjustments recorded in OCI (CTA—Cumulative Translation Adjustment)

### Remeasurement Method (Functional Currency = Parent's Currency)

When foreign entity's functional currency is the parent's reporting currency:

| Item | Exchange Rate |
|------|---------------|
| **Monetary assets/liabilities** | Current rate |
| **Non-monetary assets/liabilities** | Historical rate |
| **Revenues and expenses (most)** | Average rate |
| **Expenses related to non-monetary items** | Historical rate |

**Result:** Remeasurement gains/losses recorded in net income

---

## Translation Example

### Facts

**Foreign Subsidiary (Functional Currency = Euro):**
- Assets: €1,000,000
- Liabilities: €400,000
- Common stock: €200,000 (issued when rate was $1.00)
- Retained earnings (beginning): €300,000
- Net income: €100,000
- Exchange rates:
  - Beginning of year: €1 = $1.10
  - Average for year: €1 = $1.12
  - End of year: €1 = $1.15

### Translation Worksheet

| Item | € Amount | Rate | $ Amount |
|------|----------|------|----------|
| **Assets** | 1,000,000 | 1.15 (C) | 1,150,000 |
| **Liabilities** | (400,000) | 1.15 (C) | (460,000) |
| **Common stock** | (200,000) | 1.00 (H) | (200,000) |
| **Beginning R/E** | (300,000) | composite | (330,000) |
| **Net income** | (100,000) | 1.12 (A) | (112,000) |
| **CTA (plug)** | — | — | (48,000) |
| **Total** | 0 | | 0 |

### Journal Entry (Consolidation)

```
Dr. Investment in Subsidiary          $48,000
    Cr. OCI—Cumulative Translation Adjustment     $48,000
(Translation adjustment for year)
```

---

## Remeasurement Example

### Facts

**Foreign Branch (Functional Currency = U.S. Dollar):**
- Cash: MXN 500,000
- Inventory: MXN 800,000 (acquired when rate was $0.052)
- Equipment: MXN 1,200,000 (acquired when rate was $0.055)
- Accounts payable: MXN 300,000
- Current rate: $0.050
- Average rate: $0.051

### Remeasurement Worksheet

| Item | MXN | Rate | USD |
|------|-----|------|-----|
| **Cash** | 500,000 | 0.050 (C) | 25,000 |
| **Inventory** | 800,000 | 0.052 (H) | 41,600 |
| **Equipment** | 1,200,000 | 0.055 (H) | 66,000 |
| **Accounts payable** | (300,000) | 0.050 (C) | (15,000) |
| **Net assets** | 2,200,000 | | 117,600 |

**Remeasurement Gain/Loss:** Recognized in earnings (not OCI)

---

## Highly Inflationary Economies

### Definition

An economy is highly inflationary if cumulative inflation ≈ 100% or more over 3 years (roughly 26% annually).

### Special Treatment

For entities operating in highly inflationary economies:
- Functional currency is the **reporting currency** (not local)
- Use **remeasurement method**
- Gains/losses go to **earnings** (not OCI)

### Current Examples (as of 2024)

Countries periodically designated as highly inflationary:
- Venezuela
- Argentina
- Turkey
- Others—monitor inflation data

---

## Intercompany Transactions

### Long-Term Intercompany Balances

For intercompany balances that are "of a long-term investment nature":
- Exchange gains/losses on such balances reported in **OCI**
- Similar treatment as net investment hedge

### Short-Term Intercompany Balances

Regular intercompany receivables/payables:
- Exchange gains/losses in **earnings**
- Eliminated in consolidation

---

## Hedging Foreign Currency Exposure

### Net Investment Hedges (ASC 815)

Hedging the net investment in a foreign operation:
- Designate as net investment hedge
- Effective portion to OCI (same as translation adjustment)
- Reclassify to earnings upon sale/liquidation

### Hedging Foreign Currency Transactions

- Cash flow hedges of forecasted transactions
- Fair value hedges of firm commitments
- See ASC 815 for detailed hedge accounting

---

## Practical Examples

### Example 1: Complete Foreign Currency Transaction

**Facts:**
- December 1: U.S. company purchases inventory from German supplier for €200,000
- December 31: Year-end (payment not yet made)
- January 15: Payment made
- Exchange rates:
  - December 1: €1 = $1.08
  - December 31: €1 = $1.10
  - January 15: €1 = $1.07

**December 1—Purchase:**
```
Dr. Inventory                        $216,000
    Cr. Accounts Payable (€)                  $216,000
(€200,000 × $1.08)
```

**December 31—Year-End:**
```
New carrying amount: €200,000 × $1.10 = $220,000

Dr. Foreign Currency Loss             $4,000
    Cr. Accounts Payable (€)                   $4,000
```

**January 15—Payment:**
```
Cash paid: €200,000 × $1.07 = $214,000
Payable balance: $220,000

Dr. Accounts Payable (€)             $220,000
    Cr. Cash                                  $214,000
    Cr. Foreign Currency Gain                   $6,000
```

**Net Effect:**
- Inventory: $216,000 (historical cost)
- Transaction loss (Year 1): $4,000
- Transaction gain (Year 2): $6,000
- Net cash paid: $214,000

---

### Example 2: Foreign Subsidiary Translation

**Subsidiary Trial Balance (Local Currency = British Pound):**

| Account | £ Amount |
|---------|----------|
| Cash | 100,000 |
| Receivables | 200,000 |
| Inventory | 300,000 |
| Fixed Assets | 600,000 |
| Accumulated Depreciation | (150,000) |
| Accounts Payable | (180,000) |
| Long-term Debt | (320,000) |
| Common Stock | (100,000) |
| Retained Earnings (beg) | (350,000) |
| Sales | (800,000) |
| Cost of Sales | 500,000 |
| Operating Expenses | 200,000 |
| **Total** | **0** |

**Exchange Rates:**
- Historical (stock issued): £1 = $1.20
- Beginning of year: £1 = $1.35
- Average: £1 = $1.40
- Year-end: £1 = $1.45

**Translation to USD (Current Rate Method):**

| Account | £ | Rate | $ |
|---------|---|------|---|
| Cash | 100,000 | 1.45 | 145,000 |
| Receivables | 200,000 | 1.45 | 290,000 |
| Inventory | 300,000 | 1.45 | 435,000 |
| Fixed Assets | 600,000 | 1.45 | 870,000 |
| Accum Depr | (150,000) | 1.45 | (217,500) |
| A/P | (180,000) | 1.45 | (261,000) |
| LT Debt | (320,000) | 1.45 | (464,000) |
| Common Stock | (100,000) | 1.20 | (120,000) |
| Beg R/E | (350,000) | composite | (472,500) |
| Sales | (800,000) | 1.40 | (1,120,000) |
| COGS | 500,000 | 1.40 | 700,000 |
| Operating Exp | 200,000 | 1.40 | 280,000 |
| **CTA (plug)** | — | | **(65,000)** |

---

### Example 3: Intercompany Loan

**Facts:**
- U.S. parent loans €1,000,000 to German subsidiary
- Loan is long-term investment nature (no planned repayment)
- Year-end rate change from $1.10 to $1.15

**Analysis:**
- Exchange gain = €1,000,000 × ($1.15 - $1.10) = $50,000
- Because long-term investment nature, report in OCI

**Parent's Entry:**
```
Dr. Intercompany Loan Receivable      $50,000
    Cr. OCI—Translation Adjustment            $50,000
```

**Consolidation:** Eliminate intercompany loan; CTA remains

---

## Private Company Considerations

### Simplified Approaches

| Area | Consideration |
|------|---------------|
| **Functional currency** | Often simpler if few foreign operations |
| **Hedging** | May not elect hedge accounting |
| **Disclosure** | May have reduced requirements |
| **Translation** | Same requirements as public companies |

### Common Private Company Issues

1. **Related party foreign loans** — Determine if long-term nature
2. **Foreign vendor payments** — Track transaction gains/losses
3. **Functional currency changes** — Rare but impactful
4. **Intercompany pricing** — Tax and accounting implications

---

## Common Audit Issues

### Functional Currency

| Issue | Consideration |
|-------|---------------|
| **Determination** | Document factors considered |
| **Changes** | Only for significant economic changes |
| **Consistency** | Apply consistently across periods |

### Translation vs. Remeasurement

| Issue | Risk |
|-------|------|
| **Wrong method** | Misstated earnings vs. OCI |
| **Rate errors** | Using wrong exchange rates |
| **Intercompany** | Improper elimination |

### Documentation

- Exchange rate sources (Bloomberg, WSJ, central bank)
- Functional currency analysis
- Translation worksheets
- Intercompany balance reconciliations

---

## Disclosure Requirements

### Required Disclosures

| Item | Disclosure |
|------|------------|
| **Transaction gains/losses** | Aggregate amount in net income |
| **Translation adjustments** | Analysis of changes in CTA |
| **Functional currency** | If not obvious |
| **Rate changes** | Significant subsequent rate changes |

### Accumulated Other Comprehensive Income

| Component | Presentation |
|-----------|--------------|
| **Beginning balance** | CTA at start of period |
| **Current period change** | Translation adjustments |
| **Reclassifications** | Upon sale/liquidation |
| **Ending balance** | CTA at end of period |

---

## Sale or Liquidation of Foreign Entity

### Recognition

Upon sale or complete/substantially complete liquidation:
- Release accumulated CTA to earnings
- Part of gain/loss on disposal

**Journal Entry:**
```
Dr. Cash                           $2,000,000
Dr. OCI—CTA                          $150,000
    Cr. Investment in Subsidiary            $1,800,000
    Cr. Gain on Sale                          $350,000
```

### Partial Sales

- If control lost: Release proportionate CTA
- If control retained: No release (equity transaction)

---

## Recent Updates

| ASU | Topic | Impact |
|-----|-------|--------|
| **ASU 2023-01** | Leases—Common Control | Intercompany lease translation |
| **ASU 2020-04** | Reference Rate Reform | Impact on hedging relationships |
| **ASU 2018-02** | Stranded Tax Effects | CTA tax effects |
| **ASU 2017-12** | Hedge Accounting | Net investment hedge improvements |

---

## External Resources

- [FASB ASC 830](https://asc.fasb.org/)
- [FASB ASC 815 (Derivatives and Hedging)](https://asc.fasb.org/)
- [FASB ASC 220 (Comprehensive Income)](https://asc.fasb.org/)
- [Federal Reserve Exchange Rates](https://www.federalreserve.gov/)
- [KPMG: Handbook—Foreign Currency](https://frv.kpmg.us/)
- [PwC: Foreign Currency Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Foreign Currency](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Foreign Currency](https://www.ey.com/)

---

## Navigation

← [Back to Broad Transactions (800s)](README.md) | [Back to Main Guide](../../README.md)
