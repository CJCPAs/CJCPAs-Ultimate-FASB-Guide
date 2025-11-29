# ASC 800-899: Broad Transactions

> Accounting for complex transactions that span multiple areas: business combinations, consolidation, derivatives, and fair value.

## Topic Overview

The 800 series covers significant transactions and accounting concepts that apply broadly across financial statements.

| Topic | Title | Key Standards |
|-------|-------|---------------|
| [ASC 805](asc-805-business-combinations.md) | **Business Combinations** | Acquisition method |
| ASC 808 | Collaborative Arrangements | Joint operating activities |
| [ASC 810](asc-810-consolidation.md) | **Consolidation** | Variable interest entities, voting interest |
| [ASC 815](asc-815-derivatives-hedging.md) | **Derivatives and Hedging** | Hedge accounting |
| [ASC 820](asc-820-fair-value.md) | **Fair Value Measurement** | Fair value hierarchy |
| ASC 825 | Financial Instruments | Fair value option |
| ASC 830 | Foreign Currency | Translation, transactions |
| ASC 835 | Interest | Imputation of interest |
| ASC 840 | Leases (Superseded) | See ASC 842 in [400s](../400-liabilities/README.md) |
| ASC 842 | Leases | (See [400s](../400-liabilities/README.md)) |
| ASC 845 | Nonmonetary Transactions | Exchanges of nonfinancial assets |
| ASC 848 | Reference Rate Reform | LIBOR transition |
| ASC 850 | Related Party Disclosures | Related party transactions |
| ASC 852 | Reorganizations | Bankruptcy |
| ASC 855 | Subsequent Events | Post-balance sheet events |
| ASC 860 | Transfers and Servicing | Securitizations, factoring |

---

## Key Standards

### ASC 805: Business Combinations

📌 **Major Standard — Acquisition accounting**

See detailed guide: [ASC 805: Business Combinations](asc-805-business-combinations.md)

**Overview:**

ASC 805 requires the acquisition method for all business combinations.

**Key Steps:**
1. **Identify the acquirer** — Entity that obtains control
2. **Determine acquisition date** — Date control is obtained
3. **Recognize and measure assets/liabilities** — At fair value
4. **Recognize and measure goodwill** — Residual amount

**Acquisition Method Formula:**
```
Goodwill = Consideration Transferred + NCI + Previously Held Equity
         - Net Identifiable Assets Acquired at Fair Value
```

**Bargain Purchase (Negative Goodwill):**
- Recognize gain in earnings immediately
- First, reassess identification and measurement

---

### ASC 810: Consolidation

📌 **Major Standard — Consolidation and VIE analysis**

See detailed guide: [ASC 810: Consolidation](asc-810-consolidation.md)

**When to Consolidate:**

| Model | Apply When | Consolidate If |
|-------|------------|----------------|
| **Variable Interest Entity (VIE)** | Entity lacks sufficient equity or equity holders lack control | You are the primary beneficiary |
| **Voting Interest** | Not a VIE | You hold majority voting interest |

**VIE Primary Beneficiary Has:**
1. Power to direct activities that most significantly affect economic performance
2. Obligation to absorb losses OR right to receive benefits that could be significant

**Noncontrolling Interest (NCI):**
- Present in equity, separate from parent's equity
- Attribute comprehensive income to NCI

---

### ASC 815: Derivatives and Hedging

📌 **Major Standard — Complex derivative and hedge accounting**

See detailed guide: [ASC 815: Derivatives and Hedging](asc-815-derivatives-hedging.md)

**Derivative Characteristics:**
1. Underlying and notional amount (or payment provision)
2. No initial net investment (or small relative to expected changes)
3. Net settlement (can be settled net in cash)

**Hedge Accounting Types:**

| Hedge Type | What's Being Hedged | Treatment |
|------------|---------------------|-----------|
| **Fair Value Hedge** | Exposure to changes in fair value | Derivative and hedged item at fair value in earnings |
| **Cash Flow Hedge** | Exposure to variable cash flows | Effective portion in OCI, ineffective in earnings |
| **Net Investment Hedge** | Foreign currency exposure of investment in foreign operation | Effective portion in CTA |

**Documentation Requirements:**
- Formal designation at inception
- Risk management objective and strategy
- Hedged item and hedging instrument identification
- Effectiveness assessment method

---

### ASC 820: Fair Value Measurement

📌 **Major Standard — Framework for all fair value measurements**

See detailed guide: [ASC 820: Fair Value Measurement](asc-820-fair-value.md)

**Definition:**
> "The price that would be received to sell an asset or paid to transfer a liability in an orderly transaction between market participants at the measurement date."

**Fair Value Hierarchy:**

| Level | Input Type | Examples |
|-------|------------|----------|
| **Level 1** | Quoted prices in active markets | NYSE stock prices |
| **Level 2** | Observable inputs other than Level 1 | Interest rate swaps, comparable sales |
| **Level 3** | Unobservable inputs | Discounted cash flows with entity assumptions |

**Valuation Approaches:**
- **Market approach** — Prices and other information from market transactions
- **Income approach** — Convert future amounts to single present value
- **Cost approach** — Current replacement cost

---

### ASC 830: Foreign Currency

**Foreign Currency Transactions:**
- Record at spot rate on transaction date
- Remeasure monetary items at each balance sheet date
- Recognize exchange gains/losses in earnings

**Translation of Foreign Operations:**

