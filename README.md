# Amazon_Vine_Analysis
## Overview of Amazon Vine Analysis
The purpose of this analysis is to see if there is any relation between vine program and five-star reviews on Amazon site. For this, we collected datasets from Amazon for different categories, such as baby products, toys, shoes, clothes, and videos. I have used video dataset for this analysis. One way to get this information is to see how many "Y"s and "N"s under vine variable. "Y" means the corresponding review is paid. 

## Results
1. How many Vine reviews and non-Vine reviews were there?
Not sure about the rest of the datasets, but video dataset has 0 vine/paid reviews, and there are 20,201 non-vine/unpaid reviews.
![paid vs. unpaid vine](https://github.com/dilnigar1007/Amazon_Vine_Analysis/blob/main/vine%20paid%20vs.%20unpaid.png)

2. How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
Since there isn't any vine reviews, therefore 0 five-star vine reviews. And there is 12,331 non-vine five-star reviews.

3. What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
0% of vine reviews were five-star obviously and 61% of non-vine reviews were five-star.
![zero_paid_five_star_review](https://github.com/dilnigar1007/Amazon_Vine_Analysis/blob/main/zero_paid_five_star_review.png)

## Summary
Before we filtered out the helpful votes rate under 50%, we had some reviews with "Y", so it means we had biased/paid reviews in this new dataframe. We can't say that any reviews related to videos are accurate, unpaid because before filtering out these reviews, we had some reviews with "Y" under vine variable if we look at the dataframe here.
![paid reviews](https://github.com/dilnigar1007/Amazon_Vine_Analysis/blob/main/paid%20reviews.png)
