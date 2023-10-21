# Terry Traffic Stops Analysis: Phase 3 Project


## Author
* STEPHEN KIMITI


# Overview
This project uses three predictive models to analyze and predict the chances of a suspect being stopped and arrested buy a cop based on their race, time of report and also consider the race of the cop.

In Terry v. Ohio, a landmark Supreme Court case in 1967-8, the court found that a police officer was not in violation of the "unreasonable search and seizure" clause of the Fourth Amendment, even though he stopped and frisked a couple of suspects only because their behavior was suspicious. Thus was born the notion of "reasonable suspicion", according to which an agent of the police may e.g. temporarily detain a person, even in the absence of clearer evidence that would be required for full-blown arrests etc.

There always will be officers who aspire to make a difference in their community by being proactive in their policing rather than just reactive. They come to appreciate that palpable feeling of accomplishment knowing their personal vigilance prevented a homicide, rape or robbery. Outstanding police work is the result of proper utilization of the valuable crime-fighting tool known as the Terry stop.

The public often confuses the Terry stop with "stop and frisk." It behooves law enforcement to be ready to answer the question "What is a Terry stop?" and explain to their communities it originated from the landmark United States Supreme Court Case Terry v. Ohio in which SCOTUS laid out the guidelines to be followed by police officers for making a legal investigative stop.

Terry Stops are stops made of suspicious drivers.


# Business and Data Understanding
Officer, Am I Free to Go?

Video after video on the internet show officers not making a decision when asked by a citizen if they are free to go. There are only two answers “yes” or “no” and the answer is based on your evaluation of the known circumstances at the time of the stop. Why are officers unsure of the answer?

In this project we seek to build a classifier to predict whether an arrest was made after a Terry Stop, given information about the presence of weapons, the time of day of the call, etc. This is a binary classification problem.

Our dataset also includes information about gender and race which we used. We will inquire into whether race (of officer or of subject) plays a role in whether or not an arrest is made.

# Modelling

This project uses Logistic regression, KNN Neighbours and Decision Trees with both categorical variables.
Dummy variables are created using one-hot encoding to make the most productive models.

# Regression Results

The accuracy score obtained from the KNN model 2 is approximately 89.54%. This score represents how many of the test data points were correctly classified by the model and provides the best accuracy test.

# Conclusions

From the three models, we can see that the scaled KNN model 2 provides the highest accuracy test:

KNN Model with k=16: The KNN model was configured with a value of k=16, which means that it considers the 16 nearest neighbors when making a classification decision.

Accuracy Score: The accuracy score obtained for this KNN model is approximately 89.54%. This score represents how many of the test data points were correctly classified by the model.

Here's an analysis based on the score we got:

The KNN model, with k=16, achieved a relatively high accuracy score, indicating that it performs well in classifying the test data.

An accuracy of around 89.54% suggests that the model correctly predicted the class labels for a substantial portion of the test data.

A higher value of k tends to make the model more robust and can help reduce the impact of noise or outliers in the data.

This shows that with the Terry Stops, there is a high likelihood for a suspect to be stopped based on there race i.e there is a likelihood to be stoppe if you are Not white.