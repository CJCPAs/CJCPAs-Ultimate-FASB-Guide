# ASC 505: Equity

> The foundational standard for accounting and reporting of stockholders' equity transactions.

## Overview

ASC 505 provides guidance on the accounting and reporting for equity transactions, including issuance of stock, treasury stock transactions, dividends, stock splits, and equity-based arrangements other than share-based compensation. Understanding equity accounting is fundamental to properly presenting an entity's financial position.

**Core Principle:**
> "Equity represents the residual interest in the assets of an entity after deducting all liabilities. Transactions affecting equity should be classified and presented to distinguish between contributions from owners, distributions to owners, and other changes in equity."

---

## Scope

### Applies To:
- Issuance of common and preferred stock
- Treasury stock transactions
- Dividends (cash and stock)
- Stock splits and reverse stock splits
- Convertible instruments (equity components)
- Warrants and rights
- Equity restructurings

### Does NOT Apply To:
- Stock-based compensation (ASC 718)
- Distinguishing liabilities from equity (ASC 480)
- Derivatives indexed to entity's own stock (ASC 815)
- Earnings per share calculations (ASC 260)
- Business combinations (ASC 805)

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Common Stock** | Basic ownership interest with voting rights and residual claim |
| **Preferred Stock** | Equity with preferential rights (dividends, liquidation) |
| **Par Value** | Stated or legal value assigned to shares |
| **Additional Paid-in Capital (APIC)** | Amount received above par value |
| **Retained Earnings** | Accumulated net income less dividends |
| **Treasury Stock** | Entity's own shares reacquired |
| **Accumulated OCI** | Cumulative other comprehensive income items |

---

## Common Stock Transactions

### Stock Issuance

**At Par Value:**
```
Dr. Cash                              $100,000
    Cr. Common Stock (at par)                   $10,000
    Cr. Additional Paid-in Capital              $90,000
(10,000 shares × $10/share issued; $1 par)
```

**No Par Value Stock:**
```
Dr. Cash                              $100,000
    Cr. Common Stock                           $100,000
```

**Stock Issued for Non-Cash Consideration:**
```
Dr. Equipment (at fair value)         $75,000
    Cr. Common Stock                            $5,000
    Cr. Additional Paid-in Capital             $70,000
(Measure at fair value of consideration received or shares issued)
```

### Stock Subscriptions

**Subscription Agreement:**
```
Dr. Stock Subscriptions Receivable    $50,000
    Cr. Common Stock Subscribed               $50,000
```

**Collection and Issuance:**
```
Dr. Cash                              $50,000
    Cr. Stock Subscriptions Receivable        $50,000

Dr. Common Stock Subscribed           $50,000
    Cr. Common Stock                          $50,000
```

**Balance Sheet Presentation:**
- Stock Subscriptions Receivable: Contra-equity (usually)
- Common Stock Subscribed: Within equity, separate from issued stock

---

## Preferred Stock

### Types of Preferred Stock

| Feature | Description |
|---------|-------------|
| **Cumulative** | Unpaid dividends accumulate |
| **Non-cumulative** | Unpaid dividends do not accumulate |
| **Participating** | Share in distributions beyond stated rate |
| **Convertible** | Can be converted to common stock |
| **Callable** | Issuer can redeem |
| **Redeemable** | Holder can put back to issuer |

### Issuance of Preferred Stock

**Basic Issuance:**
```
Dr. Cash                              $500,000
    Cr. Preferred Stock (at par)              $100,000
    Cr. APIC—Preferred Stock                  $400,000
(10,000 shares × $50/share; $10 par)
```

### Preferred Stock with Multiple Features

**Convertible Preferred:**
- Under current U.S. GAAP, convertible preferred is typically recorded entirely as equity
- No bifurcation required (unlike some debt instruments)

---

## Treasury Stock

### Overview

Treasury stock represents shares reacquired by the issuing entity. Two methods are acceptable:

| Method | Accounting Approach |
|--------|---------------------|
| **Cost Method** | Record at acquisition cost; commonly used |
| **Par Value Method** | Record at par value; less common |

### Cost Method

**Acquisition:**
```
Dr. Treasury Stock                    $25,000
    Cr. Cash                                   $25,000
(1,000 shares reacquired at $25/share)
```

