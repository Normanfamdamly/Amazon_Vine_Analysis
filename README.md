# Amazon_Vine_Analysis - Module 16 Challenge
---
## Purpose
The project was for us to utilize PySpark to perform the ETL process to extract the dataset, transform the data and connect it to an AWS RDS instance.  Then load the data selected, transform he data into pgAdmin to then utilize either PySpark, Pandas or SQL to determine if there is any bias in the purchased Vine reviews from their members on the data instance we selected.

As you can see below, I selected the AWS data on Video Games and their reviews.  Below is the Customer Table, Products Table, Review Id Table and the Vine Table we imported into to pgAdmin.

![customer_table.png](https://github.com/Normanfamdamly/Amazon_Vine_Analysis/blob/main/images/customer_table.png)

![products_table.png](https://github.com/Normanfamdamly/Amazon_Vine_Analysis/blob/main/images/products_table.png)

![review_id_table.png](https://github.com/Normanfamdamly/Amazon_Vine_Analysis/blob/main/images/review_id_table.png)

![vine_table.png](https://github.com/Normanfamdamly/Amazon_Vine_Analysis/blob/main/images/vine_table.png)

## Results 
---

We took the data from the Vine Table and ran it through a more PySpark coding to perform the ETL process again to extract more from the dataset to determine if there was any bias in the reviews from the paid reviews vs. the non-paid reviews.

![vine_reviws.png](https://github.com/Normanfamdamly/Amazon_Vine_Analysis/blob/main/images/vine_reviews.png)

There is no positive correlation to the high reviews and those who were pad for the reviews in the Vine program Of the 40,565 total reviews, only 94 of them were from paid Vine reviews.  There were a greater percentage of 5-star reviews for paid (51.06%) than unpaid (38.70%), this is a relatively small differential and the sample size of paid reviews is too small to conclude that there is positivity bias. Additional analysis could be done on the 1-star reviews to determine if there is any negative correlation to those as well to further our analysis.

