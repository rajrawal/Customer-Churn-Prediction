# Customer Churn Prediction:
Dataset used : https://www.kaggle.com/datasets/blastchar/telco-customer-churn
## About Dataset
### Content :
Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

**The data set includes information about:**

* **Customers who left within the last month** – the column is called Churn
* **Services that each customer has signed up for** – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
* **Customer account information** – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
* **Demographic info about customers** – gender, age range, and if they have partners and dependents

### Columns pecification :
---
**Independent variables :**
<br>    
 1.   customerID        
 2.   gender            
 3.   SeniorCitizen     
 4.   Partner           
 5.   Dependents        
 6.   tenure            
 7.   PhoneService      
 8.   MultipleLines     
 9.   InternetService   
 10.  OnlineSecurity    
 11.  OnlineBackup      
 12.  DeviceProtection  
 13.  TechSupport       
 14.  StreamingTV       
 15.  StreamingMovies   
 16.  Contract        
 17.  PaperlessBilling  
 18.  PaymentMethod     
 19.  MonthlyCharges    
 20.  TotalCharges     

 **Dependent variable**
<br> 1.  Churn             

### Libraries to be installed :
---
* **pip install pandas**
* **pip install numpy**
* **pip install matplotlib**
* **pip install seaborn**
* **pip install scikit-learn**

### classification Model :
I have use SVM model for this classification because its gives the best prediction  With a accuracy of 80.57%.
<br>**About support vector machine(SVM) Model :**
* **Margin Maximization:** SVM finds the hyperplane that maximizes the margin between classes, promoting better generalization.
* **Kernel Trick:** It can handle non-linear data by mapping it to a higher-dimensional space using kernel functions.
* **Global Optimum:** SVM ensures finding the global optimal solution due to convex optimization.
* **Regularization:** It balances between maximizing the margin and minimizing errors via a regularization parameter (C).
* **Support Vectors:** Only data points close to the decision boundary (support vectors) influence the model, making it memory-efficient and interpretable.
* **Binary Classification:** SVM is primarily for binary classification but can be extended to multi-class using strategies like one-vs-rest.
* **Outlier Sensitivity:** It's sensitive to outliers as they can become support vectors, affecting the decision boundary.
* **Scalability:** SVM works well with small to medium-sized datasets but might face challenges with very large datasets.
* **Kernel Selection:** The choice of kernel function significantly impacts performance, requiring careful selection.
* **Interpretability:** Understanding support vectors aids in interpreting how the model makes decisions.
