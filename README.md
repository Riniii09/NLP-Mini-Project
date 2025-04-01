# Financial Contract Review and Classification

## Course: NLP (Semester 6) - Pillai College of Engineering

### Project Overview:
This project is part of the Natural Language Processing (NLP) course for Semester 6 students at Pillai College of Engineering. The project focuses on Contract Review and Classification, where we apply various Machine Learning (ML), Deep Learning (DL), and Language Models to categorize financial contracts into predefined categories. This project involves exploring techniques like text preprocessing, feature extraction, model training, and evaluating the models for their effectiveness in classifying news articles.

You can learn more about the college by visiting the official website of Pillai College of Engineering.

### Acknowledgements:
We would like to express our sincere gratitude to the following individuals:

**Theory Faculty:**  
- Dhiraj Amin  
- Sharvari Govilkar  

**Lab Faculty:**  
- Dhiraj Amin  
- Neha Ashok  
- Shubhangi Chavan  

Their guidance and support have been invaluable throughout this project.

## Project Title:
**Financial Contract Review and Classification using Natural Language Processing**

## Project Abstract:
Financial contracts, such as loan agreements and insurance policies, contain legally binding clauses that define obligations, risks, and benefits. Manually reviewing these contracts is a slow and error-prone process, making it difficult for financial analysts to efficiently assess compliance and risk. This project aims to automate contract section classification by categorizing clauses into high risk, standard, and beneficial.

The classification process involves text preprocessing techniques such as tokenization, stopword removal, and syntactic analysis to extract key financial and legal terms. Feature extraction methods and word embeddings help capture the semantic meaning of contract clauses. A supervised learning model trained on labeled contract data assigns categories based on contextual and linguistic patterns.

By automating contract classification, this system enhances accuracy, reduces manual effort, and ensures consistency in financial risk assessment. It provides financial analysts with a reliable tool for contract evaluation, improving decision-making and compliance monitoring in financial institutions.

## Algorithms Used:
### Machine Learning Algorithms:
- Logistic Regression  
- Support Vector Machine (SVM)  
- Random Forest Classifier  
- Decision Tree  
- Naive Bayes  
- K-Nearest Neighbours  

### Deep Learning Algorithms:
- Convolutional Neural Networks (CNN)  
- Long Short-Term Memory (LSTM)  
- Bidirectional Long Short-Term Memory (BiLSTM)  
- Hybrid Model combining CNN and BiLSTM  

### Language Models:
- RoBERTa  
- BERT  

## Comparative Analysis:

### Machine Learning
| No. | Model Name | Settings / Hyperparameters | Feature | Precision | Recall | F1 Score | Accuracy |
|----|------------|---------------------------|---------|-----------|--------|----------|----------|
| 1  | Logistic Regression | L2 Regularization | BoW | 0.81 | 0.82 | 0.81 | 0.82 |
| 2  | Logistic Regression | L1 Regularization | BoW | 0.81 | 0.82 | 0.81 | 0.82 |
| 3  | Decision Tree | Max Depth: 10, Min Samples Split: 5 | TF-IDF | 0.79 | 0.81 | 0.80 | 0.81 |
| 4  | Decision Tree | Max Depth: 15, Min Samples Split: 10 | BoW | 0.78 | 0.79 | 0.78 | 0.79 |
| 5  | Random Forest | 100 Trees, Max Depth: 10 | BoW+NLP | 0.83 | 0.84 | 0.83 | 0.84 |
| 6  | Random Forest | 200 Trees, Max Depth: 15 | BoW+NLP | 0.84 | 0.85 | 0.84 | 0.85 |
| 7  | SVM | Linear Kernel, C=1.0 | TF-IDF | 0.85 | 0.86 | 0.85 | 0.86 |
| 8  | SVM | RBF Kernel, C=1.0, Gamma=0.1 | BoW+NLP | 0.86 | 0.87 | 0.86 | 0.87 |
| 9  | K-Nearest Neighbors | K=5, Distance: Euclidean | BoW | 0.77 | 0.78 | 0.77 | 0.78 |
| 10 | K-Nearest Neighbors | K=10, Distance: Manhattan | BoW+NLP | 0.79 | 0.80 | 0.79 | 0.80 |
| 11 | Naive Bayes | No Smoothing | BoW | 0.71 | 0.72 | 0.71 | 0.72 |

### Deep Learning
| Model | Embedding | Accuracy | Precision | Recall | F1-Score |
|-------|-----------|----------|-----------|--------|----------|
| CNN   | Word Embeddings | 0.9756 | 0.9756 | 0.9756 | 0.9756 |
| CNN   | TF-IDF | 0.9756 | 0.9756 | 0.9756 | 0.9756 |
| LSTM  | Word Embeddings | 0.9756 | 0.9756 | 0.9756 | 0.9757 |
| LSTM  | BoW | 0.9756 | 0.9756 | 0.9756 | 0.9757 |
| BiLSTM | Word Embeddings | 0.9865 | 0.9860 | 0.9869 | 0.9864 |

### Language Models
| Model  | Precision | Recall | F1 Score | Accuracy | MCC |
|--------|-----------|--------|----------|----------|-----|
| BERT   | 0.60      | 0.38   | 0.46     | 0.72     | 0.723 |
| RoBERTa| 0.97      | 0.97   | 0.97     | 0.98     | 0.98  |

## Conclusion:
This project successfully automates the classification of financial contract clauses, addressing the inefficiencies and inaccuracies of manual review. By leveraging text preprocessing techniques, feature extraction, and supervised learning models, the system accurately categorizes clauses into high risk, standard, and beneficial. This automation not only enhances the accuracy and consistency of financial risk assessment but also reduces the manual workload for analysts. As a result, financial institutions can improve decision-making, streamline compliance monitoring, and mitigate risks more effectively. Future improvements could involve expanding the dataset, integrating advanced NLP techniques, and refining classification models for even greater precision.
