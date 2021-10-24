# Analysis of Amazon Vine Toy Reviews - Module 16 Challenge


## Project Purpose
To use the Amazon toy reviews dataset to perform the ETL process with PySpark to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then, use Pandas to determine if there is any bias toward favourable reviews from Vine members in your dataset.


## Results
**FIGURE 1: Results - Vine Toy Reviews**\
![Summary - Vine Toy Reviews](https://github.com/pmoores/Amazon_Vine_Analysis/blob/main/Resources/Analysis_Summary_Vine_Reviews.png)

- There are 1266 Vine reviews and 62028 non-Vine reviews

- There are 432 5-star Vine reviews and 29982 5-star non-Vine reviews

- 34% of all Vine reviews are 5-star and 48% of all non-Vine reviews are 5-star


## Summary
The results of this analysis demonstrate that there is no positivity bias in the Vine toy reviews program. In fact, Vine toy reviews have a slight negativity bias in terms of 5-star scores. 34% of all Vine reviews are 5-star while 48% of all non-Vine reviews are 5-star, a 14% difference towards lower review scores in Vine toy reviews.

An additional analysis to perform on the dataset would be to compare the average star ratings of Vine versus non-Vine toy reviews to investigate if the same negativity bias exists across all star ratings (1.0 to 5.0).


## Attachments
[Amazon_Reviews_ETL](https://github.com/pmoores/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb)


[Vine_Review_Analysis](https://github.com/pmoores/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb)


