# Collaborative-Movie-Recommendation-Based-on-Alternating-Least-Squares-ALS-with-Apache-Spark
Collaborative Movie Recommendation Based on Alternating Least Squares (ALS) with Apache Spark
Introduction to the report
The MovieLens (Chang, 2015) datasets are very common datasets that are used in a lot of areas such as research, education, and industry. It is downloaded by thousands of people each year which depicts the widespread use in coding, online and traditional applications.  Users’ preferences were recorded in the form of a rating system for a particular movie at a particular time. These preferences were recorded by the website called “Movielens website1”  to provide them with personalized movie recommendations.

This dataset is vastly used to create different movie recommender systems and Collaborative filtering is one of the most preferred approaches for the same with the help of ALS. This dataset is comprised of the below Comma Separated Value files:
File Name	Purpose	Count of rows	Used?
genome_scores.csv	Contains genome scores	Not used	No
genome_tags.csv	Contain genome tags	Not used	No
rating.csv	Contain rating details	9139592	Yes
movie.csv	Contains movie details	58098	Yes
tag.csv	Contains tags	Not used	No
link.csv	Contain links to movies	58098	Yes
Additional metadata files used
Movies_metadata.csv	Contains all movie information	45572	Yes
Language_code.csv (Anon., n.d.)
Contains language code and language	184	Yes
Table 1 datasets
We have only used above mentioned datasets for our analysis. Rest datasets can be used for future scope and will be discussed later. Movies_metadata.csv is not as accurate as above and for the same reason, we have performed data cleaning and pre-processing for the same.
