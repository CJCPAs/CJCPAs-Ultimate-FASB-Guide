# ASC 845: Nonmonetary Transactions

> Accounting for exchanges and transfers of nonfinancial assets.

## Overview

ASC 845 provides guidance on accounting for nonmonetary transactions—exchanges of goods, services, or other nonfinancial assets without significant monetary consideration. The key issue is determining whether to recognize gain or loss based on fair value or carry over the book value.

> **Core Principle:** Nonmonetary exchanges should be measured at fair value unless the exchange lacks commercial substance, fair value is not determinable, or a specific scope exception applies.

---

## Scope

### Transactions Covered

- Exchanges of nonmonetary assets
- Nonreciprocal transfers (contributions, dividends in kind)
- Barter transactions

### Exclusions

| Excluded Transaction | Applicable Guidance |
|---------------------|---------------------|
| Business combinations | ASC 805 |
| Transfers to owners (spin-offs) | ASC 505-60 |
| Stock issued for services | ASC 718 |
| Contributions to/from NFP | ASC 958 |
| Involuntary conversions | ASC 605-40 |

---

## Key Concept: Commercial Substance

### Definition

A nonmonetary exchange has **commercial substance** if the entity's future cash flows are expected to **change significantly** as a result.

### Indicators of Commercial Substance

| Factor | Commercial Substance |
|--------|---------------------|
| Cash flows differ in risk | Yes |
| Cash flows differ in timing | Yes |
| Cash flows differ in amount | Yes |
| Entity-specific value differs from FV | May indicate |
| Exchange for similar productive assets | Usually no |

### Two-Part Test

An exchange has commercial substance if either:
1. **Configuration of cash flows** differs significantly (risk, timing, amount), OR
2. **Entity-specific value** of assets received differs from assets given up, and the difference is significant relative to fair values

---

## Measurement Principles

### Fair Value Measurement (Commercial Substance)

**When exchange has commercial substance:**
- Measure at fair value of assets given up
- OR fair value of assets received (if more clearly evident)
- Recognize gain or loss

**Journal Entry Example:**
```
Dr. New Asset (at FV received)            $100,000
Dr. Accumulated Depreciation               $40,000
    Cr. Old Asset (at cost)                      $80,000
    Cr. Gain on Exchange                         $60,000
```

### Carrying Amount Measurement (No Commercial Substance)

**When exchange lacks commercial substance:**
- No gain recognized
- New asset = Book value of old asset + boot paid (or − boot received)
- Exception: If boot received is significant, partial gain recognized

**Journal Entry Example:**
```
Dr. New Asset (at BV of old)              $40,000
Dr. Accumulated Depreciation              $40,000
    Cr. Old Asset (at cost)                      $80,000
```

---

## Boot (Monetary Consideration)

### What Is Boot?

Cash or other monetary consideration exchanged as part of a nonmonetary transaction.

### Impact on Accounting

| Situation | Treatment |
|-----------|-----------|
| Boot paid | Add to basis of asset received |
| Boot received (< 25% of FV) | Recognize proportional gain |
| Boot received (≥ 25% of FV) | Treat as monetary transaction |

### Boot Threshold: 25% Rule

**Calculate:**
```
Boot Percentage = Boot Received ÷ (Boot Received + FV of Nonmonetary Assets Received)
```

**If boot percentage:**
- **< 25%:** Nonmonetary exchange rules apply; partial gain recognized
- **≥ 25%:** Fully monetary transaction; recognize full gain

---

## Practical Examples

### Example 1: Exchange with Commercial Substance

**Scenario:** Company A exchanges equipment for different equipment from Company B.

| Item | Company A | Company B |
|------|-----------|-----------|
| Asset given—Cost | $100,000 | $80,000 |
| Asset given—Accum Depr | $60,000 | $30,000 |
| Asset given—Book Value | $40,000 | $50,000 |
| Asset given—Fair Value | $75,000 | $75,000 |

**Company A's Journal Entry:**
```
Dr. Equipment (new)                       $75,000
Dr. Accumulated Depreciation              $60,000
    Cr. Equipment (old)                         $100,000
    Cr. Gain on Exchange                         $35,000
```

Gain = FV received ($75,000) − BV given ($40,000) = $35,000

### Example 2: Exchange WITHOUT Commercial Substance

**Scenario:** Similar trucks exchanged between delivery companies (same risk/timing of cash flows).

| Company A Data | Amount |
|----------------|--------|
| Truck given—Cost | $50,000 |
| Truck given—Accum Depr | $30,000 |
| Truck given—Book Value | $20,000 |
| Truck given—Fair Value | $25,000 |

**No commercial substance—defer gain:**
```
Dr. Truck (new, at BV)                    $20,000
Dr. Accumulated Depreciation              $30,000
    Cr. Truck (old)                             $50,000
```

### Example 3: Exchange with Boot (< 25%)

