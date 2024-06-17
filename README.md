
# H1N1 FLU VACCINATION PREDICTION: A Machine Learning Project
## Project Overview

The aim of this study is to predict how likely individuals are to receive their H1N1 flu vaccine. I believe the prediction outputs (model and analysis) of this study will give public health professionals and policy makers, as an end user, a clear understanding of factors associated with low vaccination rates. This in turn, enables end users to systematically act on those features hindering people to get vaccinated.

In this project, we used the survey data from hackathon G2G to predict whether or not respondents got the H1N1 vaccine. It is important to understand past vaccination patterns in order to understand those of more recent pandemics, such as COVID-19. The most influential factors determining vaccination status are found to be Doctor Recommendation of H1N1 vaccine, Health Insurance, Opinion of H1N1 Vaccine Effectiveness, and Opinion of H1N1 Risk.

So as to classify exactly those who got H1N1 flu shot from those that did not, we need a higher accuracy of the model outputs, as well as a high precision score, which is related to a low false positive rate (those who predicted to be vaccinated but did actually not get H1N1 flu shot). 

## Project Results

Gradient Boosting model did not overfit to the training set, we got similar AUC, precision and accuracy scores for the holdout set. Because the model does a good job of minimizing the false positive rate on the hold out data, we are fairly confident that it will generalize well to unseen data and will accurately help public health offials determine the people who didn't get the vaccine. 

I also looked into feature importances to understand the relationship between the features and vaccination behavior. I saw that the demographic and behavioral features are not that important compared to health related factors and opinions. The doctor recommendation, health insurance, opinion of vaccine efficiency, and opinion of H1N1 risk are the top important factors in determining people's vaccination status.


## Conclusion

We recommend that public health officials at the American Public Health Association (APHA) communicate to doctors the importance of recommending to patients that they get the H1N1 vaccine. We also recommend that they find a way to make the vaccine accesible to people regardless of health insurance status. Additionally, because opinion on H1N1 vaccine effectiveness and H1N1 risk to health are highly influential in determining vaccination status, we recommend that the APHA make educational outreach a priority. Our analysis might not fully resolve the goal of predicting H1N1 vaccination status because we were not able to fully rule out false negatives, or people who we predicted as not getting vaccinated but actually did get the vaccine. Additionally, there may be other factors at play which were not tapped into by this survey's questions which could also play a role in vaccination prediction. 
