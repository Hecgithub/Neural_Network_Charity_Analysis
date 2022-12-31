# Neural_Network_Charity_Analysis

## Overview of the analysis: 

This analysis aims to help create a binary classifier capable of predicting whether applicants will be successful if funded by Alphabet Soup. The analysis is conducted by using TensorFlow library to create, train, and evaluate data gathered from previous applications.

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing

	What variable(s) are considered the target(s) for your model? The variables that were considered for the model are the ten columns. 

![image](https://user-images.githubusercontent.com/110510718/210126625-dd3ba665-28f4-4036-a3c7-087ed4e7760d.png)

 
	What variable(s) are considered to be the features of your model? We are looking for successful applicants. The target variable is the “IS_SUCCESSFUL” column. The features would be the remaining columns.  

![image](https://user-images.githubusercontent.com/110510718/210126639-3f85ae4b-c6fd-4651-abfb-bf8e61d880e5.png)

 
	What variable(s) are neither targets nor features, and should be removed from the input data? The columns removed are the “EIN” & “NAME.” 
 
 ![image](https://user-images.githubusercontent.com/110510718/210126643-e11da964-cedb-43de-a8bf-0453a62be5ef.png)

 
### Compiling, Training, and Evaluating the Model

	How many neurons, layers, and activation functions did you select for your neural network model, and why?  
 
 ![image](https://user-images.githubusercontent.com/110510718/210126648-ae043f6c-c206-4671-8637-d50f8d8c350e.png)
![image](https://user-images.githubusercontent.com/110510718/210126653-a06f9aef-c744-42f4-9930-9205460a1246.png)

 
	Were you able to achieve the target model performance? No, the targeted performance was 75% accuracy, whereas this model produced 72% accuracy. 
 
 ![image](https://user-images.githubusercontent.com/110510718/210126658-025074eb-09ed-46cb-9518-6a5a6de6f9ff.png)

 
	What steps did you take to try and increase model performance? Another hidden layer and an output layer were added for the optimized model. The layers have 100 inputs each and there are 150 epochs used to run the model. This helped increase the model performance to 73%.    
 
 ![image](https://user-images.githubusercontent.com/110510718/210126664-47e80814-acf3-4644-aef2-3b6e19095bf2.png)

 
## Summary:  
In summary, the model can predict applicants with 72% accuracy, and with the optimized model, there was a 1% increase.  This does not meet the target predictive accuracy of higher than 75%. An alternative model that could be used is the Random Forest Classifier, also used for binary classification. An advantage to this model is that there are fewer parameters to optimize. Using a Neural Network may be a complex model for this specific problem.  
