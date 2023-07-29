# A/B Testing for Store Promotions
### Introduction
This project focuses on applying the famous decision-making method, A/B testing, to evaluate the impact of different promotions on sales volumes in a retail company. By comparing multiple promotions and analyzing the data, we aim to provide data-driven insights and make recommendations to optimize sales strategies.

### Business Problem and Objectives
The primary goal of this project is to determine whether one or more promotion types outperform others in terms of their impact on sales. We seek to identify statistically significant differences between promotions to guide the company's decision-making process. The dataset includes important information such as Market ID, Market Size, Location ID, Age of Store, Promotion Type, Week Number, and Sales.

### Exploratory Data Analysis
The initial step involves exploring the dataset to gain insights and identify relevant patterns. We check for null values, outliers, data distributions, and data types. The data includes three different promotions run by the company, which influences the choice of statistical tests.

![output](https://github.com/YusufGulcan/A-B_testing/assets/105684729/debba6dd-fc58-4a87-9cf5-2961cdcd0840)

### Statistical Tests
Based on the number of categories to compare and the distribution of the sales data, we employ different statistical tests. For instances where there are only two categories (variables) to compare, we use the independent Student's t-test and the Mann-Whitney U test. When there are more than two variables, we turn to the ANOVA and the Kruskal-Wallis test.

![Statistical Tests for AB Testing (2)](https://github.com/YusufGulcan/A-B_testing/assets/105684729/2d2c9dc5-ef49-483d-84e6-7256e16b2398)

### Business Insights and Recommendations


The analysis uncovers valuable insights that form the basis for business recommendations. Here are some key findings and recommendations:

Stop or Modify Promotion2: Promotion2 is underperforming compared to other promotions. It is advisable to either cease operations under this promotion or modify its offers and deals to try a new approach.

Allocate Resources to Successful Promotions: Promotions that yield higher revenue, such as Promotion1 and Promotion3, should be prioritized for resource allocation to achieve efficiency and growth.

Investigate Underperformance: In-depth analysis is crucial to identify the root causes behind underperforming promotions. Understanding these factors helps optimize decision-making processes.

Derive Alternative Promotions: Learn from both mistakes and successes in the existing promotions to create better alternative strategies.

Take Advantage of Niches: Utilize insights into specific subclasses within the data to capitalize on unique opportunities in specific market segments or customer groups.

Communication and Reporting: Share the analysis findings throughout the company to foster a data-driven approach and improve overall organizational performance.

### Acknowledgments
This project was carried out to understand the impact of different promotions on sales volumes and provide data-driven recommendations for decision-making. The code and analysis were performed by Yusuf Gulcan and inspired by real-world business scenarios.

Feel free to explore the notebook and adapt the analysis for your own projects and business needs!
