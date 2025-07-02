# Classification of Mental Health using XGBoost with Semantic, Syntactic, and Structural Features

## Project Review

The goal of this project is to classify text data related to individual mental health conditions. The classification is performed using an optimized XGBoost algorithm, with a particular focus on semantic, syntactic, and structural feature extraction from the text data. The project includes:

* Preprocessing of text data, includes text cleaning, data balancing, case folding, tokenization, and stemming.
* Feature Extraction: Features are extracted from the text data by focusing on three main categories:
  * Semantic Features: Extracting the meaning and context of words, using TF-IDF and N-gram.
  * Syntactic Features: Extracting information based on grammatical structure, using POS Tagging.
  * Structural Features: Extracting characteristics based on text format, using word, sentence, and character counts.
To achieve more optimal results, these features were combined, resulting in seven different experimental scenarios.
* Model Training and Evaluation: The classification model using the XGBoost algorithm, to achieve the best model performance, hyperparameter fine-tuning of XGBoost is performed using the Grid Search method.
* Results Visualization and Evaluation: The model's performance results are visualized and thoroughly evaluated, including confusion matrices, as well as accuracy, precision, recall, and F1-score metrics.
