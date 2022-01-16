# Neural_Network_Charity_Analysis


## Overview:  
The purpose of this challange is to create a classifier to predict whether an application will be successful based on provided features. 

## Results:  

 *use bullet and images to support the following answers :*

Data prepocessing:  
- The target is column IS_SUCCESSFUL.    
- Variables that considered as features are: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.  
- Columns EIN and NAME are considered neither targets or features.

compiling, Training, and Evaluation
- how many neurons, layers and activation functions used, and why?
- how the target model performance? accuracy and etc


The following are the approaches to increase model performance:
- increased neurons in the hidden layers
- increased hidden layers
- changed activation functions combinations
- tried RandomForestClassifier and SVM
- increased the epoch number per training
- increased input numbers by bucketing the categorical variables into various bucket numbers
- restarted kernel 



## Summary  


 *summarize overall results of the deep learning model.  
 recommend a different model for this problem, and explain why*  

In Neural_Network_Charity_Analysis.ipynb, in cell 44 where model was training by 100 epoches and checkpoints was saved by every epoch, the process was mannually stopped as it took too long to run, and yet the result accuracy was similar, around 0.7266. 
 
 
 ## *codes to be uploaded:*

 3. AlphabetSoupCharity_Optimization.ipynb
 4. AlphabetSoupCharity_Optimization.h5
