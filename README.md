<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body>

<h1>Stroke Prediction System Using Machine Learning</h1>

<h2>Project Overview</h2>
<p>
This project involves a comprehensive analysis and prediction of stroke occurrence based on healthcare data. The analysis uses various visualization techniques to understand patterns and build predictive machine learning models. 
You can directly view and run this project <a href="https://colab.research.google.com/drive/1uEzRc0ESD-cID5b4oBdy6pRY8CGbTeMD?usp=sharing" target="_blank"><strong>here on Google Colab</strong></a>.
</p>

<h2>Table of Contents</h2>
<ul>
  <li><a href="#data-overview">Data Overview</a></li>
  <li><a href="#analysis-points">Analysis Points</a></li>
  <li><a href="#visualizations">Visualizations</a></li>
  <li><a href="#conclusion">Conclusion</a></li>
  <li><a href="#future-work">Future Work</a></li>
  <li><a href="#gallery">Gallery</a></li>
</ul>

<h2 id="data-overview">📊 Data Overview</h2>
<p>The dataset includes the following columns:</p>
<ul>
  <li>Gender</li>
  <li>Age</li>
  <li>Hypertension</li>
  <li>Heart Disease</li>
  <li>Ever Married</li>
  <li>Work Type</li>
  <li>Residence Type</li>
  <li>Average Glucose Level</li>
  <li>BMI</li>
  <li>Smoking Status</li>
  <li>Stroke (Target Variable)</li>
</ul>

<h2 id="analysis-points">🔍 Analysis Points</h2>
<ul>
  <li><strong>Probability of Stroke:</strong> Estimating the likelihood of stroke based on key health indicators.</li>
  <li><strong>Health Risk Analysis:</strong> Identifying which factors most significantly contribute to stroke risk.</li>
  <li><strong>Classification Models:</strong> Applying various ML models to classify stroke occurrence.</li>
  <li><strong>Model Evaluation:</strong> Assessing performance using metrics like Accuracy, Precision, Recall, and F1-Score.</li>
</ul>

<h2 id="visualizations">📈 Visualizations</h2>
<ul>
  <li>Feature Distribution Analysis</li>
  <li>Correlation Matrix and Heatmaps</li>
  <li>Class Imbalance Analysis</li>
  <li>Confusion Matrices</li>
  <li>ROC-AUC Curves</li>
</ul>

<h2 id="conclusion">📋 Conclusion</h2>
<p>
This project provides crucial insights into the factors leading to stroke events, showing that variables like age, hypertension, heart disease, and average glucose level play critical roles. The machine learning models — including Logistic Regression, Decision Trees, Random Forest, and K-Nearest Neighbors — demonstrated good predictive capabilities, with ensemble methods offering improved robustness.
</p>

<p>
Further improvements, such as hyperparameter optimization, advanced sampling techniques (like SMOTE), and deeper feature engineering, can enhance model performance. This work highlights the potential of data-driven predictive analytics to assist in the early detection and prevention of strokes.
</p>

<h2 id="future-work">🚀 Future Work</h2>
<ul>
  <li><strong>Hyperparameter Optimization:</strong> Fine-tune model settings for even better performance.</li>
  <li><strong>SMOTE or Class Weight Adjustments:</strong> Handle class imbalance more effectively.</li>
  <li><strong>Feature Engineering:</strong> Create additional features based on domain knowledge.</li>
  <li><strong>Model Deployment:</strong> Build a web app for real-time stroke prediction (using Streamlit or Flask).</li>
  <li><strong>Integration with Medical Data:</strong> Combine with other datasets like electronic health records for deeper insights.</li>
</ul>

<h2 id="gallery">🖼️ Gallery</h2>

<h3>Stroke Patient's Gender</h3>
<img src="https://github.com/user-attachments/assets/e2dd69a6-b978-4d72-9968-940d039d82ef" width="600" height="400">

<h3>Stroke Patient's Smoking Status</h3>
<img src="https://github.com/user-attachments/assets/5e49419a-adb7-424f-8947-437fb1df5f46" width="600" height="400">

<h3>Stroke Patient's Marital Status</h3>
<img src="https://github.com/user-attachments/assets/7caaa207-13dd-4e16-bf3a-4037b53a77f2" width="600" height="400">

<h3>Stroke Patient's Heart Disease</h3>
<img src="https://github.com/user-attachments/assets/da1fb6d1-5cdc-4c3f-a614-7243c7fa7757" width="600" height="400">

<h3>Stroke Patient's Hypertension Status</h3>
<img src="https://github.com/user-attachments/assets/335f6441-5a99-4de7-b8db-10f2c1e7a676" width="600" height="400">

<h3>Stroke Patient's Occupation Type</h3>
<img src="https://github.com/user-attachments/assets/10c84c86-01dc-481f-85b2-179f1ab1e0bf" width="600" height="400">

<h3>Stroke Patient's Residence Type</h3>
<img src="https://github.com/user-attachments/assets/0b31ec15-d135-4ade-84a7-4001b0594542" width="600" height="400">

<h3>Stroke Patient's Age Distribution</h3>
<img src="https://github.com/user-attachments/assets/342265d7-68ee-4b11-8528-81afa74af587" width="600" height="400">

<h3>Stroke Patient's BMI Distribution</h3>
<img src="https://github.com/user-attachments/assets/5c716953-ca36-46c6-ac60-383651b3b132" width="600" height="400">

<h3>Stroke Patient's Average Glucose Level Distribution</h3>
<img src="https://github.com/user-attachments/assets/c1f36807-0d7f-4298-a2e2-bc9be80d4ced" width="600" height="400">

<h3>Patient's Correlation Of Features</h3>
<img src="https://github.com/user-attachments/assets/36793a9c-bbdb-43b3-aa7e-781a0a7097e9" width="600" height="400">

<h3>Training and Testing Accuracy for Models</h3>

<h3>Performance Evaluation - Stroke Patients Analysis</h3>
<img src="https://github.com/user-attachments/assets/bf1473ac-671f-4b4c-ac7d-631902a9b431" width="600" height="400">

<h3>Confusion Matrix on Applied Testing Models</h3>
<img src="https://github.com/user-attachments/assets/204fe14d-6a48-4c3a-8508-815c67694db5" width="600" height="400">

<h3>ROC - Curve on Applied Testing Models</h3>
<img src="https://github.com/user-attachments/assets/4bc86442-2615-4c4c-8b36-74c820d67fd6" width="600" height="400">

<h3>Model Performance on Test Set</h3>
<img width="368" alt="image" src="https://github.com/user-attachments/assets/3b9c46b2-f2c6-458c-9797-7d401eb838d0" />

<h3>Prediction Test</h3>
<img width="238" alt="image" src="https://github.com/user-attachments/assets/151465c1-453c-4bdb-af9c-75bf54e52338" />


<br>

<h2>📚 Dataset Source</h2>
<p>
<a href="https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset" target="_blank">
Kaggle - Stroke Prediction Dataset
</a>
</p>

</body>
</html>
