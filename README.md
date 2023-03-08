# Play Store App Review Analysis
## Abstract

Android is an operating system which has Currently 2.8 billion users are active around the globe. In this project we will be doing analysis on Play Store App Review Data. With the development of android initially it was an operation system to be used in camera but when google acquired android in 2005. They started giving android as an operating system to smartphones in 2007 which was later going to dominate 1/3rd of the world's total population as what we are experiencing today. Android is basically an open source OS giving the developers an opportunity to develop applications in this data ridden world because of this it has become necessary for the data analytics professionals to analyze those data so to help companies realize how they can grow their business effectively in every aspect and learn the needs of the users for the betterment of their products and also help App developers how they can improve their products in different categories.


## Problem Statement:
Data has been provided by ABC Advertising Pvt. Ltd. to analyze the data for different App in different categories and help them satisfy their customers needs who possibly resides around the world. From these analyses they can understand the needs of their customers in different aspects of product development and it will help solve the problems with the market superiors. The main objective of this project is to deal with the data provided by the company and to analyze the data in every aspect possible so to help them match their idea and help them to convert new and retain old customers and make reasonable growth. We have been provided with two datasets: Play Store Data.csv User Reviews.csv

### Play Store Data.csv elements:
- App - Name of the Application
- Category - Category of the Application
- Rating - Rating given to the Application
- Reviews - No of reviews given to the Application
- Size - Size of the Application
- Installs - No of downloads of the Application
- Type - Free or Paid
- Price - Price of the Application if it is paid
- Content Rating-It is Age appropriate or Not
- Genres - Type of Genre the Application belongs to 11.Last Updated - When the last time the Application is Updated
- Current Ver - Current version of the Application
- Android Version- Minimum Android version required to run the Application

### User Review.csv column elements:
- App:- Type of Applications
- Translated_Review:- Reviews being given by consumer
- Sentiment:- Sentiment of trust from customer
- Sentiment_Polarity:- It determines sentimental expression of the customer's opinion
- Sentiment_Subjectivity:- Sentimental Subjectivity in terms is a personal opinion and it falls in range [0,1].

## Introduction
Android as we know is a huge marketplace where every app developer has the opportunity. When Google acquired Android in 2005. Google incorporated the market with android in 2007 which have let developers develop android applications and in this way with very less association with their own developer and more on open source developers it opened the markets of opportunities for both the makers and the user as well what we can easily speculate today. This has also helped in the development of many new businesses and also several new professions which we can experience now. There are basically three kinds of Applications in the Android Play Store. ‘Background Services and Intent Receivers Applications’,’Foreground Background Applications’ and ‘Intermittent Applications’.

The type of Applications which we will use to analyze in Play Store App Review Analysis mostly will be Intermittent type Applications.

In this project of Play Store App Review Analysis we will be analyzing each and every prospect of the data available with us and on the basis of this data we will try to solve every problem associated with the real world problem which lets them achieve customer prosperity.

## Data Cleaning and some insights
1. App - It tells us about the name of the application.
2. Category - It tells us about the category to which an application belongs.
3. Rating - It tells us about the ratings given by the users for a specific application.
4. Reviews - It tells us about the total number of users who have given a review for the application.
5. Size - It tells us about the size being occupied the application on the mobile phone.
6. Installs - It tells us about the total number of installs/downloads for an application.
7. Type - It tells us whether the application is free or a paid one.
8. Price - It tells us about the price of the application.
9. Content_Rating - It tells us about the target audience for the application.
10. Genres - It tells us about the various other categories to which an application can belong.
11. Last_Updated - It tells us about the when the application was updated.
12. Current_Ver - It tells us about the current version of the application.
13. Android_Ver - It tells us about the android version which can support the application on its platform.



## Conclusions
1. Most of the app's belongs to Family category. They are approximately 19% among all categories.

2. Ratings are negatively skewed with mean rating of 4.19

3. Sizes are positively skewed with median size of 12 MB.

4. Prices are positively skewed with mean price of 1,median price of 0 and max price of 400.

5. Most of The Applications Are Created For Everyone

6. Approximately 92% apps are free.

7. Tools, Entertainment and Education are the top 3 genres.

8. Approximately 64% sentiments are positive, 22% are negative and 14% are neutral.

9. Mean Sentiment Polarity is 0.180904

10. Mean Sentiment Subjectivity is 0.493767

11. There are 271 apps which have 5 star rating. In which 67 apps belongs to the Family category.

12. Among Top 50 install apps 22% belongs to the communication category and 16% belongs to the Game category.

13. Events category have the maximum mean rating of 4.395313

14. Genres of Communication, Tools, Productivity and Social have the maximum no. of installs.

15. Apps belonging to Finance category have the highest mean price (8.408203) among all categories.

16. Family category has the highest no. of paid apps.

17. Game And Family Category Have The Highest No. Of Installs Of Paid Apps.

18. Installs are positively correlated with reviews with correlation value of 0.63

## References
1. GeekforGeeks
2. Kaggle
3. Analytics Vidya
