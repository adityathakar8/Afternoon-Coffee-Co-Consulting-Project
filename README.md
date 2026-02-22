# Afternoon-Coffee-Co-Consulting-Project

Afternoon Coffee: Business Profitability Optimization with Python

This project is a data-driven consulting case study focused on optimizing operations for Afternoon Coffee, a local coffee shop in Gainesville, Florida. I leveraged Linear Programming (LP) through the PuLP library to transform qualitative business stresses into a quantitative roadmap for profit.

The Business Problem

After interviewing the owner, Alex, I identified several critical bottlenecks affecting his bottom line. During the weekdays, Alex struggles with inventory perishability and finding the "sweet spot" for prep quantities. He noticed that items are consistently left over after closing, leading to unnecessary waste.

On Saturdays, the shop is "raided" by a local run club at 9 AM. This surge causes demand to spike 2x to 3x above normal levels. Alex mentioned running out of high-demand items like ceremonial matcha and healthy sandwiches, leaving potential revenue on the table.

Methodology: Linear Programming with PuLP

I built an optimization model to find the most profitable product mix while respecting real-world constraints. Every menu item was modeled not just by its price, but by its "Labor Cost" in minutes and its equipment requirements.

The model solves for:

Labor Capacity: Balancing Alex’s solo shifts against the overwhelmed duo shifts during peak hours.

Wait Time Constraints: Prioritizing speed to meet Alex's "two-minute" rule for customer retention.

Inventory Management: Setting "Loyalty Floors" for regulars and "Perishability Ceilings" to minimize 3 PM waste.

Key Insights and Results
The Saturday Labor Solution

Alex was unsure if hiring a 4th person for the Saturday rush would be worth the cost. My model proved that a 4th employee generates $191.00 in additional gross profit by unlocking high-margin specialty drinks and sandwiches. Even after paying for the labor, Alex sees a net profit increase of $146.00 every Saturday.

Weekday "Sweet Spot"

The model revealed that hiring extra help during the week is actually counter-productive. Instead, the "Sweet Spot" involves a specific prep list that maintains a 20% Breather Buffer. This allows Alex to handle cleaning and stocking without the extra overhead of another salary.

The Gainesville Weather Edge Case

Gainesville's unpredictable weather often messes up Alex's batched food orders. If it rains at the last moment, the run club doesn't show up and the prepped food goes to waste. I advised a Hybrid Prep Strategy using the extra Saturday labor to assemble sandwiches "on-demand" only if the radar is clear.


Final Verdict
By moving from "gut feelings" to data, this project provides Alex with a clear operational guide. He now knows exactly when to hire, what to prep, and how to protect his profit from the trash can.
