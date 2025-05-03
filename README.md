# 🍔 McDonald's Customer Perception Case Study - Replication

This project is a replication of a data analysis case study based on customer survey responses about McDonald’s. The aim is to extract insights into customer perceptions, preferences, and behavioral patterns using exploratory data analysis, clustering, and classification techniques.

---

## 📂 Files

- `Aniket_McDonalds_CASE_STUDY_REPLICATION.ipynb`: Main notebook containing data preprocessing, visualization, clustering, and classification model development.
- `mcdonalds.csv`: Dataset containing survey responses from customers on various aspects of McDonald’s food and service.
- `classifier.pkl`: Serialized machine learning model trained to predict customer sentiment or segment class based on input features.

---

## 📊 Project Objective

To analyze how customers perceive McDonald's in terms of food quality, value, service, and brand image by:

- Understanding patterns in customer responses  
- Visualizing sentiments and satisfaction levels  
- Identifying customer segments using clustering  
- Predicting customer types or sentiments using a classifier  

---

## 🧹 Key Steps

### 1. Data Cleaning
- Converted categorical responses into interpretable formats.
- Renamed columns for better readability.
- Handled missing or constant-value data.

### 2. Exploratory Data Analysis (EDA)
- Bar charts and correlation heatmaps to analyze preference distribution.
- Sentiment analysis across different demographic groups.

### 3. Clustering Analysis
- Applied K-Means clustering to segment customers.
- Used the Elbow Method and Silhouette Score to determine optimal cluster count.
- Interpreted clusters to define customer personas.

### 4. Classification Model
- Trained a supervised machine learning model to classify customers or predict sentiment.
- Evaluated model accuracy and performance.
- Exported the trained model using `pickle` into `classifier.pkl`.

---

## 💡 Insights

- Customers value affordability and speed the most, while healthiness is perceived less favorably.
- Cluster analysis reveals distinct segments: health-conscious, value-driven, and loyal customers.
- The classifier provides a predictive layer that can be used in future customer-focused applications.

---

## 🛠 Tools Used

- **Languages & Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Notebook**: Jupyter  
- **Model Serialization**: Pickle (`classifier.pkl`)  

---

## ✅ Future Work

- Extend analysis to include textual sentiment if open responses are available.
- Deploy the model with an interactive UI using Streamlit or Dash.
- Experiment with additional classification algorithms and tuning strategies.

---

## 📬 Contact

For questions or collaborations, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/aniket-gupta-90b49725a/) or email.
