# Machine Learning Project - Unsupervised Learning
## Project Overview/Goal
This project focuses on applying unsupervised learning techniques to a real-world dataset, "Wholesale Data". The primary objective is to use these techniques to gain insights from the data and effectively communicate these findings through data visualization tools.
The ultimate objective of this project is to extract valuable insights from the "Wholesale Data" dataset. These insights will be conveyed to stakeholders using apt visualizations and metrics. This approach empowers stakeholders to make informed business decisions based on the questions posed.

## Process
1. Exploratory Data Analysis and Pre-processing:
- Import and clean the dataset.
- Analyze and visualize relationships among variables.
- Address missing values and outliers.
- Implement relevant feature engineering techniques.

2. Unsupervised Learning:
- Apply k-means clustering, hierarchical clustering, and PCA to the "Wholesale Data" dataset.
- Identify underlying patterns and group similar data points together.
- Determine the optimal number of clusters.
- Try different variables to see if there were better ways of clustering.
- Present insights through effective data visualizations.

## Results
- Using KMeans and hierarchical clustering, I identified customer segments based on the purchasing behavior across the different product categories. KMeans yielded clusters with varying spending patterns, however, there seemed to be no significant clustering around the features in 2 dimensions. Perhaps there may be a way to tackle the outliers in more details with more time.
- After removing Detergents_Paper (as correlation to Grocery is high), Looking at the PCA, I found that milk contributes to about 73.68% of predictive power to groceries. This means that people that purchase Groceries are also likely to purchase Milk items. Using the heatmap and the correlation matrix, this supports the findings.
- Outliers could present some challenges when trying to review the spending behavior. We could possibly remove these and see if the trend/behaviors become clearer, particularly for other groups like Fresh products.
- The clusters of customers offers valuable insights for business strategies and decision-making. Businesses can tailor marketing campaigns and product offerings to cater to the preferences of specific customer segments. Through these identified clusters, we noticed that different customer segments show distinct spending behaviors. This implies that various customer groups might respond differently to promotions, discounts, or changes in product availability.

## Challenges
I had some issues surrounding the proper cleaning and pre-processing techniques used. After review, it was recommended to choose and narrow down to more specific methods like Standardize vs Normalize and PCA vs RandomForest.
Some of the code was redudant so I combed through and cleaned it up as best as possible.

## Future Goals
If I had more time with this, I'd dive deeper into all the respective methods and test more combinations together. 
