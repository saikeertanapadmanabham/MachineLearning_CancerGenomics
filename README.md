# Cancer Genomic Project using Machine Learning Algorithms

### Project Description:

This project entails the analysis and classification of cancer genomics data obtained from The Cancer Genome Atlas (TCGA). It's designed to aid oncologists and researchers in understanding cancer types through machine learning models.

### Objectives:

- To classify cancer types from genomic data.
  
- To provide a predictive model aiding in personalized cancer treatment.

### System Design:

![image](https://github.com/saikeertanapadmanabham/MachineLearning_CancerGenomics/assets/154480871/f734b93f-206f-4285-9ef7-057700b866ba)

### Methodology:

**Dataset Collection:** Gathering raw data relevant to the research study.

**Data Pre-Processing (EDA, Cleaning):** Analyzing the data to understand its characteristics (Exploratory Data Analysis) and preparing it by removing errors or irrelevant information (cleaning).

**Data Normalization:** Scaling data to a standard range without distorting differences in the ranges of values.

**Feature Extraction (PCA):** Reducing the dimensionality of the data by extracting the most important features using Principal Component Analysis (PCA).

**Unsupervised Model - K-Means Clustering:** Grouping the data into clusters that contain similar characteristics without pre-labeled outcomes.

**Supervised ML Classification Techniques:**

*RF (Random Forest):* A versatile ensemble learning method for classification, using multiple decision trees.

*SVM (Support Vector Machine):* A classification technique that finds the hyperplane that best separates the data classes.

*NN (Neural Networks):* A computational model that mimics the way neurons for pattern recognition.

*GB (Gradient Boost):* An ensemble technique that builds models sequentially, with each one correcting errors made by the previous models.

*XGB (Extreme Gradient Boost):* An optimized gradient boosting algorithm that is efficient, flexible, and portable.

**Performance Evaluations:** Assessing and comparing the effectiveness of different algorithms using metrics like accuracy, precision, recall, etc.

**Best Classification Algorithm:** Selecting the most effective algorithm based on performance evaluations for the task at hand.

### Tools Used

**Programming Language:** Python

**Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib

### Software Requirements

**Hardware Requirements:**
Processor: Any Update Processor
Ram: Min 4 GB
Hard Disk: Min 100 GB

**Software Requirements:**
Operating System: Windows family
Technology: Python 3.6
IDE: PyCharm, Jupyter Notebook

### Attached 
- The repository contains Jupyter Notebooks demonstrating the step-by-step process of data analysis, model training, and evaluation.

- Documentation provides insights into the methodologies and findings.

### Conclusion 

By applying advanced machine learning algorithms, this research on cancer genomics provides new possibilities for studying the genetic components of the disease. By using various classifiers, including Random Forest, Support Vector Machines, Neural Networks, and others, we have effectively navigated the complex genomic patterns associated with various types of cancer. The accuracy with which these malignancies were classified shows a significant advancement toward customized treatment plans and highlights the collaboration between biological research and machine analytics.
