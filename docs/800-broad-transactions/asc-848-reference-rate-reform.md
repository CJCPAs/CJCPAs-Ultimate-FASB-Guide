# ASC 848: Reference Rate Reform

> Accounting relief and guidance for transitioning from LIBOR to alternative reference rates.

## Overview

ASC 848 provides temporary optional guidance to ease the accounting burden of transitioning from interbank offered rates (IBORs), primarily LIBOR, to alternative reference rates such as SOFR. The guidance provides optional expedients and exceptions for applying existing GAAP to contracts, hedging relationships, and other transactions affected by reference rate reform.

> **Core Principle:** Provide optional relief from certain accounting requirements to reduce complexity and cost of accounting for contract modifications and hedging relationships affected by reference rate reform.

---

## Background: LIBOR Transition

### What Happened

- **LIBOR** (London Interbank Offered Rate) was the most widely used benchmark rate globally
- Regulatory concerns about LIBOR's reliability led to its discontinuation
- Most LIBOR settings ceased after June 30, 2023
- Trillions of dollars in contracts needed to be modified

### Alternative Reference Rates

| Region | Old Rate | New Rate |
|--------|----------|----------|
| United States | USD LIBOR | SOFR (Secured Overnight Financing Rate) |
| United Kingdom | GBP LIBOR | SONIA (Sterling Overnight Index Average) |
| European Union | EURIBOR | €STR (Euro Short-Term Rate) |
| Japan | JPY LIBOR | TONA (Tokyo Overnight Average Rate) |
| Switzerland | CHF LIBOR | SARON (Swiss Average Rate Overnight) |

---

## Scope and Applicability

### Contracts in Scope

- Debt instruments
- Leases
- Derivatives
- Revenue contracts
- Other contracts referencing discontinued rates

### Effective Period

| Period | Status |
|--------|--------|
| **Original:** March 12, 2020 – December 31, 2022 | Expired |
| **Extended (ASU 2022-06):** Through December 31, 2024 | Active |

### Key Limitation

Relief is **optional** and only applies to modifications directly related to reference rate reform—not general contract modifications.

---

## Contract Modification Relief

### General Principle

**Without ASC 848:** Contract modifications often require:
- Extinguishment/reissuance analysis
- Gain/loss recognition
- Derecognition of existing instruments

**With ASC 848:** Modifications related solely to reference rate reform can be accounted for as a **continuation** of the existing contract.

### Debt Instruments (ASC 470)

**Optional Expedient:**
- Modification to replace reference rate is NOT treated as extinguishment
- Continue accounting for modified debt as same instrument
- No gain/loss recognition

**Qualifying Modifications:**
- Replace reference rate with another rate
- Add or change fallback provisions
- Change timing/frequency of interest payments
- Adjust spread to maintain economic equivalence

**Example:**

Before: $10M loan at LIBOR + 2%
After: $10M loan at SOFR + 2.26%

```
No journal entry required for modification
(continue existing accounting)
```

### Lease Modifications (ASC 842)

**Optional Expedient:**
- Modification solely for reference rate change is NOT a lease modification under ASC 842
- Lessee continues existing lease classification
- No remeasurement of lease liability required

### Revenue Contracts (ASC 606)

**Optional Expedient:**
- Variable consideration changes due to reference rate reform treated as continuation
- No contract modification accounting required

---

## Hedging Relationship Relief

### Challenges Without Relief

Reference rate changes could cause:
- Hedge ineffectiveness
- Hedge discontinuation
- Inability to designate new hedges

### Optional Expedients Available

| Expedient | Description |
|-----------|-------------|
| **Probability assertion** | Assume hedged forecasted transactions remain probable |
| **Effectiveness assessment** | Assume hedge remains highly effective |
| **Cash flow hedge** | Amounts in AOCI remain despite reference rate change |
| **Fair value hedge** | Continue hedge basis adjustments |
| **Designation changes** | Allow certain changes without discontinuation |

### Hedging Documentation

**Can update documentation for:**
- New reference rate
- Spread adjustments
- Timing changes
- Method of assessing effectiveness

**Without:** Discontinuing the hedge relationship

---

## Practical Examples

### Example 1: Variable-Rate Debt Modification

**Before Modification:**
- $50M term loan
- Rate: 3-month LIBOR + 1.50%
- Maturity: December 2025

**Modification:**
- Rate changed to: SOFR + 1.65% (spread adjustment for economic equivalence)
- All other terms unchanged

**Accounting with ASC 848 Relief:**
```
No journal entry required
Continue amortizing existing debt issuance costs
No new effective interest rate calculation needed
```

### Example 2: Interest Rate Swap

**Original Hedge:**
- Pay fixed 3%, receive LIBOR
- Hedging variable-rate debt at LIBOR + 1%
- Designated as cash flow hedge

**After Rate Reform:**
- Swap modified to receive SOFR
- Debt modified to SOFR + 1.15%

**Accounting with ASC 848 Relief:**
- No hedge discontinuation
- Update hedge documentation
- Continue hedge accounting
- Amounts in AOCI remain

