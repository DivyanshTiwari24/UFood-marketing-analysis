# UFood Marketing Campaign Analysis

## Business Overview
This project analyzes customer behavior, demographic data, and marketing campaign interactions for UFood, a leading food retail and delivery company. The goal of this analysis is to explore customer metadata, segment behaviors, and provide data-driven recommendations to optimize the marketing budget and maximize campaign ROI.

## Dataset
The dataset (`u_food_marketing.csv`) contains customer data mapping across three main areas:
* Customer Profiles: Age, education, marital status, income, and household structure.
* Product Spending (Last 2 Years): Wines, rare meat, exotic fruits, fish, sweets, and gold products.
* Channel Behavior & Campaign Response: Purchases made via web, catalog, and physical stores, as well as binary responses to 5 previous marketing campaigns.

## Key Insights
* The Age Paradox: Middle-aged customers (31–70) generate the most overall revenue but have the lowest campaign acceptance rates. Younger (23–30) and older (71–85) demographics accept campaigns at much higher rates.
* The "Child Penalty": There is a strong negative correlation between the number of children in a household and both overall spending and campaign acceptance.
* Channel Preferences: While in-store purchases generate the highest raw revenue, customers who frequently use the Catalog channel show a disproportionately high acceptance rate for marketing campaigns.

## Strategic Recommendations
1. Revenue Maximization Strategy: To drive immediate high-volume sales, target middle-aged, high-income customers with no children. Allocate campaign delivery to approximately 40% Catalog, 30% In-Store, and 30% Web.
2. Market Expansion Strategy: To capture untapped markets, design specialized campaigns for the 23–30 and 71–85 age brackets. Acquiring them now will grow the active user base and offset stagnant growth.

## How to Run
1. Clone this repository.
2. Ensure you have the required libraries installed (`pandas`, `numpy`, `matplotlib`, `seaborn`).
3. Open `Food_Marketing_Analysis.ipynb` and run the cells sequentially. Ensure `u_food_marketing.csv` is in the same directory.
