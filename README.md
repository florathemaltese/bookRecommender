# Implementing Popularity-Based and Collaborative Filtering Recommender Systems

Authors: Katherine Yuan

This project demonstrates the implementation and evaluation of two types of recommender systems. By addressing both universal and personalized recommendations, the systems collectively cater to a broad audience. 

(a) Definition of the Problem
The project focuses on developing two types of recommender systems for books: a Popularity-Based Recommender System and a Collaborative Filtering Recommender System. These systems aim to provide users with book recommendations based on overall popularity metrics and personalized suggestions by analyzing patterns in user-item interactions, respectively.

(b) Rational of target variable selection
The target variable for the Popularity Based Recommender System is the popularity of books, represented by the number of ratings and the average rating. The target variable for the Collaborative Filtering Recommender System is the ratings that users give to books (aiming to predict these ratings).

(c ) Unsupervised Learning
This problem is best approached using unsupervised learning techniques for several reasons:
Popularity-Based Recommending does not rely on previous user behavior but rather on aggregate metrics that do not require labeled training data.
Collaborative Filtering utilizes user-item interaction data to uncover latent factors that explain observed ratings, which involves matrix factorization and similarity computation without explicit supervision.

(d) Conclusion
The implementation of both systems revealed distinct advantages and challenges. The Popularity-Based System, while simpler and effective for new users, lacks personalization. In contrast, Collaborative Filtering offers tailored recommendations but requires more complex data handling and computation.
(Visual: Heatmap of Books by Number of Ratings and Average Rating)
 
(e) Scope for future work 
Enhanced Machine Learning Models: Incorporate more sophisticated machine learning techniques, such as deep learning, to enhance feature extraction and refine user profiling capabilities.
Dataset Expansion: Broaden the dataset to encompass a wider array of user interactions, which will enhance the model's accuracy and extend its applicability.
Dynamic User Interface Development: Design a more interactive user interface that supports real-time recommendations and enables immediate user feedback.

(f) Extra 5 points for GUI
This project exceeded expectations by:
•	Developing a fully functional GUI to enhance user interaction and accessibility.
•	Applying advanced visualization techniques for clearer data interpretation.
•	Creating an additional evaluation metric to thoroughly assess system performance.

