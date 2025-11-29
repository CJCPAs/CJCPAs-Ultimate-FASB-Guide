# ASC 405: Liabilities

> General guidance on liability recognition, measurement, and extinguishment.

## Overview

ASC 405 provides general guidance on liability accounting, focusing on when and how liabilities should be derecognized (extinguished). This topic establishes the framework for understanding when an entity is relieved of its obligation and addresses in-substance defeasance and other extinguishment scenarios.

**Core Principle:**
> "A liability should be derecognized when and only when it has been extinguished—either by the debtor paying the creditor, or by the debtor being legally released from being the primary obligor."

---

## Scope

### Applies To:
- Derecognition of liabilities
- Extinguishment of debt
- In-substance defeasance
- Liability settlement and modification

### Does NOT Apply To:
- Initial recognition of liabilities (various topics)
- Specific liability types with dedicated guidance (leases, pensions, etc.)
- Contingent liabilities (ASC 450)

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Liability** | Probable future sacrifice of economic benefits arising from present obligations |
| **Extinguishment** | Debtor is relieved of obligation, either by payment or legal release |
| **In-Substance Defeasance** | Placing assets in trust to service debt (generally does not result in extinguishment) |
| **Legal Defeasance** | Debtor legally released from obligation |
| **Primary Obligor** | Party with primary responsibility for debt |

---

## Liability Extinguishment Criteria

### When Is a Liability Extinguished?

A debtor shall derecognize a liability if and only if:

| Condition | Description |
|-----------|-------------|
| **1. Paid** | Debtor pays the creditor and is relieved of obligation |
| **2. Legally Released** | Debtor is legally released from being primary obligor |

### In-Substance Defeasance

**Key Rule:** Placing assets in an irrevocable trust to service debt does **NOT** result in extinguishment unless:
- Debtor is legally released, OR
- Meets specific criteria for certain government obligations

**Journal Entry (In-Substance Defeasance—No Extinguishment):**
```
Dr. Assets Held in Trust            $1,000,000
    Cr. Cash                                   $1,000,000
(Assets placed in trust; debt remains on balance sheet)
```

### Legal Release Examples

| Situation | Extinguished? |
|-----------|---------------|
| Creditor formally releases debtor | Yes |
| Court judgment releases obligation | Yes |
| Assets placed in trust, debtor not released | No |
| Third party assumes debt, creditor releases original debtor | Yes |
| Third party assumes debt, creditor does not release | No (original debtor is guarantor) |

---

## Accounting for Extinguishment

### Gain or Loss Recognition

When a liability is extinguished:

```
Gain/Loss = Carrying Amount of Liability - Consideration Paid
```

**Journal Entry (Extinguishment at Less Than Carrying Amount):**
```
Dr. Bonds Payable                  $1,000,000
Dr. Premium on Bonds                  $50,000
    Cr. Cash                                    $950,000
    Cr. Gain on Extinguishment                  $100,000
```

**Journal Entry (Extinguishment at More Than Carrying Amount):**
```
Dr. Bonds Payable                  $1,000,000
Dr. Loss on Extinguishment            $75,000
    Cr. Cash                                   $1,075,000
```

### Components of Carrying Amount

| Component | Treatment |
|-----------|-----------|
| Face amount | Included |
| Unamortized premium/discount | Included |
| Unamortized debt issuance costs | Included (reduces carrying amount) |
| Fair value adjustments (hedged items) | Included |

---

## Troubled Debt Restructuring (Historical)

**Note:** For entities that have adopted ASU 2022-02, TDR guidance is eliminated. Below is historical reference.

### Pre-ASU 2022-02 Treatment

When creditor grants concession to debtor in financial difficulty:

**Debtor Accounting:**

| Restructuring Type | Treatment |
|-------------------|-----------|
| **Asset transfer** | Record asset at FV; recognize gain |
| **Equity issuance** | Record equity at FV; recognize gain |
| **Term modification** | Compare future cash flows to carrying amount |

### Post-ASU 2022-02

- TDR accounting eliminated
- Evaluate modifications under general modification guidance
- Enhanced disclosure requirements for modifications to borrowers with financial difficulty

---

## Liability Modifications

### General Framework

When liability terms are modified (not TDR):

| Test | Threshold | Treatment |
|------|-----------|-----------|
| **10% Test** | Compare PV of new cash flows to old | |
| < 10% difference | Modification | Prospective adjustment |
| ≥ 10% difference | Extinguishment | Gain/loss recognition |

### Modification Accounting

**If modification (< 10%):**
```
Dr. Debt Issuance Costs (new)         $25,000
    Cr. Cash                                    $25,000
(Capitalize new costs; adjust effective rate prospectively)
```

### Extinguishment Accounting

**If extinguishment (≥ 10%):**
```
Dr. Old Debt                       $1,000,000
Dr. Loss on Extinguishment            $30,000
    Cr. New Debt                             $1,000,000
    Cr. Cash (fees)                             $30,000
(New debt at fair value; old costs written off)
```

