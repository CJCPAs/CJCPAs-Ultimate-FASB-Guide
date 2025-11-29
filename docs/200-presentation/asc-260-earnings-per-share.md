# ASC 260: Earnings Per Share

> The comprehensive standard for calculating and presenting basic and diluted earnings per share.

## Overview

ASC 260 provides guidance on computing and presenting earnings per share (EPS) for entities with publicly traded common stock or potential common stock. EPS is a key metric used by investors and analysts to evaluate a company's profitability on a per-share basis.

**Core Principle:**
> "The objective of basic EPS is to measure the performance of an entity over the reporting period by dividing income available to common shareholders by the weighted-average number of common shares outstanding."

---

## Scope

### Required For:
- Entities with publicly traded common stock
- Entities with publicly traded potential common stock (convertibles, options, warrants)
- Entities that have filed or are in process of filing with SEC for public sale

### Not Required For:
- Private companies
- Not-for-profit organizations
- Investment companies reporting per-share data under ASC 946

### Presentation

- Present on face of income statement for:
  - Income from continuing operations
  - Net income
- Present for discontinued operations (face or notes)

---

## Basic EPS

### Formula

```
Basic EPS = (Net Income − Preferred Dividends) / Weighted-Average Common Shares Outstanding
```

### Numerator Adjustments

| Item | Treatment |
|------|-----------|
| **Cumulative preferred dividends** | Subtract (whether declared or not) |
| **Non-cumulative preferred dividends** | Subtract only if declared |
| **Preferred stock redemption premium** | Subtract from numerator |
| **Preferred stock discount** | Add to numerator |
| **Participating securities** | Apply two-class method |

### Weighted-Average Shares

**Calculation:** Time-weight shares outstanding during the period

**Formula:**
```
Weighted-Average = Σ (Shares Outstanding × Fraction of Period Outstanding)
```

### Share Transactions

| Transaction | Treatment |
|-------------|-----------|
| **Issuance for cash** | Include from issuance date |
| **Stock dividend/split** | Retroactively adjust all periods |
| **Reverse split** | Retroactively adjust all periods |
| **Share repurchase** | Exclude from repurchase date |
| **Contingently issuable** | Include when conditions met |

---

## Stock Dividends and Splits

### Retroactive Treatment

Stock dividends and splits are treated as if they occurred at the beginning of the **earliest period presented**.

### Example

**Facts:**
- 2×1 stock split in March 20X2
- Shares outstanding January 1, 20X2: 100,000
- Prior year EPS calculation used 100,000 shares

**Current Year:**
- Weighted-average shares: 200,000 (adjusted for split)

**Prior Year Restatement:**
- Restate prior year shares: 100,000 × 2 = 200,000

---

## Diluted EPS

### Formula

```
Diluted EPS = (Adjusted Net Income) / (Weighted-Average Shares + Dilutive Potential Shares)
```

### Purpose

Show the "worst case" EPS if all dilutive securities were converted or exercised.

### Dilutive vs. Antidilutive

| Effect | Include in Diluted EPS? |
|--------|------------------------|
| **Dilutive** | Decreases EPS or increases loss per share | Yes |
| **Antidilutive** | Increases EPS or decreases loss per share | No |

### Dilutive Securities (Common Types)

| Security | Method |
|----------|--------|
| Stock options/warrants | Treasury stock method |
| Convertible preferred stock | If-converted method |
| Convertible debt | If-converted method |
| Contingently issuable shares | Include if conditions are met |
| Participating securities | Two-class method |

---

## Treasury Stock Method

### Applies To:
- Stock options
- Stock warrants
- Stock purchase plans
- Other similar arrangements

### Calculation

**Step 1:** Assume exercise at beginning of period (or grant date if later)

**Step 2:** Calculate proceeds from assumed exercise

**Step 3:** Assume proceeds used to repurchase shares at average market price

**Step 4:** Net shares added = Shares issued − Shares repurchased

### Formula

```
Incremental Shares = Shares from Exercise − (Exercise Proceeds / Average Stock Price)
```

### Example: Treasury Stock Method

**Facts:**
- Options outstanding: 10,000
- Exercise price: $20
- Average market price: $50

**Calculation:**
```
Shares from exercise:           10,000
Proceeds: 10,000 × $20 =       $200,000
Shares repurchased: $200,000 / $50 = 4,000
Incremental shares:             6,000
```

### When Antidilutive

If exercise price ≥ average market price → Options are antidilutive (out of the money) → Exclude from diluted EPS

---

## If-Converted Method

### Applies To:
- Convertible preferred stock
- Convertible debt

