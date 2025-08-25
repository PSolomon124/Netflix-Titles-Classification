🎬 Netflix Titles Classification (Movie vs TV Show)

This project explores the Netflix Titles dataset and applies Natural Language Processing (NLP) with Machine Learning to classify whether a title is a Movie or a TV Show based on its description.

📂 Dataset

File used: netflix_titles.csv

Contains metadata of Netflix content including title, type, release year, and description.

⚙️ Tech Stack

Python

Pandas, Matplotlib, Seaborn → Data Analysis & Visualization

WordCloud → NLP Visualization

Scikit-learn → TF-IDF, Logistic Regression, Model Evaluation

🔎 Steps in the Project
1. Data Exploration & Visualization

Distribution of Movies vs TV Shows

Number of releases per year

WordCloud of most frequent terms in descriptions

2. Data Preprocessing

Target variable:

0 = Movie

1 = TV Show

Feature: description

TF-IDF Vectorization (max 5000 features, English stopwords removed)

3. Model Building

Algorithm: Logistic Regression

Train-Test Split: 80/20

4. Model Evaluation

Classification Report (precision, recall, f1-score)

Confusion Matrix visualization

ROC Curve with AUC score

📊 Results

The model was able to classify Movies vs TV Shows with good accuracy.

The ROC Curve demonstrated strong discriminative ability.

🚀 How to Run

Clone this repo:

git clone https://github.com/your-username/netflix-classification.git
cd netflix-classification


Install dependencies:

pip install -r requirements.txt


Run the notebook or Python script:

python netflix_classification.py

📌 Key Learnings

How to preprocess text using TF-IDF

Building and evaluating a simple text classification model

Using data visualization for exploratory analysis

🖼 Sample Visualizations

📍 Distribution of Movies vs TV Shows
📍 WordCloud of most frequent terms
📍 Confusion Matrix of predictions
📍 ROC Curve with AUC

✨ This project demonstrates how NLP + Machine Learning can uncover insights from media content descriptions.
