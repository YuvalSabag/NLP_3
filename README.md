## Authorship Attribution with Text Classification

This project applies machine learning and deep learning models to tackle the task of **authorship attribution** for tweets, distinguishing between those authored by Donald Trump and his staffers using metadata and text features. A **binary classification framework** is employed, leveraging traditional algorithms like **Logistic Regression** and **SVM**, alongside advanced neural networks such as **FFNN** and **DistilBERT**, to predict authorship.

By preprocessing tweet metadata and applying feature engineering, the project explores linguistic patterns and sentiment to improve classification accuracy. It highlights the effectiveness of **NLP techniques**, feature engineering, and advanced models like **DistilBERT**, showcasing the benefits of combining classical and modern approaches for text classification.  


### **Key Objectives**

1. **Data Preprocessing**  
   - Clean and normalize tweet text and metadata.  
   - Extract features like sentiment polarity, word count, and device type.
   - Integrate linguistic and text-based features, including n-gram representations, for improved classification.    

2. **Model Development**  
   - Train traditional machine learning models, such as **Logistic Regression**, **SVM**, and **XGBoost**, as baselines.  
   - Develop a **Feedforward Neural Network (FFNN)** using PyTorch for deeper feature learning.  
   - Fine-tune **DistilBERT** for contextual representation and classification.  

3. **Evaluation and Analysis**  
   - Assess models using metrics like **accuracy**, **precision**, **recall**, **F1-score**, and **AUC-ROC**.  
   - Compare classical and deep learning approaches to identify strengths and limitations.  
   - Analyze the impact of different features and hyperparameters on model performance.  
