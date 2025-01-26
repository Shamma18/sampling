# Sampling Assignment

**Submitted By**: Shamma
**Roll No.**: 102253003  
**Group**: 3C55 

## Overview
This Python Notebook evaluates the accuracy of **5 different models** across **5 different samples** created using various sampling techniques.

### Models Used:
1. Naive Bayes  
2. Logistic Regression  
3. K-Nearest Neighbours  
4. Support Vector Machine  
5. Decision Tree  

### Sampling Techniques:
1. Random Sampling  
2. Stratified Sampling  
3. Cluster Sampling  
4. Oversampling  
5. Undersampling  

---

## Results
The table below shows the accuracy of each model on the different sampling techniques:

| **Model**               | **Random Sampling** | **Stratified Sampling** | **Cluster Sampling** | **Oversampling** | **Undersampling** |
|--------------------------|---------------------|--------------------------|-----------------------|------------------|-------------------|
| **Naive Bayes**          | 0.797814            | 0.836066                 | 0.886463              | 0.812227         | 0.877729          |
| **Logistic Regression**  | 0.928962            | 0.874317                 | 0.906114              | 0.910480         | 0.908297          |
| **K-Nearest Neighbours** | 0.819672            | 0.792350                 | 0.847162              | 0.812227         | 0.829694          |
| **Support Vector Machine** | 0.650273          | 0.650273                 | 0.689956              | 0.679039         | 0.670306          |
| **Decision Tree**        | 0.967213            | 0.950820                 | **0.984716**          | **0.984716**     | 0.982533          |

---

### Key Insights:
- The **best accuracy achieved** is **0.984716**, using the **Decision Tree model** with both:
  - **Cluster Sampling**  
  - **Oversampling**  

> **Note**: The accuracy may vary for different rows picked when generating a sample.

---

## Final Output
The final table of results can be found at the end of the Python Notebook.  
