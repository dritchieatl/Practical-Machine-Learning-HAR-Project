# Practical-Machine-Learning-HAR-Project

Project Scope
In this project, my goal is to use data from accelerometers on the belt, forearm, arm, and dumbbell of 6 participants and accurately predict if they performed correctly or incorrectly based on the "classe" variable. I will use the Caret, Randon Forest and GMB packages within R.
Results and Conclusion
Since this is a classification prediction, I used Random Forest (RF) for my final model and ran a Generalized Boosted Model (GBM) for comparison based on my system resources and their ability to address 'empty' data fields within themselves. Both were run using K-Fold cross validation of 5 (again system resources and time were a factor), which allows repeating the cross validation function with exactly the same splitting results for each repetition. I used 70% of the 19,622 observations available for my training set.
Random Forest produced an average accuracy of 99.06% and the Generalized Boosted Model had accuracy of 95.77%. I used the RF model output as the final model on the test data of 20 observations and was able to predict with 100% accuracy. Both produce promising Confusion Matrix's and I found it very interesting in how the different models top 15 variants of importance differed. 
