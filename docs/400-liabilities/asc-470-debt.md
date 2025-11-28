# ASC 470: Debt

> The comprehensive standard for accounting for debt instruments, modifications, and extinguishments.

## Overview

ASC 470 provides guidance on the recognition, measurement, and disclosure of debt instruments, including initial recognition, ongoing measurement, modifications, extinguishments, and troubled debt restructurings. The standard also addresses classification of debt as current or noncurrent and specific guidance for convertible instruments.

**Core Principle:**
> "Debt shall be presented in the balance sheet at amounts reflecting its contractual obligations, with proper classification between current and noncurrent based on contractual maturities and available refinancing arrangements."

---

## Scope

### Applies To:
- Notes payable and bonds payable
- Convertible debt instruments
- Debt modifications and extinguishments
- Troubled debt restructurings (TDR)
- Participating mortgage loans
- Product financing arrangements
- Debt with conversion features

### Related Standards:
- ASC 405: Liabilities—Extinguishments of Liabilities
- ASC 480: Distinguishing Liabilities from Equity
- ASC 815: Derivatives and Hedging (for certain conversion features)
- ASC 835: Interest

---

## Key Updates

### ASU 2020-06: Convertible Instruments and Contracts in Entity's Own Equity

| Aspect | Previous GAAP | Current GAAP (ASU 2020-06) |
|--------|---------------|----------------------------|
| Beneficial conversion feature | Separate equity component | No separation—single liability |
| Cash conversion feature | Separate equity component | No separation—single liability |
| Treasury stock method for EPS | Used for certain convertibles | If-converted method required |
| **Effective dates** | Public: 2022; Private: 2024 | |

---

## Initial Recognition

### Issuance at Par

**Journal Entry:**
```
Dr. Cash                           $1,000,000
    Cr. Notes Payable                        $1,000,000
```

### Issuance at a Discount

**Facts:** $1,000,000 face, issued at 97 ($970,000)

**Journal Entry:**
```
Dr. Cash                           $970,000
Dr. Debt Discount                  $30,000
    Cr. Notes Payable                        $1,000,000
```

**Presentation:** Discount is contra-liability, presented net

### Issuance at a Premium

**Facts:** $1,000,000 face, issued at 103 ($1,030,000)

**Journal Entry:**
```
Dr. Cash                           $1,030,000
    Cr. Notes Payable                        $1,000,000
    Cr. Debt Premium                         $30,000
```

### Debt Issuance Costs

**Treatment:** Presented as direct deduction from carrying amount (not as an asset)

**Journal Entry:**
```
Dr. Cash (net proceeds)            $980,000
Dr. Debt Issuance Costs            $20,000
    Cr. Notes Payable                        $1,000,000
```

**Amortization:** Effective interest method over term of debt

---

## Subsequent Measurement

### Effective Interest Method

| Component | Calculation |
|-----------|-------------|
| **Interest expense** | Carrying amount × Effective interest rate |
| **Cash payment** | Face amount × Stated interest rate |
| **Amortization** | Interest expense − Cash payment |

### Example: Discount Amortization

**Facts:**
- Face: $1,000,000
- Issued at: $950,000
- Stated rate: 5%
- Effective rate: 6%
- Term: 5 years

**Year 1:**

| Component | Amount |
|-----------|-------:|
| Interest expense | $950,000 × 6% = $57,000 |
| Cash interest | $1,000,000 × 5% = $50,000 |
| Discount amortization | $57,000 − $50,000 = $7,000 |

**Journal Entry:**
```
Dr. Interest Expense               $57,000
    Cr. Debt Discount                        $7,000
    Cr. Cash                                 $50,000
```

**New carrying amount:** $950,000 + $7,000 = $957,000

---

## Classification: Current vs. Noncurrent

### General Rule

| Classification | Criteria |
|----------------|----------|
| **Current** | Due within one year (or operating cycle) |
| **Noncurrent** | Due beyond one year |

### Exceptions Allowing Noncurrent Classification

| Exception | Requirements |
|-----------|--------------|
| **Refinancing with long-term debt** | Agreement in place at B/S date; ability and intent to refinance |
| **Unused long-term credit facility** | Available for refinancing; intent to use |
| **Waiver of covenant violation** | Waiver covers > 12 months from B/S date |

### Subjective Acceleration Clauses

If lender can demand repayment based on subjective evaluation (e.g., material adverse change):
- Classify as current if circumstances make acceleration probable
- Disclose clause existence even if current classification not required

### Covenant Violations

| Situation | Classification |
|-----------|----------------|
| Violation exists at B/S date, no waiver | Current (cross-default provisions may affect other debt) |
| Violation waived for > 12 months | May remain noncurrent |
| Violation cured by B/S date | May remain noncurrent |
| Probable future violation | Generally noncurrent (disclose) |

---

## Debt Modifications and Exchanges

### Modification vs. Extinguishment

**Key Question:** Is the transaction a modification (continuation of existing debt) or an extinguishment (old debt replaced by new)?

### 10% Test for Debt with Same Creditor

**Compare:** Present value of cash flows under new terms vs. old terms

