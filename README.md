# Data_Analisis_Panda_Seaborn

# Discount Data Analysis for Eniac: A Comprehensive Overview

## Case Study Context

Welcome to my second data project! I will keep working for Eniac —the e-commerce tech company— as a Data Analyst. This time I will work with internal data, which is not anonymized but more chaotic! The complexity of these tasks will require me to use Python.

This project presents a thorough analysis of Eniac's discounting strategy and its impact on revenue. The primary focus is on understanding how monthly revenue and the average discount rate influence sales performance in the years 2017 to 2018. Additionally, the study delves into the relationship between discounts, seasonal shifts, special events, product categories, and various pricing and quantity dynamics.

The company has high hopes for the possibilities that come with Data Analysis, and they are especially hopeful that my work can finally settle an ongoing debate: whether or not it’s beneficial to discount products.

- **Marketing Team Lead**: Believes that offering discounts is beneficial in the long run, improving customer acquisition, satisfaction, and retention.
- **Investors**: Concerned about aggressive discounts, pointing out that recent quarterly results showed an increase in orders placed but a decrease in total revenue. They prefer the company positions itself in the quality segment.

## Business Questions

My analytical and business skills are needed to provide clarity in the following aspects:

- How should products be classified into different categories to simplify reports and analysis?
- What is the distribution of product prices across different categories?
- How many products are being discounted?
- How big are the offered discounts as a percentage of the product prices?
- How do seasonality and special dates (Christmas, Black Friday) affect sales?
- How could data collection be improved?


## Tools Used

- **Python with Pandas** for data manipulation and cleaning
- **Seaborn** for statistical visualization

## Folder Structure

- `/Data`: Contains raw-data clean-data and quality data.
- `/Documentation`: Contains Notes and slides.
- `/Scripts`: Contains:
  - `/data-cleaning: orders, orderlines and products data_cleaning_with_pandas_`
  - `/data-quality: quality_assessment_sample`
  - `/analysis:Analisis _Seaborn Eniac_Project `


## Analysis Summary

The analysis reveals key insights into the impact of discounts on Eniac's sales performance:

1. **Monthly Revenue and Average Discount Rate**: There is a positive correlation between monthly revenue and the average discount rate. Periods with higher average discounts show an increment in sales performance.
2. **Seasonal Shifts and Special Events**: Discounts significantly influence sales during seasonal shifts and special events. Applying discounts during these periods increases the likelihood of generating sales.
3. **Discounts Across Product Categories**: Discounts vary based on the pricing of different product categories. Lower-priced items tend to have higher discounts.
4. **Effect on Revenue per Day by Category**: Discounts impact the revenue per day, with variations observed across different product categories, especially those with the highest discounts and most sold products.

## Data Cleaning

The dataset underwent a rigorous cleaning process to ensure data integrity:

- **Corrupted Database**: Identified and addressed issues that affected the overall integrity of the database.
- **Incongruent Data**: Resolved inconsistencies, mismatched, and/or duplicate data.
- **Double Dots Numbers**: Rectified anomalies in numerical values, focusing on duplicated or irregular decimal points.
- **Data Quality Concerns**: Mitigated issues affecting the reliability and completeness of the dataset.

## Data Improvement Recommendations

To enhance the dataset, the following recommendations are proposed:

- **Standardize Currency Values**: Implement a standardized approach for writing values in currency.
- **Avoid Missing Data**: Ensure completeness by addressing blank columns and rows.
- **Include Customer Data**: Integrate customer data to assess the impact of discounts on individual customer behaviors.
- **Additional Columns for Cost Calculation**: Include new columns for product costs, delivery values, and taxes to calculate profit margins.


## Conclusion

This analysis sets the foundation for optimizing Eniac's discounting strategy, with a focus on increasing revenue and aligning discounts with specific product categories and seasonal trends. The final presentation will be concise, engaging, and convincing, aiming to provide actionable insights for the company board.

- All major categories have a moderate correlation of discounts and revenues.
- Aggressive discounts do not increase the popularity of the product.
- Seasonal sales, especially those in November, have a strong impact on the yearly revenue.

### Issues Faced

- **Data Corruption**: The dataset had issues such as corrupted data, missing values, and double dots in numbers.
- **Missing Values**: I had to delete some columns that had significant missing data.
- **New Columns**: Created a new column to better calculate revenue.

### Further Considerations

- Do not offer very high discounts of over 25%, as revenues will not increase accordingly.
- Assign products to robust categories so that the discount strategy can be determined on the basis of the categories and tested with A/B tests.
- Low and medium range discounts achieve the best seasonal revenue.
