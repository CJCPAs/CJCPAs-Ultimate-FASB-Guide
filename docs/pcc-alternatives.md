# Private Company Council (PCC) Alternatives Guide

[← Back to Main Guide](../README.md)

> **Note:** This guide is for informational purposes only. Always verify current requirements with the [FASB Codification](https://asc.fasb.org/) and consult with qualified professionals for your specific situation.

---

The **Private Company Council (PCC)** was established by FASB in 2012 to improve the standard-setting process for private companies. The PCC has issued alternatives that provide **cost-effective relief** while maintaining decision-useful financial information.

---

## Who Qualifies as a "Private Company"?

A private company is an entity that:
- Is **not** a public business entity
- Is **not** a not-for-profit entity
- Is **not** an employee benefit plan within the scope of ASC 960-965

> **Note:** Some alternatives are available to all entities "other than public business entities," which includes not-for-profit entities. Check each alternative's scope carefully.

---

## Master List of PCC Alternatives

| ASU | Topic | ASC Reference | Benefit Summary |
|-----|-------|---------------|-----------------|
| 2014-02 | Goodwill Amortization | ASC 350-20 | Amortize goodwill over 10 years or less |
| 2014-03 | Simplified Hedge Accounting | ASC 815-20 | Simplified effectiveness testing |
| 2014-07 | Common Control Leases | ASC 842-10 | Use written terms for related-party leases |
| 2014-18 | VIE Exemption | ASC 810-10 | Exemption from VIE consolidation |
| 2016-03 | Interest Rate Swaps | ASC 815-20 | Simplified swap accounting |
| 2018-17 | Related Party Arrangements | ASC 810-10 | Indirect interests in VIEs |
| 2019-08 | Stock Compensation | ASC 718-10 | Practical expedients for modifications |
| 2021-03 | Goodwill Triggering Events | ASC 350-20 | Annual impairment timing relief |
| 2021-07 | Acquired Contract Assets/Liabilities | ASC 805-20 | Practical expedient for customer contracts |
| 2023-01 | Common Control Lease Improvements | ASC 842-10 | Leasehold improvements guidance |

---

## ASC 350 — Goodwill Alternatives

### Alternative 1: Goodwill Amortization (ASU 2014-02)

**The Single Most Popular PCC Alternative**

| Aspect | Public Company GAAP | Private Company Alternative |
|--------|--------------------|-----------------------------|
| **Amortization** | No amortization | Straight-line over 10 years or less (or shorter useful life) |
| **Impairment Testing** | Annual quantitative or qualitative test | Only when triggering event occurs |
| **Impairment Level** | Reporting unit level | Entity level or reporting unit (election) |

#### Triggering Events Requiring Impairment Testing

- Adverse change in business climate
- Adverse legal/regulatory action
- Unanticipated competition
- Loss of key personnel
- Expectation of selling/disposing of entity or portion
- Recognized goodwill impairment in subsidiary's financials
- Testing long-lived assets for recoverability in asset group containing goodwill

#### Practical Example — Goodwill Amortization

```
Acquisition Facts:
- Purchase price: $5,000,000
- Fair value of net identifiable assets: $3,500,000
- Goodwill recognized: $1,500,000
- Useful life elected: 10 years

Annual Journal Entry:
Dr. Amortization Expense — Goodwill     $150,000
    Cr. Accumulated Amortization — Goodwill    $150,000

Income Statement Impact:
- Reduces net income by $150,000/year for 10 years
- Tax benefit (if book/tax conformity): $150,000 x tax rate
```

#### Election Requirements

- Must be elected for **all** goodwill
- Applied prospectively upon election
- Once adopted, cannot be reversed
- Applies to all existing and future goodwill

---

### Alternative 2: Triggering Event Evaluation Timing (ASU 2021-03)

| Aspect | Standard GAAP | Private Company Alternative |
|--------|--------------|----------------------------|
| **When to Evaluate** | As of date triggering event occurs | As of annual reporting date |
| **Frequency** | Continuously throughout year | Once per year at year-end |

**Benefit:** No need to evaluate triggering events in interim periods. Evaluation performed only at annual reporting date.

#### Example Scenario

- Company has December 31 year-end
- Major customer lost in June
- Under standard GAAP: Evaluate impairment in June
- Under alternative: Evaluate at December 31 whether June event still indicates impairment

---

## ASC 815 — Hedge Accounting Alternatives

### Alternative 1: Simplified Hedge Accounting (ASU 2014-03)

**Dramatically Simplifies Interest Rate Hedging**

| Aspect | Public Company GAAP | Private Company Alternative |
|--------|--------------------|-----------------------------|
| **Effectiveness Testing** | Quantitative analysis required | Simplified approach available |
| **Documentation** | Extensive contemporaneous documentation | Simplified documentation |
| **Benchmark Rate** | Must be benchmark rate | Receive-variable leg matches debt |
| **Shortcut Method** | Strict criteria | More accessible |

#### Qualifying Criteria for Simplified Approach

1. Both swap and debt are with same counterparty (or consolidated affiliates)
2. Swap term matches debt term (timing of payments matches)
3. Fair value of swap is zero at inception (or near zero)
4. Notional amount matches principal of debt
5. Variable rate on swap matches debt rate

#### Practical Example — Simplified Hedge

```
Facts:
- Private company borrows $10,000,000 variable rate loan (SOFR + 2%)
- Enters interest rate swap with same bank:
  - Receives: SOFR
  - Pays: 5% fixed
  - Notional: $10,000,000
  - Term: Matches loan term

Under Simplified Approach:
- Swap qualifies as perfect hedge
- No quantitative effectiveness testing required
- Swap recorded at fair value on balance sheet
- Changes in fair value recorded in OCI
- Effective interest rate = 7% fixed (5% swap rate + 2% spread)

Journal Entry at Period End (swap in liability position):
Dr. Other Comprehensive Income     $XXX,XXX
    Cr. Interest Rate Swap Liability       $XXX,XXX
```

---

### Alternative 2: Practical Expedient for Interest Rate Swaps (ASU 2016-03)

Allows private companies to assume **no ineffectiveness** when:
- Swap designated as cash flow hedge of variable-rate debt
- All criteria of simplified approach are met
- Company documents at inception that expedient is being applied

---

## ASC 810 — Consolidation Alternatives

### Alternative 1: VIE Exemption for Common Control (ASU 2014-18)

**Exempts Private Companies from Complex VIE Analysis**

| Aspect | Public Company GAAP | Private Company Alternative |
|--------|--------------------|-----------------------------|
| **VIE Analysis** | Required for all arrangements | Exemption for common control lessor entities |
| **Scope** | All potential VIEs | Can exclude qualifying arrangements |

#### Qualifying Criteria for Exemption

1. Lessor entity and private company are under **common control**
2. Private company has a **lease arrangement** with the lessor entity
3. Substantially all activities of the lessor entity are **related to leasing** activities
4. Private company **explicitly guarantees** or provides **collateral** for lessor's debt

#### Common Scenario

```
Structure:
                    ┌─────────────────┐
                    │   Shareholder   │
                    │   (Owner/CEO)   │
                    └────────┬────────┘
                             │ 100% owns both
              ┌──────────────┴──────────────┐
              ▼                              ▼
    ┌─────────────────┐           ┌─────────────────┐
    │  Operating Co   │◄──lease───│  Real Estate    │
    │  (Private Co)   │           │  Holding Co     │
    │                 │──guarantee│  (Lessor LLC)   │
    └─────────────────┘           └─────────────────┘

Under standard GAAP: Real Estate Holding Co is likely a VIE that Operating
Co must consolidate due to the guarantee.

Under PCC Alternative: Operating Co can ELECT to not apply VIE guidance
to the Real Estate Holding Co arrangement.
```

#### Required Disclosures (if exemption elected)

- Nature and risks of involvement with the lessor entity
- Amount of explicit guarantee or collateral provided
- Carrying amount and classification of assets pledged as collateral

---

### Alternative 2: Indirect Interests in VIEs (ASU 2018-17)

Clarifies that indirect interests held through related parties under common control should be considered **proportionately** rather than as if held directly.

---

## ASC 842 — Lease Alternatives

### Alternative 1: Common Control Leases (ASU 2014-07)

**Simplifies Related Party Lease Accounting**

| Aspect | Standard GAAP | Private Company Alternative |
|--------|--------------|----------------------------|
| **Lease Terms** | Enforceable terms (legal analysis) | Written terms and conditions |
| **Lease Classification** | Based on enforceable terms | Based on written agreement |
| **Accounting** | May require consolidation analysis | Use written terms regardless |

#### Qualifying Criteria

1. Lease between entities under common control
2. Written terms and conditions exist
3. No variable payments based on lessee operations

#### Practical Example

```
Scenario:
- Parent owns 100% of OpCo and PropCo
- PropCo leases building to OpCo
- Written lease: 10-year term, $10,000/month, no renewal options
- Verbal understanding: OpCo can use building "as long as needed"

Under Standard GAAP:
Must analyze enforceable rights. Verbal understanding might
create longer enforceable term requiring different classification.

Under PCC Alternative:
Use written 10-year term for classification and measurement.
No need to analyze verbal or implicit arrangements.

Classification Test (using written terms):
- Lease term: 10 years
- Remaining useful life: 30 years
- 10/30 = 33% < 75% threshold
- Result: Operating lease (if other criteria not met)
```

---

### Alternative 2: Leasehold Improvements (ASU 2023-01)

**Addresses Leasehold Improvements in Common Control Leases**

| Issue | Standard Approach | Private Company Alternative |
|-------|-------------------|----------------------------|
| **Amortization Period** | Shorter of useful life or lease term | Useful life of improvements (regardless of lease term) |
| **Transfer to Lessor** | Complex derecognition analysis | Simplified transfer accounting |

**Key Benefit:** Leasehold improvements can be amortized over their useful life even if the written lease term is shorter, when:
- Lessee controls the use of the underlying asset through a lease
- Both entities are under common control
- Lessee reasonably expects to continue controlling use

---

## ASC 805 — Business Combination Alternatives

### Alternative: Customer-Related Intangible Assets (ASU 2021-07)

**Reduces Complexity in Purchase Price Allocation**

| Aspect | Standard GAAP | Private Company Alternative |
|--------|--------------|----------------------------|
| **Customer Contracts** | Separately recognize customer-related intangibles | Can subsume into goodwill |
| **Customer Relationships** | Fair value measurement required | No separate recognition required |
| **Noncompete Agreements** | Separately measure | Can include in goodwill |

#### Qualifying Criteria

- Private company acquiror
- Customer-related intangible assets that are not:
  - Capable of being sold or licensed independently
  - Arising from contractual-legal rights

#### Practical Example

```
Acquisition Facts:
- Purchase price: $8,000,000
- Fair value of tangible assets: $2,000,000
- Fair value of assumed liabilities: $500,000

Under Standard GAAP:
Net tangible assets                           $1,500,000
Customer relationships (fair value)             $800,000
Customer contracts (fair value)                 $400,000
Trade name (fair value)                         $300,000
Goodwill (plug)                               $5,000,000
                                              ----------
Total                                         $8,000,000

Under PCC Alternative:
Net tangible assets                           $1,500,000
Trade name (separately identifiable)            $300,000
Goodwill (includes customer intangibles)      $6,200,000
                                              ----------
Total                                         $8,000,000

Benefits:
- No costly valuation of customer relationships
- No separate amortization tracking
- Customer intangibles amortized as part of goodwill (if that
  alternative is also elected)
```

---

## ASC 718 — Stock Compensation Alternatives

### Alternative: Practical Expedient for Modifications (ASU 2019-08)

**Simplifies Share-Based Payment Modifications**

| Aspect | Standard GAAP | Private Company Alternative |
|--------|--------------|----------------------------|
| **Current Price Input** | Fair value at modification date | Determine if modification is "probable" |
| **Expected Term** | Reassess at modification | Practical expedient available |

#### Practical Expedients Available

1. **Expected Term:** Use midpoint between vest date and contractual term
2. **Volatility:** Use historical volatility of appropriate industry index
3. **Forfeitures:** Elect to account for when they occur (vs. estimate)

#### Key Modification Relief

When private company awards are modified:
- If modification doesn't change fair value, no incremental cost
- Simplified calculation methods available
- Reduced documentation burden

---

## Decision Matrix: Which Alternatives Should You Elect?

| Alternative | Typical Annual Savings | Complexity Reduction | Recommendation |
|-------------|----------------------|---------------------|----------------|
| **Goodwill Amortization** | Eliminates annual impairment testing costs | High | **Highly Recommended** for companies with acquisitions |
| **Goodwill Triggering Events** | Eliminates interim evaluations | High | **Recommended** if amortization alternative elected |
| **Simplified Hedge Accounting** | $10,000-50,000+ valuation fees | High | **Highly Recommended** if using interest rate swaps |
| **VIE Exemption** | Eliminates consolidation analysis | High | **Recommended** for common control real estate structures |
| **Common Control Leases** | Simplifies lease accounting | Medium | **Recommended** for related party leases |
| **Customer Intangibles** | $15,000-100,000+ valuation fees | High | **Recommended** for acquisitions |

---

## Implementation Checklist

### Before Electing Any PCC Alternative

- [ ] **Confirm Eligibility** — Verify entity is not a public business entity
- [ ] **Review Debt Covenants** — Check if lender requires public company GAAP
- [ ] **Consider Stakeholders** — Will investors/banks accept alternative GAAP?
- [ ] **Evaluate Future Plans** — IPO or sale to public company may require restatement
- [ ] **Document Election** — Maintain formal documentation of all elections
- [ ] **Update Accounting Policies** — Revise significant accounting policies footnote
- [ ] **Disclose Elections** — Include required disclosures in financial statements

---

## Sample Disclosure Language

```
Accounting Policies — Private Company Elections

The Company has elected the following Private Company Council (PCC)
alternatives available under U.S. generally accepted accounting
principles:

Goodwill: The Company has elected to amortize goodwill on a straight-line
basis over ten years. The Company evaluates goodwill for impairment only
when a triggering event occurs, as permitted by ASU 2014-02 and ASU 2021-03.

Interest Rate Swaps: The Company applies the simplified hedge accounting
approach for its interest rate swap agreements as permitted by ASU 2014-03.
Under this approach, the Company assumes no ineffectiveness for qualifying
hedging relationships.

Variable Interest Entities: The Company has elected not to apply the
variable interest entity consolidation guidance to qualifying common
control leasing arrangements under ASU 2014-18.
```

---

## Common Mistakes to Avoid

| Mistake | Consequence | Prevention |
|---------|-------------|------------|
| Electing alternatives without documenting | Audit issues | Maintain board minutes/memo |
| Partial election of goodwill amortization | Non-compliance | Must apply to ALL goodwill |
| Forgetting to disclose elections | Modified opinion risk | Use disclosure checklist |
| Not updating for new acquisitions | Inconsistent application | Review elections annually |
| Ignoring debt covenant requirements | Covenant violation | Review agreements before electing |

---

## External Resources

| Resource | Link | Description |
|----------|------|-------------|
| FASB PCC Page | [fasb.org/pcc](https://www.fasb.org/page/PageContent?pageId=/about-us/privatecompanycouncil.html) | Official PCC information |
| AICPA Private Company Practice Section | [aicpa.org/pcps](https://www.aicpa.org/resources/landing/private-company-financial-reporting) | Implementation guidance |
| CAQ/AICPA Guide | [thecaq.org](https://www.thecaq.org/) | Private company reporting |
| Deloitte PCC Summary | [iasplus.com](https://www.iasplus.com/en-us/tag-types/private-company-council) | Comprehensive tracking |

---

[← Back to Main Guide](../README.md)
