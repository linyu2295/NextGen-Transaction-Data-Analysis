# NextGen-Transaction-Data-Analysis

1. Analyze Yahoo users’ email transactional data, and based on the Google Taxonomy split the transactional data into two subsets:
  
  - Restaurant subset
  - Grocery subset
  
2. For each transaction, assign the level-3 Google Taxonomy as the transaction label:
   
   - E.g the label of product ‘Medium Hand Tossed Pizza’ is Pizza
   
3. Explore two subsets and construct similarity graph among the transaction labels to better understand the user preferences and the relationship between different transactions.

# Confidence

1. The confidence of X -> Y is defined by the conditional probability p(Y|X):

  - How often the rule X -> Y has been found to be true
  - Conf(X -> Y) = |# of users who purchased both label-X and label-Y products| / |# of users who purchased label-X products|
  
2. Confidence helps us understanding user preferences towards different types of food deals

3. Plotly Bar Chart link: https://nbviewer.jupyter.org/github/linyu2295/NextGen-Transaction-Data-Analysis/blob/master/Confidence_Bar_chart_plotly.ipynb#
