# Legal Text Classification

A Natural Language Processing (NLP) project that uses legal case text to predict whether a case is associated with a bias label.

## Project Overview

Legal documents contain textual information such as case facts, legal reasoning, judicial opinions, and legal citations.

This project uses the `Case_Facts` text from a legal dataset and applies **TF-IDF (Term Frequency-Inverse Document Frequency)** feature extraction followed by **Logistic Regression** to predict the `Bias_Label`.

## Objective

The main objectives of this project are:

- Load and explore legal case data
- Check dataset structure and missing values
- Prepare legal case text for analysis
- Convert text into numerical features using TF-IDF
- Train a Logistic Regression classification model
- Predict the `Bias_Label`
- Evaluate model performance using accuracy

## Dataset

The dataset used in this project is:

**`legal_bias_dataset.csv`**

The dataset contains **1,500 records and 13 columns**.

### Dataset Features

- Case_ID
- Case_Type
- Court_Name
- Judges
- Case_Facts
- Legal_Reasoning
- Verdict
- Judicial_Opinions
- Bias_Indicative_Sentences
- Legal_Citations
- Document_Length
- Sentiment_Polarity_Score
- Bias_Label

The `Bias_Indicative_Sentences` column contains **766 missing values**. The remaining columns have no missing values according to the dataset check.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- Natural Language Processing (NLP)

## Text Processing

The project uses the **`Case_Facts`** column as the text input.

The text is stored in a `clean_text` column and converted into numerical features using **TF-IDF**.

The resulting TF-IDF representation contains:

- **1,500 records**
- **776 features**

## Machine Learning

### Algorithm Used

**Logistic Regression**

### Target Variable

**`Bias_Label`**

### Data Splitting

The dataset is divided into:

- 80% Training Data
- 20% Testing Data

The model uses `random_state=42` for reproducibility.

## Model Evaluation

The model is evaluated using classification accuracy.

### Result

**Accuracy: 51.33%**

## Key Highlights

- Applied Natural Language Processing techniques to legal text
- Used TF-IDF for text feature extraction
- Implemented Logistic Regression for classification
- Worked with a dataset containing 1,500 legal cases
- Achieved 51.33% classification accuracy

## Project Structure

```text
Legal-Text-Classification/
│
├── README.md
├── legal_bias_dataset.csv
└── legal_text_classification.ipynb



