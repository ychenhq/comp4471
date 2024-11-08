# Customer Purchasing Behaviors Analysis

## Overview
This project explores and visualizes customer purchasing behaviors based on a Kaggle dataset. The initial data analysis is enhanced by combining the data with an additional dataset on customer age demographics. The goal is to identify key trends, segment customers, and gain insights about factors influencing purchasing habits.

## Datasets

### Primary Dataset
[Customer Purchasing Behaviors Dataset](https://www.kaggle.com/datasets/hanaksoy/customer-purchasing-behaviors): Contains data on customer demographics, income, purchase frequency, loyalty scores, and purchase amounts. Key fields include:
Age: Customer age group
Region: Customer's regional segment
Annual Income: Customer’s yearly income
Purchase Frequency: How often purchases are made
Loyalty Score: Customer loyalty metric
Purchase Amount: Amount spent per purchase
### Enhancement Dataset
[Customer Shopping Trends Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset): This dataset provides additional insights into customer age demographics, allowing us to refine our segmentation and conduct age-based analyses.


## Project Workflow
1. Data Visualization
   - Initial visualizations helped uncover patterns and trends in purchasing behaviors:

   - ***Scatter plot***: Displays the demographics for age, income distributions as to purchase amount.
    ![age_to_income](https://github.com/ychenhq/comp4471/blob/main/images/age_to_income.png)


   - ***Loyalty Trends***: Heatmaps to highlight age with loyalty patterns.
    ![loyalty_to_age](https://github.com/ychenhq/comp4471/blob/main/images/loyalty_to_age.png)

   - These visualizations provided a preliminary understanding of customer segments and potential factors influencing purchases.

2. Data Enhancement
To gain further insights, we merged the primary dataset with age-based data:

   - ***Enhanced Age Segmentation***: Enabled a more detailed analysis of purchasing trends across different age groups.The enlarged dataset improved understanding of age-specific behaviors, combining with data that includes more fields such as:
      Location: 1 of the 55 states
      Category: Footwear, Clothing etc.
      Season: Spring, Summer, Fall, Winter
      Color: Color of the item purchased
      Item Purchased: Jeans, Glasses, Sweater, Blouse etc.

   - ***Enhanced Visualizations***: With geopgrahic location, we can expand the visualization with geographs. Along with age data, we visualized age-income correlations, loyalty score distributions, gender and purchasing habits across different states.

4. Advanced Visualization and Insights
   - The combined data enabled us to produce more granular insights in ***Age-Income Correlations***, it provides better analysis of income levels and purchasing trends by age group.


# Key Findings
***Income and Frequency Correlation***: Positive correlation in certain age groups between income and purchase frequency.
***Regional Trends by Age***: Insights into regional shopping patterns for different age demographics.
Loyalty Scores by Age Group: Differences in brand loyalty scores based on age, indicating age-related tendencies in customer loyalty.

# Conclusion
This project provides an in-depth visualzation of customer purchasing behaviors by merging 2 datasets for comprehensive data analysis. The visualization dataset can guide marketing strategies and improve customer targeting.

## Future Work
Potential improvements include:

***Additional Data Sources***: Adding datasets related to customer preferences and buying behaviors.

***Predictive Modeling***: Using machine learning models to predict purchasing behaviors based on demographic information.

## Getting Started
***Prerequisites***

Python 3.7+

Jupyter Notebook

Libraries: pandas, matplotlib, seaborn, numpy

***Installation***

Clone this repository:

`git clone https://github.com/yourusername/customer-purchasing-analysis.git`

Download the datasets from Kaggle and place them in the data/ folder.

Install required libraries:

`pip install -r requirements.txt`

Open Customer_Purchasing_Analysis.ipynb in Jupyter Notebook.

Run each cell to load, visualize, and analyze the data.

