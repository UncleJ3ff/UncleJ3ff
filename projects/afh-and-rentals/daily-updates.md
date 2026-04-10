# Daily Real Estate Updates

The monitoring agent appends entries here each day.
Newest entries appear at the top.

---

<!-- Agent entries will be prepended below this line -->

## 2026-04-10 — Strategy Clarity + Local Listings

### Your Situation (Updated)
| Detail | Info |
|--------|------|
| Location | Federal Way, Renton, Des Moines, Tacoma (South King/Pierce County, WA) |
| Strategy | House hack — owner-occupy one unit, rent others |
| Loan Target | VA second-tier entitlement (existing AFH VA loan stays) |
| AFH Occupancy | 2/6 — actively marketing |

---

### VA Loan Strategy — Key Facts
- **You can use VA again** even with an active VA loan on the AFH
- Eligible for 2-4 unit properties with $0 down *if you owner-occupy one unit*
- With partial/remaining entitlement, you may need a small down payment — depends on COE
- **2026 VA Loan Limits (WA):**
  - Triplex: $1,289,050 (normal) / $1,933,600 (high-cost like King County)
  - Fourplex: $1,602,250 (normal) / $2,403,375 (high-cost)
- **Action required:** Pull your Certificate of Eligibility (COE) to calculate exact remaining entitlement and whether any down payment is needed

---

### Local Market Snapshot — South King / Pierce County
| Area | Multi-Family Inventory | Notes |
|------|----------------------|-------|
| **Tacoma** | 22+ active listings (Zillow), median $733K | Best inventory; 5.8%–6.2% cap rates found |
| **Federal Way** | Very limited (1 on Zillow) | Low inventory — watch closely |
| **Renton** | Some listings — check Redfin/Homes77 | 6.2% cap rate seen on one listing |
| **Des Moines** | Limited — check regularly | Between Federal Way & Renton |

### Notable Listings Found (April 10, 2026)
1. **Tacoma Triplex — $558,000** | 3 units × 2BR/1BA | Coin laundry, parking | Estate sale
2. **Tacoma NE Browns Point Triplex** | 5.8% cap rate | Renovated — LVP floors, SS appliances, in-unit W/D | 2 × 4BR/2BA + 1 × 5BR/2BA units — strong cash flow
3. **Renton multi-family** | 6.2% cap rate | Strong in-place income (size TBC — may be 6 units)

> Check current listings at: Redfin, Zillow, [soundmultifamily.com](https://www.soundmultifamily.com), [homes77.com](https://www.homes77.com/multi-family/)

### Action Items
- [ ] Pull COE — contact a VA lender (Veterans United, NewDay USA, or local WA lender)
- [ ] Set up Redfin/Zillow alerts for 3-4 unit properties in Tacoma, Federal Way, Renton, Des Moines
- [ ] Underwrite the $558K Tacoma triplex — run numbers at current VA rates (~6.5–7%)
- [ ] Fill in max purchase price in `real-estate-config.md`

---

## 2026-04-10 — Market Pulse Update

> **Config status:** City/region and price range not yet filled in. Specific deal listings unavailable until `real-estate-config.md` is completed. General market data below applies nationally.

### Multi-Family Market Overview
- **Cap rates:** Holding steady at **5.7%** — longest streak (7 quarters) in 25 years. Compression expected in late 2026.
- **Fundamentals model** suggests "true" cap rate should be ~5.1%, meaning current rates are slightly favorable for buyers.
- **Vacancy:** 6.7% nationally (up slightly from 6.4% in 2024) — manageable for a buy-and-hold strategy.
- **Supply cooling:** Only 297,000 new units added in 2025 (down from 371,600 in 2024). Moderating supply = better rent growth ahead.
- **Outlook:** Balanced supply-demand dynamics; steady rent increases likely — good environment for a triplex/quadruplex acquisition.

### Financing Snapshot (April 10, 2026)
| Loan Type | Rate Range | Notes |
|-----------|-----------|-------|
| **DSCR (residential)** | 6.0% – 7.99% | Baseline ~6.25% par; qualifies on rental income, not personal income |
| **Investment property (30yr fixed)** | ~7.06% – 7.56% | Based on national avg 30yr at 6.56% + ~0.5–1% investment premium |
| **FHA (owner-occupied, 3-4 unit)** | ~6.5% – 7.0% | Requires living in one unit; only 3.5% down needed |

### FHA Option — Key Facts for You
Since your VA loan is already used on the AFH, FHA is the lowest-barrier path **if you plan to occupy one unit**:
- **3.5% down** (need 580+ credit score)
- **2026 loan limits:** Triplex up to $837,700 (low-cost) / $1,933,200 (high-cost); Quadruplex up to $1,041,125 / $2,402,625
- **75% of rental income** from other units counts toward your DTI qualification
- Must pass **self-sufficiency test** (rental income must cover PITI)
- Must live there as primary residence for at least 1 year

### Action Needed
- [ ] Fill in city/region in `real-estate-config.md` to enable local listing searches
- [ ] Fill in price range and cap rate target
- [ ] Decide: owner-occupy one unit (FHA) or pure investment (DSCR)?

---

## 2026-04-10 — Initial Setup

Agent not yet activated. Fill in `real-estate-config.md` with your city, price range, and cap rate targets, then run `/loop 24h` to start daily monitoring.

**Next steps:**
1. Fill in `real-estate-config.md`
2. Start a new Claude Code session and run `/loop 24h` with the monitoring prompt
3. Check back here daily for new listings and market updates
