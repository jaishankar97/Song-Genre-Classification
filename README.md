# Song-Genre-Classification
Training machine learning models to classify a song lyrics into two genres: 'Rock' and 'Hip-Hop'. 

The aim of the project is to identify the song genre as either 'Rock' or 'Hip-Hop' based over different variables such as follows:

- Acousticness

- Danceability

- Energy

- Instrumentalness

- Liveness

- Speechiness

- Tempo

- Valence

- Genre

Steps followed in the project:

- Finding relationship among continuous variables in the dataset using correlation and reducing the number of columns avoiding feature redundancy.

- Not much information was available using correlation, so used a dimentionality reduction algorithm to reduce the number of features.

- Identified the optimal number of features using visualisations and applied scaling to each variable. 

- Used Principal Component Analysis (PCA) to reduce the number of columns. 

- Finally the best part, used five types of classification models: Logistic Regression, Naive Bayes, SVM, Decision Trees, Random Forest to classify songs. 

- It was observeed from precision and f1 scores that the dataset was unbiased and was underperforming for the genre 'Hip-Hop' as compared to genre 'Rock'.

- Used a sampling technique to balance the dataset into equal number of genre frequencies. 

- Again declared objects and trained the different classification models using the new data. 

- Better, the results observed using new data were better and the models were performing better in determining the results for both genres. 

The f1 score for each model were above 80 for each model except Decision Trees (74).

Lastly, the classification models were trained for the final time using KFold cross validation technique using the new data where only Random Forest (81) was able to achieve a score over 80.

Overall on this dataset, Random Forest and Naive Bayes performed well, with Logistic Regression and SVM performing on average, and Decision Tree performing below average. 

Adequate references are mentioned in between scripts in the ipynb file. 

The problem statement and the data were a part of the DataCamp Projects which I have expanded a bit further as per my interests and exploring the topic more indepth. 

Future Work: Applying exploratory data analysis and statistical applications on the dataset to explore the continuous variables.
