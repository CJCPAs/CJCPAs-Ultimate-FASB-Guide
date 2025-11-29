# ASC 460: Guarantees

> Recognition, measurement, and disclosure of guarantee obligations and warranty liabilities.

## Overview

ASC 460 addresses the accounting for guarantees, including product warranties, indemnification agreements, and standby letters of credit. Guarantors must recognize a liability for the fair value of the obligation at inception and disclose the nature and terms of guarantees, even when the likelihood of payment is remote.

**Core Principle:**
> "A guarantor shall recognize a liability for the fair value of the obligation undertaken in issuing the guarantee at the guarantee's inception, except for certain specified exceptions."

---

## Scope

### Applies To:
- Product warranties
- Standby letters of credit
- Debt guarantees
- Indemnification agreements
- Surety bonds
- Performance bonds

### Exceptions (Recognition Only)

| Exception | Treatment |
|-----------|-----------|
| Guarantees between parents and subsidiaries | Disclosure only |
| Guarantees of own performance | Disclosure only |
| Guarantees accounted for as derivatives | Follow ASC 815 |
| Guarantees accounted for as insurance | Follow ASC 944 |
| Lessee guarantee of residual value | Follow ASC 842 |

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Guarantee** | Contract requiring guarantor to make payment if specified triggering event occurs |
| **Guarantor** | Party that issues the guarantee |
| **Guaranteed Party** | Party whose obligation is guaranteed |
| **Obligor** | Entity whose performance is guaranteed |
| **Indemnification** | Agreement to protect against loss |
| **Standby Letter of Credit** | Bank guarantee of payment |

---

## Types of Guarantees

### 1. Product Warranties

**Assurance-type (standard warranties):**
- Included in sale price
- Provides assurance product meets specifications
- **Accrue estimated costs under ASC 460**

**Service-type (extended warranties):**
- Sold separately or bundled
- Provides additional service
- **Account as separate performance obligation under ASC 606**

---

### 2. Debt Guarantees

Guarantee of another entity's debt obligations:
- Parent guaranteeing subsidiary debt
- Personal guarantees by owners
- Cross-company guarantees

---

### 3. Indemnification Agreements

Common in business combinations and contracts:
- Tax indemnifications
- Environmental indemnifications
- IP infringement indemnifications
- Breach of rep & warranty indemnifications

---

### 4. Standby Letters of Credit

Bank-issued guarantees:
- Performance guarantees
- Payment guarantees
- Credit enhancement

---

## Recognition and Measurement

### Initial Recognition

**At Inception of Guarantee:**
Record liability at fair value of obligation undertaken.

| Guarantee Type | Fair Value Approach |
|----------------|---------------------|
| **Stand-alone** | Price that would be charged |
| **In conjunction with other transaction** | Allocate based on relative fair value |
| **Recurring/standard** | May use expected cost approach |

### Journal Entry—Guarantee Issued

**Guarantee issued in arm's-length transaction:**
```
Dr. Cash                              $10,000
    Cr. Guarantee Obligation                  $10,000
```

**Guarantee issued to related party:**
```
Dr. Investment in Subsidiary          $10,000
    Cr. Guarantee Obligation                  $10,000
(Or other appropriate account)
```

---

## Product Warranty Accounting

### Assurance-Type Warranties

**Accrue at time of sale based on:**
- Historical warranty claim experience
- Expected future claims
- Cost to repair/replace

### Initial Accrual

```
Dr. Warranty Expense                  $50,000
    Cr. Warranty Liability                    $50,000
(Estimated warranty costs at time of sale)
```

### Warranty Claim Settlement

```
Dr. Warranty Liability                 $5,000
    Cr. Inventory (parts)                      $3,000
    Cr. Accrued Payroll (labor)                $2,000
```

### Extended Warranties (Service-Type)

**Recognize revenue over warranty period:**

**At Sale:**
```
Dr. Cash                              $1,200
    Cr. Deferred Revenue—Extended Warranty    $1,200
```

**Monthly Recognition (24-month warranty):**
```
Dr. Deferred Revenue                     $50
    Cr. Extended Warranty Revenue              $50
```

---

## Indemnification Provisions

### Common Indemnifications

| Transaction | Typical Indemnifications |
|-------------|-------------------------|
| **Business combinations** | Tax, environmental, litigation, employee |
| **Sale agreements** | Breach of reps and warranties |
| **Licensing** | IP infringement |
| **Service contracts** | Performance, negligence |

### Recognition

**If fair value determinable:**
```
Dr. Indemnification Asset/Expense     $25,000
    Cr. Indemnification Obligation            $25,000
```

**If maximum exposure determinable but no fair value:**
- Disclose only (no recognition)

**If no maximum exposure determinable:**
- Disclose that fact

---

## Subsequent Measurement

### Release of Guarantee Liability

**If guarantee expires without payment:**
```
Dr. Guarantee Obligation              $10,000
    Cr. Other Income                          $10,000
(Guarantee liability released)
```

**If payment required under guarantee:**
```
Dr. Guarantee Obligation              $10,000
Dr. Loss on Guarantee                 $15,000
    Cr. Cash                                  $25,000
(Payment exceeds recorded liability)
```

### Warranty Liability Updates

At each reporting period:
1. Evaluate actual claims experience
2. Update estimate of future claims
3. Adjust liability accordingly

```
Dr. Warranty Expense                  $8,000
    Cr. Warranty Liability                    $8,000
(Increase in estimate)
```

---

## Practical Examples

### Example 1: Product Warranty Accrual

**Facts:**
- 100,000 units sold during year at $50 each
- 2-year warranty on all units
- Historical claim rate: 3%
- Average cost per claim: $15

