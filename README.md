## Authorship Attribution with Text Classification

This project explores **authorship attribution** for tweets using machine learning and deep learning models, aiming to distinguish between tweets authored by Donald Trump and his staffers. A **binary classification framework** is implemented, leveraging traditional algorithms like **Logistic Regression**, **SVM**, and advanced neural networks such as **FFNN** and **DistilBERT**, to predict authorship.

By preprocessing tweet metadata and applying feature engineering, the project analyzes linguistic patterns and sentiment to improve classification accuracy. It highlights the effectiveness of **NLP techniques**, feature engineering, and advanced models like **DistilBERT**, demonstrating the benefits of combining classical and modern approaches for text classification.

&nbsp; 
### **Key Objectives**

1. **Data Preprocessing**  
   - Clean and normalize tweet text and metadata using **Pandas** and **NumPy**.  
   - Extract features such as sentiment polarity, word count, device type, and n-gram representations.

2. **Model Development**  
   - Train traditional models, including **Logistic Regression**, **SVM**, and **XGBoost**, using **scikit-learn**.  
   - Build a **Feedforward Neural Network (FFNN)** using **PyTorch** and **Keras** for deep feature learning.  
   - Fine-tune **DistilBERT** with the Hugging Face **Transformers** library for contextualized text representation.

3. **Evaluation and Analysis**  
   - Assess models using metrics such as **accuracy**, **precision**, **F1-score**, and **AUC-ROC**.  
   - Compare the performance of classical and deep learning models to identify strengths and areas for optimization.