**Reissuance Above Cost:**
```
Dr. Cash                              $30,000
    Cr. Treasury Stock                        $25,000
    Cr. APIC—Treasury Stock                    $5,000
(Reissued 1,000 shares at $30/share)
```

**Reissuance Below Cost:**
```
Dr. Cash                              $20,000
Dr. APIC—Treasury Stock                $3,000
Dr. Retained Earnings                  $2,000
    Cr. Treasury Stock                        $25,000
(Reissued at $20/share; debit APIC first, then R/E)
```

### Par Value Method

**Acquisition:**
```
Dr. Treasury Stock (at par)           $1,000
Dr. APIC—Common Stock                $19,000
Dr. Retained Earnings                  $5,000
    Cr. Cash                                   $25,000
(Original issue at $20/share; reacquired at $25)
```

### Balance Sheet Presentation

**Cost Method:**
```
Stockholders' Equity:
  Common stock                        $100,000
  APIC                                 500,000
  Retained earnings                    800,000
  Treasury stock (at cost)            (25,000)
                                      --------
  Total stockholders' equity        $1,375,000
```

---

## Dividends

### Cash Dividends

**Declaration:**
```
Dr. Retained Earnings                 $50,000
    Cr. Dividends Payable                     $50,000
(Board declaration; liability created)
```

**Payment:**
```
Dr. Dividends Payable                 $50,000
    Cr. Cash                                   $50,000
```

### Stock Dividends

**Small Stock Dividend (< 20-25%):**
```
Dr. Retained Earnings                 $25,000
    Cr. Common Stock                           $1,000
    Cr. APIC—Common Stock                     $24,000
(1,000 shares × $25 FMV; $1 par)
```

**Large Stock Dividend (> 20-25%):**
```
Dr. Retained Earnings                 $10,000
    Cr. Common Stock                          $10,000
(10,000 shares × $1 par value only)
```

### Property Dividends

**Declaration (at fair value):**
```
Dr. Investment (or other asset)        $5,000
    Cr. Gain on Distribution                   $5,000
(Remeasure property to fair value)

Dr. Retained Earnings                 $35,000
    Cr. Property Dividend Payable             $35,000
(FMV of property to be distributed)
```

### Scrip Dividends

**Declaration:**
```
Dr. Retained Earnings                 $10,000
    Cr. Scrip Dividends Payable              $10,000
```

**Interest Accrual (if interest-bearing):**
```
Dr. Interest Expense                     $500
    Cr. Interest Payable                        $500
```

### Liquidating Dividends

When dividends exceed retained earnings:
```
Dr. Retained Earnings                 $80,000
Dr. APIC                              $20,000
    Cr. Dividends Payable                    $100,000
```

---

## Stock Splits

### Forward Stock Split

**2-for-1 Split:**
- Double the shares outstanding
- Halve the par value (if any)
- No journal entry required (memo entry only)

**Memo Entry:**
```
"On [date], the Board authorized a 2-for-1 stock split, increasing
shares outstanding from 100,000 to 200,000 and reducing par value
from $2 to $1 per share."
```

### Reverse Stock Split

**1-for-5 Split:**
- Reduce shares outstanding by 80%
- Increase par value proportionally
- No journal entry required (memo entry only)

### Stock Split in Form of Dividend

Sometimes a large stock dividend is called a "split":
```
Dr. Retained Earnings                $100,000
    Cr. Common Stock                         $100,000
(100% stock dividend effectuated as 2-for-1 split)
```

---

## Equity Restructurings

### Recapitalization

**Reducing Par Value:**
```
Dr. Common Stock                      $50,000
    Cr. APIC—Par Value Reduction             $50,000
(Reduced par from $10 to $5 on 10,000 shares)
```

### Quasi-Reorganization

**Purpose:** Eliminate accumulated deficit and "fresh start"

**Requirements:**
1. Must be authorized by shareholders
2. Assets written down to fair value first
3. Deficit eliminated against APIC
4. Disclose for 10 years

**Entry:**
```
Dr. APIC                             $200,000
    Cr. Retained Earnings (Deficit)          $200,000
```

---

## Convertible Securities

### Convertible Preferred Stock Conversion

