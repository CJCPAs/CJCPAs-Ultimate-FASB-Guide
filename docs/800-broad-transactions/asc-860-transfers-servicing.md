# ASC 860: Transfers and Servicing

> Comprehensive guidance on determining when transfers of financial assets qualify as sales versus secured borrowings.

## Overview

ASC 860 provides guidance on accounting for transfers and servicing of financial assets. The critical determination is whether a transfer of financial assets qualifies as a sale (resulting in derecognition) or a secured borrowing (assets remain on transferor's books). This topic is essential for understanding factoring arrangements, securitizations, and other asset transfer transactions.

**Core Principle:**
> "A transfer of financial assets shall be accounted for as a sale when the transferor has surrendered control of those assets. Control is considered surrendered when specific criteria are met regarding isolation, transferee rights, and transferor's continuing involvement."

---

## Scope

### Applies To:
- Transfers of financial assets (receivables, loans, securities)
- Servicing of financial assets
- Secured borrowings and collateral
- Repurchase agreements
- Securities lending transactions

### Does NOT Apply To:
- Transfers of nonfinancial assets
- Leases (ASC 842)
- Business combinations (ASC 805)
- Transfers to variable interest entities (evaluate under ASC 810 first)

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Financial Asset** | Cash, ownership interest, or contractual right to receive cash/financial instruments |
| **Transfer** | Conveyance of a financial asset by the transferor to another party |
| **Transferor** | Entity that transfers financial assets |
| **Transferee** | Entity that receives financial assets |
| **Servicing Asset** | Right to receive future revenues from servicing |
| **Servicing Liability** | Obligation to service for benefits less than adequate compensation |
| **Secured Borrowing** | Transfer accounted for as financing (collateralized loan) |
| **Sale** | Transfer resulting in derecognition of assets |

---

## Sale vs. Secured Borrowing

### The Three Conditions for Sale Treatment

A transfer qualifies as a sale if and only if ALL three conditions are met:

| Condition | Requirement |
|-----------|-------------|
| **1. Isolation** | Assets have been isolated from the transferor (beyond reach in bankruptcy) |
| **2. Transferee's rights** | Transferee can pledge or exchange the assets without constraint |
| **3. Effective control** | Transferor does not maintain effective control |

### Condition 1: Legal Isolation

**Key Question:** Are the transferred assets beyond the reach of the transferor and its creditors (even in bankruptcy)?

| Factor | Analysis |
|--------|----------|
| **True sale opinion** | Legal counsel confirms sale |
| **Bankruptcy remoteness** | Structure provides protection |
| **SPE involvement** | May enhance isolation |
| **Jurisdiction** | Different rules by country |

### Condition 2: Transferee's Rights

**Key Question:** Can the transferee freely pledge or exchange the transferred assets?

| Situation | Meets Condition? |
|-----------|------------------|
| Transferee can sell assets | Yes |
| Transferee can pledge as collateral | Yes |
| Restrictions prevent transfer | No |
| Beneficial interest holder (in SPE) can pledge | Evaluate based on SPE |

### Condition 3: Effective Control

**Key Question:** Does the transferor maintain effective control through:**

| Feature | Effective Control? |
|---------|-------------------|
| **Unilateral ability to repurchase** | Yes—control maintained |
| **Agreement to repurchase same assets** | Generally yes—control |
| **Option to repurchase at fair value** | Generally no—not control |
| **Right of first refusal at fair value** | Generally no—not control |
| **Cleanup call** | Generally no—not control |
| **Removal of accounts provision (ROAP)** | Analyze specific terms |

---

## Accounting for Sales

### Recognition

When transfer qualifies as a sale:

1. **Derecognize** transferred assets
2. **Recognize** assets received and liabilities incurred
3. **Recognize** gain or loss

### Components of Gain/Loss Calculation

```
Proceeds received (cash, new assets)
+ Fair value of beneficial interests retained
+ Fair value of servicing asset (or less servicing liability)
- Carrying amount of assets transferred
- Transaction costs
= Gain or loss on sale
```

### Journal Entry Example

**Facts:**
- Sold receivables with carrying amount of $1,000,000
- Cash proceeds: $950,000
- Retained beneficial interest (fair value): $80,000
- Servicing asset (fair value): $15,000
- Recourse liability (fair value): $25,000

**Entry:**
```
Dr. Cash                             $950,000
Dr. Retained Interest                 $80,000
Dr. Servicing Asset                   $15,000
    Cr. Accounts Receivable                  $1,000,000
    Cr. Recourse Liability                      $25,000
    Cr. Gain on Sale                            $20,000
```

---

## Accounting for Secured Borrowings

### When Sale Criteria Not Met

If any of the three conditions is not met:
- Transfer is accounted for as secured borrowing
- Transferred assets remain on transferor's books
- Recognize liability for proceeds received

### Journal Entry Example

**Facts:**
- Pledged $1,000,000 receivables as collateral
- Received $900,000 cash
- Interest rate: 6%

**Entry:**
```
Dr. Cash                             $900,000
    Cr. Secured Borrowing                     $900,000

(Receivables remain on balance sheet; disclose pledging)
```

---

## Servicing Rights

### When to Recognize Servicing Asset or Liability

**Servicing Asset:** When servicing fee exceeds adequate compensation
**Servicing Liability:** When servicing fee is below adequate compensation

### Initial Measurement

Measure at fair value when:
- Transfer qualifies as sale
- Servicing is separated from transferred assets
- Servicing rights are purchased

### Subsequent Measurement

**Two options (irrevocable election by class):**

| Method | Description |
|--------|-------------|
| **Amortization method** | Amortize in proportion to servicing income; assess for impairment |
| **Fair value method** | Measure at fair value each period; changes in earnings |

### Servicing Asset Amortization

**Entry (monthly):**
```
Dr. Amortization Expense              $5,000
    Cr. Servicing Asset                        $5,000
```

### Servicing Asset—Fair Value Method

**Fair Value Increase:**
```
Dr. Servicing Asset                   $8,000
    Cr. Servicing Revenue                      $8,000
```

**Fair Value Decrease:**
```
Dr. Servicing Expense                 $6,000
    Cr. Servicing Asset                        $6,000
```

---

## Repurchase Agreements (Repos)

### Overview

A repurchase agreement involves:
1. Transfer of securities to counterparty
2. Agreement to repurchase same/substantially same securities
3. At fixed price plus interest

### Accounting Treatment

**Typically secured borrowing:**
- Agreement to repurchase = effective control retained
- Securities remain on transferor's books
- Record liability for cash received

### Journal Entries

**At inception:**
```
Dr. Cash                           $1,000,000
    Cr. Repo Liability                      $1,000,000

(Securities transferred remain on balance sheet as pledged)
```

**At maturity:**
```
Dr. Repo Liability                 $1,000,000
Dr. Interest Expense                   $5,000
    Cr. Cash                               $1,005,000
```

### Dollar Rolls

Special type of repo in mortgage-backed securities:
- Transfer and repurchase substantially same (not identical) securities
- May qualify as sale depending on structure

---

## Securities Lending

### Overview

Securities lending involves:
1. Transfer of securities to borrower
2. Collateral received from borrower
3. Agreement to return equivalent securities

### Accounting Treatment

**Typically secured borrowing:**
- Lender maintains control (right to demand return)
- Securities remain on lender's books
- Record collateral (asset) and obligation to return collateral (liability)

### Journal Entries

**Cash collateral received:**
```
Dr. Cash (collateral)               $500,000
    Cr. Obligation to Return Collateral      $500,000

(Securities remain on balance sheet; disclose lending)
```

---

## Practical Examples

### Example 1: Factoring with Recourse (Sale)

**Facts:**
- Company factors $500,000 receivables
- Receives $475,000 cash
- Recourse provision: guarantees $25,000 of collections
- Fair value of recourse liability: $15,000
- Legal opinion confirms isolation
- Factor can freely sell receivables

**Analysis:**
1. ✓ Isolated (legal opinion)
2. ✓ Factor has pledge/exchange rights
3. ✓ No effective control (recourse ≠ repurchase right)

**Treatment:** Sale

**Entry:**
```
Dr. Cash                             $475,000
Dr. Loss on Sale                      $40,000
    Cr. Accounts Receivable                   $500,000
    Cr. Recourse Liability                     $15,000
```

---

### Example 2: Factoring with Recourse (Secured Borrowing)

**Facts:**
- Same as above, BUT:
- Factor cannot pledge/sell receivables without company consent
- Company has right to repurchase at any time

**Analysis:**
1. ? Isolation may be questionable
2. ✗ Constraint on factor's rights
3. ✗ Repurchase right = effective control

**Treatment:** Secured borrowing

**Entry:**
```
Dr. Cash                             $475,000
    Cr. Secured Borrowing—Factor              $475,000

(Receivables remain on balance sheet)
```

---

### Example 3: Securitization with Retained Interest

**Facts:**
- Company transfers $10,000,000 receivables to SPE
- SPE issues:
  - Senior certificates ($8,000,000)—sold to investors
  - Subordinated certificates ($2,000,000)—retained by company
- Servicing retained by company
- Legal isolation confirmed
- SPE can pledge senior certificates

**Analysis:**
- Sale of $8,000,000 to investors (if all conditions met)
- Retained interest in residual

**Calculation:**
- Carrying amount transferred: $10,000,000
- Allocated to sold: $10,000,000 × ($8,000,000 / $10,000,000) = $8,000,000
- Allocated to retained: $10,000,000 × ($2,000,000 / $10,000,000) = $2,000,000
- Proceeds: $8,000,000
- Gain/loss calculation requires fair value allocation

---

### Example 4: Servicing Retained

**Facts (continuing Example 3):**
- Company retains servicing rights
- Annual servicing fee: 0.5% of outstanding principal
- Adequate compensation: 0.3%
- Fair value of servicing asset: $150,000

**Entry for servicing asset:**
```
Dr. Servicing Asset                  $150,000
    Cr. Gain on Sale (additional)            $150,000
```

**Subsequent measurement (amortization method):**
- Amortize over estimated servicing period
- Assess for impairment annually

---

## Participating Interest Transfers

### Requirements for Sale Treatment

A participating interest must have:
1. **Pro rata share** of entire financial asset
2. **Pro rata priority** in cash flows
3. **No recourse** except standard reps and warranties
4. **No subordination** of holder's interest

### Examples

| Transfer | Participating Interest? |
|----------|------------------------|
| 80% undivided interest in loan | Yes (if pro rata) |
| First $1 million of loan | No (not pro rata) |
| Senior tranche of securitization | No (has priority) |
| Receivable segment by customer | No (not pro rata of whole) |

---

## Private Company Considerations

### Common Transactions

| Transaction | Typical Treatment |
|-------------|------------------|
| **Factoring receivables** | Often secured borrowing (recourse, continued involvement) |
| **Lines of credit secured by A/R** | Secured borrowing |
| **Sale of mortgage servicing** | May qualify as sale |

### Documentation Requirements

- Legal analysis of isolation
- Transferee's rights analysis
- Fair value of interests retained
- Servicing arrangement terms

### Simplified Approach

Many private company transfers are clearly:
- Secured borrowings (typical factoring with recourse)
- True sales (outright cash sale with no continuing involvement)

Document analysis and conclusion even if straightforward.

---

## Common Audit Issues

### Sale Qualification

| Issue | Audit Consideration |
|-------|---------------------|
| **Legal isolation** | Obtain/review legal opinion |
| **Transferee constraints** | Review agreement terms |
| **Repurchase provisions** | Analyze for effective control |
| **Related party transfers** | Enhanced scrutiny |

### Fair Value Measurements

| Component | Challenge |
|-----------|-----------|
| **Retained interests** | May require valuation specialist |
| **Servicing assets** | DCF or market approach |
| **Recourse obligations** | Estimate expected losses |

### Disclosure Completeness

- Transferred assets derecognized
- Continuing involvement
- Retained interests
- Servicing assets/liabilities

---

## Disclosure Requirements

### Transfers Accounted for as Sales

| Disclosure | Content |
|------------|---------|
| **Characteristics** | Type of assets transferred |
| **Gain or loss** | Amount and income statement line |
| **Continuing involvement** | Nature and purpose |
| **Key assumptions** | Fair value and cash flow estimates |
| **Servicing** | Nature and fair value of rights |

### Transfers Accounted for as Secured Borrowings

| Disclosure | Content |
|------------|---------|
| **Carrying amount** | Of pledged assets |
| **Collateral rights** | Transferee's rights |
| **Liability** | Associated with transfer |

### Servicing Assets and Liabilities

| Disclosure | Content |
|------------|---------|
| **Carrying amount** | By class |
| **Fair value** | If different from carrying |
| **Method** | Amortization or fair value |
| **Activity** | Additions, disposals, changes |

---

## Interaction with Other Standards

| Topic | Relationship |
|-------|--------------|
| **ASC 810** | Evaluate VIE consolidation first |
| **ASC 820** | Fair value measurement |
| **ASC 310** | Loan accounting |
| **ASC 450** | Guarantee liabilities |
| **ASC 815** | Derivatives in transfer agreements |

---

## Decision Framework

```
Step 1: Is this a transfer of financial assets?
         ↓ Yes
Step 2: Does transferor consolidate transferee (ASC 810)?
         ↓ No (If yes, no sale—both on consolidated books)
Step 3: Are all three sale conditions met?
         • Legal isolation
         • Transferee can pledge/exchange
         • No effective control
         ↓
If ALL YES → Account as Sale
If ANY NO → Account as Secured Borrowing
```

---

## Recent Updates

| ASU | Topic | Impact |
|-----|-------|--------|
| **ASU 2022-02** | TDR and Vintage | Impact on loan transfers |
| **ASU 2020-04** | Reference Rate Reform | Impact on transfer agreements |
| **ASU 2016-15** | Cash Flow Classification | Proceeds from transfers |
| **ASU 2014-11** | Repo Agreements | Enhanced disclosures |

---

## External Resources

- [FASB ASC 860](https://asc.fasb.org/)
- [FASB ASC 810 (Consolidation)](https://asc.fasb.org/)
- [FASB ASC 820 (Fair Value)](https://asc.fasb.org/)
- [SEC Staff Guidance on Securitizations](https://www.sec.gov/)
- [KPMG: Handbook—Transfers and Servicing](https://frv.kpmg.us/)
- [PwC: Transfers and Servicing Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Transfers and Servicing](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Transfers](https://www.ey.com/)

---

## Navigation

← [Back to Broad Transactions (800s)](README.md) | [Back to Main Guide](../../README.md)
