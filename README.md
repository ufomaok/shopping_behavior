# shopping-behavior

This dataset represents a hypothetical clothing site called Flashfash (based in Bengaluru, India) attempting to understand its US customer base. This project aims to analyze customer behavior through aggregate descriptive statistics and visualizations on American consumers. This project aims at discovering following: Discovering the "seasonality" of shoppers, discovering which demographic of shoppers purchase the most items, and deciphering which market strategies can be utilized to increase purchases. 

# Methods Used

Inferential Statistics
Data Visualization
T-Tests/P-Value

# Technologies Used

Python
Mathplotlib
Numpy
Scipy
Seaborn
Pandas
Jupyter
Power BI

## Observations 

This project consists of univariate analysis and bivariate analysis to analyze the composition of our customer dataset/analyze the relationship between variables associated with shopping behavior. Additionally, the pivot tables displaying popular colors per season helps us to infer that customers often select items based on colors popular to each season (e.g.: purchasing black item in the Winter or brown in the Fall).  One of the notable observations made in dataset is that customers split into the promo codes spent around $50 on average, while customers in the non-promo code group spent $30 average on items (boxplot/histogram distribution to provide visuals for differences in mean). After running t-test on two groups, we observed t-test statistic of 93.2464714350831, p-value of 0.0, and df of 3156.0. T-test statisic of this amount is very unusual, and likely suggests significant difference between two groups. Additonally, obtaining a p-value of 0.000... in the practical world is highly unlikely. In this case, based on the p-value observed, we can reject H0 (which states that there are no differences in purchase amounts between the promo-code and non-promo code group). Lastly, there is a proportional difference in individuals in the "High" Previous Purchase group who leave ratings (proportion: 0.4714) compared to those in the "Low" Previous Purchase group, who proportionally leave less ratings (proportion: 0.3325). It is possible that those in the "High" Previous Purchase group are more likely to leave reviews since they are more consistent buyers and possess a level of familiarity to the company's products. However, there might be a higher number of people in the "Low" group leaving reviews (840) compared to the "High group (298), as there might simply be a larger amount of people in population who are either new users to site, or who only purchase items from the site sparingly. 

Ultimately, analyzing customer shopping habits provides us with a glimpse into consumer behavior, helping us make more informed decisions on how to increase customer engagement, retention, and profit.
