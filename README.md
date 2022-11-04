# Neural_Network_Charity_Analysis

1.	Overview of the analysis:
    o	The purpose of the analysis is to determine the applicants will be successful if funded by Alphabet Soup.  
    
2.	Results: 
    o	Data Preprocessing
      	The variables that are predictive are if the money is successful with the amount requested compared to what it is use for.
      	The variables used are features are affiliation, classification, use_case, organizations, status, income_amt, special_considerations and ask_amt.
      	We removed the EIN and name due to not being part of the applicable data for determining if it is successful.
      
    o	Compiling, Training, and Evaluating the Model
      	I initially performed the evaluation with 2 hidden neural layers and produced a 72% accuracy. 
      
      ![image](https://user-images.githubusercontent.com/103297084/200041461-d905d35c-0a0a-44a4-9c84-31e27ff72694.png)

      	Then I removed the affiliation and use case columns and added a 3rd hidden neural layer; however the accuracy declined to 65%.
      
      ![image](https://user-images.githubusercontent.com/103297084/200041549-f66562f8-6d3b-461b-b98c-aa5e157144ee.png)

      
      	I was not able to achieve the 75% accuracy rating within my findings.
      	My steps to try to optimize the data was removing 2 columns, running RandomForest and adding a third neural hidden layer.
      
3.	Summary: Overall I would continue to run the data and add more columns into the data and classify the amount asked down into categories to decrease the amount of data. This is a very interesting real-world example of using neural networks for predicting which businesses are the most likely to succeed with money donated. 

