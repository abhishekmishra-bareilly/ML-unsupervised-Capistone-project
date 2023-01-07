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

**'date_added' column:-**

  * We have so many content relese in October(785), November(738), December(833) and January(757) may be it is because of Holiday season.
  * The number of release have significantly increased after 2015 to 2020
  * Bul sudden drop in 2021 may be it is because of covid 19.

**'release_year' column**
  * We have 744 movies and	268 TV Show relese in 2017

  * Also 734 movies and	386 TV Show relese in 2018

  * 82%(6431) of the content was released between 2010 and 2021
  * 17.28%(1346) of the content was released before 2010.
**'Rating" column**

  * Most number of movies rated TV-MA i.e. Adult Rating

  * Most number of TV Shows rated TV-MA i.e. Adult Rating

**Tv shows duration**
  * We have most listed duration as season 1 with 1608 listing.
  * We have second most listed duration as season 2 with 378 listing.

**Movie duration**
  * Mainly the movie duration is in b/w 55 to 150 minutes.
  * Most of the movies list for 90 to 120 minutes.

## **3- Data pre-processing**

**1- Feature Engineering**
  * For train the model we use description column, listed_in column, rating column, country column, title column, director column, cast column.

**2- We performe Text cleaning as our next step**
  * convert all words in lowercase.

**3- We performe Stemming as our next step**
  * We remove all stopwords.
  * Also use stemming function.

**4- We performe TF-IDF vectorizer**
  * Term frequency-inverse document frequency is a text vectorizer that transforms the text into a usable vector.

**5- Applying PCA-Principal Component Analysis to reduce dimensions.**
  * We will use 3000 components
  ![image](https://user-images.githubusercontent.com/112492310/211157449-eaa0dab4-20d1-4666-8a4b-f9e8482c1c8d.png)

## **3- Applying models**

**1- Find the value of clusters**
  * WE use Elbow method for finding k values.
  * Also use Silhouette Score for best score.
  * Also use Dendogram for finding the value of clusters.
  
**2- Use Agglomerative Clustering**

**3- Use KMeans Clustering**

Here are few clusters with there word cloud graph
**Analysis of cluster 0**

  * Type - Movie, TV Show

  * Title- Naruto, high, girl, low, movie, dragon, bleach, fate, battle

  * Countries- Japan, US, India

  * Ratings- TV-MA, PG, Y7

  * Genres- International TV series- Anime

  * Description- family, world, human, friend
## **4- Movie Recommendation Sytem**



