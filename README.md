# Write_a_Data_Science_Blog_Post_Project
Udacity DS ND Write a Data Science Blog Post Project

**Installation:**

Code for the project requires python 3 and the followinf librariws:
    - pandas
    - numpy
    - zipfile
    - seaborn
    - matplotlib.pyplot
    - re
    - nltk
    - wordcloud
    - folium
Most of the libraries above are included in anaconda distribution. Trough coding i've needed to pip install folium only.

## 1. Bussiness Understanding and Problem Definition##
For this project i've chosed to analyze given AirBnb data sets for Boston and Seattle.

**Motivation:**

My main motivation to select this project it has soo many aspects a data scientist can investigate
contains 2 differet citties for comparison which will made answers more rubost.
I've wanted to analyze:
    - Can wording effect perception of any host bussinesses?
    - Can location is still the first element to look at if someone decides to open a host bussiness. 

Therefore through the project i will try to answer the following questions:
    - Does wording effect reviews?
    - Location vs revenue where to invest?
    - Is finding aplicable to other data set?

**Data Sets:**

Data files provided by Udacity and Kaggle for this project which derived from AirBnb Seattle and Boston Cities data.
- seattle.zip
    - calendar.csv : Availablity of AirBnb Listings for each day of 2016 with prices.
    - listings.csv : Description of AirBnb Listings with many descriptive features.
    - reviews.csv : Reviews related to AirBnb Listing with unique reviewer ids.
- boston.zip
    - calendar.csv : Availablity of AirBnb Listings for each day of 2017 with prices.
    - listings.csv : Description of AirBnb Listings with many descriptive features.
    - reviews.csv : Reviews related to AirBnb Listing with unique reviewer ids.

**Objective and Plan :**

At the first glance data set seems well prepared and organized. It has 3 files for each city and total of 100 columns for listings. On the other hand it is clear that there are some missing values that must be handled.

My main objective at this phase is find relative and simple anwsers to question i've explained above. For this reason i've decided to investigate:
    - listing.csv for descriptive columns and their wording, also coordinate data
    - reviews.csv for reviews entered for listings and their wording
    - calendar.csv to calculate average prices and availablity to assess location based pricing affects.

So first i will investigate data sets on data undestanding phase and handle missing values and create data frames for my modelling and evaluation phases. 

**Results :**

My Results according to question i've trying to find out shortly are:
    - Does wording effect reviews : No, I couldn't find sharp relation between description and reviews.
    - Location vs revenue where to invest : Yes, it is clear that center-located listings have more nightly stay prices.
    - Is finding aplicable to other data set : Yes above 2 questions give the same results on both Seattle and Boston data sets.

More detailed results are in below blog post:
https://medium.com/@m.bilgehankilinc/an-experienced-business-developer-vs-a-lazy-traveler-on-airbnb-seattle-and-boston-data-12771267b28b

**Acknowledgement**
This dataset is part of Airbnb Inside and presented on Kaggle.com. I've used data by direction of Udacity for Write a Data Science Blog Post assignment.
