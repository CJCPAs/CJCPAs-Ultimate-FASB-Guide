# ASC 220: Comprehensive Income

> Reporting all changes in equity from non-owner sources—the complete picture of financial performance.

## Overview

ASC 220 establishes standards for reporting and presentation of comprehensive income and its components. Comprehensive income captures all changes in equity during a period except those resulting from investments by owners and distributions to owners, providing a more complete view of an entity's financial performance.

**Core Principle:**
> "Comprehensive income includes all changes in equity during a period except those resulting from investments by owners and distributions to owners."

---

## Scope

### Applies To:
- All entities that provide a full set of financial statements
- Reporting of net income and other comprehensive income
- Presentation of accumulated other comprehensive income (AOCI)

### Does NOT Apply To:
- Not-for-profit organizations (follow ASC 958)
- Investment companies reporting net assets (follow ASC 946)
- Defined benefit pension plans (follow ASC 960)
- Entities presenting only condensed financial information

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Comprehensive Income** | Change in equity during a period from transactions and events from non-owner sources; includes net income and other comprehensive income |
| **Net Income** | Revenues, expenses, gains, and losses included in earnings under GAAP |
| **Other Comprehensive Income (OCI)** | Items of comprehensive income excluded from net income |
| **Accumulated Other Comprehensive Income (AOCI)** | Cumulative OCI amounts reported in stockholders' equity |
| **Reclassification Adjustments** | Amounts reclassified from AOCI to net income |

---

## Components of Other Comprehensive Income

### Summary Table

| Component | Initial Recognition | Reclassification to Net Income |
|-----------|--------------------|-----------------------------|
| **Foreign currency translation adjustments** | OCI | Upon sale/liquidation of investment |
| **Unrealized gains/losses on AFS debt securities** | OCI | When sold or impaired |
| **Cash flow hedge gains/losses** | OCI | When hedged transaction affects earnings |
| **Pension/OPEB adjustments** | OCI | As amortized to pension expense |
| **Revaluation surplus (rare in U.S. GAAP)** | OCI | Upon sale or use of asset |

---

## Detailed Component Guidance

### 1. Foreign Currency Translation Adjustments (ASC 830)

**When Recognized in OCI:**
- Translation of functional currency financial statements to reporting currency
- Exchange rate changes on intercompany foreign currency transactions of long-term investment nature

**Reclassified to Net Income When:**
- Sale or complete/substantially complete liquidation of investment in foreign entity

**Example:**
```
Dr. Foreign Subsidiary Net Assets     $50,000
    Cr. Cumulative Translation Adjustment (OCI)    $50,000
(To record favorable translation adjustment)
```

---

### 2. Available-for-Sale (AFS) Debt Securities (ASC 320)

**When Recognized in OCI:**
- Unrealized holding gains and losses on AFS debt securities

**Reclassified to Net Income When:**
- Security is sold
- Security is impaired (credit loss portion to earnings)

**Example:**
```
Dr. AFS Debt Securities              $10,000
    Cr. OCI—Unrealized Gain on AFS Securities     $10,000
(To record unrealized gain on AFS securities)
```

**Note:** Under ASC 321, equity securities are generally measured at fair value through net income (not OCI), except for the practicability exception.

---

### 3. Cash Flow Hedge Gains and Losses (ASC 815)

**When Recognized in OCI:**
- Effective portion of gains/losses on derivatives designated as cash flow hedges

**Reclassified to Net Income When:**
- Forecasted hedged transaction affects earnings
- Hedge is discontinued and forecasted transaction is no longer probable

**Example:**
```
Dr. Derivative Asset                 $25,000
    Cr. OCI—Cash Flow Hedge Gain              $25,000
(To record effective portion of cash flow hedge)
```

---

### 4. Pension and OPEB Adjustments (ASC 715)

**Components Recognized in OCI:**

| Item | Description |
|------|-------------|
| **Prior service cost/credit** | Plan amendments affecting prior periods |
| **Net actuarial gain/loss** | Changes in assumptions or experience different from expected |
| **Transition asset/obligation** | Historical amounts from initial adoption |

