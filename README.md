# CinFind: Your Personalized Movie Recommender

## Introduction
The CinFind project aims to develop a personalized movie recommendation tool that enhances user satisfaction by leveraging cloud, big data, and machine learning technologies.

## Research Questions
1. What factors are more important in movie ratings: critical reviews (Tomatometer scores) or audience preferences?
2. Can we create personalized movie recommendations based on individual user preferences?
3. How accurate can predictive modeling be in figuring out movie ratings?
4. What are the potential business outcomes of this project for streaming platforms and movie-aggregation websites?

## Dataset
The dataset for this project was sourced from Rotten Tomatoes, a renowned cinema review-aggregation website. Web scraping techniques with BeautifulSoup and the rottentomatoes Python library were used to extract diverse movie data, including ratings, genres, and audience scores. The data was then stored in a SQLite database for efficient access and processing.

## Web Application
The CinFind project includes a web application developed using Streamlit, a popular Python library for building interactive web applications. The Streamlit deployment allows users to interact with the movie recommendation system and explore the project's findings.

The key features of the Streamlit web application include:

1. **Personalized Recommendations**: Users can input their preferences, such as genre, rating, and cast, and the application will provide personalized movie recommendations based on the K-Means clustering model.

2. **Exploratory Data Analysis**: The application includes interactive visualizations and data exploration tools that allow users to gain insights into the factors influencing movie ratings, such as the relationship between critical reviews and audience preferences.

3. **Predictive Modeling**: Users can explore the performance of the predictive modeling techniques used in the project, such as the accuracy of the K-Means clustering model in estimating similar movies.

4. **Analytics**: The application provides various analytics and metrics related to the movie data, such as genre trends, top-rated movies, and performance of different recommendation algorithms.

5. **Maintenance and Updates**: The Streamlit deployment allows for easy maintenance and updates to the web application, ensuring that the recommendation system remains current and relevant.

The web application is designed to be user-friendly and intuitive, allowing both movie enthusiasts and industry professionals to leverage the insights and personalized recommendations provided by the CinFind project.

To run the web application, users will need to have the following files in their project directory:

- `movies.db`: The SQLite database containing the movie data.
- `app.py`: The Streamlit application file that defines the user interface and functionality.

By providing a robust and interactive web-based interface, the CinFind project aims to enhance the movie-watching experience for users and offer valuable insights to streaming platforms and movie-aggregation websites.


## Methodology
The project followed a four-step methodology:
1. Web scraping and database storage
2. Exploratory data analysis (EDA), data pre-processing, and cleaning
3. Predictive modeling using K-Means clustering
4. Deployment of the web application using Streamlit

## Results and Findings
1. Both critical reviews (Tomatometer scores) and audience preferences significantly influence movie ratings, with certain genres like drama and sci-fi tending to have higher-rated movies.
2. The K-Means clustering model demonstrates promising cluster creation in estimating similar movies based on features like genre, rating, cast, and title, which can be leveraged by streaming platforms and movie-aggregation websites to provide personalized recommendations and enhance user engagement and satisfaction.

## Conclusions
1. The project successfully utilized web scraping, relational databases, machine learning, data pre-processing, and web application deployment to create a personalized movie recommender.
2. The findings shed light on critical factors influencing movie ratings, genre trends, and the effectiveness of personalized recommendations.
3. Future opportunities include integrating the application with PySpark Streaming and comparing/updating records in the database.

## References
1. Rottentomatoes-python Library · PyPI
2. Localtunnel for Web Application Hosting
3. "Machine Learning based Movie Recommendation System"
4. "An Efficient movie recommendation algorithm based on improved k-clique methods"
5. Other referenced links
