# Health-Insurance-Risk-Profitability-Analysis-Power-BI
### Project Overview
This project analyzes a health insurance dataset to understand the drivers of medical expenses, evaluate premium pricing adequacy, assess the financial impact of customer discounts, and identify the most profitable customer segments.

Using Power BI, the analysis transforms raw insurance data into an executive-level dashboard designed to support strategic decision-making for insurance underwriting, pricing strategy, and risk management.

The goal of the analysis is to answer key business questions that affect profitability, cost control, and customer segmentation within a health insurance portfolio.

### Business Questions
The analysis focuses on four key strategic questions:
1. Which customer characteristics most strongly influence medical expenses?
2. Are insurance premiums appropriately priced relative to customer risk and healthcare expenses?
3. Are customers receiving discounts more or less profitable?
4. Which customer segments generate the highest profitability?

### Dataset Description
The dataset contains customer-level insurance information with the following fields:
| Column               | Description                                           |
| -------------------- | ----------------------------------------------------- |
| Age                  | Age of the insured individual                         |
| Gender               | Customer gender                                       |
| BMI                  | Body Mass Index (indicator of health risk)            |
| Children             | Number of dependents covered                          |
| Region               | Geographic region of the customer                     |
| Discount Eligibility | Whether the customer qualifies for a premium discount |
| Expenses             | Total medical costs incurred                          |
| Premium              | Insurance premium paid by the customer                |

Each row represents a single insurance customer.

### Key Metrics Created
Several analytical metrics were created to support the analysis:
- Total Customers
- Total Premium Revenue
- Total Medical Expenses
- Profit = Premium − Expenses
- Loss Ratio = Expenses ÷ Premium
- Average Premium
- Average Medical Expense

These metrics allow the dashboard to evaluate both operational cost drivers and financial performance.

### Dashboard Structure
#### Page 1: Cost Drivers
Visuals include:
+ Scatter chart analyzing BMI vs Medical Expenses
+ Expense comparison across Age groups
+ Expense comparison across Regions
+ Expense comparison by Number of Children

This page highlights the key risk drivers that increase healthcare costs.

#### Page 2: Pricing Adequacy
Purpose: Evaluate whether premiums sufficiently cover customer healthcare expenses.
Visuals include:
- Combined line and column chart comparing Premium vs Expenses
- Loss Ratio analysis by region and customer segment

This helps determine whether the insurance company is underpricing high-risk customers.

#### Page 3: Discount Impact
Purpose: Assess the financial performance of customers who receive discounts.
Visuals include:
- Profit comparison between Discount vs Non-Discount customers
- Expense and Premium comparison by discount eligibility

This analysis evaluates whether the discount program supports or erodes profitability.

#### Page 4: Profitability by Customer Segment
Purpose: Identify the most profitable customer segments.
Visuals include:
- Matrix segmentation of customers by Age, Gender, and Children
- Treemap of profit contribution by region
- Waterfall chart showing profit drivers

This page identifies high-value customer groups and risk-heavy segments.

### Key Insights
+ BMI and Age are the strongest predictors of higher medical expenses.
+ Certain high-risk segments show expenses approaching or exceeding premium levels, suggesting pricing misalignment.
+ Customers receiving discounts demonstrate lower profit margins, indicating the discount strategy may require refinement.
+ Mid-age customers with moderate BMI generate the most stable profitability.

### Recommendations
1. Introduce risk-adjusted premium pricing based on BMI and age groups.
2. Monitor loss ratios at the segment level to prevent underwriting losses.
3. Redesign the discount program to target lower-risk customers.
4. Focus acquisition efforts on customer segments with stable loss ratios and positive margins.

### Tools Used
- Power BI (Data modeling, dashboard design, DAX measures)
- Power Query (Data transformation)
- Business analytics frameworks for profitability and risk segmentation.

### Skills Demonstrated
This project demonstrates the application of:
+ Business analytics
+ Financial analysis
+ Risk assessment
+ Data visualization for executive decision-making
+ Dashboard storytelling

### Project Outcome
The dashboard provides a structured framework for evaluating insurance portfolio performance and identifying opportunities to improve pricing strategy, risk management, and customer profitability.

The analysis demonstrates how operational data can be transformed into strategic insights for executive decision-making.
