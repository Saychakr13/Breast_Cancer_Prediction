<h1><u>Breast Cancer Prediction</u></h1>

<h3>Prediction of Breast Cancer using SVM with <u>99%</u> accuracy</h3>
Using the Breast Cancer Wisconsin (Diagnostic) Database, we can create a classifier that can help diagnose patients and predict the likelihood of a breast cancer. A few machine learning techniques will be explored. In this exercise, Support Vector Machine is being implemented with 99% accuracy.
<br>

<h3>An important catch</h3>
We have also implemented a maximum voting classifier using the two best performing classifiers. The main takeaway from this experimentation is that although the SVC classifier gives a better accuracy, the confidance(i.e the probability that the given input belongs to a particular class) with which it classifies is probably lower as compared to the KNN Classifier because of which the KNN dominates and hence SVC works better than the Voting Classifier.

<br>
<h3>Ideas for more advanced prediction techniques</h3>
Here I have experimented only with very basic models, the major reason being the small size of the dataset. If I had more data then I could have experimented with more complex models like ANN, Randomforest Classifier, XGBoost. These could have been used as baseline models in addition to the already implemented ones and the further stacking or even cascading could've been done quiet easily if a larger dataset had been given. 
Have a look at <a href="https://github.com/Saychakr13/Cancer-Diagnosis"><u>ADVANCED CANCER DIAGNOSIS USING TEXTUAL DATA</u></a> for a greater insight on how to handle such classification problems if you have a decent amount of data.
