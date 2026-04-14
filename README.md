<h1 align="center">🛡️ Fraud Detection & Model Performance Analysis (PaySim)</h1>

<p align="center">
  This project analyzes financial transaction data to detect fraudulent behavior using 
  <b>Machine Learning models</b> and visualizes performance through an interactive <b>Tableau dashboard</b>.
  It focuses on identifying high-risk patterns and evaluating models to support 
  <b>better fraud detection decisions</b>.
</p>

<p align="center">
  <a href="https://public.tableau.com/app/profile/kishen.das/viz/FraudBehaviourAnalysisinFinancialTransactionsPaySim/Dashboard1" target="_blank">
    <img src="https://img.shields.io/badge/View-Dashboard-blue?style=for-the-badge&logo=tableau" alt="View Dashboard">
  </a>
</p>

<hr>

<h2>📂 Dataset</h2>
<p>
  This project uses the <b>Credit Card Fraud Detection dataset</b> from Kaggle.
</p>

<p>
  <a href="https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud" target="_blank">
    🔗 Credit Card Fraud Detection
  </a>
</p>

<p>
  Credit: Machine Learning Group - ULB (Université Libre de Bruxelles)
</p>

<h2>📌 Overview</h2>
<p>
  An end-to-end fraud detection project using the PaySim dataset, combining 
  <b>feature engineering</b>, <b>classification models</b>, and <b>interactive dashboards</b> 
  to evaluate and explain model performance in a business context.
</p>

<h2>⚙️ Features</h2>
<ul>
  <li>🤖 Built and compared multiple models: Logistic Regression, Random Forest, and XGBoost</li>
  <li>📊 Model evaluation using Precision, Recall, F1 Score, and ROC-AUC</li>
  <li>🎯 Confusion matrix to analyze fraud detection performance</li>
  <li>📈 Precision vs Recall trade-off visualization</li>
  <li>🧠 Feature engineering for behavioral fraud signals (e.g. balance discrepancies, transaction patterns)</li>
  <li>📊 Interactive Tableau dashboards for both EDA and model insights</li>
</ul>

<h2>💡 Key Insights</h2>
<ul>
  <li><b>XGBoost is the best-performing model</b>, achieving the highest F1 score and near-perfect recall (~99.9%)</li>
  <li>The model successfully detects almost all fraudulent transactions, with <b>only 2 missed fraud cases</b></li>
  <li>High recall is prioritized, as <b>capturing fraud is more critical than avoiding false alarms</b></li>
  <li>Key fraud indicators include:
    <ul>
      <li>Large balance discrepancies (<b>balance_diff</b>)</li>
      <li>High-risk transaction types such as <b>TRANSFER</b> and <b>CASH_OUT</b></li>
      <li>Behavioral patterns like rapid transactions and unusual timing</li>
    </ul>
  </li>
</ul>

<hr>

<h2>📊 Dashboard Highlights</h2>
<ul>
  <li>🔍 Fraud behavior analysis and exploratory insights</li>
  <li>📊 Model comparison across key performance metrics</li>
  <li>⚖️ Precision vs Recall trade-off visualization</li>
  <li>📉 Confusion matrix for real-world model evaluation</li>
</ul>
