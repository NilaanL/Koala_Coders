#CKD prediction ML Model

#Problem
In the last two decades, chronic kidney disease of unknown etiology (CKDu) has emerged as a significant contributor
to the burden of chronic kidney disease (CKD) in rural Sri Lanka. It is characterized by the absence of identified causes for CKD.
The prevalence of CKDu is 15.1–22.9% in some Sri Lankan districts, and papers from renowned conferences have found an association
with farming occupations. Over the last two decades, 23,000 people have died from and an estimated 69,000 have been diagnosed with CKDnT.
Main victims of this disease are farmers, as we all aware that SL is a farming country so CKDu greatly affects our economy too. 
Evidence to date suggests that the disease is related to one or more environmental agents, however pinpointing a definite 
cause for CKDu is challenging. It is plausible that CKDu is multifactorial. From the research we have done we found that in 
Srilanka doctors are doing EGFR (estimated glomerular filtration rate) test to predict and diagnose CKDu, it is a number based 
on the amount of keratin (waste cells) in our blood cells. This test itself is not ideal because the test is not suitable for children,
pregnant ladies and overweight people. This is an expensive test so this test can’t be applied for mass population. So our team has
come up with a solution which will act as a path breaker in the area of prevention and quality diagnosis from CKDu.


#Solution
The solution we are proposing is a machine learning model which has the ability to predict CKDu in the people who are affected/not affected by CKDu. 
As a first step we are planning to implement this model as an pre-test for CKDu so if someone is tested and the result suggests that 
they have high probability of CKDu in our test so they can be preceded to eGFR test. If the probability is low, they can avoid the eGFR 
test which is expensive. As our future step we have a vision to achieve a high accuracy so we can solely depend on this model. 

We have chosen the supervised learning ML model for our project as the classifications needed has a clear decision boundary to distinguish
the different classes accurately (we are very specific about the definition of the classes). Since we have gathered data sets of patients 
under more than 20 features (age, gender, diabetes history, mean eGFR etc.) labelling the data set will have a huge advantage on our 
training model.  As we have sufficient labeled data sets of both CKDu affected patients and healthy patients, training the model with 
the data known (labeling) will have an added advantage on the learning rate and reach the optimal model. 
