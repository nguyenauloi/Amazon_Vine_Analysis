# Amazon_Vine_Analysis
Module 16

# Project Overview

$ellby has hired BigMarket to compare their products versus their competitors. They want to know if giving products away for free to reviewers is the right choice. To do this we will be analyzing data from Amazon reviews written by members of the paid Amazon Vine program. For the purposes of our project, we will be using Amazon's U.S.Kitchen review dataset. We'll use PySpark to perform ETL into a AWS RDS instance and load the data into pgAdmin. 

# Results

#### Paid Reviews
<img src="https://github.com/nguyenauloi/Amazon_Vine_Analysis/blob/main/resources/imgs/paid_reviews.PNG" width="600">

#### Unpaid Reviews
<img src="https://github.com/nguyenauloi/Amazon_Vine_Analysis/blob/main/resources/imgs/unpaid_reviews.PNG" width="600">

 - How many Vine reviews and non-Vine reviews were there?
    - There were 1,207 Vine (paid) reviews and 97,839 non-Vine (unpaid) reviews.

- How many Vine reviews were 5-stars? What percentage of non-Vine reviews were 5-stars?
    - There were 509 Vine (paid) 5-star reviews and 45,858 non-Vine (unpaid) reviews.

- What percentage of Vine reviews were 5-stars? What percentage of non-Vine reviews were 5-stars?
    - Of the Vine (paid) reviews, 42.17% were 5-star compared to the 46.87% for non-Vine (unpaid)

# Summary

It doesn't seem as though the Vine program is worth the time, money, and effort. The ratio between 5-star reviews and all other reviews appears similar for those in the Vine program and everyday consumers (about 2:1). Though this dataset does not include information about products that were not reviewed by those in the Vine program. In order to see if there was any influence we would need to observe if the 2:1 ratio of 5-star to all other reviews remains the same in a dataset where there were no Vine reviewers at all, while still having a large enough sample size to come to a reasonable conclusion. 
