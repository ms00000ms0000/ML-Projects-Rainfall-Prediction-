# 🌧️ ML Project - Rainfall Prediction  

## 🚀 Overview  
This **Machine Learning project** focuses on **Rainfall Prediction** using the **Random Forest Classifier**.  
The dataset includes meteorological parameters such as **Day, Pressure, MaxTemp, Temperature, MinTemp, DewPoint, Humidity, Cloud, Rainfall, Sunshine, WindDirection, and WindSpeed** to predict the likelihood of rainfall.  

Extensive **Exploratory Data Analysis (EDA)** was performed, covering:  
* Pressure Distribution  
* Max Temperature Distribution  
* Temperature Distribution  
* Min Temperature Distribution  
* Dewpoint Distribution  
* Humidity Distribution  
* Cloud Distribution  
* Sunshine Distribution  
* Wind Speed Distribution  
* Rainfall Distribution  

A **correlation heatmap** was also constructed to analyze relationships among all features.  
For model selection and tuning, techniques like **train_test_split**, **GridSearchCV**, and **cross_val_score** were used.  

The **cross-validation scores** obtained were:  
`[0.68421053, 0.81578947, 0.83783784, 0.83783784, 0.91891892]`  
with a **mean cross-validation score of 0.8189**.  

Model performance was evaluated using **classification_report**, **confusion_matrix**, and **accuracy_score**.  
This project demonstrates the potential of **Machine Learning in weather prediction**, enhancing the accuracy and reliability of **climate forecasting systems**.  

---

## 🔍 About the Project  
This project showcases the use of **Random Forest Classifier** for **predicting rainfall** based on historical weather and atmospheric data.  
By analyzing various meteorological attributes, the system learns hidden patterns that determine the likelihood of rainfall events.  

The project highlights the role of **data-driven climate models** in weather forecasting and agricultural planning, supporting timely and informed decision-making.  

---

## 🧠 Model Architecture  
The project workflow includes:  
1. **Data Collection & Cleaning** – Importing and preprocessing the dataset for training.  
2. **Exploratory Data Analysis (EDA)** – Understanding distributions and correlations between weather features.  
3. **Feature Selection** – Identifying the most relevant factors influencing rainfall.  
4. **Model Training** – Using **Random Forest Classifier** for prediction.  
5. **Hyperparameter Tuning** – Optimizing parameters using **GridSearchCV**.  
6. **Cross-Validation** – Evaluating consistency via **cross_val_score**.  
7. **Performance Evaluation** – Using accuracy, confusion matrix, and classification report.  

---

## 🧾 Dataset Description  
The dataset contains key meteorological inputs and rainfall data for predictive modeling.  

| Feature Name | Description |
|---------------|-------------|
| `day` | Day of observation |
| `pressure` | Atmospheric pressure |
| `maxtemp` | Maximum temperature |
| `temperature` | Average daily temperature |
| `mintemp` | Minimum temperature |
| `dewpoint` | Dew point temperature |
| `humidity` | Humidity percentage |
| `cloud` | Cloud coverage |
| `rainfall` | Recorded rainfall amount |
| `sunshine` | Duration of sunlight (hours) |
| `winddirection` | Direction of wind |
| `windspeed` | Wind speed (km/h) |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical operations  
* **Pandas** – Data manipulation  
* **Matplotlib / Seaborn** – Visualization and EDA  
* **Scikit-learn** – Model training, validation, and evaluation  

---

## 🚀 Features  
* Predicts **rainfall occurrence** based on meteorological inputs  
* Performs **comprehensive EDA** to explore feature relationships  
* Implements **Random Forest Classifier** for accurate predictions  
* Utilizes **GridSearchCV** for model optimization  
* Evaluates model using **cross-validation and classification metrics**  
* Demonstrates **real-world weather prediction** through ML  

---

## 📊 Results  
* **Cross-Validation Scores:** [0.6842, 0.8158, 0.8378, 0.8378, 0.9189]  
* **Mean Cross-Validation Score:** 0.8189  
* **Evaluation Metrics:** classification_report, confusion_matrix, accuracy_score  

These results show that the Random Forest Classifier performed strongly and consistently, confirming its suitability for rainfall prediction.  

---

## 📁 Repository Structure  

```
📦 ML-Projects-Rainfall-Prediction
│
├── Rainfall_Prediction.ipynb                                                      # Main Jupyter Notebook Model implementation
├── Rainfall.csv                                                                   # Dataset used for training and testing
└── README.md                                                                      # Project documentation

```
---

## 🧪 How to Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Projects-Rainfall-Prediction.git
   cd ML-Projects-Rainfall-Prediction
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook Rainfall_Prediction.ipynb
   ```

4. **Execute all cells to train, test, and evaluate the rainfall prediction model.**

---

## 📈 Future Improvements

* Integrate Deep Learning models (e.g., LSTM) for sequential weather prediction

* Add real-time data collection via weather APIs

* Build an interactive Streamlit dashboard for visualization and forecasting

* Experiment with feature engineering and ensemble methods

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
