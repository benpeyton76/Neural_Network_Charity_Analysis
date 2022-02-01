# Neural_Network_Charity_Analysis

## ***Overview of the analysis:***

In this challenge, Alphabet Soup, a nonprofit group needs an algorithm written to predict whether an organization will be successful if they participate in the funding of the applicants. By using machine learning and neural networks, we will be analyizing the data of 34,000 applicants so that Alphabet Soup can be more informed which of the applicants will be most successful. Using the raw data provided by Alphabet Soup, we preprocessed, compiled and trained the data, then built a model that optimized the data into useful knowledge.

## ***Results:***

### ***Data Preprocessing***

- What variable(s) are considered the target(s) for your model?
    
   The IS_SUCCESSFUL column is the target for this model.


- What variable(s) are considered to be the features for your model?
    
   The columns 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', and 'ASK_AMT'     are considered to be the features of the model.


- What variable(s) are neither targets nor features, and should be removed from the input data?
  
  The columns 'EIN,' and 'Name' do not add any relavent data, therefore they were removed from the input data.


### ***Compiling, Training, and Evaluating the Model***

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

  <img width="622" alt="Screen Shot 2022-02-01 at 10 53 52 AM" src="https://user-images.githubusercontent.com/87077325/152013659-83c11ebb-7fda-49be-afe3-05797871fe9f.png">
  
  In the first model, it was compiled with two hidden layers, the first with 100 neurons and 50 in the second. The result was an accuracy score of 72.5%.
  
  <img width="622" alt="Screen Shot 2022-02-01 at 10 59 23 AM" src="https://user-images.githubusercontent.com/87077325/152014684-3a5fd294-9c7f-4ece-97a9-2ac0bb78e5db.png">

  The second model was compiled with two hidden layers, with 50 and 25 neurons respectively. The result was an accuracy score of 72.7%.
  
  <img width="625" alt="Screen Shot 2022-02-01 at 11 02 13 AM" src="https://user-images.githubusercontent.com/87077325/152015214-6a952a07-fbc3-41d6-9a1a-6fa549d74d4e.png">

   The third model was compiled of three hidden layers, with 200, 100, and 50 neurons respectively. The result was an accuracy score of 72.6%.

- Were you able to achieve the target model performance?
  
  Since none of the models acheived a score at or above 75%, this model is unsuccessful.

- What steps did you take to try and increase model performance?
  
  The steps I took to increase model performance was lower and raise the number of layers and neurons.

## ***Summary:*** 

Although the model did not acheive 75% or above, it stayed consistent and did not overperform. In order to achieve a higher accuracy score, consideration to drop more features or simply having more data could be the answer. Also, by using a different classifier and supervised learning, such as the Random Forest Classifier, we could reduce the number of outliers. By doing this, the accuracy score could become higher and a more productive model be made.