### Example 3: Cross-Currency Swap

**Scenario:** USD/EUR cross-currency swap references USD LIBOR.

**Modification:** Replace USD LIBOR with SOFR.

**With ASC 848:**
- Update hedge documentation
- Continue hedge accounting
- No ineffectiveness recognition for rate change

---

## Specific Expedients by Topic

### ASC 310: Receivables

- Loan modifications for reference rate change → Not TDR
- Not a new loan for CECL purposes

### ASC 815: Derivatives and Hedging

| Expedient | Benefit |
|-----------|---------|
| Change designated rate | Without dedesignation |
| Change hedged risk | In limited circumstances |
| Shortcut method | Continue if only rate changes |
| Critical terms match | Continue if only rate changes |

### ASC 842: Leases

- Variable payment changes not lease modification
- No remeasurement required
- Lessors continue existing accounting

### ASC 470: Debt

- Modification not extinguishment
- No gain/loss recognition
- Debt discounts/premiums continue

---

## Spread Adjustments

### Purpose

Alternative rates (like SOFR) are typically lower than LIBOR. Spread adjustments maintain economic equivalence.

### ISDA Spread Adjustments

| Tenor | Approximate Spread (LIBOR vs. SOFR) |
|-------|-------------------------------------|
| Overnight | 0.00644% |
| 1-month | 0.11448% |
| 3-month | 0.26161% |
| 6-month | 0.42826% |
| 12-month | 0.71513% |

### Accounting Treatment

Spread adjustments are treated as part of the modified reference rate—no separate accounting required under ASC 848.

---

## Disclosure Requirements

### Required Disclosures

1. **Nature and extent** of contracts affected by reference rate reform
2. **Expedients elected** and exceptions applied
3. **How expedients affect** financial statements

### Example Disclosure

> **Reference Rate Reform:** The Company has contract modifications that are accounted for under the optional expedients in ASC 848. These modifications relate to the Company's variable-rate debt and interest rate swap agreements that previously referenced LIBOR and have been amended to reference SOFR. The Company elected to account for these modifications as continuations of the existing contracts rather than as extinguishments or new instruments. As of December 31, 20XX, the Company has modified $X million in debt agreements and $X million notional in derivative contracts.

---

## Interaction with Other Standards

### ASC 815: Derivatives

- Reference rate changes in derivatives
- Hedge accounting preservation
- Effectiveness testing relief

### ASC 470: Debt

- Modification vs. extinguishment analysis
- Debt issuance costs treatment
- Effective interest rate implications

### ASC 842: Leases

- Variable lease payments
- Lease classification
- Remeasurement triggers

### ASC 326: Credit Losses

- Loan modification accounting
- Vintage disclosure impacts
- PCD asset considerations

---

## Timeline and Sunset

### Key Dates

| Date | Event |
|------|-------|
| March 2020 | ASC 848 issued |
| June 30, 2023 | Most LIBOR settings ceased |
| December 31, 2024 | ASC 848 expedients sunset |

### After Sunset

- Modifications after December 31, 2024 follow normal GAAP
- Existing elections remain in place
- No retroactive application concerns

---

## Private Company Considerations

### Common Exposures

- Variable-rate bank loans
- Interest rate swaps
- Equipment financing
- Real estate loans

### Practical Steps

1. **Identify** all LIBOR-based contracts
2. **Assess** modification terms
3. **Elect** expedients as appropriate
4. **Document** elections made
5. **Update** accounting policies

---

## Common Audit Issues

1. **Documentation** — Insufficient support for expedient elections
2. **Scope** — Applying expedients to non-qualifying modifications
3. **Timing** — Elections made after sunset date
4. **Disclosure** — Incomplete or missing disclosures
5. **Hedging** — Not updating hedge documentation
6. **Consistency** — Inconsistent application across similar contracts

---

## Checklist for Implementation

### Contract Review
- [ ] Identify all LIBOR-referenced contracts
- [ ] Determine if modification qualifies for relief
- [ ] Document expedient election
- [ ] Update contract terms

### Hedging Relationships
- [ ] Review affected hedges
- [ ] Update hedge documentation
- [ ] Elect applicable expedients
- [ ] Continue effectiveness testing (if required)

### Financial Reporting
- [ ] Prepare disclosures
- [ ] Update accounting policies
- [ ] Train accounting staff
- [ ] Coordinate with auditors

---

## External Resources

- [FASB ASC 848](https://asc.fasb.org/)
- [FASB Reference Rate Reform Resource Center](https://www.fasb.org/)
- [Alternative Reference Rates Committee (ARRC)](https://www.newyorkfed.org/arrc)
- [ISDA IBOR Fallbacks](https://www.isda.org/)
- [KPMG: Handbook—Reference Rate Reform](https://frv.kpmg.us/)
- [PwC: LIBOR Transition Guide](https://viewpoint.pwc.com/)

---

## Navigation

← [Back to Broad Transactions (800s)](README.md) | [Main Guide](../../README.md)
