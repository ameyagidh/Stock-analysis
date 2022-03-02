# Sentiment Analysis of Stock market

## Dataset Description

I have used the Kaggle dataset. The link is here 
https://github.com/ameyagidh/Stock-analysis/blob/main/Stock%20market%20data.csv
This dataset is a combination of Kaggle's world news and stock prices. In the data frame, there are 25 columns of top news headlines for each day, as well as Date and Label (dependent feature). The data was scraped from a variety of web sites between 2008 and 2016, with the data frame 2000 to 2008 being the most recent.

In the end I was able to reach an accuracy of 0.846.

### Steps Involved:-
1. Import the necessary Libraries.

2. Reading the dataset using pandas library.

3. Divide the data set into test and train.

4. Preprocessing on the dataset which includes stripping off the punctuations as it is unnecessary for 
sentiment analysis. Use regular expression to replace it with blank spaces.

5. Combine the headlines for a particular day placed in a row together.

6. Display the dataset periodically to check if the changes are reflected.

7. Apply random forest and count vectorizer.

8. Form the model predict the values for the test data set.

9. Plot the confusion matrix and predict the accuracy.

## Installation
Install my-project 
### Requirements:-
 1. Simply open the project on github and view it on the web browser. 
 2. To modify and work with the code you will need to have python prefered version (3.7 and above). 
 3. Change the file path in ln(3) of the notebook.
 4. An Integrated Development Environment (IDE) for python like anaconda Environment with jupyter notebook or pycharm.
 5. Libraries include sklearn, pandas, matplotlib, ntlk, seaborn and imblearn.

## Demo
you can view the notebook at https://github.com/ameyagidh/Stock-analysis/blob/main/NLP%20(Natural%20Language%20Processing)%20Stock%20analysis.ipynb
