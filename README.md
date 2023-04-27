# Hybrid-Movie-Recommendation-System
Keywords: Recommendation System, Machine Learning, Deep Learning, Natural Language Preprocessing, Convolutional Neural Networks (CNN), Hybrid Prediction System

# Summary
The increasing demand for personalized movie recommendations has motivated researchers to develop more accurate prediction systems that not only enhance user experience but also save costs for companies by targeting their marketing efforts more effectively
Ricci et al. (2011) Lu et al. (2015). The primary challenge addressed in this study is to estimate users’ movie ratings for unwatched movies based on their historical rating feedback, in
order to provide tailored recommendations Koren et al. (2009). Our proposed methodology
uses deep learning techniques (BERT and CNN) that combined text and images data in a
single network to analyze users’ historical ratings, movie profiles, descriptions, and posters
for predicting future ratings Devlin et al. (2018) Krizhevsky et al. (2012).
The key contribution of our research is the development of a hybrid prediction system
that integrates various data sources to improve the accuracy of movie recommendations.
The resulting model demonstrates a promising level of performance, with a Root Mean
Square Error (RMSE) of 0.677. This research has the potential to significantly impact
the field of movie recommendation systems and contribute to the development of more
efficient solutions for both users and companies in the entertainment industry Bobadilla
et al. (2013).

# Methods
* Text Preprocessing: Stop Words, Lowercase, Unigram and bigram, TFIDF Vectorizer, Trunicated SVD, Bert Tokenizer
* Scaler and Encoder: Min-max Scaler, Target Encoder
* Image Preprocessing: Resize Images, Tokenizer
* Modeling: XGBoost, Random Forest, BERT, CNN, Hybrid Model

# Files
* Movie_Len_data_overview.ipynb: Overview for Movie Len data, including ratings 
* data generation TMDB large.ipynb: Steps for generating descriptions for TMDB dataset and Posters
* CUDA_Model_v0_4_XGB_RF.ipynb: GPU-based XGBoost and Random Forest Models
* Model_v0_5_BERT.ipynb: BERT model
* Model_v0_5.ipynb: Hybrid Prediction System (BERT and CNN)
* Hybrid Movie Recommendation System.pdf: Final Report
