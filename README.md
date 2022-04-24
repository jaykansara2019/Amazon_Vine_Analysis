# **Amazon_Vine_Analysis**

## **Background**

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are required to publish a review.

## **Purpose**
The project aimed to analyse Amazon reviews written by members of the paid Amazon Vine program. We have access to more than 50 datasets. (https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
We have chosen a book review dataset, and we will analyse it to determine bias between paid v/s unpaid reviews. (https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Books_v1_00.tsv.gz)

## **Results**

- How many Vine reviews and non-Vine reviews were there?
There is a total 5012 number of paid reviews and 109297 unpaid reviews.

- How many Vine reviews were 5-stars? How many non-Vine reviews were 5 stars?
A total 2031 of paid reviews were given 5-stars, and 49967 unpaid reviews got 5-stars.

- What percentage of Vine reviews were 5-stars? What percentage of non-Vine reviews were 5-stars?
The ratio of 5-star reviews by paid reviewers was 40.52%, and by unpaid reviews, it was %.

The results from the Google Colab notebook are depicted below:
![](https://github.com/jaykansara2019/Amazon_Vine_Analysis/blob/5624dab2913333770be32007ca9f8575f0d31ccf/Images/paid%20v:s%20unpaid%20reviews%20analysis.png)

Modified tables based on the master data is presented in the images below:

![](https://github.com/jaykansara2019/Amazon_Vine_Analysis/blob/5624dab2913333770be32007ca9f8575f0d31ccf/Images/customers_df.png)

![](https://github.com/jaykansara2019/Amazon_Vine_Analysis/blob/5624dab2913333770be32007ca9f8575f0d31ccf/Images/products_df.png)

![](https://github.com/jaykansara2019/Amazon_Vine_Analysis/blob/5624dab2913333770be32007ca9f8575f0d31ccf/Images/review_id_df.png)

![](https://github.com/jaykansara2019/Amazon_Vine_Analysis/blob/5624dab2913333770be32007ca9f8575f0d31ccf/Images/vine_df.png)


## **Summary**

Our analysis can conclude that the incentive bias is less likely to affect the book reviews. Unlike other products (e.g. jewellery and apparel), most book readers seem honest about the reviews and are less likely to get influenced by the incentives from the company/publishers.

Additional analysis could be performed by deriving the mean, median and mode of the total rating. Also, the type of incentive can be separated to determine if a certain type of incentive is likely yot influence the product rating.


