# Amazon_Vine_Analysis
## **Overview of the analysis**
     In this project, I analyzed Amazon reviews database of Jewelry (url=https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Jewelry_v1_00.tsv.gz) written by members of the Amazon Vine program. Data were uploaded as a Google Colab Notebook, then extraced and transformed using pyspark, four data tables (customers_table, products_table, review_id_table, and vine_table) are generated and uploaded into pgAdmin. Then I analyzed wethere there is any bias towards reviews that were written as part of the Vine program vs non-Vine progame by comparing the percentage of 5-star reviews for these two types of review. 
     
 ## **Results**
    ![Results_counts](https://user-images.githubusercontent.com/90361056/148712846-4d82298c-e8a0-4a9e-84e9-4a0c787d3741.PNG)
     

 - How many Vine reviews and non-Vine reviews were there?
    There are 21 Vine reviews and 7689 non-Vine reviews in this database. 
    
 - How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    There are 11 out of 21 Vine reviews are 5 stars, and 4444 out of 7689 non-Vine reviews are 5 stars.
    
 - What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    52% of Vine reviews were 5 stars, and 58% of non-Vine reviews were 5 stars.
 
 ## **Summary**
    From data provided in Results session, 52% of Vine reviews were 5 stars, and 58% of non-Vine reviews were 5 stars. We can see that the percentage of 5-star reviews for the two types of review (paid vs unpaid) is very close. Therefore, I don't think there is bias towards reviews that were written as part of the Vine program.
