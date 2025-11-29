# ASC 835: Interest

> Imputation of interest, capitalization of interest, and interest income recognition.

## Overview

ASC 835 provides guidance on three key aspects of interest accounting:
1. **Imputation of interest** on notes receivable/payable without stated interest or below-market rates
2. **Capitalization of interest** on assets constructed for own use
3. **Interest income and expense** recognition

> **Core Principle:** Economic substance should prevail over form—transactions should reflect a realistic interest component even when not explicitly stated.

---

## ASC 835-20: Capitalization of Interest

### Scope

Capitalize interest on assets:
- Constructed or produced for an entity's **own use**
- Constructed or produced for **sale or lease** as discrete projects
- **Equity method investments** when investee is using funds for qualifying assets

### Qualifying Assets

| Qualifies | Does NOT Qualify |
|-----------|------------------|
| Assets under construction | Inventories routinely manufactured |
| Self-constructed assets | Assets ready for use |
| Assets produced as discrete projects | Assets not in use and not undergoing preparation |
| Real estate development | Financial instruments |
| Equipment being installed | Investments (unless equity method exception) |

### Capitalization Period

**Begin when ALL conditions met:**
1. Expenditures have been made
2. Activities to prepare asset are in progress
3. Interest cost is being incurred

**End when:**
- Asset is substantially complete and ready for intended use
- Or activities are suspended (not including brief, normal delays)

---

## Interest Capitalization Calculation

### Steps

1. **Determine average accumulated expenditures (AAE)**
2. **Apply interest rates**
3. **Limit to actual interest incurred**

### Average Accumulated Expenditures

Weight expenditures by time outstanding during period:

| Month | Expenditure | Months Outstanding | Weighted Amount |
|-------|-------------|-------------------|-----------------|
| January | $1,000,000 | 12/12 | $1,000,000 |
| April | $500,000 | 9/12 | $375,000 |
| July | $300,000 | 6/12 | $150,000 |
| October | $200,000 | 3/12 | $50,000 |
| **Total** | **$2,000,000** | | **$1,575,000** |

### Interest Rate Selection

| Borrowing Type | Rate to Use |
|----------------|-------------|
| **Specific borrowings** | Rate on that debt |
| **General borrowings** | Weighted average rate |

**Apply specific borrowing rate first, then weighted average for excess AAE**

### Calculation Example

**Facts:**
- AAE: $1,575,000
- Specific construction loan: $1,000,000 at 6%
- General borrowings: $5,000,000 at 5%
- Actual interest incurred: $310,000

**Calculation:**

| | Amount | Rate | Capitalizable Interest |
|--|--------|------|----------------------|
| Specific borrowing | $1,000,000 | 6% | $60,000 |
| General borrowing | $575,000 | 5% | $28,750 |
| **Total** | **$1,575,000** | | **$88,750** |

**Compare to actual interest:** $310,000
**Capitalize:** $88,750 (lower of calculated or actual)

### Journal Entry

```
Dr. Construction in Progress             $88,750
    Cr. Interest Expense                        $88,750
```

---

## ASC 835-30: Imputation of Interest

### When to Impute

Impute interest on notes receivable/payable when:
- No stated interest rate, OR
- Stated rate is unreasonably low, OR
- Face amount materially different from fair value

### Exceptions

Do NOT impute interest for:
- Normal trade receivables/payables (≤1 year)
- Security deposits
- Usual lending activities of financial institutions
- Transactions where interest rates are prescribed

### Determining Interest Rate

**Use in order of preference:**

1. **Established exchange price** of goods/services
2. **Market rate** for similar instruments
3. **Imputed rate** that discounts to FV of goods/services

### Example—Zero-Interest Note

**Scenario:** Company sells equipment worth $80,000 for a $100,000 note due in 3 years, no stated interest.

**Analysis:**
- FV of equipment: $80,000
- Note face: $100,000
- Discount: $20,000
- Calculate implicit rate

**Implicit Rate:** Rate where PV of $100,000 in 3 years = $80,000
Rate ≈ 7.72%

**Journal Entry at Sale:**
```
Dr. Notes Receivable                    $100,000
    Cr. Discount on Notes Receivable            $20,000
    Cr. Revenue                                 $80,000
```

