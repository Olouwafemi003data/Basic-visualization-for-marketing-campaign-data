# Basic-visualization-for-marketing-campaign-data

### Objective
Show each SQL finding with the right chart type, so a non-technical reader sees the business message at a glance.
Input : 	analysis.db (table sales, created in notebook 02)
sns.set_theme(style="whitegrid") with consistent colors, titles, axis labels, value labels and annotations

## Chart	Type	Business question	Takeaway
1	Response rate by education	Bar chart	Which education level responds best?

2	Spending and response by income quartile	Bar + line	Do wealthier customers spend and respond more?

3	Spending by product category	Horizontal bar	Which categories weigh most?	

4	Purchases per channel by household profile	Grouped bar	Does the household change how people buy?	

5	Acceptance rate by campaign	Bar chart	Which campaign worked best?	

Why no pie chart: composition is shown with 6 categories, and the assignment limits pie charts to 5 or fewer.

### How to run
Run 01 and 02 first, then all cells of 03_visualizations.ipynb.
