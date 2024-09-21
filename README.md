# Marketing-Campaign-A-B-Testing-Analysis
A detailed analysis of a marketing campaign's A/B test to evaluate the performance of three promotional strategies. The project includes data cleaning, exploratory data analysis (EDA), outlier removal, and statistical hypothesis testing using Python libraries such as pandas, seaborn, and statsmodels.


# Marketing Campaign A/B Testing Analysis

## Project Overview
This project analyzes the effectiveness of three different promotional campaigns (Promotion 1, 2, and 3) on store sales. The dataset includes various store attributes like promotion type, market size, and sales. Statistical techniques and visualizations are applied to assess the impact of each promotion.

## Key Features:
1. **Data Cleaning & Preprocessing:**  
   - Handled missing values and removed outliers to ensure a clean dataset.
   - Grouped and segmented data by promotion type and market size for detailed analysis.

2. **Exploratory Data Analysis (EDA):**  
   - Visualized sales distribution by promotion type using count plots, histograms, and boxplots.
   - Analyzed the relationship between sales and store age, market size, and weeks.

3. **Statistical Testing:**  
   - Conducted Shapiro-Wilk test to check for normality in sales distributions.
   - Applied Levene’s test to assess homogeneity of variances across promotions.
   - Used the Kruskal-Wallis H-test to compare sales distributions across promotions.

4. **Visualizations:**  
   - Sales distribution by promotions and market size.
   - Q-Q plots for sales data across different market sizes.
   - Boxplots for sales per week across promotions.

## Dataset
The dataset used for this analysis is named `WA_Marketing-Campaign(AB-Test).csv`, which contains the following columns:
- **Promotion:** Type of promotion applied (1, 2, or 3).
- **SalesInThousands:** Sales amount in thousands.
- **MarketSize:** Market size (Small, Medium, or Large).
- **AgeOfStore:** Age of the store in years.
- **Week:** Time period of the promotion.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/omar520/marketing-campaign-ab-test-analysis.git
   cd marketing-campaign-ab-test-analysis
