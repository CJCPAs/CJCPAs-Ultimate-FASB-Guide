# ASC 810: Consolidation

> The comprehensive standard for determining when and how to consolidate entities.

## Overview

ASC 810 provides guidance on when a reporting entity should consolidate another entity in its financial statements. It establishes two primary consolidation models: the Variable Interest Entity (VIE) model and the Voting Interest Entity model.

**Core Principle:**
> "A reporting entity with a controlling financial interest in another entity should consolidate that entity."

---

## Scope

### Applies To:
- All legal entities (corporations, LLCs, partnerships, trusts)
- Variable interest entities
- Voting interest entities
- Limited partnerships and similar structures

### Does NOT Apply To:
- Employer's interest in employee benefit plans (ASC 712, 715)
- Investment companies (ASC 946) for investment accounting
- Governmental entities (GASB)

---

## The Consolidation Decision Framework

### Primary Question

**Does the reporting entity have a controlling financial interest?**

### Decision Tree

```
START: Is the entity a VIE?
        │
        ├── YES → Apply VIE Model
        │         Is reporting entity the Primary Beneficiary?
        │         │
        │         ├── YES → CONSOLIDATE
        │         └── NO → Do not consolidate (may need equity method)
        │
        └── NO → Apply Voting Interest Model
                  Does reporting entity have majority voting interest?
                  │
                  ├── YES → CONSOLIDATE
                  └── NO → Do not consolidate (may need equity method)
```

---

## Variable Interest Entity (VIE) Model

### What is a VIE?

A legal entity that has **ANY** of the following characteristics:

| Characteristic | Description |
|----------------|-------------|
| **Insufficient equity** | Equity investment at risk is insufficient to finance activities without additional subordinated financial support |
| **Lack of control** | Equity holders as a group lack power to direct activities that most significantly impact economic performance |
| **Non-proportionate economics** | Equity holders don't receive returns proportionate to voting rights (e.g., through special agreements) |
| **Lack of risk** | Equity holders don't absorb expected losses proportionate to their interests |

### Equity Sufficiency Test

**Generally:** Equity < 10% of total assets = Rebuttable presumption of insufficient equity

**Factors to consider:**
- Entity's activities and assets
- Historical capital needs
- Comparison to similar entities
- Expected variability of future cash flows

### Variable Interests

**Definition:** Contractual, ownership, or other pecuniary interests that change with changes in the entity's net asset fair value.

| Variable Interests | Not Variable Interests |
|-------------------|------------------------|
| Equity investments | Fixed-rate debt (generally) |
| Subordinated debt | Trade payables/receivables at market |
| Guarantees | Operating leases at market |
| Certain service contracts | Fixed-price service contracts |
| Residual value guarantees | Typical employee relationships |
| Most derivatives with entity | Government grants |

### Primary Beneficiary Determination

The primary beneficiary is the party that has **BOTH**:

| Criterion | Description |
|-----------|-------------|
| **Power** | Power to direct the activities that most significantly impact the VIE's economic performance |
| **Economics** | Obligation to absorb losses OR right to receive benefits that could potentially be significant to the VIE |

### Key Activities Analysis

**Question:** Which activities most significantly impact economic performance?

| Entity Type | Typical Key Activities |
|-------------|------------------------|
| Real estate | Operating/leasing, selling property |
| Lending SPE | Managing/servicing loans, workout decisions |
| Securitization | Servicing, credit decisions, liquidation |
| Manufacturing JV | Production, sales, product development |

### Shared Power

If power is shared among multiple parties and both have economics:
- Determine if a single party has power
- Consider substantive participating rights
- If no single party → No primary beneficiary

### Reconsideration Events

Reassess VIE status and primary beneficiary upon:
- Changes in governing documents or contracts
- Changes in equity investment
- Changes in relationships between variable interest holders
- New variable interests or changes to existing ones

---

## Voting Interest Entity Model

### Majority Voting Interest

**General Rule:** Consolidate if >50% voting interest

### Exceptions to Majority Voting

| Exception | Description |
|-----------|-------------|
| **Noncontrolling shareholder rights** | Substantive participating rights may overcome majority ownership |
| **Bankruptcy/legal restrictions** | Control may be with court or trustee |
| **Contractual arrangements** | May transfer effective control to minority |

### Substantive Participating Rights

Rights that allow minority to participate in significant financial and operating decisions in ordinary course of business:

| Substantive Rights | Non-Substantive Rights |
|--------------------|------------------------|
| Approval of operating/capital budgets | Protective rights only |
| Selection of management | Rights exercisable only on trigger events |
| Setting compensation | Rights requiring super-majority |
| Establishing operating/financing policies | Rights subject to significant economic barriers |

### Limited Partnerships

