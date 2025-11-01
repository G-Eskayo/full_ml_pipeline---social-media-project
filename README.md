# ML Pipeline for Social Media Engagement Prediction

This project demonstrates how to build a **complete machine learning pipeline** in Python using **scikit-learn** to predict engagement levels on social media posts. The workflow includes data exploration, preprocessing, pipeline construction, model training, and evaluation.

---

## 🎯 Project Overview

- **Goal:** Predict social media engagement based on post attributes.
- **Dataset:** Custom dataset of social media posts with attributes such as platform, post type, post day, sentiment score, and engagement metrics (likes, comments, shares).
- **Motivation:** Showcase ability to design end-to-end ML workflows using scikit-learn Pipelines and ColumnTransformer.

---

## 🛠️ Features

- **Exploratory Data Analysis (EDA):**
    - Inspected dataset structure with `.info()`, `.describe()`, and `.value_counts()`.
    - Visualized distributions and correlations (e.g., engagement by platform and post type).
- **Data Preprocessing:**
    - Numeric features (likes, comments, shares) scaled with `StandardScaler`.
    - Categorical features (platform, post_type, post_day, sentiment_score) encoded with `OneHotEncoder`.
    - Verified dataset completeness (no imputation required).
- **Pipeline Design:**
    - Constructed a `ColumnTransformer` to apply transformations.
    - Combined preprocessing + model into a unified **scikit-learn Pipeline**.
- **Model Training & Evaluation:**
    - Trained **Logistic Regression** and **Decision Tree Classifier**.
    - Split dataset into training/testing sets with `train_test_split`.
    - Evaluated performance using accuracy metrics.

---

## 🤖 Tech Stack

- **Language:** Python 3.x
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn
- **Tools:** Jupyter Notebook

---

## 🚀 How to Run

git clone https://github.com/yourusername/social-media-ml-pipeline.git
cd social-media-ml-pipeline
pip install -r requirements.txt
jupyter notebook social_media_pipeline.ipynb


---

## 📊 Example Outputs

- Distribution plots of engagement metrics across platforms.
- Correlation heatmaps for likes, comments, and shares.
- Accuracy comparison of Logistic Regression vs. Decision Tree.

*Consider adding screenshots of your visualizations or confusion matrix here.*

---

## ✅ Skills Demonstrated

- End-to-end ML pipeline construction
- Feature engineering (scaling, encoding, categorical handling)
- Classification model training (Logistic Regression, Decision Tree)
- Model evaluation with accuracy metrics
- Visualization & EDA for structured data

---

## 📂 Project Structure

social-media-ml-pipeline/

├── social_media_pipeline.ipynb # main notebook

├── requirements.txt # dependencies

├── report.pdf # optional project write-up

└── README.md # documentation
