# Amazon_Vine_Analysis
You can find the Analysis file here: [Amazon_Reviews_ETL.ipynb](https://github.com/NedaAJ/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb) | [VineReviews_Analysis.ipynb](https://github.com/NedaAJ/Amazon_Vine_Analysis/blob/main/VineReviews_Analysis.ipynb)

## Analysis Overview
This project examines the Amazon Vine service to see if there is a bias favouring positive Vine member reviews.
PySpark is used to extract the dataset, convert the data, connect to an AWS RDS instance, load the changed data into pgAdmin, and calculate various metrics in the analysis.
We concentrated on video game reviews in the United States.

## Results

- Vine Reviews Summary:
<p align="center">
  <img src="https://github.com/NedaAJ/Amazon_Vine_Analysis/blob/main/Resources/Vine_Reviews.PNG">
</p>

- Non-vine reviews Summary:
<p align="center">
  <img src="https://github.com/NedaAJ/Amazon_Vine_Analysis/blob/main/Resources/non_Vine_Reviews.PNG">
</p>

## Summary
There could be biased among "Star Ratings". There were 40,471 records that did not have vine reviews, but only 94 records that did have vine reviews.The Vine programme received a 5-star rating from 51 percent of recordings. In comparison, about 38% of records not included in the Vine programme received a 5-star rating. Given the fact that there were much fewer recordings with Viners than there were records without Viners, the Vine/Star-Rating ratings might be skewed.
For future studies, We might also look at the statistical distribution of the star rating for Vine and non-Vine reviews (mean, median, and mode).

## Contact:
- Email : [neda.ahmadi.jesh@gmail.com](mailto:neda.ahmadi.jesh@gmail.com?subject=[GitHub]%20Source%20Han%20Sans)
- Linkedin: www.linkedin.com/in/neda-ahmadi-j
