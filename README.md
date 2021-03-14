# Neural_Network_Charity_Analysis

## Objective
The objective of this project is helping Bek building the predicted model where the model has capability of predicting whether applicants to "Alphabet Soup’s organization" will be successful if funded by them.

The tool we are using in this analysis is machine learning and neural networks toghether with CSV data file which containing more than 34,000 organizations that have received funding from Alphabet Soup over the years

## Preprocessing Data for a Neural Network Model

The data set we have is raw data with numperous of missing, and unusable values. We have to perform a clean up in order to be apply machine learning Neural Network Model for the analysis. After cleaning up we were able to put them into new data frame and are ready for use. Dataframe is shown as below :

Merged_DataFrame_for_Neural_Network_Model  : 
 ![alt text][Image1]
  
 [Image1]: https://github.com/ttan0408/Neural_Network_Charity_Analysis/blob/main/Merge_Dataframe.PNG "Merged_DataFrame_for_Neural_Network_Model"

## Compile, Train, and Evaluate the Model

After cleaning/pre-processing data, now we define the model "deep neural network" .The number of input features and hidden nodes for each layer are define as : two hidden layers which includes 80, 30 neuron network accordingly shown below :

hidden_nodes_1 = 80
hidden_nodes_2 = 30
 
Model using as Sequential and define as shown in the table below :

Sequential Model Summary  : 

 ![alt text][Image2]
  
 [Image2]: https://github.com/ttan0408/Neural_Network_Charity_Analysis/blob/main/Sequential_Model_Summary.PNG "Sequential Model Summary"


We compiled model with adam optimizer and trained it with 100 epoch. In this excersice we have 50% accuracy outcome for the model, and we will optimize it in the next trials
Model results as shown below :

Model Results  : 
 ![alt text][Image3]
  
 [Image3]: https://github.com/ttan0408/Neural_Network_Charity_Analysis/blob/main/First_Trained_Model.PNG "Model Results"


## Optimize the Model