**Scenario:** Asset exchange plus $10,000 cash received.

| Data | Amount |
|------|--------|
| Asset given—BV | $30,000 |
| Asset given—FV | $50,000 |
| Asset received—FV | $40,000 |
| Boot received | $10,000 |

**Boot percentage:** $10,000 ÷ ($10,000 + $40,000) = 20% (< 25%)

**Total gain if fully recognized:** $50,000 − $30,000 = $20,000

**Gain recognized (proportional):** $20,000 × 20% = $4,000

**Journal Entry:**
```
Dr. New Asset                             $26,000
Dr. Cash                                  $10,000
Dr. Accumulated Depreciation              $XX
    Cr. Old Asset                               $XX
    Cr. Gain on Exchange                        $4,000
```

New asset basis = $30,000 BV − $10,000 boot + $4,000 gain recognized + $XX = $26,000

### Example 4: Exchange with Boot (≥ 25%)

**Scenario:** Asset exchange plus $30,000 cash received.

| Data | Amount |
|------|--------|
| Asset given—FV | $100,000 |
| Asset received—FV | $70,000 |
| Boot received | $30,000 |

**Boot percentage:** $30,000 ÷ ($30,000 + $70,000) = 30% (≥ 25%)

**Treatment:** Fully monetary—recognize entire gain.

---

## Determining Fair Value

### Hierarchy for Nonmonetary Transactions

1. **Quoted prices** in active markets
2. **Similar assets** with observable prices
3. **Valuation techniques** (income, market, cost approaches)

### When FV Not Determinable

If fair value cannot be reasonably determined:
- Use carrying amount of asset given up
- No gain or loss recognized

---

## Special Situations

### Advertising Barter Transactions

**General Rule:** Recognize revenue at fair value only if entity has received cash for similar advertising from unrelated parties.

**If no cash history:** Use book value (typically zero for advertising)

### Inventory Exchanges

Exchanges of inventory for similar inventory are **NOT exchanges** under ASC 845—they are purchases and sales:
- Common in commodities
- Oil and gas industry swaps
- Do not apply nonmonetary exchange rules

### Involuntary Conversions

Insurance proceeds received for destroyed assets:
- Generally results in gain/loss recognition
- Not subject to ASC 845

---

## Disclosure Requirements

### Required Disclosures

1. **Nature** of transaction
2. **Basis of accounting** for assets transferred
3. **Gains or losses** recognized
4. **Fair value** of assets involved (if determinable)

### Example Disclosure

> **Nonmonetary Transactions:** During 20XX, the Company exchanged manufacturing equipment with a net book value of $X million for similar equipment from another manufacturer. No gain or loss was recognized because the exchange lacked commercial substance. The fair value of the assets exchanged was approximately $X million.

---

## Private Company Considerations

### Common Situations

- Vehicle/equipment trade-ins
- Property exchanges
- Barter arrangements with vendors

### Practical Approach

1. Identify if transaction is monetary or nonmonetary
2. Assess commercial substance
3. Determine appropriate measurement basis
4. Document analysis

---

## Common Audit Issues

1. **Commercial substance** — Incorrectly concluding exchange has substance
2. **Fair value determination** — Inadequate support for values used
3. **Boot calculations** — Errors in percentage calculation
4. **Similar assets** — Not recognizing lack of commercial substance
5. **Gain recognition** — Recognizing gains when not appropriate
6. **Related party exchanges** — Additional scrutiny required
7. **Disclosure completeness** — Missing required disclosures

---

## Related Standards

| Standard | Relationship |
|----------|-------------|
| ASC 360 | PP&E recognition and measurement |
| ASC 820 | Fair value measurement |
| ASC 606 | Revenue from contracts with customers |
| ASC 610-20 | Gains from sales of nonfinancial assets |

---

## Summary Decision Tree

```
Is the transaction nonmonetary?
│
├── No → Apply other GAAP (ASC 606, etc.)
│
└── Yes → Does it have commercial substance?
          │
          ├── Yes → Can FV be determined?
          │         │
          │         ├── Yes → Measure at FV; recognize gain/loss
          │         │
          │         └── No → Use carrying amount; no gain/loss
          │
          └── No → Was boot received?
                   │
                   ├── No → Use carrying amount; no gain/loss
                   │
                   └── Yes → Is boot ≥ 25%?
                             │
                             ├── Yes → Monetary transaction; full gain/loss
                             │
                             └── No → Proportional gain; limited recognition
```

---

## External Resources

- [FASB ASC 845](https://asc.fasb.org/)
- [AICPA Practice Aid: Nonmonetary Transactions](https://www.aicpa.org/)
- [KPMG: Handbook—Nonmonetary Transactions](https://frv.kpmg.us/)
- [PwC: Property, Plant, and Equipment Guide](https://viewpoint.pwc.com/)

---

## Navigation

← [Back to Broad Transactions (800s)](README.md) | [Main Guide](../../README.md)
