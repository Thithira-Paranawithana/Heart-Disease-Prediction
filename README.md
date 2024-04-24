# Heart-Disease-Prediction
This project aims to predict the likelihood of heart disease in patients based on various medical factors using machine learning techniques. The model is built using logistic regression, a popular algorithm for binary classification tasks.

<h3>Features</h3>
The dataset contains the following features:

<ul>
<li>Age</li>
<li>Sex</li>
<li>Chest pain type (4 values)</li>
<li>Resting blood pressure</li>
<li>Serum cholesterol in mg/dl</li>
<li>Fasting blood sugar > 120 mg/dl</li>
<li>Resting electrocardiographic results (values 0, 1, 2)</li>
<li>Maximum heart rate achieved</li>
<li>Exercise induced angina</li>
<li>ST depression induced by exercise relative to rest</li>
<li>The slope of the peak exercise ST segment</li>
<li>Number of major vessels (0-3) colored by fluoroscopy</li>
<li>Thal: 0 = normal, 1 = fixed defect, 2 = reversible defect</li>
</ul>

<h3>Dataset</h3>
Dataset contains more than 1000 tuples and all the columns except 'target' were taken as features. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.
<ul><li>Dataset link: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset</li></ul>

<h3>Model Evaluation</h3>
The logistic regression model achieved an accuracy of approximately 84% on both the training and test datasets, indicating good generalization performance. 

<h3>Libraries</h3>
<ul>
  <li>Pandas</li>
  <li>Numpy</li>
  <li>Scikit-learn</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
</ul>
