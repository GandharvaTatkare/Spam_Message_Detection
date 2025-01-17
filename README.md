# Spam Message Detection

## Project Overview
This project focuses on leveraging Natural Language Processing (NLP) techniques to analyze and extract insights from text data. The goal is to process raw textual inputs and derive meaningful patterns and information to detect the Spam messages using classification machine learning models.

## Key Features
- **Data Preprocessing**: Includes text cleaning, tokenization, stop-word removal, and lemmatization.
- **Exploratory Data Analysis (EDA)**: Visualizations and statistical summaries to understand the dataset.
- **Model Building**: Training and evaluation of machine learning models with hyperparamert tuning.
- **Performance Evaluation**: Metrics such as accuracy, precision and recall.

## Dataset
The project utilizes a dataset consisting of textual messages and its lable. The data was sourced from kaggle.

## Methodology
1. **Data Preprocessing**: Standard text preprocessing techniques were applied:
   - Lowercasing
   - Removal of special characters
   - Stop-word elimination
   - Lemmatization
2. **EDA**:
   - Word cloud generation
   - Token frequency analysis
3. **Modeling**:
   - Algorithms used: Random Forest Classifier and Gradient Boosting Classifier
4. **Evaluation**:
   - Metrics: Accuracy, Precision, Recall
   - Visualization tools: Matplotlib

## Results
The final model achieved:
- **Accuracy**: [insert accuracy]
- **Precision**: [insert precision]
- **Recall**: [insert recall]
- **F1-Score**: [insert F1-score]

### Model Comparison
| Metric        | Random Forest Classifier | Gradient Boosting Classifier |
|---------------|----------------|----------------|
| Accuracy      | 97.6       | 97.2        |
| Precision     | 1.0        | 0.944        |
| Recall        | 0.829        | 0.854        |

## Dependencies
- Python 3
- Libraries:
  - Pandas
  - NumPy
  - Scikit-learn
  - NLTK
  - Matplotlib
  - Seaborn


## Future Work
- Integration of deep learning models for improved performance.
- Deployment as a web application using Flask with Docker.
- Expansion of dataset for better generalizability.
