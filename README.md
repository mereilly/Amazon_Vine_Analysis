# Amazon_Vine_Analysis

## Overview of the Analysis
After working on the SellBy Project, my team was asked to evaluate Amazon Reviews from the Amazon Vine program. I picked the pet items dataset to evaluate the reviews on that specific product set. The data was extracted and transformed and loaded into AWS and managed through pgAdmin. 


## Results
### Total Reviews 2643619

![Screen Shot 2021-10-15 at 10 42 46 PM](https://user-images.githubusercontent.com/82982952/137570588-b8480644-9d59-43b3-8940-a408f9106ccb.png)
![Screen Shot 2021-10-15 at 10 42 53 PM](https://user-images.githubusercontent.com/82982952/137570590-d91840d8-a290-4c50-a181-458eee13a0d4.png)

![Screen Shot 2021-10-15 at 10 43 01 PM](https://user-images.githubusercontent.com/82982952/137570591-7700db6e-4010-4e87-bb1d-f099187f856a.png)
![Screen Shot 2021-10-15 at 10 43 08 PM](https://user-images.githubusercontent.com/82982952/137570592-159be584-4675-4c5b-94e1-351d43fee180.png)

### At the end of our Vine_Analysis file we see a clear report with a break down of the prominance of 5 stars in the different subsections: 

#### Total Reviews for each sub group (paid and not paid for the Vine Program)
 -Paid Vine Total Reviews: 21
 -Vine X/Non Vine Total Reviews: 6690
 
#### How many Vine reviews were 5 stars?  How many non-Vine reviews were 5 stars? 
-Five Stars in Vine Y (Paid): 10
-Five Stars in Vine N (Not Paid): 3448

#### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
-Paid Vine - Portion that were five star reviews: 47.6%
-Not Paid - Portion that were five star reviews: 51.5%

## Summary
In your summary, these results don't reflect a bias for reviews in the Vine program, if anything it's pretty even percentagewise and maybe a little more negative by Vine Members (47.6% 5-stars vs 51.5%). Still, the latter (not paid) group is a much greater ammount of reviews, so that means many more people who leave reviews and feel positively are non paying people. This alure to participate may be because they are not directly related, whereas lower engagement among paid members and a harder effort to get them satisfied makes sense since they are paying for the service and probably have higher/set expectations, whereas others ho don't subscribe could be plesantly surpricsed and more willing to give 5 stars. It would be interesting to compare the different categories beyond just pet products to see if the trend is similar. 


