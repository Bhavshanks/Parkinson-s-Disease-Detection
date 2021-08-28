# Parkinson's-Disease-Detection

EXPLANATION OF THE CODE:
 
First, we are importing all the dependencies which are needed for us that helps in detection. After this, we collect the data of 194 people from our dataset “parkinsons.csv”. The data which we have collected is in the format of voice and it is divided into 20 attributes. The head() function is used to display the whole data. The shape() function is used to display the number of rows and columns present. We have used the describe() function which gives us the statistical measures of our data. 
 
Here, we have a ‘status’ column which gives us the status of the person whether he has or does not have the disease. If the value in the status column is ‘0’, then the person does not have Parkinson’s Disease. If it is ‘1’, then the person is having Parkinson’s Disease. By using value_counts()
Function we get to know the count of diseased people and healthy people.
 
Next, we split the data into two parts, training data and test data. Usually 80% of the data is categorized as training data and the rest 20% data as test data. In our dataset after splitting the data we get, train data and test data as (156, 22) (39, 22) respectively. 
 
Next we standardize the data in our dataset. Standardization means that we convert all the values into the same value type and value range. After doing this, our data range becomes -1 to +1. 
 
We call our Support Vector Model. This model is used to train our data and check the performance of our data. As we evaluate our data, we can check the accuracy score of our model. Accuracy score is calculated by using training data and testing data. 
 
Now we will build our Predictive System which will show us the message after running the code. This acts as the main function which will in turn call the respective functions when needed.


CONCLUSION:

In this project we have discussed the importance of data mining in the field of bioinformatics and various subfields of bioinformatics in which data mining has shown its great impact. Using Colab notebook (which runs on the cloud), we pre- process the dataset on which we have worked and then using one of the classification methods i.e. Support Vector Machine method (SVM), we distinguished people with Parkinson's disease from the healthy people. Appling libsvm we have tried to find the best possible accuracy on different kernel values for the given dataset. We study the ROC curve variation, and the way the value of true positive and false positive rates changes with increasing number of the cross validation folds.
