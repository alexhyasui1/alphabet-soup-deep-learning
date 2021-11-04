# deep-learning-challenge

## Analysis Overview
The analysis used machine learning and neural networks to predict whether if the applicants funded by the charity organization known as Alphabet Soup will be successful or not. The prediction resulted from the creation of a binary classifier that analyzed a dataset containing 30,000+ organizations funded by Alphabet Soup. In this project, it comprised of:
* Preprocessing data for the neural network
* Compiling, training, and evaluating the model
* Optimizing the model

## Results

### Data Preprocessing
* Variable that I considered as the target in my model is the 'IS_SUCCESSFUL' column.
* Varibales that were considered as the features in my model is every other column except for the 'IS_SUCCESSFUL' column and everything else that has been dropped. 
* Variables that were considered to be neither targets or features are the 'EIN' and 'NAME' columns as they would have no significant value to the analysis. 

### Compiling, Training, and Evaluating the Model
* For my neural network model, it contained two hidden layers where my first layer had 80 neurons and the second layer had 30 neurons. There is also an output layer. Both my first and second hidden layers have the 'relu' activation and the activation of the output layer is 'sigmoid'.
* Unfortunately the neural network model was unable to reach the target model performance of 75%. The accuracy of my model turned out to be around 69%.
* Optimizing the neural network model to make the attempt to reach target model performance, I have increased the amount of neurons in the first hidden layer from 80 to 100. I have also increased the amount of neurons the second hidden layer from 30 to 60. Making these changes resulted in a target performance of 71% which is closer to the target model. However, I did make attempts to adding another hidden layer with varying neuron values which resulted in lower accuracy ratings. 

## Summary
The optimization model as a result reached a peak of 71% which is relatively close to the target performance model and surpassed the initial model. The loss in accuracy from making other attempts such as adding in more hidden layers could be the result of the model being overfit. The model could have also become more accurate by potentially removing more features from the dataset and also adding more data. A different model that could have been used is possibly the Random Forest Classifer which could have avoided the data from bein overfit. The Random Forest Classifier is also robust and could be deemed to be a more accurate model because of its sufficient number of estimators and tree depth. 