**Special Rules:**
- General partner presumed to control limited partnership
- Presumption may be overcome if limited partners have substantive:
  - Kick-out rights (can remove GP without cause), OR
  - Participating rights

---

## Consolidation Procedures

### Initial Consolidation

**At Acquisition Date:**

1. Measure identifiable assets and liabilities at fair value
2. Measure noncontrolling interest (NCI) at fair value or proportionate share
3. Calculate goodwill or gain on bargain purchase
4. Eliminate intercompany investments

### Ongoing Consolidation

**Each Period:**

1. Add 100% of subsidiary assets, liabilities, revenues, expenses
2. Eliminate intercompany transactions:
   - Intercompany sales/purchases
   - Intercompany receivables/payables
   - Intercompany profit in inventory
   - Intercompany dividends
   - Intercompany interest
3. Attribute net income to controlling and noncontrolling interests
4. Present NCI in equity section

### Journal Entry Format

**Elimination of Investment:**
```
Dr. Common Stock—Subsidiary         $XXX
Dr. Retained Earnings—Subsidiary    $XXX
Dr. Goodwill                        $XXX
    Cr. Investment in Subsidiary            $XXX
    Cr. Noncontrolling Interest             $XXX
```

**Elimination of Intercompany Sale:**
```
Dr. Sales                           $XXX
    Cr. Cost of Goods Sold                  $XXX
```

**Elimination of Intercompany Profit in Inventory:**
```
Dr. Cost of Goods Sold              $XXX
    Cr. Inventory                           $XXX
```

---

## Noncontrolling Interest (NCI)

### Presentation

| Statement | Presentation |
|-----------|--------------|
| **Balance Sheet** | Separate component of equity, clearly identified |
| **Income Statement** | Net income attributable to NCI separately stated |
| **Statement of Changes in Equity** | NCI shown separately |

### Measurement Options (at acquisition)

| Method | Measurement |
|--------|-------------|
| **Fair value** | Full goodwill recognized |
| **Proportionate share** | NCI at % of identifiable net assets |

### Changes in Parent's Ownership

| Transaction | Accounting |
|-------------|------------|
| **Parent acquires additional shares (maintains control)** | Equity transaction—no gain/loss recognized |
| **Parent sells shares (maintains control)** | Equity transaction—no gain/loss recognized |
| **Parent sells shares (loses control)** | Deconsolidation—recognize gain/loss |

---

## Deconsolidation

### When to Deconsolidate

- Loss of controlling financial interest
- Subsidiary enters bankruptcy and control transferred
- Contractual loss of control

### Accounting Treatment

1. Derecognize subsidiary's assets and liabilities
2. Recognize any retained investment at fair value
3. Recognize gain or loss in income
4. Reclassify amounts in AOCI to income (if applicable)

### Gain/Loss Calculation

| Component | Amount |
|-----------|--------|
| Fair value of consideration received | $XXX |
| Fair value of retained investment | XXX |
| **Total** | $XXX |
| Less: Carrying amount of subsidiary's net assets | (XXX) |
| Less: NCI at deconsolidation | (XXX) |
| **Gain (Loss)** | $XXX |

---

## Practical Examples

### Example 1: VIE Analysis

**Facts:**
- Company A creates Entity B to lease equipment
- Entity B has:
  - $10 million in assets (equipment)
  - $1 million equity from unrelated investor
  - $9 million debt guaranteed by Company A
- Company A has option to purchase equipment at end of lease
- Unrelated investor receives fixed preferred return
- Company A directs all leasing decisions

**Step 1: Is Entity B a VIE?**

| Characteristic | Analysis |
|----------------|----------|
| Insufficient equity? | $1M / $10M = 10% → Borderline |
| Equity lacks power? | YES—Company A directs activities |
| Non-proportionate economics? | YES—Company A has upside through purchase option |
| Equity lacks risk? | YES—Company A guarantees debt |

**Conclusion:** Entity B is a VIE

**Step 2: Is Company A the Primary Beneficiary?**

| Criterion | Analysis |
|-----------|----------|
| Power? | YES—directs leasing activities (key activity) |
| Economics? | YES—absorbs losses via guarantee; receives benefits via purchase option |

**Conclusion:** Company A is primary beneficiary → **CONSOLIDATE**

---

### Example 2: Voting Interest with NCI

**Facts:**
- Parent Co. acquires 80% of Subsidiary for $800,000
- Fair value of Subsidiary's identifiable net assets: $900,000
- Fair value of NCI (20%): $200,000
- After acquisition, Parent eliminates $100,000 intercompany sale with $20,000 profit in ending inventory

**At Acquisition:**

NCI fair value: $200,000
Goodwill: ($800,000 + $200,000) - $900,000 = $100,000

**Consolidation Entries:**

