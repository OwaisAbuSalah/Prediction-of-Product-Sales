
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

## 🔍 Model Explainability

### 📈 Linear Regression
![تنزيل (1)](https://github.com/user-attachments/assets/890e5230-c5d9-408a-acb8-a9bece6526f3)


**Top 3 Most Impactful Features:**
- `num_Item_MRP`: Higher prices increase sales value, even with fewer items sold..
- `cat_Outlet_Identifier_OUT027`: This store sells more, likely due to a good location or size.
- `cat_Outlet_Type_Supermarket Type3`: These outlets perform better, possibly from more variety or traffic.

### 🌳 Random Forest (Tuned)
![بالىرلا](https://github.com/user-attachments/assets/39c9fed8-cbbf-47b1-b64d-f731a84e20e2)


**Top 5 Important Features:**
- `num__Item_MRP` : Higher item prices often lead to higher sales value.
- `cat__Outlet_Type_Grocery Store` : Grocery stores tend to sell more than other outlet types.
- `cat__Outlet_Identifier_OUT027` : This specific outlet usually has high sales.
- `num__Item_Visibility` :Items that are easier to see get bought more.
- `num__Item_Weight` :Heavier items may suggest bigger packages, attracting buyers.

### ✅ Final Recommendations
- `Set Smart Prices` : The price of an item (MRP) is the biggest factor in sales. Try discounts or special offers to boost sales. 
- `Focus on Grocery Stores` : Grocery store outlets sell more. You might want to open more of them or improve the ones you already have.
- `Learn from Top Stores` : Some outlets (like OUT027) do really well. Look at what they’re doing right and use those ideas in other stores.
- `Make Products Easy to See` : Items that are easier to see sell better. Put popular items in clear, front-facing spots.



  

    

    

