# Project 4: Superstore Business Health Analysis

## Project Overview
As a consultant hired to save a struggling superstore from bankruptcy, my task was to identify operational inefficiencies and profitability issues through advanced data analysis and visualization. The project focused on pinpointing profit centers, evaluating product strategies, proposing advertising opportunities, and analyzing return rates to inform critical business decisions.

Each business question was answered using individual, well-justified visualizations built from the Superstore dataset.

## Business Questions Answered
- Which combinations of dimensions generate the most profits and the biggest losses?
- Which specific products and subcategories should the superstore stop selling?
- Which states and months should the superstore target for advertising based on profitability?
- Which products and customers have the highest return rates?
- How do profit and return rates correlate across different operational dimensions?

## Key Tasks and Methodology
- **Profitability Analysis**:
  - Analyzed profitability across various dimension pairs (e.g., subcategory + region, shipping mode + product).
  - Identified top 2 profit drivers and top 2 loss drivers with supporting visualizations.
  - Recommended products and subcategories to discontinue or promote.
- **Advertising Strategy**:
  - Evaluated monthly profit trends across states.
  - Identified the three best state + month combinations for ad investments.
  - Calculated maximum recommended advertising spend using a 1/5 profit ratio.
- **Returned Items Analysis**:
  - Merged Returns data with Orders using a LEFT JOIN.
  - Created a calculated field to represent returns as 0 (no) or 1 (yes).
  - Visualized return rates by product and customer.
  - Analyzed average profit versus return rate by chosen dimensions (e.g., state, shipping mode).

## Key Findings
- **Profit and Loss Centers**:
  - Specific subcategory-region combinations were driving the largest profits and losses.
  - A small group of products accounted for disproportionately high losses.
- **Product Strategy**:
  - Recommended discontinuing certain underperforming subcategories while doubling down on top performers.
- **Advertising Opportunities**:
  - Identified three specific states and months with high profitability potential for targeted advertising campaigns.
- **Return Rate Risks**:
  - Flagged products and customers with abnormally high return rates.
  - Found correlations between high return rates and lower profitability across certain categories.

## Tools Used
- Tableau / Power BI (for all visualizations)
- SQL for data merging and transformations
- Data analysis and visualization best practices

## Deliverables
- Profitability visualizations by dimension combinations
- Product and subcategory recommendations
- State-by-month advertising recommendations and budget estimates
- Return rates analysis by product and customer
- Profit vs return rate correlation visualizations
- Executive-ready dashboard and presentation of findings

## Project Link
👉 [View Full Project Workbook or Dashboard](https://public.tableau.com/views/README_md3/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
