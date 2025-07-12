Revenue Leakage Analysis in Retail Banking
This project identifies hidden sources of revenue loss for a retail bank using simulated ICICI-style customer, transaction, and account data. It highlights fee waivers, interest underperformance, and inactivity among premium customers.

Objective
To analyze banking data and uncover areas where expected revenue is not being realized, using Python (pandas), and visualize the findings.

 Tools & Technologies
- Python (pandas, seaborn, matplotlib)
- Google Colab
- SQL-style joins and filters
- Business logic simulations

Key Analyses
1. Fee Leakage
- Detected transactions where **fee was waived or undercharged**
- Total ₹ lost computed from fee_expected vs fee_charged

2. Interest Revenue Loss
- Identified accounts where **interest paid > expected**
- Calculated annual revenue loss per account

3. Inactive Premium Accounts
- Found “Premium Savings” customers with **no transactions in last 60 days**
- Flagged accounts for potential downgrade or engagement

Visualizations
- Bar chart: Leakage by type (fee, interest)
- Pie chart: Proportional loss
- Top 5 customers by fee leakage

Outcome
Banking data can reveal operational inefficiencies and overlooked revenue gaps. This project provides a clear framework for revenue recovery initiatives.
