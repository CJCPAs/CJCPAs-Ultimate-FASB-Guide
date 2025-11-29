# ASC 940: Financial Services—Brokers and Dealers

> Specialized accounting guidance for securities broker-dealers operating in capital markets.

## Overview

ASC 940 provides accounting guidance specific to broker-dealers in securities. These entities operate in a highly regulated environment with unique accounting requirements for securities transactions, customer accounts, and proprietary trading activities. The guidance addresses fair value measurement, revenue recognition, and specialized financial statement presentation.

**Core Principle:**
> "Broker-dealers account for securities transactions at fair value and recognize revenues from trading, commissions, and related services as they are earned, with specialized presentation reflecting the unique nature of these operations."

---

## Scope

### Applies To:
- Securities broker-dealers registered with SEC
- Entities engaged in securities trading (proprietary)
- Entities acting as agents in securities transactions
- Introducing brokers
- Clearing brokers

### Does NOT Apply To:
- Banks and thrifts (ASC 942)
- Insurance companies (ASC 944)
- Investment companies (ASC 946)
- Entities not registered as broker-dealers

---

## Key Definitions

| Term | Definition |
|------|------------|
| **Broker-Dealer** | Entity engaged in the business of effecting securities transactions for customers or its own account |
| **Clearing Broker** | Broker-dealer that clears and settles securities transactions |
| **Introducing Broker** | Broker-dealer that introduces customer accounts to a clearing broker |
| **Proprietary Trading** | Trading in securities for the entity's own account |
| **Customer Accounts** | Securities and funds held on behalf of customers |
| **Fails to Deliver/Receive** | Unsettled securities transactions |
| **Net Capital** | Regulatory capital measure under SEC Rule 15c3-1 |

---

## Regulatory Framework

### Primary Regulators

| Regulator | Jurisdiction |
|-----------|--------------|
| **SEC** | Securities Exchange Act of 1934 |
| **FINRA** | Self-regulatory organization |
| **State regulators** | State securities laws |
| **CFTC** | If futures involved |

### Key Regulations

| Rule | Description |
|------|-------------|
| **SEC Rule 15c3-1** | Net capital requirements |
| **SEC Rule 15c3-3** | Customer protection rule |
| **SEC Rule 17a-5** | Financial reporting requirements |
| **FINRA Rules** | Conduct and operational rules |

---

## Financial Statement Presentation

### Statement of Financial Condition

Broker-dealers use a **statement of financial condition** (not balance sheet):

```
BROKER-DEALER INC.
Statement of Financial Condition
December 31, 20X1

ASSETS
  Cash and cash equivalents                    $  5,000,000
  Cash segregated under regulations               8,000,000
  Deposits with clearing organizations            2,500,000
  Receivable from broker-dealers                  3,200,000
  Receivable from customers                      15,000,000
  Securities owned, at fair value                25,000,000
  Securities borrowed                            12,000,000
  Fixed assets, net                               1,500,000
  Other assets                                    1,000,000
                                               ------------
    Total assets                               $ 73,200,000
                                               ============

LIABILITIES AND STOCKHOLDERS' EQUITY
  Payable to broker-dealers                    $  4,500,000
  Payable to customers                           18,000,000
  Securities sold, not yet purchased             10,000,000
  Securities loaned                              11,000,000
  Accrued expenses and other liabilities          2,200,000
  Subordinated borrowings                         5,000,000
                                               ------------
    Total liabilities                            50,700,000

  Stockholders' equity:
    Common stock                                  2,000,000
    Additional paid-in capital                    8,000,000
    Retained earnings                            12,500,000
                                               ------------
    Total stockholders' equity                   22,500,000
                                               ------------
    Total liabilities and equity               $ 73,200,000
                                               ============
```

### Unclassified Balance Sheet

Broker-dealers typically do **NOT** distinguish between current and noncurrent:
- Highly liquid nature of assets
- Short-term nature of most positions
- Regulatory focus on liquidity

---

## Securities Positions

### Securities Owned (Long Positions)

**Measurement:** Fair value through earnings

**Journal Entry—Purchase:**
```
Dr. Securities Owned                  $100,000
    Cr. Cash/Payable to Broker               $100,000
```

**Journal Entry—Fair Value Change:**
```
Dr. Securities Owned                   $5,000
    Cr. Trading Gains                          $5,000
(Unrealized gain)
```

### Securities Sold, Not Yet Purchased (Short Positions)

**Measurement:** Fair value through earnings (liability)

**Journal Entry—Short Sale:**
```
Dr. Cash                             $100,000
    Cr. Securities Sold, Not Yet Purchased   $100,000
```

**Journal Entry—Fair Value Change (Adverse):**
```
Dr. Trading Losses                     $3,000
    Cr. Securities Sold, Not Yet Purchased    $3,000
(Liability increases due to price increase)
```

### Netting Considerations

Generally, securities positions are presented gross unless:
- Legal right of setoff exists
- Intent to settle net

---

## Customer and Broker-Dealer Receivables/Payables

### Receivable from Customers

