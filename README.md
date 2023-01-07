# ML-unsupervised-Capistone-project
# **Conclusion:-**

## **1- Data Overview**

**1- Data Overview**
  * We have 7787 rows and 12 columns provided in the data.

  * In the dataset we have 11 object columns and 1 integer column as release_year.

**2- Checking the null values**
  * Fist we have 2389 null values in director column.We have almost 30% null values in this column so we can not use this column in model training but we can use it in EDA.

  * We have 718 null values in cast column. and it can be replaced with 'unknown'.

  * we have 507 null values in country column.Replacing nulls with 'mode'.

  * Also we have 10 null values in date_added column.we have few rows of date_added so we can 'drop' these rows.

  * Also we have 7 null values in rating column.Replacing nulls with 'mode'.
   ![image](https://user-images.githubusercontent.com/112492310/211157022-7be25f19-c928-41c1-a16c-2cda8aff22ad.png)


**3- Check Duplicate values in the dataset**

  * we do not have any Duplicate values in the dataset.


---
## **2- Exploratory Data Analysis**

**type column**
  * According to the graph we have 5377(69.14%) movies

  * And 2400(30.86%) as TV Show in this dataset.

**'director' column**
  * According to plot we can say Raul Campos and Jan Sulter collectively have the most content on Netflix.
  * Marcus Raboy have the second most content on Netflix.

**'cast' column**
  * Now we can say in this data Anupam Kher having 38 number of listing.
  * Takahiro Sakurai is the second most listed actor on netflix.
  * Shah Rukh Khan is the 3rd most listed actor on netflix.

**'country' column**
  * According to the plot we can understanding United States have 2080 Movies and	975 TV Show

  * INDIA have second most listed country with 852 movies and	71 TV Show on Netflix.

