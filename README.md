### Bangla-Text-Classification-Using-Machine-Learning-Approch
This repository contains the code and resources for classifying Bangla text comments into five categories: not bully, sexual, religious, threat, and troll. The project explores the use of various machine learning algorithms for text classification, including Logistic Regression, SVM, Decision Tree, Random Forest, and Multinomial Naïve Bayes.

## Dataset
The dataset used for this project can be found here. It contains a total of 44,001 Bangla text comments categorized into the five classes mentioned above.

## Data Cleaning and Preprocessing
The data cleaning and preprocessing steps included:

* Removing null values
* Removing duplicate values
* Removing unnecessary columns
* Removing punctuation marks
* Removing noise (Bangla numbers, English lines, URLs, Arabic lines, and emojis)
* Removing stop words using a publicly available stop word list from Kaggle for the Bangla language
* Performing stemming using the Bangla Stemmer library
## Feature Extraction
TF-IDF Vectorization: Term Frequency-Inverse Document Frequency (TF-IDF) Vectorization was used to convert text data into numerical features for machine learning models.
## Machine Learning Models
The following machine learning algorithms were applied to the preprocessed text data:

* Logistic Regression
* SVM (Support Vector Machine) with a linear kernel
* Decision Tree
* Random Forest
* Multinomial Naïve Bayes
## Results
* Logistic Regression: Accuracy of 78.34%
* SVM: Accuracy of 80.17%
* Decision Tree: Accuracy of 74.24%
* Random Forest: Accuracy of 75.42%
* Multinomial Naïve Bayes: Accuracy of 70.83%
## Conclusion
SVM emerged as the most suitable algorithm for classifying Bangla text comments, achieving the highest accuracy among the tested algorithms. This project demonstrates the effectiveness of machine learning in classifying Bangla text comments and provides insights for future research in text classification for the Bangla language.
## Usage Instructions
* Clone the repository
* Goggle Colab or Install Jupyter Notebook
* Python
