# review-star-ranker
Project for University of Texas Data Analytics and Visualization Bootcamp



## Goal
Create a ML prediction model that predicts the star_rating (1-5) based on review_body text.

## Question
Is there a relationship between the written language review body and numerical star ratings within Amazon product reviews?

## Important Links
* [Colab Grouped 1-3 and 4-5 (Acc. ~86%)](https://github.com/Fergus1212/review-star-ranker/blob/master/sparnknlp_review_rating_1and5.ipynb)

## Challenges
* Data is large
  * 2,643,619 records | 491.92 MB
* Data not entirely clean
* Classification difficult for labels 1, 2, 3, 4, and 5 requiring label consolidation.
* UniversalSentenceEncoder is large and adds to model size
 * 923.7 MB

## Pipeline


## Tech
* [Python](https://www.python.org/) - The coding language of champions
* [John Snow (Spark NLP)](https://nlp.johnsnowlabs.com/docs/en/quickstart) - NLP library built on top of Apache Spark 2.4.4
* [Google Colaboratory](https://colab.research.google.com/notebooks/basic_features_overview.ipynb) - Google cloud-based jupyter notebook
