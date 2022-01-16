# Neural_Network_Charity_Analysis


## Overview:  
The purpose of this challange is to create a deep learning classifier to predict whether an application will be successful based on provided features. 

## Results:  
Data prepocessing:  
- The target is column IS_SUCCESSFUL.    
- Variables that considered as features are: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, NAME, and ASK_AMT.  
- Columns EIN is considered neither target or feature.

Compiling, Training, and Evaluation:  
- As shown in the screenshot below, there are 185 neurons for the first layer, 95 for the second layer, 65 for the third layer, and one for output layer: total 3 hidden layers. The activation functions are relu for the hidden layers, and sigmoid for the output layer. These numbers are reached to increased model performance. Increasing number of neurons and hidden layers will enhance model performance to some degree.   
![image](https://github.com/kaylaisnomyname/Neural_Network_Charity_Analysis/blob/main/Images/model_structure.png?raw=true)  

- This deep learning model has an accuracy of 0.751。  

- The following are the approaches to increase model performance:
    - increased neurons in the hidden layers
    - increased hidden layers
    - changed activation functions combinations  
    - increased the epoch number 
    - increased input features by bucketing the categorical variables



## Summary:  

The overall outcome is merely satisfying as the model only achived 75.1% of accuracy, with a loss of 55.4%. The total runtime for the optimization is 22min. The deep learning model is expected to be further refactored.  

The same training\testing sets are fitted to Random Forest model and SVM, with the accuracy of 75.2% and 73.7% respectively. If to recommand a different model, the Random Forest model is a better one, as it achived slightly better accruracy.  

  
ps:  
In Neural_Network_Charity_Analysis.ipynb, in cell 44 where model was training by 100 epoches and checkpoints was saved by every epoch, the process was mannually stopped as it took too long to run, and yet the result accuracy was similar, around 0.7266. 
 
 