Includes:
- Unsettled customer trades
- Margin loans
- Customer debit balances

**Journal Entry—Margin Loan:**
```
Dr. Receivable from Customers         $50,000
    Cr. Customer Bank Loan                    $50,000
```

### Payable to Customers

Includes:
- Free credit balances
- Customer funds on deposit
- Unsettled sales proceeds due to customers

### Receivable from / Payable to Broker-Dealers

Includes:
- Unsettled interdealer trades
- Clearing deposits
- Securities lending balances

---

## Securities Borrowing and Lending

### Securities Borrowed

**Treatment:** Collateralized financing (not purchase)

**Journal Entry:**
```
Dr. Securities Borrowed (collateral asset)  $100,000
    Cr. Cash Collateral Paid                        $100,000
```

### Securities Loaned

**Treatment:** Collateralized financing (not sale)

**Journal Entry:**
```
Dr. Cash Collateral Received          $100,000
    Cr. Securities Loaned (collateral liability)   $100,000
```

### Presentation

- Securities borrowed: Asset (right to return securities for cash)
- Securities loaned: Liability (obligation to return cash for securities)
- Original securities remain on books

---

## Revenue Recognition

### Trading Revenue

| Component | Recognition |
|-----------|-------------|
| **Realized gains/losses** | Upon settlement of trade |
| **Unrealized gains/losses** | Fair value changes each period |
| **Mark-to-market** | Daily for regulatory purposes |

### Commission Revenue

**Recognition:** When trade is executed (transaction date)

**Journal Entry:**
```
Dr. Receivable from Customer          $10,100
    Cr. Commission Revenue                      $100
    Cr. Receivable (trade payable to customer) $10,000
```

### Other Revenue Sources

| Source | Recognition Timing |
|--------|-------------------|
| **Investment banking fees** | Per ASC 606—over time or point in time |
| **Advisory fees** | As services rendered |
| **Interest on margin loans** | Accrual basis |
| **Underwriting revenue** | When offering completed |
| **Market making spreads** | As trades executed |

---

## Underwriting Activities

### As Lead Underwriter

**Firm Commitment:**
```
Dr. Securities Owned                $10,000,000
    Cr. Payable to Issuer                    $10,000,000
(Purchase commitment)

Dr. Receivable from Selling Group    $8,000,000
    Cr. Securities Owned                      $8,000,000
(Allocation to syndicate members)

Dr. Cash                             $2,200,000
    Cr. Securities Owned                      $2,000,000
    Cr. Underwriting Revenue                    $200,000
(Direct sales and gross spread)
```

### Best Efforts

- Agent relationship
- Commission revenue only
- No inventory risk

---

## Net Capital Requirements

### Overview

SEC Rule 15c3-1 requires minimum net capital:
- Ratio-based or aggregate indebtedness method
- Designed to protect customers
- Prompt liquidation capability

### Net Capital Computation

```
NET CAPITAL COMPUTATION
As of December 31, 20X1

Net worth per GAAP                           $22,500,000
Add: Subordinated debt (qualifying)            5,000,000
                                             -----------
Tentative net capital                         27,500,000

Deductions:
  Non-allowable assets                        (1,200,000)
  Haircuts on securities positions            (2,500,000)
  Aged fails and other charges                  (300,000)
                                             -----------
Net capital                                  $23,500,000
                                             ===========

Minimum required net capital                 $ 1,000,000
Excess net capital                           $22,500,000
```

### Non-Allowable Assets

Assets deducted from net capital:
- Fixed assets
- Prepaid expenses
- Receivables from employees/affiliates
- Goodwill and intangibles
- Unsecured receivables

### Haircuts

Percentage deductions on securities based on:
- Type of security
- Maturity
- Market risk

| Security Type | Typical Haircut |
|---------------|-----------------|
| U.S. Treasuries | 0-6% |
| Agency securities | 1-7% |
| Municipal bonds | 7-15% |
| Corporate bonds | 10-30% |
| Equities | 15-30% |
| Options | Various formulas |

---

## Customer Protection Rule (Rule 15c3-3)

### Overview

Requires broker-dealers to:
1. **Segregate** customer fully-paid and excess margin securities
2. Maintain **reserve formula** deposits

### Possession and Control

Customer securities must be:
- In possession of the broker-dealer, OR
- In acceptable control locations

### Reserve Requirement

```
CUSTOMER RESERVE COMPUTATION

Credits:
  Free credit balances                        $18,000,000
  Customer securities value (fails to deliver)  2,000,000
  Other credits                                 1,000,000
                                              -----------
Total credits                                  21,000,000

Debits:
  Margin debit balances                        12,000,000
  Customer securities value (fails to receive)  1,500,000
  Other debits                                    500,000
                                              -----------
Total debits                                   14,000,000
                                              -----------
Reserve requirement                           $ 7,000,000
```

---

## Fair Value Measurement

### Hierarchy Application

| Level | Description | Examples |
|-------|-------------|----------|
| **Level 1** | Quoted prices in active markets | Listed equities, treasuries |
| **Level 2** | Observable inputs | Corporate bonds, derivatives |
| **Level 3** | Unobservable inputs | Illiquid securities, complex derivatives |

