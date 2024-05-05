# Analyzing-Amazon-Sales-data
"Analyzing Amazon Sales Data" is a project focused on leveraging ETL techniques to extract, transform, and load Amazon sales datasets. It aims to uncover sales trends on a month-wise, year-wise, and yearly-month-wise basis.
## Problem Statement:
Sales management has gained importance to meet increasing competition and the need for improved methods of distribution to reduce cost and to increase profits. Sales management today is the most important function in a commercial and business
enterprise.
Do ETL: Extract-Transform-Load some Amazon dataset and find for me Sales-trend -> month-wise, year-wise, yearly_month-wise. Find key metrics and factors and show the meaningful relationships between attributes.
## Dataset:
Find the dataset in the given [link](https://drive.google.com/drive/folders/1c4XtmLWR-3tmwv17eRv5YsdoScC_kTxr).

**Technologies:**  Data Science

**Domain:** E-commerce

**Tools:** Tableau Public

**Language:** Python

## Approach
The main goal of the project is to find key metrics and factors and then show meaningful relationships between them based on different features available in the dataset.
```
Data Collection : Imported data from various datasets available in the project using Pandas library. 

Data Cleaning : Removed missing values and created new features as per insights. 

Data Preprocessing : Modified the structure of data in order to make it more understandable and suitable and convenient for statistical analysis. 

Data Analysis : I started analyzing dataset using Pandas, NumPy, Matplotlib and Seaborn. 

Data Visualization : Plotted graphs to get insights about dependent and independent variables. Also used Tableau for data visualization.
```
# Data Collection, Data Cleaning, and Data analysis:
[Amazon_sales_data_analysis.ipynb](https://colab.research.google.com/drive/18W2lTUZ24NaYHKnY_ZpdJCMhBo-3OpI8?usp=sharing)

# Data Visualization:
## Correlation between dataset

![1111](https://github.com/Swagatika-Meher/Analyzing-Amazon-Sales-data/assets/114692581/a49382fc-454e-4693-a0f7-131c5345758e)

1. Total Revenue and Total Profit have a high Pearson correlation coefficient, indicating a strong relationship between the two variables. Greater profit will be made if revenue is strong, and vice versa. 
2. The correlation coefficient between units sold and unit cost is negative, which suggests that the relationship between product quantity and cost is inverse. The situation with units sold and units priced is the same. The more expensive a product is, the fewer units it is available in.
3. We may deduce from the heatmap above that there is a substantial correlation between Total Cost, Unit Price, Unit Cost, and Total Profit. 
4. [Unit Price and Unit Cost] and Units Sold are entirely separate entities. The quantity of a product sold is unaffected by the price per unit, just as the cost of a unit is unaffected by the quantity of units sold. 
5. The relationship between Total Revenue and Unit Cost, Unit Price, and Total Cost is essentially nonexistent.

## Yearly Analysis
**Tableau Link** : Click [here](https://public.tableau.com/views/TotalSale_yearly/Sale_2?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

![Sale_2](https://github.com/Swagatika-Meher/Analyzing-Amazon-Sales-data/assets/114692581/677ceb05-d374-493a-9b27-6f3432229cdf)

As we can see, total profit and total revenue is directly proportional to each other. Maximum profit and maximum revenue have been achieved in 2012. Minimum profit and minimum revenue have been achieved in 2011.

## Monthly Analysis
**Tableau Link** : Click [here](https://public.tableau.com/views/TotalSale_monthly/Sale_4?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

![Sale_4](https://github.com/Swagatika-Meher/Analyzing-Amazon-Sales-data/assets/114692581/6393ab1c-bba5-49e8-9b9f-fcf668c3ad5f)

Maximum profit and maximum revenue have been achieved in the month of February. Minimum profit and minimum revenue have been achieved in the month of august.

## Region-wise Analysis
**Tableau Dashboard** : Click [here](https://public.tableau.com/views/Dashboard_2_17145484370550/Dashboard2?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

![Dashboard 2](https://github.com/Swagatika-Meher/Analyzing-Amazon-Sales-data/assets/114692581/90d1604d-74d9-4469-b6c6-44f7cd0aca4a)

Maximum profit and maximum revenue have been in **Sub-Saharan Africa** region. Lowest profit and lowest revenue have been in **North America** region.

# Analogy
**Tableau Dashboard** : Click [here](https://public.tableau.com/views/comparison_1_17148417598020/Dashboard5?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

![Dashboard 5](https://github.com/Swagatika-Meher/Analyzing-Amazon-Sales-data/assets/114692581/964be08b-0d7a-4b2c-ad23-0a0fc17ba417)

1. **Units Sold vs. Total Profit :** As we can see, maximum profit has been generated when the number of units sold were between 5000 and 10000 i.e. more the number of units sold, more will be the profit generated.
2. **Total Revenue vs. Total Profit :** The scatter plot suggests that total profit and total revenue are directly proportional to each other.
3. **Unit Cost vs. Units Sold :** Here, the two variables 'Units Sold' and 'Unit Cost' are inversely proportional to each other to some extent. When more units of a product are sold, the unit cost of that product becomes lesser and vice versa.
4. **Total Cost vs. Units Sold :** As we can see, maximum cost has been generated when the number of units sold were between 7000 and 9000. More the number of units sold of a product, more will be the total cost associated with it.

## Selling item type
**Tableau Dashboard** : Click [here](https://public.tableau.com/views/Dashboard_4_17145771557530/Dashboard4?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

![Dashboard 4](https://github.com/Swagatika-Meher/Analyzing-Amazon-Sales-data/assets/114692581/b0a620e2-eddc-404c-a58b-25567f32ef58)

* Maximum units has been sold having the items ‘Cosmetics' and ‘Clothes' closely followed by ‘Beverages’.
* Even though higher units of clothes sold, less profit and less revenue has been generated.
* Maximum revenue has been generated from the items ‘Office supplies' and 'Cosmetics' closely followed by ‘Household’.
* Highest net profit margin has been achieved in ‘clothes’ and ‘cosmetics’.

## Net Profit margin yearly
**Tableau Link** : Click [here](https://public.tableau.com/views/Net_Profit_Margin_yearly/Sale_14?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

![Sale_14](https://github.com/Swagatika-Meher/Analyzing-Amazon-Sales-data/assets/114692581/bdbe55ae-dac3-4b5b-9ec3-932cbbd2669a)

Highest net profit margin has been achieved in the year 2012 and lowest profit margin has been achieved in the year 2011.

## Net Profit margin monthly
**Tableau Link** : Click [here](https://public.tableau.com/views/Net_Profit_Margin_monthly/Sale_15?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

![Sale_15](https://github.com/Swagatika-Meher/Analyzing-Amazon-Sales-data/assets/114692581/c96d5438-3d42-4473-8c74-421ce146d094)

Highest net profit margin has been achieved in the month of july and lowest profit margin has been achieved in the month of December.

## Year-month wise
* **Units Sold**
  **Tableau Dashboard** : Click [here](https://public.tableau.com/views/Dashboard_1_17145454023930/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

  **Tableau Dashboard** : Click [here](https://public.tableau.com/views/Dashboard_3_17145763236120/Dashboard3?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)

![Dashboard 1](https://github.com/Swagatika-Meher/Analyzing-Amazon-Sales-data/assets/114692581/bb3fd855-f217-415a-94ae-9afe9aed3d23)

Maximum units sold in the year 2012 and in the month July. Minimum units sold in the year 2016 and in the month march.

* **Profit**

  **Tableau Dashboard** : Click [here](https://public.tableau.com/views/Profit_yearly_month-wise/Sale_9?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)
   




















