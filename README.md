![image](https://github.com/user-attachments/assets/5c02b02a-3b5c-45a2-8eb0-a8b9a770392c)


# Google-Play-Store-App-Review-Analysis

# Project Summary
- This exploratory data analysis (EDA) project focuses on analyzing the Google Play Store apps data and customer reviews dataset. The goal is to derive actionable insights that can help app-making businesses succeed in the Android market.

- The Google Play Store data includes information about various apps such as their names, categories, average user ratings, number of reviews, size, number of installs, pricing, content rating, genres and more. This dataset provides a comprehensive overview of the apps available on the Play Store. The user reviews dataset contains customer reviews for different apps. It includes the app name, sentiment of the review (positive, neutral, or negative), sentiment polarity (numerical score indicating the review's positivity or negativity) and sentiment subjectivity (score indicating the review's objectivity or subjectivity).

# By analyzing these datasets, valuable insights can be obtained. Some potential areas of analysis include:

# App Categories: 
Identifying the most popular app categories can help developers understand the market demand and focus their efforts accordingly.

# Ratings and Reviews: 
Examining the relationship between app ratings, the number of reviews, and sentiment can provide insights into user satisfaction and feedback. It can help developers understand the factors that contribute to positive or negative user experiences.

# App Size and Installs: 
Analyzing the relationship between app size, number of installs, and user ratings can help developers optimize app sizes and understand the impact on user adoption and satisfaction.

# Pricing Strategy: 
Exploring the distribution of free and paid apps, analyzing their revenue potential, and understanding the relationship between pricing, user ratings, and downloads can guide developers in formulating effective pricing strategies.

# App Updates: 
Analyzing the frequency and impact of app updates on user ratings and reviews can provide insights into the importance of maintaining and improving app quality over time.

# Sentiment Analysis: 
Studying sentiment polarity and subjectivity in customer reviews can help identify key strengths and weaknesses of apps and guide developers in addressing user concerns and enhancing user satisfaction.

By conducting a thorough ED and gaining insights from the data, app developers can make informed decisions, prioritize areas for improvement, and create apps that cater to user needs and preferences.

# Problem Statement
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market.Each app (row) has values for category, rating, size, and more. Another dataset contains customer reviews of the android apps.

# Define Business Object :
Discovering key factors responsible for app engagement and success.

# What did you know about your dataset?
We can see that it contains two different datasets. First dataset containing information on apps that are available in the Google Play Store. This dataset contains information such as the name of the app, its category, its rating, the number of installs, price, etc. Second dataset is user reviews that contains information about app and it's reviews, sentiment of the customers, Sentiment_Polarity Sentiment_Subjectivity.

The datasets can be used for various data analysis like predicting the popularity of an app based on its characteristics or identifying trends in the types of apps that are most popular on the Play Store.

# Veriables Description
Google Play Store Data
- App - Name of the app
- Category - Category of the app
- Rating - The average user rating of the app, ranging from 1 to 5
- Reviews - Number of user reviews for the app
- Size - Size of the app in MB
- Installs - Number of installs for the app
- Type - Whether the app is free or paid
- Price - Price of the app (o if the app is free)
- Content Rating - Age group for which the app is suitable
- Genres - The category of the app according to the Play Store's classification system
- Last Updated - The date when the app was last updated on the Plav Store
- Current Ver - Current version of the app
- Android Ver - Minimum Android version reguired to run the app

# User Reviews Data
- App - The name of the app for which the review was submitted
- Translated_Review - The review text submitted by the user, translated to English if necessary.
- Sentiment - The sentiment of the customer review, which can be "Positive", "Natural", or "Negative".
- Sentiment_Polarity - The numerical polarity score of the review, rangig from -1(most negative) to 1(most positive)
- Sentiment_Subjectivity - The subjectivity score of the review, ranging form 0(objective) to 1 (subjevtive)

# What all manipulations have you done and insights you found?
- We have removed the duplicate items in 'Apps' column.
- We have the Android version and current version column as we felt that those columns are not much useful for analysis.
- We have replaced the null values in the 'Ratinas' column with median of rest of values
- We have changed the Reviews data column from object type to float.
- We have changed the Last Undated data column from dataframe tve to datetime.
- We have cleaned the Size data column by converting KB to MB for the sake of uniformity and changed the column from object type to float.
- We have changed the Price data column from object type to float.
- We have cleaned the Installs data column by removing some characters and changed the column from object type to float

# Conclusion

# App Distribution: 
- The majority of apps on the Play Store (approximately 92%) are free, indicating a preference for free apps among users. This highlights the importance of considering monetization strategies such as ads or in-app purchases.

# Age Restrictions: 
- Around 81.8% of the apps in the dataset have no age restrictions, indicating a broad target audience. This provides opportunities for developers to create apps that cater to a wide range of users

# Competitive Category: 
- The "Family" category is identified as the most competitive category, suggesting a need for developers to focus on differentiation and unique value propositions within this category.

# Popular Category: 
- The "Game" category has the highest number of app installs, highlighting the popularity of gaming apps among users. Developers can leverage this demand by creating engaging and high-quality game apps.

# Top-Rated Apps: 
- The majority of apps in the dataset are top-rated, which indicates a positive reception from users. This emphasizes the importance of delivering excellent user experiences and maintaining high-quality standards

# Category Analysis: 
- The top three categories with the highest app count are "Family! "Game" and "Tools." Developers can consider these categories for potential business opportunities.

# Genre Analysis: 
- The top genres include "Tools. "Entertainment" "Education," "Business, and "Medical." Developers can explore these genres to target specific user needs and preferences.

# Correlation: 
- There is a strong positive correlation between the number of app reviews and app installs, suggesting that popular apps tend to have a larger user base and consequently receive more reviews.