| Result | Accounting |
|--------|------------|
| Difference ≥ 10% | **Extinguishment**—recognize gain/loss |
| Difference < 10% | **Modification**—adjust terms prospectively |

### Cash Flow Test Calculation

Include in cash flows:
- Principal payments
- Interest payments
- Fees (paid to creditor)

**Discount rate:** Original effective interest rate

### Extinguishment Accounting

**When debt is extinguished:**

| Component | Treatment |
|-----------|-----------|
| Carrying amount of old debt | Derecognize |
| New debt | Record at fair value |
| Difference | Gain or loss in earnings |
| Third-party costs | Expense immediately |
| Creditor fees | Include in gain/loss calculation |

**Journal Entry—Extinguishment with Gain:**
```
Dr. Notes Payable (Old)            $1,000,000
    Cr. Notes Payable (New)                  $950,000
    Cr. Gain on Debt Extinguishment          $50,000
```

### Modification Accounting

**When debt is modified (< 10% change):**

| Component | Treatment |
|-----------|-----------|
| Carrying amount | Adjust for fees paid to creditor |
| Third-party costs | Expense immediately |
| Creditor fees | Amortize over remaining term |
| Interest rate | Calculate new effective rate going forward |

**Journal Entry—Modification:**
```
Dr. Notes Payable (reduce for fee)  $XXX
    Cr. Cash (fee paid to creditor)          $XXX
```

---

## Troubled Debt Restructuring (TDR)

### Definition

A restructuring where the creditor grants a concession it would not otherwise consider for economic or legal reasons related to the debtor's financial difficulties.

**Note:** ASU 2022-02 eliminated TDR accounting for creditors but retained debtor guidance.

### Debtor Accounting

**Two Types of Restructuring:**

| Type | Description |
|------|-------------|
| **Transfer of assets** | Debtor transfers assets to settle debt |
| **Modification of terms** | Creditor agrees to reduced payments, lower interest, extended maturity |

### Transfer of Assets

**Accounting:**
1. Recognize gain/loss on asset disposition
2. Recognize gain on debt restructuring

**Journal Entry:**
```
Dr. Notes Payable                  $500,000
    Cr. Asset Transferred                    $300,000
    Cr. Gain on Asset Sale                   $50,000
    Cr. Gain on TDR                          $150,000
```

### Modification of Terms

**Compare:**
- Carrying amount of debt (including accrued interest)
- Total future cash payments under new terms

| Result | Accounting |
|--------|------------|
| Future payments < Carrying amount | Recognize gain immediately; no future interest |
| Future payments ≥ Carrying amount | No gain; reduce effective interest rate |

---

## Convertible Debt (Post-ASU 2020-06)

### Simplified Accounting

Under current GAAP, most convertible debt is accounted for as a **single liability**:
- No separation of conversion feature
- No beneficial conversion feature (BCF) accounting
- Entire instrument measured at amortized cost

### When Separation Still Required

| Feature | Separation Required? |
|---------|---------------------|
| Embedded derivatives meeting bifurcation criteria | Yes (ASC 815) |
| Instruments with substantial premium conversion | May require ASC 815 analysis |

### Example: Convertible Debt Issuance

**Facts:**
- Issue $1,000,000 convertible notes
- Convertible into 20,000 shares
- Issued at face value
- Debt issuance costs: $40,000

**Journal Entry:**
```
Dr. Cash                           $960,000
Dr. Debt Issuance Costs            $40,000
    Cr. Convertible Notes Payable            $1,000,000
```

### Conversion

**Upon Conversion:**

| Method | Description |
|--------|-------------|
| **Book value method** | Most common—carrying amount becomes equity |
| **Market value method** | Rarely used—recognize gain/loss |

**Journal Entry—Book Value Method:**
```
Dr. Convertible Notes Payable      $1,000,000
    Cr. Common Stock                         $20,000
    Cr. Additional Paid-in Capital           $980,000
```

### Induced Conversions

If additional consideration given to induce conversion:
- Recognize expense for fair value of additional consideration

---

## Fair Value Option

### Election

Entities may elect to measure debt at fair value (ASC 825):
- Election irrevocable
- Made on instrument-by-instrument basis
- Changes in fair value → Earnings (except own credit component → OCI)

### Own Credit Risk

Changes in fair value due to changes in entity's own credit risk:
- Recognized in OCI
- Not reclassified to earnings

---

## Practical Examples

### Example 1: Debt Modification vs. Extinguishment

**Facts:**
- Existing debt: $1,000,000 at 6%, 3 years remaining
- Modified debt: $1,000,000 at 5%, 4 years
- Fees paid to creditor: $20,000
- Third-party costs: $15,000

**10% Test:**

| Cash Flows | Old Terms | New Terms |
|------------|----------:|----------:|
| Year 1 | $60,000 | $50,000 |
| Year 2 | $60,000 | $50,000 |
| Year 3 | $1,060,000 | $50,000 |
| Year 4 | — | $1,050,000 |
| **PV at 6%** | **$1,000,000** | **$?** |

