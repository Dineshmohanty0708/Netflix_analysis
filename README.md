# Netflix_analysis

#  Netflix Movie Data Analysis Project

##  Overview

Netflix is renowned for its work in **Data Science**, **AI**, and **Machine Learning**, particularly in building recommendation algorithms that understand customer behavior and viewing patterns.  

In this project, we analyze a dataset containing over **9,000 Netflix movies** to uncover insights that can help the company make informed data-driven decisions.

---

##  Objectives

We aim to answer the following business questions:

1.  What is the most frequent genre of movies released on Netflix?  
2.  What genre has the highest votes?  
3.  What movie got the highest popularity? What's its genre?  
4.  What movie got the lowest popularity? What's its genre?  
5.  Which year has the most filmed movies?

---

##  Dataset Summary

- The dataset consists of **9,827 rows** and **9 columns**.  
- The data is fairly tidy, with **no missing values** or **duplicates**.  
- `Release_Date` needs to be converted to a datetime object for analysis.  
- Columns like `Original_Language`, `Overview`, and `Poster_Url` are dropped as they are not useful for this analysis.  
- The `Popularity` column shows some **noticeable outliers**.  
- The `Genre` column contains extra whitespace and multiple genres per row, which were cleaned and separated using the `explode()` function in Pandas.

---
