<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
  </head>
  <body>
    <h1> PMEDS </h1>
    <p> PMEDS is a web-based system which adds an extensible diagnosis feature to the traditional HMS.
      It'll integrate entire information regarding patients, doctors, hospitals-administration etc. into one platform. For efficient data integrity and management, we provide segregation of the Core-HMS integrated with our Diagnosis Flow.
    </p>
    <p> In our application we implement a feature which allows us to predict diseases based on particular set of features </p>
    <h3> Disease Prediction based on Symptoms</h3>
    <p> To predict diseases based on symptoms we have used a dataset from kaggle.
      The processed dataset is composed of a total of <b>41 Disease</b> categores and <b>132 possible Symptoms</b> (features).
      The Classification of diseases is done by 2 methods:
      <ol>
        <li><b>Guassian Naive Bayes Classifier: </b><br> Considering the relatively small size of the dataset the test accuracy for the gaussian naive bayes classifier is 100%. Note that we have made sure that the data in the test and train file is not repeated and that the test file contains atleast 1 instance of each disease to be predicted.
         </li>
         <li><b>Decision Tree Classifier: </b> The decision tree classifier also show 100% test accuracy.
         </li>
       </ol>
<p>
     The user will input his/her symptoms (based on the symptoms set)<br><br>
        <img src="Images\page1.png"><br><br>
     And we will predict the disease acoordingly<br><br>
        <img src="Images\page2.png"><br><br>
      To run the code simply clone the git repostory and run the PMEDS_Digonstics,ipynb file</p>
        <p>Thank you!!</p>
        <p>from Team: Kleinsteins (Atulya Arya, Sayani Das, Namrata Chaudhari)</p>
  </body>
</html>
