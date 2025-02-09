# Fake-News-Detection-System
## Overview
This project aims to classify news articles as *real* or *fake* using machine learning. It utilizes **TF-IDF vectorization** for feature extraction and implements classification models such as **Logistic Regression, Random Forest, and Decision Tree**.

## Technologies Used
- **Python, Scikit-learn, Pandas & NumPy**
- **TF-IDF Vectorizer**
- **Machine Learning Models (Logistic Regression, Random Forest, Decision Tree)**

## Dataset & Preprocessing
The dataset consists of labeled news articles categorized as *true* or *false*. Preprocessing steps include text cleaning, tokenization, and feature extraction using **TF-IDF**.

## Project Workflow
1. **Data Preprocessing**: Cleaning text data and removing stopwords.
2. **Feature Extraction**: Converting text into numerical form.
3. **Model Training**: Training classifiers such as Logistic Regression, Random Forest, and Decision Tree.
4. **Evaluation**: Comparing models using accuracy, precision, recall, and F1-score.

## Installation & Setup
### Clone Repository & Install Dependencies
```bash
git clone https://github.com/yourusername/fake-news-detection.git
cd fake-news-detection
pip install -r requirements.txt
```

### Run the Project
```bash
python Fake_News_Detection.py
```

## Results
- **Random Forest** achieved the highest accuracy.

## Future Enhancements
- Implement **LSTM** or **BERT** models.
- Improve **NLP techniques** for feature extraction.
- Develop a **web app** for real-time news verification.
