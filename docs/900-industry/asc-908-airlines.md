# ASC 908: Airlines

> Specialized accounting for the airline industry including frequent flyer programs, aircraft, and maintenance.

## Overview

ASC 908 provides industry-specific guidance for airlines, addressing unique accounting issues including frequent flyer programs, aircraft acquisition and disposition, maintenance costs, and passenger revenue recognition. The airline industry has complex economics requiring specialized accounting treatment.

> **Core Principle:** Airline accounting must address the unique challenges of deferred revenue from loyalty programs, high-value long-lived assets, and complex maintenance arrangements.

---

## Scope

### Applies To

- Commercial airlines (passenger and cargo)
- Regional carriers
- Charter operators
- Entities operating aircraft fleets

### Key Accounting Areas

| Area | Key Issues |
|------|------------|
| **Revenue** | Ticket sales, frequent flyer, ancillary |
| **Loyalty programs** | Deferred revenue, breakage |
| **Aircraft** | Acquisition, depreciation, impairment |
| **Maintenance** | Heavy maintenance, reserves |
| **Leases** | Aircraft leasing |

---

## Passenger Revenue Recognition

### General Framework

Revenue recognized when transportation is provided (ASC 606 applies):

| Stage | Accounting |
|-------|------------|
| Ticket sale | Deferred revenue (air traffic liability) |
| Flight occurs | Recognize revenue |
| Ticket expires/unused | Recognize (breakage) |

### Air Traffic Liability

**Ticket purchase:**
```
Dr. Cash                                 $500
    Cr. Air Traffic Liability                    $500
```

**Flight occurs:**
```
Dr. Air Traffic Liability                $500
    Cr. Passenger Revenue                        $500
```

### Breakage (Unused Tickets)

Estimate and recognize revenue for tickets expected to expire unused:

**Methods:**
- Historical experience
- Proportional recognition
- At expiration

**Journal Entry—Breakage:**
```
Dr. Air Traffic Liability                $10,000
    Cr. Passenger Revenue                       $10,000
```

---

## Frequent Flyer Programs

### Overview

Airlines award miles/points to customers that can be redeemed for flights or other rewards.

### Accounting Treatment (ASC 606)

**Two Components:**
1. **Deferred revenue** for miles earned from flights
2. **Marketing expense** for miles earned from partners

### Miles Earned on Flights

**Recognize as separate performance obligation:**

**At ticket sale ($500 ticket, $50 allocated to miles):**
```
Dr. Cash                                 $500
    Cr. Air Traffic Liability                    $450
    Cr. Frequent Flyer Deferred Revenue          $50
```

**When miles redeemed:**
```
Dr. Frequent Flyer Deferred Revenue      $50
    Cr. Passenger Revenue                        $50
```

### Miles Sold to Partners

Credit card companies, hotels, and others purchase miles:

**Sale of miles to bank partner:**
```
Dr. Cash                               $1,000,000
    Cr. Frequent Flyer Deferred Revenue        $700,000
    Cr. Marketing Revenue (distinct services)   $300,000
```

### Breakage on Miles

Estimate miles that will expire unredeemed:
- Use historical redemption patterns
- Recognize proportionally as miles are redeemed
- Or at expiration

---

## Aircraft Accounting

### Acquisition

**Purchase:**
```
Dr. Aircraft                          $50,000,000
    Cr. Cash                                  $50,000,000
```

**Components to Capitalize:**
- Aircraft frame (airframe)
- Engines
- Interiors
- Navigation equipment

### Component Depreciation

Airlines often depreciate aircraft components separately:

| Component | Useful Life | Residual Value |
|-----------|-------------|----------------|
| Airframe | 20-30 years | 5-15% |
| Engines | 15-20 years | 10-20% |
| Interior | 5-10 years | 0% |

### Depreciation Example

**Aircraft cost: $50,000,000**

| Component | Cost | Life | Annual Depr |
|-----------|------|------|-------------|
| Airframe | $30,000,000 | 25 yrs | $1,080,000* |
| Engines | $15,000,000 | 20 yrs | $675,000* |
| Interior | $5,000,000 | 8 yrs | $625,000 |

*After residual value

### Aircraft Modifications

| Type | Treatment |
|------|-----------|
| **Betterments** | Capitalize |
| **Mandatory modifications** | Capitalize |
| **Interior refresh** | Capitalize, depreciate over life |
| **Repairs** | Expense |

---

## Maintenance and Overhaul

### Heavy Maintenance (D-Checks)

Major overhauls required by regulation every 6-10 years.

**Accounting Methods:**

| Method | Description |
|--------|-------------|
| **Capitalize & depreciate** | Capitalize cost, depreciate to next overhaul |
| **Deferral method** | Similar to capitalize |
| **Direct expense** | Expense as incurred (rare) |
| **Built-in overhaul** | Separate component at acquisition |

### Capitalize and Depreciate Approach

