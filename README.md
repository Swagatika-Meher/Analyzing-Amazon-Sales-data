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







