# coderscave

Task-1 EDA analysis on Terrorism-dataset can be downloaded from Kaggle
In task 1 of eda analysis we made data collection,data preprocessing,data cleaning,data visualizations are made for better understanding the analysis made on terrorism 
intially I cleaned the data and I made an analysis on how much the data has been distributed over a particular range for this I used country_codes that refers the country names, I found the central tendency measures of 'killed','wounded' and I found how much the data has been distributed throughout the raw data using interquartile range and z score gives us the number of standard deviations of the particular data after finding all these we used data visualization techniques to draw out the outcomes of terrorism and comparison is made on different types of attacks and killed people and different types of weapons used and targets were made and so on. As the data is highly imbalanced,raw and unorganized we need to adapt k means clustering for avoiding the complexity of the analysis that we are making. Thus k means provides us a good accuracy level on the which part of terrorism was more and hamming loss and subset accuracy are calculated as it is a mulitlabel classification and time series analysis is used to see how terrorism can affect in the future times.

Task-2 Breast Cancer prediction
In task 2 we deal with breast cancer prediction here we cleaned the data I preprocessed it and visualized it and applied some algorithms to see which model is suitable for giving an accurate level of predictions.
intially data is cleaned and calculations on the distribution of the data are made and the best part about this is the dataset was really organised to work on. I created data visualizations on various metrics of the tumor and the diagnosis. The algorithm comparisons here was made on KNN,regression and decision tree classfification,I train-test and split the model and in knn with n_neighbours=3 I created a y prediction set and a model was fit into it the performance analysis were made and it gave an accuracy of 0.94 which is probably not overfitting and not underfitting. In decision tree model we yielded a 1 which is overfitting that may cause further problems in the model such as the model cannot be flexible in some situations and so on. In regression we got a good results lower the MAE,RMSE,MSE the good is the model and a higher of variance score is preferred so according the analysis made knn can be a choice to predict breast cancer.



Task-3 Email spam Detection 
In task 3 we dealt about email spam detection a dataset was taken with the mixture of both spams and hams. Hams were the predominants in our dataset.So started by data cleaning and processing and categorized values for spams and hams were given as we know for each type of dataset there must be a different approach carried on as this being a full of text variables we used multinomial naive bayes and count vectorizer for natural language processing to make our work much simpler and easier and we then trained and fit the model and made it to do a prediction on email spam detection the scores for the prediction was 0.98 percent which is not overfitting and underfitting. Thus our model has been successfully developed

Task-4 Speech Emotion Recognition

In task 4 we dealt with speech emotion we used the dataset RAVDESS from kaggle which contained numerous amounts of actors voices with different emotions such as happy,sad,disgusted,calm,neutral,angry and so on a dataframe was created for the respective emotions and visualizations were made further we made data augmentations such as stretch,pitch,noise and so on as a model was developed for the repective speech emotion dataset 