### Approach

Assume conversion occurred at:
- Beginning of period, OR
- Date of issuance (if later)

### Convertible Preferred Stock

**Numerator:** Add back preferred dividends (no longer deducted)
**Denominator:** Add shares that would be issued upon conversion

### Convertible Debt

**Numerator:** Add back interest expense (net of tax)
**Denominator:** Add shares that would be issued upon conversion

### Example: Convertible Debt

**Facts:**
- Convertible bonds: $1,000,000 face value
- Interest rate: 5%
- Convertible into 40,000 common shares
- Tax rate: 25%
- Net income: $500,000
- Basic shares: 200,000

**Basic EPS:**
```
$500,000 / 200,000 = $2.50
```

**Diluted EPS Calculation:**

*Numerator adjustment:*
```
Interest expense: $1,000,000 × 5% = $50,000
Tax effect: $50,000 × 25% = $12,500
After-tax interest: $50,000 − $12,500 = $37,500

Adjusted numerator: $500,000 + $37,500 = $537,500
```

*Denominator adjustment:*
```
Adjusted shares: 200,000 + 40,000 = 240,000
```

*Diluted EPS:*
```
$537,500 / 240,000 = $2.24
```

**Dilution test:** $2.24 < $2.50 → Dilutive → Include

---

## Two-Class Method

### Applies To:
Entities with participating securities or multiple classes of common stock.

### Participating Securities

Securities that:
- May participate in undistributed earnings with common stock
- Examples: Certain preferred stock, restricted stock with dividend rights

### Calculation

**Step 1:** Allocate undistributed earnings to common and participating securities based on participation rights

**Step 2:** Calculate EPS for common stock using only common stock's share of earnings

### Example: Two-Class Method

**Facts:**
- Net income: $1,000,000
- Preferred dividends declared: $100,000
- Preferred stock participation rate: 10% of remaining earnings
- Common shares: 500,000
- Preferred shares (participating): 50,000

**Step 1: Calculate undistributed earnings**
```
Net income:                     $1,000,000
Less: Preferred dividends         (100,000)
Undistributed earnings:           $900,000
```

**Step 2: Allocate undistributed earnings**
```
To participating preferred (10%): $90,000
To common (90%):                  $810,000
```

**Step 3: Calculate basic EPS**
```
Common earnings: $810,000
Common shares: 500,000
Basic EPS: $810,000 / 500,000 = $1.62
```

---

## Contingently Issuable Shares

### Definition

Shares issuable for little or no consideration upon certain conditions being met.

### Treatment

| Condition Status | Treatment |
|------------------|-----------|
| **Conditions met** | Include in basic and diluted EPS |
| **Conditions not yet met** | Include in diluted if would be dilutive (assuming conditions met at period end) |

### Examples

- Earnout shares in acquisition
- Performance-based restricted stock
- Market condition-based awards

---

## Complex Capital Structures

### Order of Dilution

When multiple dilutive securities exist, test each for dilution in order from most to least dilutive:

**Step 1:** Calculate basic EPS

**Step 2:** Rank securities by dilutive effect (most dilutive first)

**Step 3:** Add each security sequentially, recalculating EPS

**Step 4:** Stop when adding a security becomes antidilutive

### Measuring Dilutive Effect

For convertibles:
```
Dilutive Effect = Earnings Adjustment / Share Adjustment
```

Lower ratio = More dilutive

---

## ASU 2020-06: Convertible Instruments

### Key Changes

| Before ASU 2020-06 | After ASU 2020-06 |
|--------------------|-------------------|
| Treasury stock method for certain convertibles | If-converted method for all convertibles |
| Cash conversion feature—treasury stock | If-converted method |
| Beneficial conversion feature | Eliminated |

### Impact on EPS

- Generally more dilutive EPS for convertible instruments
- Simpler calculation (one method for all convertibles)

### Effective Dates

| Entity Type | Effective Date |
|-------------|----------------|
| Public (excluding SRCs) | Fiscal years beginning after 12/15/2021 |
| All others | Fiscal years beginning after 12/15/2023 |

---

## Practical Examples

### Example 1: Comprehensive Basic and Diluted EPS

**Facts:**
- Net income: $2,000,000
- Preferred dividends (cumulative): $200,000
- Common shares (full year): 800,000
- Stock options: 100,000 at $30 exercise price
- Average stock price: $50
- Convertible bonds: $2,000,000 at 6%, convertible to 80,000 shares
- Tax rate: 25%

