# spacex-capstone-project
SpaceX Falcon 9 Landing Prediction Project
# 🚀 SpaceX Falcon 9 Landing Prediction – Data Science Capstone

## 📌 Project Overview

This project analyzes SpaceX Falcon 9 launch data to predict whether the first stage will successfully land. The ability to predict landing success is crucial because reusable rockets significantly reduce launch costs.

Through this capstone, we applied the full data science workflow:

* Data collection (API + web scraping)
* Data wrangling and cleaning
* Exploratory Data Analysis (EDA)
* Interactive visual analytics
* Predictive modeling (classification)

---

## 🎯 Business Problem

SpaceX advertises Falcon 9 launches at a lower cost compared to competitors. A key factor is the successful recovery of the first stage.

**Goal:**
Predict whether a Falcon 9 first stage landing will be successful using historical launch data.

---

## 🗂️ Repository Structure

```
├── notebooks/
│   ├── merged_spacex_capstone.ipynb
│   ├── data_collection_api.ipynb
│   ├── web_scraping.ipynb
│   ├── data_wrangling.ipynb
│   ├── eda_visualization.ipynb
│   ├── eda_sql.ipynb
│   ├── folium_maps.ipynb
│   └── machine_learning.ipynb
│
├── dashboards/
│   └── plotly_dash_app.py
│
├── presentation/
│   └── spacex_capstone.pdf
│
├── data/
│
└── README.md
```

---

## 🔧 Data Collection

Data was gathered from two main sources:

* **SpaceX REST API**
* **Wikipedia (Web Scraping)**

Key features collected:

* Launch site
* Payload mass
* Orbit type
* Booster version
* Landing outcome

---

## 🧹 Data Wrangling

* Cleaned missing and inconsistent values
* Converted categorical variables
* Created a binary classification target:

  * `1` = Successful landing
  * `0` = Failure

---

## 📊 Exploratory Data Analysis (EDA)

### Visualization Insights

* Launch success increases over time
* Certain launch sites have higher success rates
* Payload mass influences landing success

### SQL Analysis

Performed queries to:

* Identify launch site patterns
* Compute payload statistics
* Analyze mission outcomes

---

## 🌍 Interactive Visual Analytics

### Folium Maps

* Visualized launch sites geographically
* Added markers and success/failure color coding
* Calculated distances to nearby infrastructure

### Plotly Dash Dashboard

* Interactive filters for launch site and payload
* Pie charts for success rates
* Scatter plots for payload vs. outcome

---

## 🤖 Predictive Analysis (Machine Learning)

### Models Used

* Logistic Regression
* Support Vector Machine (SVM)
* Decision Tree
* K-Nearest Neighbors (KNN)

### Process

* Feature selection and scaling
* Hyperparameter tuning (GridSearchCV)
* Model evaluation using accuracy

### 📈 Results

* Best performing model: **(update with your model)**
* Achieved highest accuracy among tested models
* Confusion matrix used to evaluate classification performance

---

## 📷 Key Results

### EDA Findings

* Success rate improves significantly after early launches
* Orbit type strongly correlates with landing outcome

### Dashboard Insights

* Certain payload ranges yield higher success rates
* Specific launch sites dominate successful launches

---

## 🏁 Conclusion

* Machine learning models can effectively predict Falcon 9 landing success
* Launch site, payload, and orbit type are key predictors
* Data-driven insights can help estimate launch risk and cost

---

## 🚀 Future Improvements

* Incorporate real-time launch data
* Use more advanced models (e.g., XGBoost, Neural Networks)
* Deploy model as a web application

---

## 📎 Project Deliverables

* ✅ Jupyter Notebooks (full workflow)
* ✅ Interactive Dashboard (Plotly Dash)
* ✅ Folium Maps
* ✅ Final Presentation (PDF)

---

## 🧠 Skills Demonstrated

* Data Collection (API & Web Scraping)
* Data Cleaning & Feature Engineering
* SQL Analysis
* Data Visualization (Matplotlib, Plotly)
* Geospatial Analysis (Folium)
* Machine Learning & Model Evaluation
* Dashboard Development

---

## 🙌 Acknowledgements

* IBM Data Science Professional Certificate (Coursera)
* SpaceX API
* Wikipedia datasets

---

## 📬 Contact

If you have questions or feedback, feel free to connect!