**Calculation:**
```
Estimated claims: 100,000 × 3% = 3,000 units
Estimated cost: 3,000 × $15 = $45,000
```

**Journal Entry:**
```
Dr. Warranty Expense                  $45,000
    Cr. Warranty Liability                    $45,000
```

---

### Example 2: Parent Guarantee of Subsidiary Debt

**Facts:**
- Parent guarantees $5,000,000 bank loan to subsidiary
- Fair value of guarantee: $75,000

**Parent's Entry:**
```
Dr. Investment in Subsidiary          $75,000
    Cr. Guarantee Obligation                  $75,000
```

**Subsidiary's Entry:**
- No entry for the guarantee itself
- Record loan proceeds as normal

---

### Example 3: Indemnification in Acquisition

**Facts:**
- Acquired company for $10,000,000
- Seller indemnifies buyer for unknown tax liabilities up to $500,000
- Fair value of indemnification: $50,000

**Buyer's Entry:**
```
(As part of purchase price allocation)
Dr. Indemnification Asset              $50,000
    Cr. Bargain Purchase Gain/Goodwill        $50,000
(Reduces goodwill or increases bargain purchase gain)
```

---

### Example 4: Warranty Liability Rollforward

```
WARRANTY LIABILITY ROLLFORWARD
For the Year Ended December 31, 20X1

Balance, January 1, 20X1              $   120,000
Warranties issued                          85,000
Settlements and claims                    (78,000)
Changes in estimates                       (5,000)
                                      -----------
Balance, December 31, 20X1            $   122,000

Current portion                       $    75,000
Noncurrent portion                         47,000
```

---

## Disclosure Requirements

### General Disclosure Requirements

**For all guarantees, disclose:**

| Element | Disclosure |
|---------|------------|
| **Nature** | Purpose and terms of guarantee |
| **Maximum exposure** | Maximum potential amount of payments |
| **Current carrying amount** | Liability recorded |
| **Recourse provisions** | Rights against third parties |
| **Collateral** | Assets securing guarantee |

### Even When Remote

Unlike contingencies, guarantees must be disclosed **even when likelihood of payment is remote**.

---

### Product Warranty Disclosures

| Element | Disclosure |
|---------|------------|
| **Accounting policy** | How warranty costs are estimated |
| **Liability rollforward** | Beginning, additions, settlements, ending |
| **Nature of warranties** | Terms and coverage |

---

### Example Disclosure—Guarantees

```
NOTE X: GUARANTEES

Product Warranties
The Company provides a standard two-year warranty on all products
sold. A liability is recorded at the time of sale based on
historical claim experience, which has averaged approximately 3%
of sales. Warranty costs include parts and labor to repair
defective products.

Warranty liability activity was as follows:
                                      20X1         20X0
Beginning balance                  $120,000     $110,000
Provision for warranties             85,000       75,000
Warranty claims                     (78,000)     (65,000)
Changes in estimates                 (5,000)          -
                                   --------     --------
Ending balance                     $122,000     $120,000

Debt Guarantees
The Company has guaranteed $2,000,000 of bank indebtedness of its
50%-owned joint venture. The guarantee expires in December 20X4.
The Company's maximum potential liability is $2,000,000. No amount
has been recorded as management believes the joint venture will
meet its debt obligations. The Company has no recourse provisions
or collateral with respect to this guarantee.

Indemnifications
In connection with the sale of its Widget Division in 20X1, the
Company agreed to indemnify the buyer for certain tax matters
arising prior to the sale date, up to a maximum of $500,000. The
Company has recorded a liability of $50,000 for this
indemnification based on expected exposures.
```

---

## Private Company Considerations

### Common Guarantees

| Type | Private Company Context |
|------|------------------------|
| **Owner guarantees** | Personal guarantees on company debt |
| **Related party** | Guarantees between affiliates |
| **Lease guarantees** | Residual value, rent |
| **Product warranties** | Standard and extended |

### Documentation

For guarantees:
- Keep copies of all guarantee agreements
- Document fair value determinations
- Track guarantee expirations
- Monitor for triggering events

---

## Common Audit Issues

### Identification

| Issue | Audit Procedure |
|-------|-----------------|
| **Completeness** | Review contracts, legal confirmations |
| **Related party** | Inquire about intercompany guarantees |
| **Off-balance sheet** | Search for SLOCs, surety bonds |

### Measurement

| Issue | Consideration |
|-------|---------------|
| **Fair value** | Methodology appropriateness |
| **Warranty estimates** | Historical accuracy |
| **Changes in estimates** | Proper treatment |

### Disclosure

| Issue | Focus |
|-------|-------|
| **Maximum exposure** | All guarantees disclosed |
| **Remote likelihood** | Still require disclosure |
| **Warranty rollforward** | Completeness and accuracy |

---

## Recent Updates

| ASU | Topic | Impact |
|-----|-------|--------|
| **ASU 2023-01** | Leases—Common Control | Lessee guarantee guidance |
| **ASU 2016-02** | Leases | Residual value guarantees |
| **ASU 2014-09** | Revenue | Service-type warranty treatment |

---

## External Resources

- [FASB ASC 460](https://asc.fasb.org/)
- [FASB ASC 450 (Contingencies)](https://asc.fasb.org/)
- [FASB ASC 606 (Warranties)](https://asc.fasb.org/)
- [AICPA Audit Guide—Warranties and Guarantees](https://www.aicpa.org/)
- [KPMG: Handbook—Guarantees](https://frv.kpmg.us/)
- [PwC: Financial Instruments Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Guarantees](https://www.iasplus.com/en-us)

---

## Navigation

← [Back to Liabilities (400s)](README.md) | [Back to Main Guide](../../README.md)