**Book Value Method (standard):**
```
Dr. Preferred Stock                  $100,000
Dr. APIC—Preferred Stock              $50,000
    Cr. Common Stock                          $20,000
    Cr. APIC—Common Stock                    $130,000
(No gain or loss recognized)
```

### Induced Conversion

If additional consideration provided to induce conversion:
```
Dr. Preferred Stock                  $100,000
Dr. APIC—Preferred Stock              $50,000
Dr. Inducement Expense                $15,000
    Cr. Common Stock                          $20,000
    Cr. APIC—Common Stock                    $130,000
    Cr. Cash                                   $15,000
```

---

## Warrants and Rights

### Stock Warrants Issued with Debt (ASC 470-20)

**Allocation Based on Relative Fair Values:**
```
Debt fair value: $900,000
Warrant fair value: $100,000
Proceeds: $1,000,000

Allocation:
  Debt: $900,000 / $1,000,000 × $1,000,000 = $900,000
  Warrants: $100,000 / $1,000,000 × $1,000,000 = $100,000
```

**Journal Entry:**
```
Dr. Cash                           $1,000,000
Dr. Discount on Bonds Payable       $100,000
    Cr. Bonds Payable                      $1,000,000
    Cr. APIC—Stock Warrants                  $100,000
```

### Stock Rights (Rights Offering)

**Issuance:** No entry (memo only until exercised)

**Exercise:**
```
Dr. Cash                              $40,000
    Cr. Common Stock                           $4,000
    Cr. APIC—Common Stock                     $36,000
(Rights exercised at $40/share; $4 par)
```

### Warrant/Right Expiration

```
Dr. APIC—Stock Warrants               $5,000
    Cr. APIC—Expired Warrants                  $5,000
(Reclassification within APIC; no income effect)
```

---

## Noncontrolling Interests

### Presentation

Noncontrolling interests (NCI) are presented within equity, separate from parent's equity:

```
Stockholders' Equity:
  Common stock                        $100,000
  APIC                                 500,000
  Retained earnings                    800,000
                                      --------
  Total parent equity               1,400,000
  Noncontrolling interests             200,000
                                      --------
  Total equity                      $1,600,000
```

### Transactions with NCI

**Parent Acquires Additional NCI (no change in control):**
```
Dr. APIC (or Retained Earnings)       $25,000
    Cr. Cash                                   $25,000
(Equity transaction—no gain or loss)
```

**Parent Sells Interest to NCI (retains control):**
```
Dr. Cash                              $30,000
    Cr. APIC                                   $30,000
(Equity transaction—no gain or loss)
```

---

## Practical Examples

### Example 1: Complete Treasury Stock Transaction

**Facts:**
- Company has 100,000 shares outstanding, $1 par
- Reacquires 5,000 shares at $15/share
- Reissues 3,000 shares at $18/share
- Reissues 2,000 shares at $12/share

**Acquisition:**
```
Dr. Treasury Stock                    $75,000
    Cr. Cash                                   $75,000
```

**Reissuance at $18:**
```
Dr. Cash                              $54,000
    Cr. Treasury Stock                        $45,000
    Cr. APIC—Treasury Stock                    $9,000
```

**Reissuance at $12:**
```
Dr. Cash                              $24,000
Dr. APIC—Treasury Stock                $6,000
    Cr. Treasury Stock                        $30,000
```

---

### Example 2: Dividend Calculation—Preferred and Common

**Facts:**
- 10,000 shares 6% cumulative preferred, $100 par
- 50,000 shares common, $10 par
- Dividends in arrears: 2 years
- Total dividend declared: $200,000

**Calculation:**

| Component | Calculation | Amount |
|-----------|-------------|--------|
| Preferred—arrears | 10,000 × $100 × 6% × 2 years | $120,000 |
| Preferred—current | 10,000 × $100 × 6% | $60,000 |
| Common | Remainder | $20,000 |
| **Total** | | **$200,000** |

**Journal Entry:**
```
Dr. Retained Earnings               $200,000
    Cr. Dividends Payable—Preferred          $180,000
    Cr. Dividends Payable—Common              $20,000
```

---

### Example 3: Stock Dividend vs. Stock Split

**Facts:**
- 100,000 shares outstanding
- $2 par value
- Market price: $50/share

