# Daily Real Estate Updates

The monitoring agent appends entries here each day.
Newest entries appear at the top.

---

<!-- Agent entries will be prepended below this line -->

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
