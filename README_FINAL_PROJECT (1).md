<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Predicting Hotel Reservation Cancelations
*[Mubarik Ibrahim]*

*[DAFT, Berlin, January 2021]*

## Content
- [Project Description](#project-description)
- [Hypotheses / Questions](#hypotheses-questions)
- [Dataset](#dataset)
- [Cleaning](#cleaning)
- [Analysis](#analysis)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

## Project Description
Hotel reservation cancelation pose a challenge to management. In order to avert this challenge there is the need to dig deeper to understand reasons that might be contributing to the cancelations. This project seeks to identify the features related to cancellation and to predict the rate at which reservations are cancelled. 

 Question
Using machine learning to predict hotel reservation cancelations. 

## Dataset
Dataset obtained from kaggle

## Cleaning
The data was pretty much clean. I have to deal with some few nans, convert some floats into int. 

## Analysis
Data Wrangling

## Model Training and Evaluation
*Include this section only if you chose to include ML in your project.*
*I initially picked my features manually by looking at the hit map for numericals and then chi2 for categoricals. I ran my first model and then proceded to use RFE to get my 10 best features. Eventhough the feautures are not that different my score varied slightly. I ended up running the model using Logistic regression, Radom Forest and Decision tree.

## Conclusion
The feautures that are picked for the model are the best in terms of correlation but could not give a very high score.
Detailed customer information needs to be added to the data in order to get a better prediction. Feuatures do not include hotel facilities that are related to the rooms so it may contribute to cancelations or even customer ratings. 
* Interpret your findings in terms of the questions you try to answer.


## Future Work
Address any questions you were unable to answer, or any next steps or future extensions to your project.

## Workflow
Obtaining data from kaggle as a csv file, dealt with nans, feauture engineered, built models and then observed the results. 
How did you test the accuracy of your analysis and/or machine learning algorithm?

## Organization
How did you organize your work? Did you use any tools like a trello or kanban board?

What does your repository look like? Explain your folder and file structure.

## Links
Include links to your repository, slides and trello/kanban board. Feel free to include any other links associated with your project.


[Repository](https://github.com/)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/en)  
