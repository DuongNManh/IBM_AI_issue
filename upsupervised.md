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
