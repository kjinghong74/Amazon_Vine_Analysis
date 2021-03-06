## **Overview of Project**
In this project, I analyzed Amazon reviews database of Jewelry written by members of the Amazon Vine program. Data were uploaded as a Google Colab Notebook, then extracted and transformed using pyspark, four data tables (customers_table, products_table, review_id_table, and vine_table) are generated and uploaded into pgAdmin. Then I analyzed wethere there is any bias towards reviews that were written as part of the Vine program vs non-Vine program by comparing percentage of 5-star reviews for these two types of review.

## **Results**

- How many Vine reviews and non-Vine reviews were there?
     There are 21 Vine reviews and 7689 non-Vine reviews in this database.
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
     There are 11 out of 21 Vine reviews are 5 stars, and 4444 out of 7689 non-Vine reviews are 5 stars.
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
     52% of Vine reviews were 5 stars, and 58% of non-Vine reviews were 5 stars. 
 
![Results_counts](https://user-images.githubusercontent.com/90361056/148713668-917815db-471b-48d5-84cb-abdb1aa9920f.PNG)


## **Summary**
From data in results session, 52% of Vine reviews were 5 stars, and 58% of non-Vine reviews were 5 stars. We can see that the percentage of 5-star reviews for the two types of review (paid vs unpaid) is very close. Therefore, I don't think there is bias towards reviews that were written as part of the Vine program.
     
