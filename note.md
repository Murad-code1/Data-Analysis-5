## Methodology

* Loaded the `vgsales.csv` dataset using pandas
* Inspected dataset structure and identified missing values
* Removed rows with missing **Year** to ensure accurate time-based analysis
* Filled missing **Publisher** values with `"Unknown"`
* Performed aggregations using `groupby()` for genres, platforms, and publishers
* Built visualizations to analyze trends and comparisons
* Compared regional sales across **NA, EU, and JP**

---

## Business Insights

**Platform Lifecycle Impact:**
Video game sales strongly depend on console lifecycle stages. Platforms like PS2 and Wii reached peak performance during their mid-lifecycle when game libraries were mature. → Focus releases during peak lifecycle periods to maximize sales potential.

**Regional Preference Differences:**
Japan shows significantly different behavior compared to NA and EU. While Western markets prefer Action and Shooter games, Japan favors more localized genres like RPGs. → Adapt game design and marketing strategies based on regional preferences.

**Post-2008 Market Shift:**
Global sales peaked around 2008 and then stabilized or declined. This shift may be driven by digital distribution, mobile gaming growth, and market saturation. → Companies should prioritize digital ecosystems and new revenue models.

**Publisher Dominance vs Market Fragmentation:**
Although major publishers like Nintendo lead total sales, the market remains highly fragmented with many smaller contributors. → Strong IP and brand identity are key to maintaining long-term dominance.

