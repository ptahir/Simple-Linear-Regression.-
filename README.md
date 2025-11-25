Advertising Sales Prediction Using Simple Linear Regression 
This project analyzes the impact of TV, Radio, and Newspaper advertising spending on Sales using Simple Linear Regression. It includes three separate regression models and a full comparison of ROI and predictive performance.

The dataset used in this project: advertising.csv

Project Objectives

• Build three simple linear regression models 

• Evaluate each model using:
  o Slope (Coefficient) → ROI indicator 
  o R² Score → Predictive performance
  
• Visualize trends using scatter plots and regression lines 

• Compare all channels with a summary table and bar charts 

• Provide business insights and marketing recommendations

Dataset Description

The dataset contains advertising spending across three media channels and corresponding product sales. 

The file is included in this repository: advertising.csv

Technologies Used

• Python • NumPy • Pandas • Matplotlib • Scikit-Learn

Methodology

1. Load and inspect dataset
   
2. Train/test split (80/20)
  
3. Build three separate linear regression models
   
4. Compute slopes and R² scores
   
5. Visualize training & test results
 
6. Create comparison summary
  
7. Provide marketing insights

Model Results

1. Slope (ROI Indicator) The slope tells us how much Sales increase when you increase spending by 1 unit in that channel.
    
• Radio has the highest ROI; strongest increase in Sales per dollar spent

• TV has moderate ROI

• Newspaper has the weakest ROI

2. R² Score (Predictive Power) The R² score shows how well the model explains Sales variation.
   
• TV is the most reliable predictor of Sales

• Radio moderately predicts Sales 

• Newspaper barely predicts Sales

Visualizations

The notebook includes:

1. Scatter Plots with Regression Lines • Sales vs TV (train + test) • Sales vs Radio • Sales vs Newspaper
   
2. ROI Bar Chart Comparing slopes for all three channels
   
3. Predictive Power Bar Chart Comparing R² scores

Marketing Insights

1. Highest ROI: Radio advertising
   
• Highest slope

• Best return per dollar spent

2. Strongest Predictor of Sales: TV advertising
   
• Highest R² score

• Most reliable channel for forecasting

3. Weakest Channel: Newspaper advertising

• Very low ROI

• Almost no predictive value

Business Recommendations

Increase Radio advertising • Best immediate impact on Sales • Highest efficiency (ROI)

Maintain or moderately increase TV advertising • Strong predictor of future Sales • Reliable long-term investment

Reduce Newspaper advertising • Minimal impact • Low ROI

Conclusion 

This project demonstrates how Simple Linear Regression can be applied to marketing data to uncover insights about advertising effectiveness. It showcases essential skills for data analytics: 

• Model building • Statistical interpretation • Data visualization • Business-focused reporting • ROI-driven decision-making

This analysis can help businesses optimize their advertising budgets and improve revenue outcomes.





https://github.com/ptahir/Simple-Linear-Regression.-/blob/main/advertising.png

<p align="center">
  <img src="https://github.com/ptahir/Simple-Linear-Regression.-/blob/main/advertising.png
" width="800">
</p>