---

## Practical Examples

### Example 1: Debt Repurchase in Open Market

**Facts:**
- Bond carrying amount: $980,000 (face $1,000,000 less $20,000 discount)
- Repurchase price: $920,000

**Journal Entry:**
```
Dr. Bonds Payable                  $1,000,000
    Cr. Discount on Bonds Payable              $20,000
    Cr. Cash                                   $920,000
    Cr. Gain on Extinguishment                  $60,000
```

---

### Example 2: Debt Assumed by Third Party

**Facts:**
- Company A owes Bank $500,000
- Company B agrees to assume the debt
- Bank releases Company A from obligation
- Company A pays Company B $480,000 for assumption

**Company A Journal Entry:**
```
Dr. Note Payable—Bank               $500,000
    Cr. Cash                                   $480,000
    Cr. Gain on Extinguishment                  $20,000
```

---

### Example 3: Failed In-Substance Defeasance

**Facts:**
- $2,000,000 bonds outstanding
- Place $2,100,000 in irrevocable trust (sufficient for all payments)
- Creditor does NOT release debtor

**Journal Entry:**
```
Dr. Assets Held in Defeasance Trust  $2,100,000
    Cr. Cash                                  $2,100,000

(NO entry to remove debt—remains on balance sheet)
```

**Balance Sheet Presentation:**
- Assets: Restricted assets held in trust: $2,100,000
- Liabilities: Bonds payable: $2,000,000
- Disclose the defeasance arrangement

---

### Example 4: Negotiated Settlement

**Facts:**
- Accounts payable to vendor: $100,000
- Vendor agrees to accept $75,000 as payment in full

**Journal Entry:**
```
Dr. Accounts Payable                $100,000
    Cr. Cash                                    $75,000
    Cr. Gain on Settlement                      $25,000
```

---

## Participating Mortgage Loans

### Overview

Some mortgage arrangements include lender participation in:
- Property appreciation
- Property cash flows
- Both

### Accounting Treatment

| Element | Treatment |
|---------|-----------|
| **Base loan** | Standard liability accounting |
| **Participation feature** | May be separate liability or combined |
| **Contingent amounts** | Accrue when determinable |

---

## Insurance-Related Assessments

### Premium-Based Assessments

Recognize liability when:
- Assessment relates to insured event in current/prior period
- Amount is reasonably estimable
- Obligating event has occurred

### Loss-Based Assessments

Recognize liability when:
- Related to losses in current/prior period
- Amount is reasonably estimable

---

## Private Company Considerations

### Simplified Extinguishment Analysis

Many private company debt modifications are straightforward:
- Refinancing with same bank at market rate
- Clear modification or extinguishment determination
- Document analysis even if conclusion is obvious

### Common Private Company Issues

| Issue | Consideration |
|-------|---------------|
| **Related party debt** | Must still apply extinguishment criteria |
| **Informal modifications** | Document terms and evaluate |
| **Covenant waivers** | May not change debt terms |
| **Guarantees** | Consider if primary obligor changes |

---

## Disclosure Requirements

### Extinguishment Disclosures

| Item | Disclosure |
|------|------------|
| **Description** | Nature of extinguishment |
| **Gain or loss** | Amount and income statement location |
| **Source of funds** | How extinguishment was funded |

### In-Substance Defeasance

| Item | Disclosure |
|------|------------|
| **Description** | Terms of arrangement |
| **Assets in trust** | Amount and nature |
| **Debt outstanding** | Related debt still on books |

---

## Common Audit Issues

### Extinguishment Recognition

| Issue | Consideration |
|-------|---------------|
| **Legal release** | Obtain evidence of release |
| **Third party assumptions** | Confirm creditor agreement |
| **In-substance defeasance** | Verify debt remains on books |

### Gain/Loss Calculation

| Issue | Audit Focus |
|-------|-------------|
| **Carrying amount** | Include all components |
| **Consideration** | Fair value of non-cash items |
| **Debt issuance costs** | Properly written off |

---

## Recent Updates

| ASU | Topic | Impact |
|-----|-------|--------|
| **ASU 2022-02** | TDR and Vintage | Eliminated TDR; new modification disclosures |
| **ASU 2020-06** | Convertible Instruments | Impacts debt carrying amounts |
| **ASU 2017-07** | Presentation of Pension Costs | Impacts certain liabilities |

---

## External Resources

- [FASB ASC 405](https://asc.fasb.org/)
- [FASB ASC 470 (Debt)](https://asc.fasb.org/)
- [FASB ASC 860 (Transfers)](https://asc.fasb.org/)
- [KPMG: Handbook—Debt and Equity Financing](https://frv.kpmg.us/)
- [PwC: Financing Transactions Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Debt](https://www.iasplus.com/en-us)

---

## Navigation

← [Back to Liabilities (400s)](README.md) | [Back to Main Guide](../../README.md)