**Reclassified to Net Income:**
- Amortized as component of net periodic pension cost

**Example:**
```
Dr. OCI—Pension Actuarial Loss       $100,000
    Cr. Pension Liability                      $100,000
(To record actuarial loss from assumption changes)
```

---

## Presentation Requirements

### Presentation Alternatives

Entities must present comprehensive income using ONE of the following approaches:

| Option | Description | Preference |
|--------|-------------|------------|
| **Single continuous statement** | Combined statement of income and comprehensive income | FASB preferred |
| **Two separate but consecutive statements** | Income statement immediately followed by statement of comprehensive income | Acceptable |

**Not Permitted:**
- Presentation of OCI components only in statement of changes in equity
- Presentation of OCI components only in notes

---

### Format Examples

#### Option 1: Single Continuous Statement

```
COMPANY XYZ
Statement of Comprehensive Income
For the Year Ended December 31, 20X1

Revenues                                           $1,000,000
Cost of goods sold                                   (600,000)
                                                    ----------
Gross profit                                          400,000
Operating expenses                                   (250,000)
                                                    ----------
Operating income                                      150,000
Interest expense                                      (20,000)
                                                    ----------
Income before income taxes                            130,000
Income tax expense                                    (32,500)
                                                    ----------
Net income                                             97,500
                                                    ----------
Other comprehensive income, net of tax:
  Foreign currency translation adjustment              12,000
  Unrealized gain on AFS securities                    5,000
  Cash flow hedge loss                                (3,000)
  Pension actuarial gain                               8,000
                                                    ----------
Other comprehensive income                             22,000
                                                    ----------
Comprehensive income                               $  119,500
                                                    ==========
```

---

#### Option 2: Two Separate Consecutive Statements

**Income Statement:**
```
COMPANY XYZ
Statement of Income
For the Year Ended December 31, 20X1

Revenues                                           $1,000,000
Cost of goods sold                                   (600,000)
Gross profit                                          400,000
Operating expenses                                   (250,000)
Operating income                                      150,000
Interest expense                                      (20,000)
Income before income taxes                            130,000
Income tax expense                                    (32,500)
                                                    ----------
Net income                                         $   97,500
                                                    ==========
```

**Statement of Comprehensive Income (immediately following):**
```
COMPANY XYZ
Statement of Comprehensive Income
For the Year Ended December 31, 20X1

Net income                                         $   97,500
Other comprehensive income, net of tax:
  Foreign currency translation adjustment              12,000
  Unrealized gain on AFS securities                    5,000
  Cash flow hedge loss                                (3,000)
  Pension actuarial gain                               8,000
                                                    ----------
Other comprehensive income                             22,000
                                                    ----------
Comprehensive income                               $  119,500
                                                    ==========
```

---

## Tax Effects on OCI

### Presentation Options

Entities must display OCI components either:
1. **Net of related tax effects**, OR
2. **Before related tax effects** with one line showing aggregate tax effect

### Allocation of Tax

Tax effects should be allocated to each component of OCI:

| Component | Pre-Tax | Tax Effect | Net of Tax |
|-----------|---------|------------|------------|
| Translation adjustment | $15,000 | $(3,000) | $12,000 |
| AFS securities gain | $6,250 | $(1,250) | $5,000 |
| Cash flow hedge loss | $(3,750) | $750 | $(3,000) |
| Pension gain | $10,000 | $(2,000) | $8,000 |
| **Total OCI** | **$27,500** | **$(5,500)** | **$22,000** |

---

## Reclassification Adjustments

### Purpose

Reclassification adjustments prevent double counting when amounts initially recognized in OCI are later recognized in net income.

### Disclosure Requirements

Entities must present reclassification adjustments either:
- On the face of the statement of comprehensive income, OR
- In the notes to financial statements

### Example Presentation (Face of Statement)

