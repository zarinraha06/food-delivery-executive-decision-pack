# Foodi Expansion Strategy: Operational Reliability & Unit Economics
# Executive Summary
This project analyzes weekly operational and financial data (Week 79 vs. Week 80) for Foodi, a food delivery platform operating in Dhaka. The objective was to provide a data-backed leadership recommendation on a critical business decision: whether to expand operations into 3 new Dhaka zones or pause expansion to fix existing reliability and margin issues.
# The Business Problem
Foodi's top-line metrics showed a seemingly positive trend: overall cancellation rates dropped significantly from 15.85% to 12.10%, and active customers grew by 6.25%. However, leadership needed to know if this performance was stable enough to support immediate territorial expansion without scaling operational failures and financial losses.
# Key Strategic Insights
By digging into zone-level performance and financial guardrails, the analysis revealed that the top-line improvements were masking critical underlying issues:
The Cost of Reliability is Unsustainable: The improvement in cancellation rates was financially engineered. Contribution Margin (CM) crashed to an unsustainable -BDT 65 per order to achieve the 12% cancellation rate.
Averages Mask Regional Crises: While the overall cancellation rate sits at 12.1%, specific zones are failing. Old Dhaka suffers from a 15.73% cancellation rate, and Badda-Rampura sits at 14.51%.
Diagnosed Bottlenecks: The data pinpointed the exact root causes in failing zones. For example, Badda-Rampura is bottlenecked by both a severe Rider Shortage (Supply Index: 0.75) and Restaurant Prep Issues (11.75%).
Data Integrity Blindspot: Identified an ~8% reconciliation gap (absence of 17,000 zone-wise cancellation data points), which poses a risk of hiding further bottlenecks in supposedly stable zones.
# Strategic Recommendations & Action Plan
Primary Decision: Hold expansion for 2 weeks. Scaling now would mean scaling negative unit economics. The focus must shift to achieving sustainable reliability first.
Targeted Monitoring & Intervention Plan:
Fixing Kitchen Delays: If zone-wise restaurant prep issues exceed 10%, temporarily hide the bottom 10% of restaurants during peak hours to reduce rider wait times.
Mitigating Rider Shortages: If the Rider Supply Index drops below 80% in zones like Badda or Gulshan, dynamically reduce the delivery radius to shed long-distance orders and protect core-zone reliability.
Protecting Margins: If Contribution Margin hits -BDT 65 per order in high-loss zones, immediately cap rider incentives and pause consumer promos.

