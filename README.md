
![FUqHEVVUsAAbZB0-1024x580-1](https://github.com/user-attachments/assets/f2c8d3b5-da3f-4478-a65d-26e2ae46f19d)
# Prediction of Product Sales
## sales prediction for food items sold at various stores
Owais AbuSalah

This project focuses on analyzing and predicting sales for a retail company using historical sales data. The dataset, sales_predictions_2023.csv, contains detailed information about various products sold across multiple outlets, including attributes such as product type, price, visibility, and outlet characteristics. The goal is to leverage this data to build predictive models that can forecast future sales, identify key factors influencing sales performance, and provide actionable insights for strategic decision-making.

## Data Link:
sales predictions 2023 https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view

For this dataset, there were 8523 rows and 12 columns.

## Data Dictionary
![ffgfff](https://github.com/user-attachments/assets/0d33e0e6-7304-4b8a-ac00-abd9c9bbfa8f)

## To prepare this data, the data was cleaned, and the following processes were performed:
### Exploratory Data Analysis
    - During the exploratory data analysis, a histogram was visualized for each numeric datatype column.
    - Also, a boxplot was visualized for each categorical column.
## Explanatory Visuals
  ![imp](https://github.com/user-attachments/assets/730f63ba-cac3-4474-b489-ba58e8612f74)

   * Most items have an MRP within the range of 100-200, which could indicate this price range is popular or competitive in the market.
     
   * Fewer items are priced very low (below 50) or very high (above 200), suggesting these price points might be less common or targeted towards niche markets.

![qqq](https://github.com/user-attachments/assets/a3731ec9-88b7-44f0-9217-41061ef1e2dd)

* The majority of sales values fall between 0 and 3000, indicating that most products have relatively low sales.

* There are fewer occurrences of very high sales, suggesting that only a few products achieve significantly high sales.
    
![ؤبايل](https://github.com/user-attachments/assets/2026866f-d1d0-4713-92a1-7c561fbf7271)


* The median sales for each category are relatively similar, but there is variability in the interquartile ranges.

* Some categories, such as Starchy Foods, Breads, and Seafood, show a wider spread, indicating greater variability in sales.

* Many categories have numerous outliers (small circles above the whiskers), indicating that certain products achieve significantly higher sales than others in the same category.

* This visualization helps identify which product types have more consistent sales and which have a higher chance of extreme sales fluctuations.

![nfg](https://github.com/user-attachments/assets/8d8146bf-735c-4b47-8bbc-e67632152886)

* The store or dataset appears to have a strong focus on fresh produce ("Fruits and Vegetables") and convenience items like "Snack Foods."

* Categories like "Seafood" and "Breakfast" items are less represented, suggesting they might be niche or less frequently purchased items in this context.

* Household items are also a significant category, indicating a broad range of non-food essentials.

![yyy](https://github.com/user-attachments/assets/56854b93-d0f6-42d7-b992-93bbdd7b4f4a)

* The most significant factor influencing Item_Outlet_Sales appears to be Item_MRP, indicating that pricing strategy plays a crucial role in sales performance.

* Factors like Item_Weight, Item_Visibility, and Outlet_Establishment_Year have minimal impact on sales, based on this dataset.

  

    

    