```
Other comprehensive income, net of tax:
  Unrealized gain on AFS securities:
    Unrealized holding gain arising during period       $8,000
    Less: reclassification adjustment for gains
      included in net income                            (3,000)
                                                       --------
    Net unrealized gain on AFS securities               $5,000
```

### Example Note Disclosure

```
Reclassification Adjustments from AOCI to Net Income

The following amounts were reclassified from accumulated other
comprehensive income to net income:

                                        Year Ended December 31
                                          20X1        20X0
Realized gains on AFS securities         $3,000      $1,500
  Income tax effect                        (750)       (375)
  Net of tax                             $2,250      $1,125

Affected income statement line: Investment gains (losses)
```

---

## Accumulated Other Comprehensive Income (AOCI)

### Balance Sheet Presentation

AOCI is presented within stockholders' equity, separate from retained earnings:

```
Stockholders' Equity:
  Common stock                                    $  100,000
  Additional paid-in capital                        500,000
  Retained earnings                               1,200,000
  Accumulated other comprehensive income (loss):
    Foreign currency translation                     45,000
    Unrealized gain on AFS securities               22,000
    Cash flow hedge loss                           (15,000)
    Pension adjustments                            (80,000)
                                                  ---------
    Total AOCI                                     (28,000)
                                                  ---------
  Total stockholders' equity                    $1,772,000
```

### AOCI Rollforward Disclosure

Entities must disclose changes in each component of AOCI:

```
Changes in Accumulated Other Comprehensive Income by Component
For the Year Ended December 31, 20X1

                    Foreign    AFS        Cash Flow   Pension
                    Currency   Securities Hedges      Adjust.   Total
Balance, 1/1/X1     $33,000    $17,000   $(12,000)  $(88,000) $(50,000)
OCI before
 reclassifications   15,000      8,000     (5,000)    10,000    28,000
Reclassifications        -      (3,000)     2,000     (2,000)   (3,000)
                    -------    -------    -------    -------   -------
Net OCI              12,000      5,000     (3,000)     8,000    22,000
Balance, 12/31/X1   $45,000    $22,000   $(15,000)  $(80,000) $(28,000)
```

---

## Practical Examples

### Example 1: Complete OCI Calculation

**Facts for Year Ended December 31, 20X1:**
- Net income: $500,000
- AFS debt securities increased in fair value by $20,000 (pretax)
- Sold AFS securities with $8,000 gain previously recorded in AOCI
- Foreign subsidiary had favorable translation adjustment of $30,000
- Pension plan had actuarial loss of $50,000
- Tax rate: 25%

**OCI Calculation:**

| Item | Pretax | Tax (25%) | Net of Tax |
|------|--------|-----------|------------|
| Unrealized gain—AFS | $20,000 | $(5,000) | $15,000 |
| Reclassification—AFS | $(8,000) | $2,000 | $(6,000) |
| Net AFS | $12,000 | $(3,000) | $9,000 |
| Translation adjustment | $30,000 | $(7,500) | $22,500 |
| Pension actuarial loss | $(50,000) | $12,500 | $(37,500) |
| **Total OCI** | **$(8,000)** | **$2,000** | **$(6,000)** |

**Comprehensive Income:**
- Net income: $500,000
- Other comprehensive loss: $(6,000)
- Comprehensive income: $494,000

---

### Example 2: Journal Entries for OCI Items

**Recording Unrealized Gain on AFS Securities:**
```
Dr. Investment in AFS Securities     $20,000
    Cr. OCI—Unrealized Gain (pretax)          $20,000

Dr. OCI—Tax Effect                   $5,000
    Cr. Deferred Tax Liability                 $5,000
```

**Reclassification When AFS Security Sold:**
```
Dr. Cash                             $108,000
    Cr. Investment in AFS Securities           $100,000
    Cr. Realized Gain on Sale                   $8,000

Dr. OCI—Reclassification             $8,000
    Cr. OCI—Unrealized Gain                    $8,000

Dr. Deferred Tax Liability           $2,000
    Cr. OCI—Tax Effect                         $2,000
```

---

### Example 3: Pension OCI Entries

