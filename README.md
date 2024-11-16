# Named Entity Recognition and Predictive Modeling for News Articles

## **Overview**
This project analyzes news articles using Named Entity Recognition (NER) to extract and quantify entities such as organizations, locations, and people. These extracted entities, along with other engineered features, are used to predict article popularity based on engagement metrics (e.g., likes, shares, and comments). The process involves text preprocessing, feature engineering, predictive modeling, and visualization.

---

## **Features**
- **Named Entity Recognition**: Extraction of named entities (e.g., organizations, locations, people) using SpaCy.
- **Text Preprocessing**: Cleaning and normalizing text for analysis.
- **Feature Engineering**:
  - Article length
  - Sentiment analysis (TextBlob)
  - Entity frequency counts
- **Predictive Modeling**:
  - Random Forest Regressor for popularity prediction.
  - Evaluation using Mean Absolute Error (MAE) and R² score.
- **Visualizations**:
  - Bar charts for entity frequency.
  - Scatter plots for sentiment vs. engagement.
  - Heatmaps for feature correlation.

---

## **Setup and Installation**

### **1. Prerequisites**
Ensure the following libraries are installed:
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- nltk
- spacy
- textblob
- scikit-learn

### **2. Install Dependencies**
```bash
pip install pandas numpy matplotlib seaborn nltk spacy textblob scikit-learn
