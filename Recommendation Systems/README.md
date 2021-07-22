AIM: 
This project replicates a real time use case of an e-commerce company, which can recommend mobile phones to a user, which are most popular and personalized respectively. 
The project was accomplished by employing recommendation techniques such as popularity based recommendation and collaborative filtering methods to recommend a mobile handset to its users based on the individual consumer’s behavior/choice.

Jupyter NB: SmartphoneRecommendation
Dataset: phone_user_review_file_1.csv to phone_user_review_file_6.csv

Actions perform:

1.Merge all the files and perform Basic EDA
2.Check for distribution of data
3.Analysis of users/products ratings : 
    Identify the most rated features
    Identify the users with most number of reviews
    Identifying products having more than 50 ratings and users who have given more than 50 ratings.   
4.Recommend top 5 mobile phones using popularity based model.
5.Build collaborative filtering models using SVD and KNNWithMeans (item based and user based)
6.Prediction and evaluation using SVD model using RMSE and MAE.
7.Recommend top 5 products for test users using SVD and KNNWithMeans.
