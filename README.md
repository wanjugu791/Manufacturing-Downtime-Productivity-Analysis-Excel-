# Manufacturing-Downtime-Productivity-Analysis-Excel-
This project analyzes manufacturing line performance to identify the key drivers of downtime and evaluate production efficiency across operators and products.  The objective is to move beyond basic reporting and uncover actionable insights that can improve operational efficiency.
# Business Questions
What is the overall production efficiency?
What factors contribute most to downtime?
How does downtime vary by operator?
Are inefficiencies driven by operators or system-level issues?
# Dataset
The dataset includes:
Production details (Product, Batch, Date)
Operator information
Start time, end time, and total production time
Minimum (ideal) batch time
Downtime categorized by factors (machine failure, adjustment, inventory shortage, etc.)
# Methodology
Efficiency Calculation:
Efficiency (%) = (Minimum Batch Time / Actual Time Taken) × 100
Analysis approach:
Pivot tables to aggregate downtime and efficiency
Breakdown of downtime by factor and operator
Comparison of efficiency across operators and products
Combined analysis of downtime vs efficiency
# Key Insights
Machine adjustment (332 mins) was the largest contributor to downtime—higher than machine failure
Over 60% of total downtime came from just three factors:
machine adjustment, machine failure, and inventory shortage
Operator efficiency showed minimal variation (63%–71%), indicating issues are process-driven rather than operator-driven
Dennis had the highest efficiency (71%) despite relatively high downtime, suggesting system or equipment constraints
Product efficiency varied significantly (44%–72%), highlighting inconsistencies in production processes
A comparison of downtime vs efficiency showed no strong negative correlation, reinforcing that inefficiencies are driven more by system and process issues than individual performance
# Recommendations
Based on the analysis, the most impactful improvements would be:
Standardize machine setup procedures to reduce adjustment time
Implement preventive maintenance scheduling to minimize machine failures
Improve inventory planning and material flow to reduce shortages
Investigate low-efficiency products for process optimization
