 AB Testing & Regression Analysis on Marketing Campaigns

This notebook analyzes marketing campaign performance across AdWords and Facebook Ads using exploratory data analysis, hypothesis testing, and regression modeling.

## Key Steps in the Analysis

1. Data Import and Cleaning

   * Uploaded and read marketing\_campaign.csv
   * Checked data types, summary statistics, and created categorical conversions

2. Exploratory Data Analysis (EDA)

   * Visualized distributions of clicks, conversions, and ad views for AdWords and Facebook
   * Created conversion categories (<6, 6–12, 12–18, >18) for comparison
   * Compared frequency of conversions across platforms using bar plots

3. Campaign Comparison

   * Facebook Ads showed more frequent high conversion days
   * AdWords often clustered around low-to-moderate conversion ranges

4. Correlation Analysis

   * Calculated correlation between clicks and conversions for both platforms
   * Facebook clicks showed stronger correlation with conversions

5. Hypothesis Testing

   * Compared mean conversions between AdWords and Facebook
   * Facebook proved more effective in generating conversions

6. Regression Analysis (Facebook)

   * Built a linear regression model with Clicks as predictor and Conversions as target
   * Model performance: R² Score around 76%, MSE reported for error measure
   * Visualized scatter plot with best-fit regression line
   * Predicted conversions for specific click counts (e.g., 50 and 80)

## Insights

* Facebook Ads outperform AdWords in driving conversions
* Conversions scale predictably with Facebook clicks, making it a better investment channel
* Regression modeling provides a reliable way to forecast conversions and guide ad spend decisions
