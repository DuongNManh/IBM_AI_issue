# 🌟 **IBM AI Issue**

## 🚀 **Python Library for Machine Learning**
The `scikit-learn` package allows you to complete machine learning tasks with just a few lines of code.

![Scikit-learn ML](https://github.com/user-attachments/assets/dafc4799-d3b4-4e5c-9947-6d7acec8f3fa)

---

## 🤖 **Supervised and Unsupervised Algorithms**

![Algorithm Types](https://github.com/user-attachments/assets/cfc9b6fc-978a-4d8f-b7c8-9a6ae2cdc581)

---

### 📘 **Supervised Learning**
Supervised learning involves training a model using labeled data. For example, consider a **cancer dataset**:

![Cancer Dataset](https://github.com/user-attachments/assets/708977db-09b3-4fbf-8d4e-66b84503ec84)

#### 🧠 **Types of Supervised Learning**
1. **Classification**  
   Classification predicts discrete categories or classes for a given input.

   ![Classification Example](https://github.com/user-attachments/assets/3d8142ec-f445-4906-b9a9-cab78c16e924)

2. **Regression**  
   Regression predicts continuous values based on input data.
   Base on the **independent variable** to determite continuous value of **Dependent variable**
   

   ![Regression Example](https://github.com/user-attachments/assets/ab8407f7-af24-4cad-bdbc-44d5ce5c8608)
   ![Regression Example](https://github.com/user-attachments/assets/ee05f076-bbd9-41b9-8812-1def7da438c2)
   ![Regression Example](https://github.com/user-attachments/assets/f03bdfc0-d9aa-47d4-8202-7e1b9cc521d5)

   - Types of regression models:
     - Simple Regression: Simple Linear & Non-linear Regression
       ---
          1.Linear Regression representation
         ![Linear Regression representation](https://github.com/user-attachments/assets/455ead21-8ac5-4eae-b239-5f143ccbb932)
          2.Find the best fit linear
         ![Find the best fit linear](https://github.com/user-attachments/assets/79da396b-42f4-4646-970a-26725300776c)
          3.Estimating the parameters
         ![Estimating the parameters](https://github.com/user-attachments/assets/a9c64f28-8edd-469c-bea0-ddbb6ec64722)
          4.Predict with linear regression
         ![image](https://github.com/user-attachments/assets/1ad70d32-5808-426d-9c99-1ab25c400ee8)



     - Multiple Regression: Multiple Linear & Non-linear Regression

   - Application:
      ![Regression Application](https://github.com/user-attachments/assets/ae1a171c-0545-468c-8c2d-522fa834a3bd)
---

### 📙 **Unsupervised Learning**
Unsupervised learning works with unlabeled data to find hidden patterns or structures in the dataset.

![Unsupervised Learning](https://github.com/user-attachments/assets/a2867f55-062b-4176-927f-94964f877ffe)

#### 🧩 **Dataset for Unsupervised Learning**
Unsupervised learning uses **unlabeled data**:

![Unlabeled Dataset Example](https://github.com/user-attachments/assets/4cf7b563-175c-46fd-bc55-21ef3e207bd8)

---

#### 🔍 **Types of Unsupervised Learning**
1. **Clustering**  
   Group similar data points into clusters.

   ![Clustering Example](https://github.com/user-attachments/assets/7647fa00-5a23-48cf-b8c2-d09c36fed914)

2. **Dimensionality Reduction**  
   Reduce the number of variables while retaining essential information.

---

#### 🧠 **Model evaluation**
**1. Caculate the accurency of the model (how can this model predict an unknown dataset)**
   - **Using a portion of the dataset**: train the model by entire dataset (labeled) and check by part of unlabeled data in same dataset
     ![accurency of the model](https://github.com/user-attachments/assets/f18d3d70-e0a6-4c8f-a358-13556cdf33bd)
     ![accurency of the model](https://github.com/user-attachments/assets/aeaff0db-c0a7-4fc7-915a-893f04ad32b0)

   - **Training & out-of-sample Accuracy**
     - **Training Accuracy**: % of correct predictions that the model makes when using the test dataset.
       - when we train and testing on the same dataset => produces a high training accuracy
         ![Training accuracy](https://github.com/user-attachments/assets/66fed1b6-d9be-416f-b280-8a80eed9e8ff)

     - **Out-of-Sample Accuracy**: % of correct predictions that the model makes when using the unknown data.
       ![Out-of-Sample Accuracy](https://github.com/user-attachments/assets/0ea43539-9584-4448-9c81-62d121ed1132)

     - **Split train/test evaluation approach**: reduce the overfit and can evaluate the Out-of-Sample Accuracy of the model
       ![Split train/test evaluation approach](https://github.com/user-attachments/assets/5c5aad1f-1bc7-467e-873a-71b98ece44bd)
       ![Split train/test evaluation approach](https://github.com/user-attachments/assets/65bbc8b2-6caa-4844-900a-e554ecc61d34)

     - **K-fold cross-validation**: splitting the dataset into K equally sized subsets. The model is trained on K-1 folds and tested on the remaining fold.
       Result = avg of all test accuracy
       ![K-fold cross-validation](https://github.com/user-attachments/assets/197b0574-c176-4c36-a2c7-d24cd2c9bd73)






     