**Interest Recognition (Year 1):**
Interest = $80,000 × 7.72% = $6,176
```
Dr. Discount on Notes Receivable         $6,176
    Cr. Interest Income                         $6,176
```

---

## Interest Income and Expense Recognition

### General Principles

| Topic | Treatment |
|-------|-----------|
| Interest expense | Accrue based on effective interest method |
| Interest income | Recognize as earned |
| Discounts/premiums | Amortize over instrument life |

### Effective Interest Method

**Formula:**
```
Interest = Carrying Amount × Effective Rate × Time
```

**Amortization Schedule Example:**

Note: $100,000 face, $95,000 proceeds, 5% stated rate, 6% effective rate, 5 years

| Year | Beginning Balance | Interest (6%) | Cash (5%) | Amortization | Ending Balance |
|------|------------------|---------------|-----------|--------------|----------------|
| 1 | $95,000 | $5,700 | $5,000 | $700 | $95,700 |
| 2 | $95,700 | $5,742 | $5,000 | $742 | $96,442 |
| 3 | $96,442 | $5,787 | $5,000 | $787 | $97,229 |
| 4 | $97,229 | $5,834 | $5,000 | $834 | $98,063 |
| 5 | $98,063 | $5,937* | $5,000 | $937 | $100,000 |

*Rounded to reach face value

---

## Presentation and Disclosure

### Balance Sheet

| Item | Presentation |
|------|--------------|
| Discount on notes receivable | Contra-asset (deducted from notes) |
| Discount on notes payable | Contra-liability (deducted from notes) |
| Capitalized interest | Part of asset cost |

### Income Statement

| Item | Classification |
|------|----------------|
| Interest expense (net of capitalized) | Other expense |
| Interest income | Other income |

### Disclosures

**Capitalized Interest:**
- Amount capitalized during period
- Total interest cost incurred (before capitalization)

**Imputed Interest:**
- Face amount of notes
- Effective interest rate
- Discount/premium amortization method

### Example Disclosure

> **Capitalized Interest:** The Company capitalizes interest on qualifying construction projects. During the year ended December 31, 20XX, total interest incurred was $X million, of which $X million was capitalized.

---

## Special Situations

### Land Expenditures

- Land under development: Interest capitalizable
- Land held for future use: Interest NOT capitalizable
- Land being prepared for sale: Interest capitalizable

### Suspended Projects

If activities on qualifying asset are suspended:
- Stop capitalizing interest during suspension
- Brief, normal interruptions do NOT stop capitalization

### Equity Method Investments

Capitalize interest on additional investment when:
- Investee has activities in progress for qualifying assets
- Investee is capitalizing interest

---

## Private Company Considerations

### Practical Approaches

- Same guidance applies
- May have simpler capital structures
- Interest capitalization still required for qualifying assets

### Common Issues

1. Forgetting to capitalize interest
2. Not tracking AAE properly
3. Using incorrect interest rates
4. Not stopping capitalization when asset is ready

---

## Common Audit Issues

1. **Qualifying asset determination** — Capitalizing on non-qualifying assets
2. **Average accumulated expenditures** — Calculation errors
3. **Rate selection** — Using incorrect rates
4. **Capitalization period** — Starting too early or ending too late
5. **Imputation** — Not recognizing below-market terms
6. **Disclosure** — Incomplete interest cost disclosure
7. **Suspended activities** — Continuing to capitalize during suspension

---

## Comparison: US GAAP vs. IFRS

| Topic | US GAAP (ASC 835) | IFRS (IAS 23) |
|-------|-------------------|---------------|
| Capitalization | Required for qualifying assets | Required for qualifying assets |
| Definition | Broader scope | Slightly different criteria |
| General borrowings | Weighted average rate | Similar approach |
| Disclosure | Total interest incurred | Capitalized amount, rate used |

---

## Recent Developments

- No significant recent updates to ASC 835
- Continues to operate as foundational guidance
- Interactions with ASC 842 (leases) for finance leases

---

## External Resources

- [FASB ASC 835](https://asc.fasb.org/)
- [AICPA Practice Aid: Interest Capitalization](https://www.aicpa.org/)
- [SEC Staff Accounting Bulletin: Interest Capitalization](https://www.sec.gov/)
- [KPMG: Handbook—Interest](https://frv.kpmg.us/)

---

## Navigation

← [Back to Broad Transactions (800s)](README.md) | [Main Guide](../../README.md)