**Basic EPS:**
```
Numerator: $2,000,000 − $200,000 = $1,800,000
Denominator: 800,000

Basic EPS: $1,800,000 / 800,000 = $2.25
```

**Diluted EPS—Step 1: Treasury Stock Method (Options)**
```
Shares from exercise: 100,000
Proceeds: 100,000 × $30 = $3,000,000
Shares repurchased: $3,000,000 / $50 = 60,000
Incremental shares: 40,000

Adjusted shares: 800,000 + 40,000 = 840,000
EPS after options: $1,800,000 / 840,000 = $2.14
```

**Diluted EPS—Step 2: If-Converted (Bonds)**
```
Interest add-back: $2,000,000 × 6% = $120,000
Tax effect: $120,000 × 25% = $30,000
After-tax: $90,000

Adjusted numerator: $1,800,000 + $90,000 = $1,890,000
Adjusted shares: 840,000 + 80,000 = 920,000

EPS with bonds: $1,890,000 / 920,000 = $2.05

Dilution test: $2.05 < $2.14 → Dilutive → Include
```

**Final Diluted EPS: $2.05**

---

### Example 2: Stock Split During Year

**Facts:**
- January 1: 100,000 shares outstanding
- April 1: Issued 20,000 shares
- October 1: 2-for-1 stock split
- Net income: $600,000

**Weighted-Average Shares (Pre-Split):**
```
Jan 1 - Mar 31: 100,000 × 3/12 = 25,000
Apr 1 - Sep 30: 120,000 × 6/12 = 60,000
Oct 1 - Dec 31: 240,000 × 3/12 = 60,000 (already reflects split)

But we need to adjust pre-split periods for the split!
```

**Correct Calculation (All Adjusted for Split):**
```
Jan 1 - Mar 31: (100,000 × 2) × 3/12 = 50,000
Apr 1 - Sep 30: (120,000 × 2) × 6/12 = 120,000
Oct 1 - Dec 31: 240,000 × 3/12 = 60,000

Weighted-average: 230,000
```

**Basic EPS:** $600,000 / 230,000 = $2.61

---

### Example 3: Loss from Continuing Operations

**Facts:**
- Loss from continuing operations: $(500,000)
- Income from discontinued operations: $200,000
- Net loss: $(300,000)
- Basic shares: 100,000
- Stock options: 10,000 (in the money)

**Analysis:**

When there's a loss from continuing operations:
- All potential common shares are **antidilutive**
- Use same share count for basic and diluted

**EPS Presentation:**
```
                                    Basic    Diluted
Loss from continuing operations    $(5.00)   $(5.00)
Income from discontinued ops         2.00      2.00
Net loss                           $(3.00)   $(3.00)
```

**Note:** Even though discontinued operations are positive, options remain antidilutive because the control number (continuing operations) is a loss.

---

## Presentation and Disclosure

### Income Statement Presentation

```
Earnings per share:
  Basic:
    Income from continuing operations        $X.XX
    Discontinued operations                   X.XX
    Net income                               $X.XX
  Diluted:
    Income from continuing operations        $X.XX
    Discontinued operations                   X.XX
    Net income                               $X.XX
```

### Required Disclosures

| Disclosure |
|------------|
| Reconciliation of numerators and denominators |
| Effect of potential common shares on income and shares |
| Securities excluded as antidilutive |
| Description of potentially dilutive securities |
| Transactions after balance sheet date affecting shares |

---

## Common Implementation Issues

### 1. Weighted-Average Calculation
- Not time-weighting properly
- Missing retroactive adjustments for splits
- Incorrect treatment of contingently issuable shares

### 2. Treasury Stock Method
- Using period-end price instead of average
- Including out-of-the-money options
- Not considering exercise price changes

### 3. Order of Dilution
- Not testing securities individually
- Adding antidilutive securities
- Wrong ordering of dilutive securities

### 4. Control Number
- Not using income from continuing operations
- Including all securities when there's a loss
- Different denominators for different line items

### 5. Stock Compensation
- Missing performance conditions
- Incorrect treatment of restricted stock
- Not considering forfeitures

---

## External Resources

- [FASB ASC 260](https://asc.fasb.org/)
- [KPMG: Handbook—Earnings Per Share](https://frv.kpmg.us/)
- [PwC: Financing Transactions Guide](https://viewpoint.pwc.com/)
- [Deloitte: A Roadmap to Earnings Per Share](https://www.iasplus.com/en-us)
- [EY: Financial Reporting Developments—Earnings Per Share](https://www.ey.com/)

---

## Navigation

← [Back to Presentation (200s)](README.md) | [Back to Main Guide](../../README.md)
