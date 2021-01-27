# Amazon_Vine_Analysis

## This project is to analyze Amazon reviews written by members of the paid Amazon Vine program and determine if there is any bias toward favorable reviews from Vine members in reviews dataset.

### Resources
- Data Source: 
	- https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Camera_v1_00.tsv.gz

- Software: 
	- Google Colaboratory
	- pgAdmin 4.24

### Results
- How many Vine reviews and non-Vine reviews were there?

![alt text](https://github.com/Yunaka1269/Amazon_Vine_Analysis/blob/main/pic/vine_and_non_vine_review.PNG "Vine_non_Vine")

	- vine: 607
	- non-vine: 50522 

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![alt text](https://github.com/Yunaka1269/Amazon_Vine_Analysis/blob/main/pic/five_star_vine_and_non_vine_review.PNG "5_start_Vine_non_Vine")

	- vine: 257
	- non-vine: 25220 

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![alt text](https://github.com/Yunaka1269/Amazon_Vine_Analysis/blob/main/pic/percentage_of_five_star.PNG "Percentage_five_star_review")

	- vine: 42.34%
	- non-vine: 49.92% 

### Summary
Based on selected dataset, I conclude that there is no bias toward favorable reviews from Vine members. The percentage of 5 stars review of non-Vine member is approximately 7% higher than Vine member. The additional analysis that we could do is to use other datasets and see if the result will be the same. Also, we can perform statistical analysis (ie: mean, median, mode, and Std).
