# LTTS StepIn Titanic Project
## The Project is Basically divided into 3 parts 
 ### 1 .  Data Visualization
 ### 2 . Data Pre-processing
 ### 3 . Model building
 
## 1 . Data Visualization 
 
  for Data Visualization i have used Matplotlib and Seaborn libariries in which i have plotted the count of all columns from both classes i.e survived as well as Dead
  in that i got it .
  
  ![image](https://user-images.githubusercontent.com/55554884/126062459-221663ac-fc19-4373-9d52-4af2fbecc30f.png)

  As like this figure i have plotted al the counts of dead and survived for all columns except passenger Id
  After Some Data Pre-processing i used pair plot to get the relationship between all features using pairplot of seaborn library
  
  ![image](https://user-images.githubusercontent.com/55554884/126062529-d4380904-5fbf-4263-92db-fc4acd47fb3f.png)
## 2. Data Preprocessing part

  In data pre-processing part i remove null vaues using mean in age and ticket feature 
  Converted all the categoricals varibales into numerical 
  Finally I have selected 7 Features from all that this features are:
  
    1 . Pclass	
    2 . Sex	
    3 . Age	
    4 . SibSp
    5 . Parch	
    6 . Fare	
    7 . Embarked
## 3 . Model Bulding
  As this is classification problem we can use any classification algorithm but this is my initial stage therefore i have used logistic regression with following accuracy.
  Accuracy = 78.11 %
  
## challanges Faced 

    1 . selection of best data pre-proceesing techniques 
    2 . identifying whcich feature is important to get the best results
