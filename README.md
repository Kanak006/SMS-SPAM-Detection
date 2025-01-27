
# SMS Spam Detection Model  

### Developed by **Kanak Rahangdale**  

## Overview  
SMS Spam Detection is a machine learning model designed to classify SMS messages as **Spam** or **Not Spam**. The model processes the text input and makes predictions in real-time through a simple and user-friendly web interface.  

## Features  
- Data Collection and Cleaning  
- Text Preprocessing (Tokenization, Stop Words Removal, Stemming)  
- Exploratory Data Analysis (EDA) with visualizations like word clouds and heatmaps  
- Machine Learning Model Training and Selection  
- Deployed on the web using **Streamlit**  

## Technology Stack  
- **Python**  
- **Scikit-learn**  
- **Pandas**  
- **NumPy**  
- **Streamlit**  

## Dataset  
The dataset was sourced from [Kaggle SMS Spam Collection](https://www.kaggle.com/uciml/sms-spam-collection-dataset), containing over 5,500 SMS messages labeled as spam or non-spam.  

## Workflow  

### 1. Data Collection  
- Imported the SMS Spam Collection dataset from Kaggle.  
- The dataset includes two columns: the SMS message and its label (`ham` for not spam, `spam` for spam).  

### 2. Data Cleaning and Preprocessing  
- Removed null and duplicate values.  
- Performed label encoding for the "type" column.  
- Preprocessed text by:  
  - Converting to lowercase.  
  - Removing special characters, punctuation, and stop words.  
  - Stemming the words to their root form.  

### 3. Exploratory Data Analysis  
- Analyzed word frequencies and character/word distributions.  
- Created word clouds for spam and non-spam messages.  
- Used bar charts, pie charts, and heatmaps to visualize correlations and message patterns.  

### 4. Model Building and Evaluation  
- Tested multiple classifiers:  
  - Naive Bayes  
  - Random Forest  
  - Logistic Regression  
  - Decision Tree  
  - Extra Trees Classifier  
  - SVC  
- Achieved **100% precision** using the best-performing model.  

### 5. Web Deployment  
- Deployed the model as a web app using **Streamlit**.  
- The app provides a simple interface where users can input a message to classify it as Spam or Not Spam.  

## Installation  
To run this project locally, follow these steps:  

1. Clone the repository:  
   ```bash  
   git clone https://github.com/kanakrahangdale/sms-spam-detection.git  

