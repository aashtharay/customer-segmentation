# Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project applies **K-Means Clustering** to segment customers of a mall based on their purchasing behavior.
Customer segmentation helps businesses understand different groups of customers and design better marketing strategies.

The clustering is performed using the following features:

* **Age**
* **Annual Income (k$)**
* **Spending Score (1–100)**

---

## 📂 Dataset

The dataset used is **Mall Customers Dataset**.

Columns in the dataset:

| Column                 | Description                                                    |
| ---------------------- | -------------------------------------------------------------- |
| CustomerID             | Unique ID of the customer                                      |
| Gender                 | Male / Female                                                  |
| Age                    | Customer age                                                   |
| Annual Income (k$)     | Annual income in thousand dollars                              |
| Spending Score (1-100) | Score assigned by the mall based on customer spending behavior |

---

## ⚙️ Technologies Used

* Python
* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

---

## 🔎 Machine Learning Techniques

The following techniques were used in this project:

1. **Data Preprocessing**
2. **Feature Scaling using StandardScaler**
3. **Elbow Method** to determine the optimal number of clusters
4. **K-Means Clustering**
5. **Data Visualization**

---

## 📊 Elbow Method

The Elbow Method is used to determine the optimal number of clusters (K).

![Elbow Method](images/elbow_method.png)

---

## 📈 Customer Clusters

Visualization of customer clusters after applying K-Means clustering.

![Clusters](images/clusters_plot.png)

---

## 🚀 How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/customer-segmentation.git
```

2. Install required libraries

```
pip install -r requirements.txt
```

3. Run the Jupyter Notebook

```
customer_segmentation.ipynb
```

---

## 📌 Applications

Customer segmentation is widely used in:

* Targeted marketing
* Customer behavior analysis
* Personalized recommendations
* Business strategy planning

---

## 👨‍💻 Author

Your Name

GitHub: https://github.com/aashtharay