### Bid-Ask Considerations

- **Long positions:** Generally use bid price
- **Short positions:** Generally use ask price
- **Mid-market:** May be appropriate for dealer market makers

---

## Practical Examples

### Example 1: Proprietary Trading Day

**Facts:**
- Buy 1,000 shares XYZ at $50 (commission: $10)
- Sell 500 shares XYZ at $52 (commission: $5)
- End of day: XYZ trading at $51

**Purchase:**
```
Dr. Securities Owned (XYZ)            $50,010
    Cr. Receivable from Clearing Broker       $50,010
```

**Sale:**
```
Dr. Receivable from Clearing Broker   $25,995
    Cr. Securities Owned (500 shares)         $25,005
    Cr. Trading Gain                             $990
```

**Mark-to-Market (500 remaining shares):**
```
Fair value: 500 × $51 = $25,500
Book value: $25,005
Unrealized gain: $495

Dr. Securities Owned                     $495
    Cr. Trading Gain                            $495
```

---

### Example 2: Customer Margin Trade

**Facts:**
- Customer buys $100,000 securities
- Initial margin: 50% ($50,000)
- Commission: $500

**Trade Execution:**
```
Dr. Receivable from Customer          $50,500
Dr. Securities (Customer Account)    $100,000
    Cr. Payable to Clearing                   $100,000
    Cr. Commission Revenue                        $500
    Cr. Customer Securities Obligation        $49,500
(Note: Securities held for customer separate from firm)
```

---

### Example 3: Fails to Deliver/Receive

**Facts:**
- Sold securities that were not delivered by settlement
- Trade: $200,000

**Fail to Deliver:**
```
Dr. Cash (from buyer)                $200,000
    Cr. Fail to Deliver (Liability)          $200,000
```

**When Delivered:**
```
Dr. Fail to Deliver                  $200,000
    Cr. Securities Owned                     $195,000
    Cr. Trading Gain                           $5,000
```

---

## Financial Statement Disclosures

### Required Disclosures

| Area | Disclosure |
|------|------------|
| **Net capital** | Actual vs. required; excess |
| **Customer protection** | Reserve status |
| **Fair value hierarchy** | Level 1, 2, 3 breakdown |
| **Related parties** | Affiliated transactions |
| **Concentrations** | Credit risk, market risk |
| **Contingencies** | Litigation, regulatory matters |

### Regulatory Filings

| Filing | Frequency | Content |
|--------|-----------|---------|
| **FOCUS Report** | Monthly/Quarterly | Net capital, reserve |
| **Annual Audit** | Annual | GAAP financials + compliance |
| **Form BD** | As needed | Registration updates |

---

## Common Audit Issues

### Fair Value

| Issue | Consideration |
|-------|---------------|
| **Valuation methodology** | Appropriate for security type |
| **Level 3 inputs** | Reasonableness of assumptions |
| **Pricing services** | Controls and validation |

### Regulatory Compliance

| Issue | Audit Focus |
|-------|-------------|
| **Net capital** | Accurate computation |
| **Customer reserve** | Formula accuracy |
| **Possession/control** | Securities locations |

### Revenue Recognition

| Issue | Consideration |
|-------|---------------|
| **Trade date vs. settlement** | Proper timing |
| **Principal vs. agent** | Gross vs. net presentation |
| **Complex products** | Revenue allocation |

---

## Private Entity Considerations

### Non-Registered Entities

Some broker-dealer activities by non-registered entities:
- May be exempt (certain transactions)
- May require registration
- Consult securities counsel

### Smaller Broker-Dealers

| Consideration | Impact |
|---------------|--------|
| **Reduced complexity** | Fewer products, simpler operations |
| **Introducing vs. clearing** | Different capital requirements |
| **SIPC membership** | Customer protection fund |

---

## Recent Updates

| Update | Topic | Impact |
|--------|-------|--------|
| **SEC Modernization** | Enhanced reporting | Additional disclosures |
| **FINRA CAT** | Consolidated audit trail | Transaction reporting |
| **Reg BI** | Best interest | Customer relationship rules |
| **Form CRS** | Customer relationship summary | New disclosure requirement |

---

## External Resources

- [FASB ASC 940](https://asc.fasb.org/)
- [SEC Rules 15c3-1 and 15c3-3](https://www.sec.gov/)
- [FINRA Rules](https://www.finra.org/)
- [AICPA Audit and Accounting Guide—Brokers and Dealers](https://www.aicpa.org/)
- [SEC Form X-17A-5 Instructions](https://www.sec.gov/)
- [KPMG: Broker-Dealer Accounting Guide](https://frv.kpmg.us/)
- [PwC: Broker-Dealer Guide](https://viewpoint.pwc.com/)
- [Deloitte: Broker-Dealer Services](https://www.deloitte.com/)
- [EY: Broker-Dealer Industry Updates](https://www.ey.com/)

---

## Navigation

← [Back to Industry (900s)](README.md) | [Back to Main Guide](../../README.md)