PV of new cash flows at 6%: $50,000/1.06 + $50,000/1.06² + $50,000/1.06³ + $1,050,000/1.06⁴ = ~$966,000

**Difference:** ($1,000,000 − $966,000) / $1,000,000 = 3.4%

**Conclusion:** < 10% = **Modification** (not extinguishment)

**Accounting:**
```
Dr. Notes Payable                  $20,000
    Cr. Cash                                 $20,000
Dr. Expense (Third-party costs)    $15,000
    Cr. Cash                                 $15,000
```

New effective rate calculated prospectively.

---

### Example 2: Troubled Debt Restructuring

**Facts:**
- Debtor owes $500,000 principal + $25,000 accrued interest
- Creditor agrees to:
  - Reduce principal to $400,000
  - Reduce interest to 3%
  - Extend term to 5 years

**Calculate future payments:**
- Annual interest: $400,000 × 3% = $12,000
- Total payments: ($12,000 × 5) + $400,000 = $460,000

**Compare:**
- Carrying amount: $525,000
- Future payments: $460,000

**Gain:** $525,000 − $460,000 = $65,000

**Journal Entry:**
```
Dr. Notes Payable                  $500,000
Dr. Accrued Interest               $25,000
    Cr. Restructured Notes Payable           $460,000
    Cr. Gain on TDR                          $65,000
```

**Future periods:** No interest expense (future payments allocated entirely to principal)

---

### Example 3: Convertible Debt with Subsequent Conversion

**Facts:**
- Issued $2,000,000 convertible notes at par
- Convertible into 100,000 common shares ($1 par)
- Debt issuance costs: $100,000
- After 2 years, unamortized DIC: $60,000
- Carrying amount at conversion: $2,000,000 − $60,000 = $1,940,000

**Conversion Entry (Book Value Method):**
```
Dr. Convertible Notes Payable      $2,000,000
    Cr. Debt Issuance Costs                  $60,000
    Cr. Common Stock                         $100,000
    Cr. APIC                                 $1,840,000
```

---

## Disclosure Requirements

### General Debt Disclosures

| Disclosure | Description |
|------------|-------------|
| Fair value | Fair value of debt (ASC 825) |
| Maturities | Aggregate maturities for 5 years |
| Interest rates | Weighted-average or range |
| Collateral | Assets pledged as security |
| Covenants | Significant financial covenants |

### Specific Disclosures

| Topic | Required Disclosure |
|-------|---------------------|
| Line of credit | Amounts available, terms |
| Debt modifications | Nature, terms, gain/loss |
| Convertible debt | Conversion terms, shares issuable |
| TDR | Description, gain recognized |
| Covenant violations | Nature, impact, waivers |

---

## Common Implementation Issues

### 1. Classification Errors
- Not considering subjective acceleration clauses
- Improper assessment of refinancing ability
- Missing cross-default provisions

### 2. Modification Accounting
- Not performing 10% test
- Wrong discount rate for PV calculation
- Improper treatment of costs

### 3. Effective Interest Method
- Using straight-line when not materially different
- Calculation errors with complex instruments
- Not including all components in amortization

### 4. Convertible Debt
- Applying old BCF guidance after ASU 2020-06
- Improper conversion accounting
- Wrong EPS treatment

### 5. TDR Analysis
- Not identifying concessions granted
- Improper gain calculation
- Missing disclosures

---

## Private Company Considerations

### Practical Expedients

| Area | Consideration |
|------|---------------|
| **Variable-rate debt** | May use simplified hedge accounting (ASU 2017-12) |
| **Related-party debt** | Consider stated vs. imputed interest |
| **Closely-held entities** | Debt vs. equity classification critical |

### Common Structures

- Shareholder loans
- Related-party financing
- Owner guarantees
- Subordinated debt arrangements

### Debt vs. Equity Evaluation

For private companies, carefully evaluate:
- Fixed maturity date
- Fixed payment schedule
- Creditor remedies on default
- Subordination terms
- Economic substance of arrangement

---

## Line of Credit and Revolving Arrangements

### Classification

| Arrangement | Classification |
|-------------|----------------|
| Short-term revolver | Current liability (drawn amounts) |
| Long-term revolver | May classify as noncurrent if qualifying |
| Evergreen facilities | Evaluate based on terms |

### Disclosure

- Total commitment amount
- Amount drawn vs. available
- Expiration date
- Financial covenant requirements
- Interest rate terms

---

## Product Financing Arrangements

### Definition

Arrangements where entity sells product and simultaneously agrees to repurchase it (or substantially identical product).

### Accounting

If arrangement is in substance a financing:
- Do not derecognize inventory
- Record liability for proceeds received
- Recognize financing costs over term

---

## External Resources

- [FASB ASC 470](https://asc.fasb.org/)
- [KPMG: Handbook—Debt and Equity Financing](https://frv.kpmg.us/)
- [PwC: Financing Transactions Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Debt and Equity](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Debt](https://www.ey.com/)
- [AICPA: Debt Accounting Guide](https://www.aicpa.org/)

---

## Navigation

← [Back to Liabilities (400s)](README.md) | [Back to Main Guide](../../README.md)