| Functional Currency | Translation Method | Exchange Differences |
|--------------------|-------------------|----------------------|
| Foreign currency | Current rate method | Cumulative translation adjustment (CTA) in OCI |
| Parent's currency | Remeasurement | In earnings |

**Highly Inflationary Economies:**
- Use parent's currency as functional currency
- Remeasure to parent's currency

---

### ASC 850: Related Party Disclosures

**Required Disclosures:**
- Nature of relationship
- Description of transactions
- Dollar amounts of transactions
- Amounts due to/from related parties

**What's a Related Party?**
- Principal owners (>10% ownership)
- Management
- Immediate families of above
- Affiliates
- Entities under common control

---

### ASC 855: Subsequent Events

**Types:**

| Type | Description | Treatment |
|------|-------------|-----------|
| **Recognized** | Conditions existed at balance sheet date | Adjust financial statements |
| **Non-recognized** | Conditions arose after balance sheet date | Disclose only |

**Evaluation Period:**
- Through the date financial statements are issued (public)
- Through the date financial statements are available to be issued (private)

---

## Recent Updates (2024-2025)

| ASU | Topic | Effective Date | Summary |
|-----|-------|----------------|---------|
| ASU 2024-02 | Crypto Assets | Dec 2024 | Fair value measurement for certain crypto assets |
| ASU 2023-05 | Joint Venture Formations | Jan 2025 | New basis accounting for contributed assets |
| ASU 2020-04 | Reference Rate Reform | Dec 2024 | Optional expedients for LIBOR transition |
| ASU 2017-01 | Business Definition | 2018 | Narrowed definition of business |

### ASU 2024-02: Crypto Assets

**Scope:** Crypto assets that meet all criteria:
- Created/residing on distributed ledger
- Secured through cryptography
- Fungible
- Not created or issued by reporting entity
- Not a financial instrument

**Accounting:** Measure at fair value with changes in net income

**Disclosure:**
- Name, cost basis, fair value for significant holdings
- Annual roll-forward of activity

---

## Practical Examples

### Business Combination

**Scenario:** Company A acquires 100% of Company B for $10M cash. Fair value of B's net identifiable assets: $8M.

**Journal Entry:**
```
Dr. Identifiable Assets (at FV)  $8,000,000
Dr. Goodwill                     $2,000,000
    Cr. Cash                             $10,000,000
```

### Fair Value Hedge (Interest Rate Swap)

**Scenario:** Company has fixed-rate debt and enters swap to receive fixed/pay variable to hedge fair value exposure.

**At Period End (rates decline, swap has negative fair value of $50,000):**
```
Dr. Loss on Hedge                $50,000
    Cr. Derivative Liability             $50,000

Dr. Debt (carrying amount)       $50,000
    Cr. Gain on Hedged Item              $50,000
```

### Foreign Currency Transaction

**Scenario:** US company sells €100,000 of goods when rate is $1.10. At collection, rate is $1.15.

**At Sale:**
```
Dr. Accounts Receivable (€)      $110,000
    Cr. Revenue                          $110,000
```

**At Collection:**
```
Dr. Cash                         $115,000
    Cr. Accounts Receivable (€)          $110,000
    Cr. Foreign Currency Gain            $5,000
```

---

## Private Company Considerations

### PCC Alternatives

| Topic | Private Company Alternative |
|-------|---------------------------|
| **Goodwill** | Amortize over 10 years; simplified impairment |
| **Business Combinations** | Subsume certain intangibles into goodwill |
| **VIEs** | Alternative consolidation guidance under common control |
| **Derivatives** | Simplified hedge accounting |

### Practical Expedients

**Interest Rate Swaps:**
- Private companies can use simplified hedge accounting for plain vanilla swaps
- Shortcut method available if criteria met

---

## Common Audit Issues

1. **Business Combinations** — Incorrect fair value of intangibles
2. **Consolidation** — Missing VIE analysis
3. **Derivatives** — Inadequate hedge documentation
4. **Fair Value** — Insufficient support for Level 3 inputs
5. **Related Parties** — Incomplete identification

---

## Disclosure Checklist

### ASC 805 Business Combinations
- [ ] Name and description of acquiree
- [ ] Acquisition date
- [ ] Percentage acquired
- [ ] Primary reasons for combination
- [ ] Fair value of consideration
- [ ] Amounts for major classes of assets/liabilities
- [ ] Goodwill amount and factors
- [ ] Contingent consideration terms

### ASC 820 Fair Value
- [ ] Fair value measurements by level
- [ ] Transfers between levels
- [ ] Level 3 reconciliation
- [ ] Valuation techniques and inputs
- [ ] Sensitivity analysis for significant Level 3 measurements

---

## External Resources

- [FASB ASC 800 Topics](https://asc.fasb.org/)
- [KPMG: Handbook—Business Combinations](https://frv.kpmg.us/)
- [KPMG: Handbook—Derivatives and Hedging](https://frv.kpmg.us/)
- [PwC: Business Combinations and Noncontrolling Interests](https://viewpoint.pwc.com/)
- [PwC: Fair Value Measurements](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Accounting for Business Combinations](https://www.iasplus.com/en-us)
- [EY: Fair Value Measurement](https://www.ey.com/)

---

## Navigation

← [Previous: Expenses (700s)](../700-expenses/README.md) | [Back to Main Guide](../../README.md) | [Next: Industry-Specific (900s) →](../900-industry/README.md)
