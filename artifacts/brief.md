# Bay Area Wages vs. Rent — Summary

**Question.** Did wages keep up with rent in the San Francisco–Oakland–Hayward metro, and what happened to affordability?

**Data.** BLS/QCEW wages (FRED ENUC418640510SA); CPI-U All Items (FRED CUUSA422SA0); CPI-U Rent of Primary Residence (FRED CUUSA422SEHA). Monthly CPI averaged to quarters; wages are quarterly; base index = 2015-01-01.

**Method.** Align to the same quarters; compute indices (2015=100), real wages (deflated by local CPI), wage-to-rent ratio, YoY, and CAGRs. Simple Δlog regression of wages on rent with robust SE.

**Headline findings (1990-03-31 → 2024-09-30).**
- Wages: **395.1%**
- Rent CPI: **242.0%**
- Real wages: **84.6%**
- Wage-to-rent ratio: **44.8%**

**Interpretation.** If wages rose faster than rent CPI, affordability pressures eased; if rent CPI outpaced wages, they tightened. The wage-to-rent index summarizes affordability in one line (↑ is better).

**Limits.** CPI-Rent is a price index for renters (not listing medians like Zillow ZORI). QCEW wages include bonuses/stock; Bay Area quarters can spike. Descriptive analysis; correlation ≠ causation.

**Figures.** See `figures/sf_wage_vs_rent.png`, `figures/sf_real_wage_vs_rent.png`, `figures/sf_yoy.png`.