**Recording Actuarial Loss:**
```
Dr. OCI—Pension Actuarial Loss       $50,000
    Cr. Pension Liability                      $50,000

Dr. Deferred Tax Asset               $12,500
    Cr. OCI—Tax Effect (Pension)               $12,500
```

**Amortization of Prior Service Cost to Net Income:**
```
Dr. Pension Expense                  $10,000
    Cr. OCI—Prior Service Cost                 $10,000

Dr. OCI—Tax Effect                   $2,500
    Cr. Deferred Tax Asset                     $2,500
```

---

## Private Company Considerations

### Simplified Reporting

Private companies follow the same OCI reporting requirements, but:
- May have fewer OCI components (less complex financial instruments)
- Pension alternatives under PCC may reduce OCI volatility
- May use practical expedients that reduce OCI items

### Common Private Company OCI Items

| Item | Common? | Notes |
|------|---------|-------|
| Foreign currency | Less common | Unless foreign subsidiaries |
| AFS securities | Moderate | If investment portfolio exists |
| Cash flow hedges | Less common | Fewer hedging activities |
| Pension adjustments | Common | If defined benefit plan exists |

### PCC Alternatives Affecting OCI

**Pension Alternative:** Private companies can elect to measure pension obligations using practical expedients that may reduce actuarial volatility.

---

## Common Audit Issues

### Presentation Errors

| Error | Impact |
|-------|--------|
| OCI in statement of changes in equity only | Not permitted—must use statement |
| Missing reclassification disclosures | Incomplete presentation |
| Incorrect tax allocation | Misstated individual components |
| AOCI not separately presented | Equity presentation incomplete |

### Calculation Issues

| Issue | Risk |
|-------|------|
| Incorrect reclassification amounts | Double counting or omission |
| Tax rate errors on OCI | Misstated net of tax amounts |
| Missing OCI components | Incomplete comprehensive income |
| Incorrect AOCI rollforward | Cannot reconcile to balance sheet |

### Documentation Requirements

- Support for fair value changes (AFS securities)
- Translation rate calculations
- Pension actuarial reports
- Hedge effectiveness documentation
- Tax effect calculations

---

## Disclosure Requirements

### Required Disclosures

| Disclosure | Location |
|------------|----------|
| Total comprehensive income | Statement (face) |
| Components of OCI | Statement (face) or notes |
| Tax effects | Statement or notes |
| Reclassification adjustments | Statement or notes |
| AOCI by component | Balance sheet or notes |
| Changes in AOCI | Notes (rollforward) |

### Enhanced Reclassification Disclosure

Must disclose for each component:
- Amount reclassified to net income
- Income statement line item affected
- Whether reclassification relates to noncontrolling interest

---

## Recent Updates

| ASU | Topic | Impact on OCI |
|-----|-------|---------------|
| **ASU 2023-01** | Leases—Common Control | May affect certain lease OCI items |
| **ASU 2020-04** | Reference Rate Reform | Hedge accounting modifications |
| **ASU 2018-02** | Stranded Tax Effects | One-time reclassification from AOCI for tax reform |
| **ASU 2017-12** | Hedge Accounting | More items may qualify for OCI |
| **ASU 2016-01** | Financial Instruments | Equity securities through net income (not OCI) |

---

## External Resources

- [FASB ASC 220](https://asc.fasb.org/)
- [FASB ASC 320 (Investments—Debt Securities)](https://asc.fasb.org/)
- [FASB ASC 715 (Pensions)](https://asc.fasb.org/)
- [FASB ASC 815 (Derivatives and Hedging)](https://asc.fasb.org/)
- [FASB ASC 830 (Foreign Currency)](https://asc.fasb.org/)
- [SEC Regulation S-X](https://www.sec.gov/)
- [KPMG: Handbook—Statement of Cash Flows and OCI](https://frv.kpmg.us/)
- [PwC: Financial Statement Presentation Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Comprehensive Income](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—OCI](https://www.ey.com/)

---

## Navigation

← [Back to Presentation (200s)](README.md) | [Back to Main Guide](../../README.md)
