# book-recommendation-system
![235067025-0717cfa6-3977-40c5-b865-94226f679795](https://github.com/smaran19/book-recommendation-system/assets/150596819/7b9f11ee-5abd-4372-a60f-8ff7a21b127a)
Developed a book recommendation system for Amazon customers using memory and model based collaborative filtering by utilizing the description of book consumed and user interests. A recommendation engine is a class of machine learning which offers relevant suggestions to the customer. Before the recommendation system, the major tendency to buy was to take a suggestion from friends. But Now Google knows what news you will read, Youtube knows what type of videos you will watch based on your search history, watch history, or purchase history.

A recommendation system helps an organization to create loyal customers and build trust by them desired products and services for which they came on your site. The recommendation system today are so powerful that they can handle the new customer too who has visited the site for the first time. They recommend the products which are currently trending or highly rated and they can also recommend the products which bring maximum profit to the company.

Book-Recommendation-System-Project

Objective:

The main objective is to create a book recommendation system for users. Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors.

Methods Used:

Descriptive Statistics Data Visualization Machine Learning

Technologies:

Python Pandas Numpy Matplotlib Seaborn Scikit-learn Surprise

Data:

The Book-Crossing dataset comprises 3 files.

Users : Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL values.

Books : Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon website.

Ratings : Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.

![235067070-ba0f6652-847d-4b7d-97ca-962b3dee51ef](https://github.com/smaran19/book-recommendation-system/assets/150596819/1873db55-2075-4e3f-ac92-f5cfe65e895c)
Project Description:

EDA - Performed exploratory data analysis on numerical and categorical data.

Data Cleaning - Missing value imputation,Outlier Treaatment

Feature Selection - Used User-ID,ISBN and Books-Rating for model development.

Model development - Tried Popularity based model and Collaborative filtering (Both Memory based and Model based).

Needs of this project:

data exploration data processing/cleaning recommendation system developer

Getting Started:

Clone this repo (for help see this tutorial).

Raw Data:

Users_data is being kept here within this repo.

Ratings_data is being kept here within this repo.

Books_data is being kept here

Complete notebook containing Data exploration/Data processing/transformation/model development is being kept here.

![235066969-3add7676-4009-4879-94cf-25438fb86340](https://github.com/smaran19/book-recommendation-system/assets/150596819/377b1ad6-4d09-4ed7-a779-b4b75ef3bd59)
Conclusion:

A book search recommendation system is needed to reduce large data output so that book search will be more effective compared to book search system with syntax method. The book search recommendation system uses a user-based collaborative filtering method. The main objective is to create a book recommendation system for users. Recommender systems are really critical in some industries as they can generate a huge amount of income when they are efficient or also be a way to stand out significantly from competitors. Recommendation systems allow you to drive much higher conversions and enhance average order value. You can bring multiple data sets (historical data, real-time visitor behavior, and third-party insights) into a recommendation algorithm using a recommendations engine.