*Investment elimination:*
```
Dr. Identifiable Net Assets         $900,000
Dr. Goodwill                        $100,000
    Cr. Investment in Subsidiary            $800,000
    Cr. Noncontrolling Interest             $200,000
```

*Intercompany sale elimination:*
```
Dr. Sales                           $100,000
    Cr. Cost of Goods Sold                  $100,000
```

*Intercompany profit elimination:*
```
Dr. Cost of Goods Sold              $20,000
    Cr. Inventory                           $20,000
```

---

### Example 3: Change in Ownership (Maintaining Control)

**Facts:**
- Parent owns 80% of Subsidiary
- NCI (20%) carrying amount: $150,000
- Parent acquires additional 10% for $90,000
- Fair value of 10% interest: $90,000

**Analysis:**
- Parent maintains control (80% → 90%)
- Equity transaction—no gain/loss

**Entry:**
```
Dr. Noncontrolling Interest         $75,000  (50% of $150,000)
Dr. Additional Paid-in Capital      $15,000  (plug)
    Cr. Cash                                 $90,000
```

---

### Example 4: Deconsolidation

**Facts:**
- Parent owns 100% of Subsidiary with net assets of $500,000
- Parent sells 70% for $420,000
- Fair value of retained 30%: $180,000
- No amounts in AOCI

**Calculation:**

| Component | Amount |
|-----------|-------:|
| Consideration received | $420,000 |
| Fair value of retained interest | 180,000 |
| **Total** | **$600,000** |
| Carrying amount of net assets | (500,000) |
| NCI | (0) |
| **Gain on deconsolidation** | **$100,000** |

**Entry:**
```
Dr. Cash                            $420,000
Dr. Investment in Former Subsidiary $180,000
    Cr. Net Assets of Subsidiary            $500,000
    Cr. Gain on Deconsolidation             $100,000
```

---

## Private Company Alternatives

### VIE Simplification (ASU 2014-07)

Private companies may elect to not apply VIE guidance to:
- Leasing arrangements with lessor under common control
- If lessee (private company) and lessor are under common control
- Substantially all activity is leasing to private company
- Private company has explicitly guaranteed or provided collateral for lessor's debt

**If Elected:**
- Use voting interest model instead
- Additional disclosures required

### Common Control Leasing Arrangements

**Practical Impact:**
- Avoids consolidating common-control lessors
- Particularly helpful for real estate owned by related parties
- Must disclose arrangement details

---

## Disclosure Requirements

### VIEs

**Primary Beneficiary:**
- Carrying amounts and classification of VIE assets and liabilities
- Lack of recourse to general credit of primary beneficiary

**Significant Variable Interest (not Primary Beneficiary):**
- Nature of involvement and when involvement began
- Nature, purpose, size of VIE
- Maximum exposure to loss
- Qualitative and quantitative information about involvement

### General Consolidation

- Consolidation policy
- Nature and effects of changes in ownership
- Terms of any restrictions on consolidated assets
- Information about NCI

### Collateralized Assets

If VIE assets can only be used to settle VIE obligations:
- Carrying amount of assets
- Carrying amount of liabilities with no recourse to general credit

---

## Common Implementation Issues

### 1. VIE Identification
- Not evaluating all relationships for variable interests
- Ignoring implicit variable interests
- Misapplying equity sufficiency test

### 2. Primary Beneficiary Analysis
- Focusing only on power OR economics (need both)
- Not identifying key activities correctly
- Ignoring related party relationships

### 3. Ongoing Reassessment
- Not reassessing upon reconsideration events
- Missing changes that trigger reassessment
- Improper documentation of conclusions

### 4. Consolidation Mechanics
- Incomplete intercompany eliminations
- Improper allocation of income to NCI
- Missing upstream/downstream transactions

### 5. Related Parties
- Not aggregating related party interests
- Ignoring de facto agent relationships
- Missing common control arrangements

---

## Related Party Considerations

### VIE Analysis with Related Parties

When determining primary beneficiary, consider:
- Related parties as a single party
- De facto agents (parties acting on behalf of others)
- Principal-agent relationships

### De Facto Agent Indicators

| Indicator |
|-----------|
| Party cannot finance operations without support from decision maker |
| Decision maker was involved in entity's design |
| Party received interests as contribution from decision maker |
| Interests held are disproportionately large relative to services |

---

## External Resources

- [FASB ASC 810](https://asc.fasb.org/)
- [KPMG: Handbook—Consolidation](https://frv.kpmg.us/)
- [PwC: Consolidation and Equity Method of Accounting Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Consolidation](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Consolidation](https://www.ey.com/)
- [AICPA: VIE Accounting Guide](https://www.aicpa.org/)

---

## Navigation

← [Back to Broad Transactions (800s)](README.md) | [Back to Main Guide](../../README.md)