**10% Stock Dividend:**
```
Dr. Retained Earnings               $500,000
    Cr. Common Stock                          $20,000
    Cr. APIC                                 $480,000
(10,000 shares × $50 FMV)
```

**2-for-1 Stock Split:**
```
(Memo entry only—shares double to 200,000; par becomes $1)
```

**Effect Comparison:**

| Item | Stock Dividend | Stock Split |
|------|---------------|-------------|
| Shares outstanding | 110,000 | 200,000 |
| Par value per share | $2 | $1 |
| Total par value | $220,000 | $200,000 |
| Retained earnings | Reduced $500,000 | No change |
| Total equity | No change | No change |

---

## Private Company Considerations

### Common Issues

| Issue | Consideration |
|-------|---------------|
| **Related party** | Document fair value for stock issued to related parties |
| **Compensation** | Stock to employees may be ASC 718 |
| **Redemption features** | May require liability classification (ASC 480) |
| **Buy-sell agreements** | Evaluate whether creates redemption obligation |

### Valuation Challenges

Private company stock valuation considerations:
- Lack of marketability discount
- Minority interest discount
- Control premium
- Documentation requirements

### S Corporation / Partnership Issues

- Different equity structures
- Distribution requirements
- AAA/capital account tracking
- Tax basis vs. GAAP differences

---

## Common Audit Issues

### Equity Classification

| Issue | Risk |
|-------|------|
| **Redeemable preferred** | Should be liability or mezzanine |
| **Contingent equity** | Evaluate probability and classification |
| **Conversion features** | May require bifurcation |

### Treasury Stock

| Issue | Audit Procedure |
|-------|-----------------|
| **Improper cost allocation** | Trace to actual acquisition cost |
| **Incorrect reissuance** | Verify sequence of APIC vs. R/E debits |
| **Legal restrictions** | Review state law limitations |

### Dividend Authorization

- Board authorization documentation
- Retained earnings availability
- Covenant restrictions
- Record date accuracy

---

## Disclosure Requirements

### General Equity Disclosures

| Item | Required Disclosure |
|------|---------------------|
| **Capital structure** | Rights and preferences of each class |
| **Changes in equity** | Components of changes during period |
| **Dividends** | Per share amounts, arrearages |
| **Treasury stock** | Method used, shares held |
| **Stock-based payments** | Cross-reference to ASC 718 |

### Redeemable Securities

If redeemable equity exists:
- Redemption terms
- Redemption amount
- Timing

### Concentration

If stock ownership concentrated:
- Significant shareholders
- Related party holdings

---

## Equity vs. Liability Distinction

### Key Considerations (ASC 480)

| Feature | Likely Equity | Likely Liability |
|---------|---------------|------------------|
| Redemption at holder's option | | X |
| Mandatory redemption | | X |
| Obligation to deliver cash | | X |
| Settlement in variable shares | | X |
| No redemption feature | X | |
| Perpetual | X | |

### Mezzanine Equity

Securities not clearly equity may be presented between liabilities and equity:
```
Total liabilities                   $1,000,000

Redeemable preferred stock             200,000

Stockholders' equity:
  Common stock                         100,000
  Retained earnings                    500,000
  Total stockholders' equity           600,000
```

---

## Recent Updates

| ASU | Topic | Impact |
|-----|-------|--------|
| **ASU 2023-01** | Leases—Common Control | May affect equity for related party arrangements |
| **ASU 2022-03** | Fair Value of Equity Securities | Measurement with sale restrictions |
| **ASU 2020-06** | Convertible Instruments | Simplified conversion accounting |
| **ASU 2017-11** | Complex Equity Instruments | Down-round features |

---

## External Resources

- [FASB ASC 505](https://asc.fasb.org/)
- [FASB ASC 480 (Distinguishing Liabilities from Equity)](https://asc.fasb.org/)
- [FASB ASC 260 (Earnings Per Share)](https://asc.fasb.org/)
- [SEC Regulation S-X](https://www.sec.gov/)
- [AICPA Audit and Accounting Guide](https://www.aicpa.org/)
- [KPMG: Handbook—Equity](https://frv.kpmg.us/)
- [PwC: Financing Transactions Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Equity](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Equity](https://www.ey.com/)

---

## Navigation

← [Back to Equity (500s)](README.md) | [Back to Main Guide](../../README.md)
