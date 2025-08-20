<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; padding: 20px; max-width: 800px; margin: auto; background: #f8f9fa; border-radius: 8px;">
  <h1 style="color: #1565C0; text-align: center; margin-bottom: 5px;">🚢 Titanic Survival Prediction</h1>
  <p style="text-align: center; color: #455A64; font-size: 1.1em;">A machine learning project that predicts passenger survival using data analysis, feature engineering, and deep learning—built interactively in Google Colab.</p>

  <h2 style="color: #0D47A1; margin-top: 25px;">🔍 Project Overview</h2>
  <p>This project answers a classic data science question: <strong>Who survived the Titanic?</strong> It demonstrates an end-to-end workflow, from raw data to predictive model, focusing on real-world skills like handling missing data, feature engineering, model selection, and evaluation.</p>
  <ul>
    <li><strong>Exploratory Data Analysis (EDA):</strong> Uncover patterns in demographics, fares, and survival.</li>
    <li><strong>Feature Engineering:</strong> Create new features, impute missing ages with machine learning, and encode categorical data.</li>
    <li><strong>Feature Selection:</strong> Use statistical tests and wrapper methods to find the most predictive features.</li>
    <li><strong>Model Training:</strong> Build and evaluate a neural network with K-fold cross-validation.</li>
    <li><strong>Prediction:</strong> Predict survival for unseen passenger records.</li>
  </ul>

  <h2 style="color: #0D47A1; margin-top: 25px;">🧰 Libraries & Tools</h2>
  <ul>
    <li><code>pandas</code>, <code>numpy</code> — data manipulation</li>
    <li><code>matplotlib</code>, <code>seaborn</code> — visualization</li>
    <li><code>scikit-learn</code> — machine learning</li>
    <li><code>lightgbm</code>, <code>xgboost</code>, <code>mlxtend</code> — advanced modeling & feature selection</li>
    <li><code>tensorflow</code>, <code>keras</code> — deep learning</li>
    <li><code>google.colab</code> — Colab integration</li>
  </ul>

  <h2 style="color: #0D47A1; margin-top: 25px;">📁 Dataset</h2>
  <p>The <a href="https://www.kaggle.com/c/titanic/data" target="_blank">Kaggle Titanic Dataset</a> includes passenger details like class, age, sex, fare, cabin, and survival status.</p>
  <pre style="background: #f0f0f0; padding: 10px; border-radius: 5px; overflow-x: auto;">
PassengerId | Survived | Pclass | Name           | Sex   | Age  | SibSp | Parch | Ticket  | Fare   | Cabin | Embarked
----------------------------------------------------------------------------------------
     1     |    1     |   3    | Braund, Mr... | male  | 22   |  1    |  0    | A/5 2117| 7.25   |       | S
     2     |    1     |   1    | Cumings, M... | female| 38   |  1    |  0    | PC 17599| 71.2833| C85   | C
  </pre>

  <h2 style="color: #0D47A1; margin-top: 25px;">⚙️ Data Preprocessing</h2>
  <ul>
    <li>Handle missing values and outliers</li>
    <li>Encode categorical features (one-hot, label)</li>
    <li>Engineer new features (e.g., title, cabin group)</li>
    <li>Impute missing ages with LightGBM & Random Forest</li>
    <li>Scale and normalize features for neural networks</li>
  </ul>

  <h2 style="color: #0D47A1; margin-top: 25px;">📊 Exploratory Data Analysis</h2>
  <ul>
    <li>Visualize survival by class, sex, and age group</li>
    <li>Analyze fare distribution vs. survival</li>
    <li>Plot missing value patterns</li>
    <li>Heatmaps for feature correlation</li>
    <li>Cross-feature survival rate plots</li>
  </ul>

  <h2 style="color: #0D47A1; margin-top: 25px;">🧠 Machine Learning Pipeline</h2>
  <ul>
    <li><strong>Feature Selection:</strong> SelectKBest (Chi-square, ANOVA), Variance Threshold, correlation, and wrapper methods (SFS, RFE, SFFS)</li>
    <li><strong>Model Training:</strong> Neural network with TensorFlow/Keras, K-fold cross-validation</li>
    <li><strong>Evaluation:</strong> Accuracy, precision, recall, F1, confusion matrix, ROC/AUC</li>
    <li><strong>Visualization:</strong> Training history, feature importance</li>
  </ul>

  <h2 style="color: #0D47A1; margin-top: 25px;">🚀 How to Run</h2>
  <ol>
    <li><strong>Clone the repo:</strong> <code>git clone https://github.com/praveenc1903/titanic-survival-prediction.git</code></li>
    <li><strong>Open in Colab or Jupyter:</strong> Launch the notebook in your preferred environment.</li>
    <li><strong>Install dependencies:</strong> <code>pip install pandas numpy matplotlib seaborn scikit-learn lightgbm xgboost mlxtend tensorflow keras</code></li>
    <li><strong>Download the dataset:</strong> From Kaggle or use the built-in Colab loader.</li>
    <li><strong>Run the notebook:</strong> Follow the narrative, visualize the data, and train the model step by step.</li>
  </ol>

  <h2 style="color: #0D47A1; margin-top: 25px;">👨‍💻 Author</h2>
  <p><a href="https://github.com/praveenc1903" target="_blank">Praveen C</a></p>
</body>
</html>
