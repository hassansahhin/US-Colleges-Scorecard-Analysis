# US-Colleges-Scorecard-Analysis
The College Scorecard is designed to increase transparency, putting the power in the hands of the public — from those choosing colleges to those improving college quality — to see how well different schools are serving their students.
College Scorecards make it easier for students to search for a college that is a good fit for them. They can use the College Scorecard to find out more about a college's affordability and value so they can make more informed decisions about which college to attend. 


## Introduction to the dataset
><a href="https://catalog.data.gov/dataset/most-recent-cohorts-scorecard-elements">Dataset link</a> <br>
><a href="https://collegescorecard.ed.gov/assets/FullDataDocumentation.pdf">Technical Documentation: College Scorecard Institution-Level Data</a> <br>
><a href="https://collegescorecard.ed.gov/assets/FieldOfStudyDataDocumentation.pdf">Technical Documentation: College Scorecard Data by Field of Study</a> <br>
>Dataset last update: August 7, 2021

## Explorative model
<ul>
    <li>Visualizing the percenatge of US  Colleges accrding to Control type (public / private) and Degree granting (bachelor ,associate  ,etc.. )</li>
    <li>Visualizing the relation between the Control type and the Degree granting</li>
    <li>Visualizing the distribution of the Colleges across US</li>
    <li>Visualizing The distribution of SAT and Scores accross the degree granting</li>
</ul>

## Predictive Model
### Problem definition
Build a predictive model to predict the fair net price for each college  (public institutions)and (private for-profit and nonprofit institutions)
### Context
Does your college deserve the net price paid for it ?<br>
Whether you’re just beginning to build your college list, or if you’re narrowing down some choices you’ve already made, one of the top factors in many students’ decision is, you guessed it: money.  Most of us know college can be expensive, but what you might not know is that college doesn’t cost the same amount of money for every student. <br>
<b>College can and should be affordable. That’s why we’re here to help.</b>
### Approch
Using the College scorecard dataset we will use some predictor factors including some information on the school itself  , information about the admission requirement  , information about the earning and aid to predict the fair price of the colleges using Random forrest regressor    


## Contribution
please feel free to colne the repo
`https://github.com/hassansahhin/US-Colleges-Scorecard-Analysis.git`
* Descover more pattern and relationships between the varaibles 
* Increase the accuracy of the predicting model 
* Review my code and provide me with more efficent ones


## Limitation

The future work in this project may include implementing some other machine learning models like knn (k-nearest neighbors), rpart (decision trees), etc., training the model with only top important features, exploring additional features related to institutes and demographics, and exploring other years’ cohort data.

Also the Data contain a big amount of Null values which effect the performance of the model  
    
    