**Heavy maintenance performed ($5M):**
```
Dr. Aircraft (or Deferred Maintenance)   $5,000,000
    Cr. Cash/Accounts Payable                   $5,000,000
```

**Depreciation over 6-year cycle:**
```
Dr. Maintenance Expense                  $833,333
    Cr. Accumulated Depreciation                 $833,333
```

### Engine Overhauls

**Power-by-the-hour arrangements:**
- Pay third party based on flight hours
- Expense as incurred
- Maintenance covered by provider

```
Dr. Maintenance Expense                  $200,000
    Cr. Cash                                     $200,000
```

### Maintenance Reserves (Leased Aircraft)

**Monthly reserve payment:**
```
Dr. Maintenance Deposit                  $50,000
    Cr. Cash                                     $50,000
```

**When maintenance performed:**
```
Dr. Maintenance Expense                  $600,000
    Cr. Maintenance Deposit                     $600,000
```

---

## Aircraft Leases

### Classification Under ASC 842

Most aircraft leases are **finance leases** for lessees due to:
- Long lease terms
- Specialized nature of asset
- High value

### Sale-Leaseback Transactions

Common in airline industry for financing:

**If qualifies as sale:**
- Derecognize aircraft
- Recognize gain/loss (limited by ASC 842)
- Record right-of-use asset and lease liability

**If financing:**
- Keep aircraft on books
- Record financing liability

---

## Ancillary Revenue

### Types

| Revenue Stream | Recognition |
|----------------|-------------|
| Baggage fees | When service provided |
| Change fees | When processed |
| Seat selection | When flight occurs |
| In-flight sales | When delivered |
| Cargo | When transported |

### Bundled vs. Unbundled

**Bundled fare:** Allocate transaction price to performance obligations

**Unbundled (à la carte):** Recognize each element separately

---

## Fuel Hedging

### Common Practice

Airlines hedge fuel costs using:
- Futures contracts
- Options
- Swaps

### Hedge Accounting (ASC 815)

**Cash flow hedge of forecasted fuel purchases:**

**Hedge gain in OCI:**
```
Dr. Derivative Asset                     $500,000
    Cr. OCI—Fuel Hedge Gain                     $500,000
```

**Reclassify when fuel purchased:**
```
Dr. OCI—Fuel Hedge Gain                 $500,000
    Cr. Fuel Expense                            $500,000
```

---

## Special Charges

### Restructuring

Airlines frequently undergo restructuring:
- Fleet changes
- Route eliminations
- Workforce reductions

**Apply ASC 420 for exit costs**

### Impairment

Test aircraft for impairment when:
- Routes eliminated
- Fleet type retired
- Market conditions worsen

**Apply ASC 360 for long-lived asset impairment**

---

## Practical Example: Complete Flight Cycle

**1. Ticket Purchase ($300, includes 500 miles worth $15):**
```
Dr. Cash                                 $300
    Cr. Air Traffic Liability                    $285
    Cr. Frequent Flyer Deferred Revenue          $15
```

**2. Flight Operates:**
```
Dr. Air Traffic Liability                $285
    Cr. Passenger Revenue                        $285
```

**3. Miles Redeemed on Future Flight:**
```
Dr. Frequent Flyer Deferred Revenue      $15
    Cr. Passenger Revenue                        $15
```

---

## Disclosure Requirements

### Industry-Specific Disclosures

1. **Revenue recognition** policies
2. **Frequent flyer** program description
3. **Aircraft** fleet composition
4. **Maintenance** accounting policies
5. **Fuel hedging** activities
6. **Commitments** for aircraft purchases

### Example Disclosure

> **Passenger Revenue:** Passenger revenue is recognized when transportation is provided. Tickets sold but not yet used are included in air traffic liability. The Company estimates that a portion of tickets will expire unused and recognizes such amounts as revenue using historical experience patterns.
>
> **Frequent Flyer Program:** Miles earned by passengers are accounted for as a separate performance obligation. The Company allocates a portion of ticket revenue to miles earned based on standalone selling price. Miles sold to partners are recognized as deferred revenue for the travel component and as other revenue for marketing services.

---

## Common Audit Issues

1. **Air traffic liability** — Proper deferral and breakage estimation
2. **Frequent flyer** — Standalone selling price, breakage rates
3. **Depreciation** — Useful lives, residual values
4. **Maintenance** — Capitalization vs. expense
5. **Impairment** — Fleet and route changes
6. **Fuel hedges** — Documentation, effectiveness
7. **Lease classification** — Sale-leaseback treatment

---

## External Resources

- [FASB ASC 908](https://asc.fasb.org/)
- [AICPA Airline Industry Guide](https://www.aicpa.org/)
- [IATA Accounting Guidance](https://www.iata.org/)
- [SEC Industry Guides](https://www.sec.gov/)

---

## Navigation

← [Back to Industry (900s)](README.md) | [Main Guide](../../README.md)
