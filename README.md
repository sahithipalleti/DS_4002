# DS_4002
# Restaurant Review Sentiment Analysis Case Study

This repository contains a DS 4002 case study based on the project **Predicting Restaurant Review Sentiment From Text**. The goal of this case study is to guide students through building a machine learning model that predicts whether restaurant reviews are positive, neutral, or negative based on written review text.

---

## Repository Contents

This repository includes the materials needed to understand and complete the case study, including the hook document, rubric, raw dataset, starter code, and background references on sentiment analysis and restaurant reviews.

---

## Software and Platform

This project was completed using:

- Python
- Jupyter Notebook / Google Colab
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

### Platform Used

- MacOS

---

## Repository Map

```text
restaurant-sentiment-case-study/
│
├── README.md
│
├── data/
│   └── restaurant_reviews.csv
│
├── hook_document/
│   └── hook_document.pdf
│
├── rubric/ 
│   └── cs3_rubric.pdf
│
└── references/
    ├── starter_code.py
    ├── Understanding Sentiment Analysis.pdf/
    └── Opinion mining and sentiment analysis.pdf/
    └── Hospitality_Insights_Restaurant_Reviews.pdf.pdf
```

---

## Instructions for Reproducing Results

### Step 1: Download Repository

Download or clone this repository to your local machine.

### Step 2: Install Required Packages

Run the following command:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Step 3: Open Dataset

Open the raw dataset located in the `data/` folder.

### Step 4: Open Starter Code

Open the starter code file located in the `references/` folder.

### Step 5: Load Dataset

Load the restaurant review CSV file into Python using pandas.

### Step 6: Clean the Data

Clean the dataset by:
- Removing missing review text
- Removing unnecessary columns
- Standardizing text formatting

### Step 7: Create Sentiment Labels

Convert star ratings into sentiment categories:

- 1–2 stars = negative
- 3 stars = neutral
- 4–5 stars = positive

### Step 8: Split the Data

Split the dataset into training and testing sets.

### Step 9: Vectorize Text

Use TF-IDF or Count Vectorization to convert review text into numerical features.

### Step 10: Train Models

Train at least two classification models, such as:

- Logistic Regression
- Naive Bayes

### Step 11: Evaluate Performance

Evaluate model performance using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrices

### Step 12: Compare Results

Compare the model performances and identify which model performs best.

### Step 13: Review References

Use the references in the `references/` folder to support your discussion of sentiment analysis, restaurant reviews, and limitations of the model.

---

## Expected Output

By the end of the case study, students should have:

- A cleaned restaurant review dataset
- A trained sentiment classification model
- Model evaluation metrics
- Visualizations showing class distribution and model performance
- A short written explanation of results, limitations, and next steps
