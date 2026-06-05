# Commercial Real Estate Levered DCF Model
## Residential-to-Commercial Conversion 

Six-year pro forma leveraged DCF model underwriting the acquisition and repositioning of a residentially-zoned property for commercial use. Built for a real estate finance course project at the Darla Moore School of Business.

## Property Overview

| Detail | Value |
|---|---|
| Address | 909 W Tamarisk St, Phoenix, AZ 85041 |
| List Price | $345,000 |
| Square Footage | 2,004 sq ft |
| Current Zoning | R1-8 (Residential) |
| Proposed Use | Commercial Business |
| County | Maricopa |
| Holding Period | 6 Years |

---

## Investment Thesis

The property is acquired at residential pricing under R1-8 zoning and repositioned as a commercial retail space. R1-8 zoning designation allows for mixed-use redevelopment, enabling a conversion that captures the spread between residential acquisition pricing and commercial rental income of $26.13/sqft.

The conversion strategy increases projected rental income by 11.5% relative to residential use, while the going-in cap rate of 7.5% versus the terminal cap rate of 7.0% reflects expected stabilization and value creation over the 6 year holding period.

---

## Model Structure

| Tab | Description |
|---|---|
| Company | Borrower and business profile |
| Property | Property-level inputs and rental assumptions |
| Data | Market assumptions, rates, loan parameters, and sourced data |
| CF Projections | Six-year NOI projections, levered/unlevered cash flows, IRR, NPV, and DSR |

---

## Key Assumptions

| Assumption | Value | Source |
|---|---|---|
| Commercial Rental Rate | $26.13/sqft | PropertyShark: Maricopa County |
| Rental Growth Rate | 2.2% | General inflation rate (BLS, Dec 2023) |
| Vacancy & Loss | 5.0% of PGI | Standard |
| CapEx Allowance | 10.0% of EGI | Given |
| Managerial Expense | 10.0% of EGI | Estimated |
| Property Tax Rate | 4.7% | Maricopa County |
| Insurance | $2,359/yr | MarketWatch: Arizona Homeowners Insurance |
| Selling Costs | 5.0% of exit value | Givem |
| Going-In Cap Rate | 7.5% | Given |
| Terminal Cap Rate | 7.0% | Given |
| Discount Rate (Unlev) | 7.0% | Given |
| Discount Rate (Lev) | 9.0% | Given |
| LTV | 75% | Given |
| Commercial Mortgage Rate | 5.875% | Market (Forbes Advisor) |
| Amortization | 30 Years | Given |
| Upfront Financing Costs | 3.0% | Given |

---

## Market Research Summary

**Rental Market:** Phoenix residential rents declined approximately 4.5% YoY in 2023. The model uses the general inflation rate of 2.2% for commercial rent escalation, consistent with stabilized retail leasing assumptions in the Phoenix market.

**Property Taxes:** Maricopa County passed the largest tax rate cut in its history in January 2023, providing a favorable tax environment despite rising property values.

**Mortgage Rate:** Commercial mortgage rates started at 5.24% at time of analysis, with the model using 5.875% to portray a conservative assumption.

**Economic Outlook:** Phoenix economy projected to strengthen with recent tax cuts, federal funds rate reduction from 5.33% to 4.6%, and government focus on job creation and housing.

---

## Financial Results

| Metric | Value |
|---|---|
| Levered IRR | 39.6% |
| Unlevered IRR | 19.0% |
| NPV (Unleveraged, 7%) | $192,083 |
| NPV (Leveraged, 9%) | $173,418 |
| Debt Service Coverage Ratio | 1.94x |
| Equity Multiple | 4.20x |
| Offer Price | $345,000 |
| Exit Value (Terminal) | $568,011 |
| Total Lender Return | $18,367/yr |
| Loan Proceeds | $250,988 |

---

## Cash Flow Summary

| Year | NOI | Levered CF |
|---|---|---|
| 0 (Acquisition) | : | ($94,013) |
| 1 | $35,662 | $17,294 |
| 2 | $36,446 | $18,079 |
| 3 | $37,248 | $18,881 |
| 4 | $38,067 | $19,700 |
| 5 (Exit) | $38,905 + $568,011 | $319,745 |

---

## Technical Highlights

**Financial Modeling**
- Six-year levered and unlevered pro forma DCF
- Direct capitalization exit methodology (NOI Year 6 ÷ Terminal Cap Rate)
- NNN lease structure: recoveries (property tax + insurance) kept positive on income side
- NOI → Levered cash flows with full debt service and loan payoff at exit
- Named ranges throughout for auditable formula architecture

**Credit & Underwriting**
- Debt Service Coverage Ratio (DSR) analysis
- LTV-based loan sizing with upfront financing cost deduction
- Remaining loan balance (HP Balance) calculated via PV function
- Going-in cap rate implied value check against acquisition price

**Market Analysis**
- Benchmarked going-in cap rate (7.5%) against Maricopa County comparables
- Sourced rental rates from PropertyShark commercial market data
- Incorporated Phoenix inflation, tax, and mortgage rate environment
- Identified conversion premium between residential acquisition and commercial income

**Tools**
- Microsoft Excel - dynamic formulas; IRR, NPV, PMT, PV, MIN, NOI functions
---

## Risk Analysis

| Risk | Description | Mitigant |
|---|---|---|
| Rezoning Execution | R1-8 zoning approval for commercial use not guaranteed | Cap rate spread compensates for conversion risk; once stabilized property should re-rate |
| Lease-Up Risk | Commercial conversion assumes immediate full occupancy | 5% vacancy factor applied throughout holding period |
| Rental Growth | Phoenix market showed -4.5% residential rent decline in 2023 | Model uses conservative 2.2% commercial escalation tied to inflation |
| Interest Rate Risk | Rising rates increase debt service burden | Fixed-rate 30-year commercial mortgage locks in 5.875% |

---

## Disclaimer

*Built independently; Property data sourced from publicly available market data. All projections are estimates based on stated assumptions. Not investment advice.*

## License

© 2025 Kristen Gallagher. All rights reserved.

This work is made available for viewing and reference purposes only. Reproduction, distribution, modification, or use of this work without explicit written permission from the author is strictly prohibited. Any reference to this work must include appropriate credit to the author.
