# Crop Recommendation System

A Machine Learning-powered system that helps farmers choose the **most suitable crop** to grow based on environmental and soil conditions. Using the **Random Forest algorithm**, this system analyzes key factors like **Nitrogen, Phosphorus, Potassium, Humidity, and Temperature** to recommend the best crop for a given set of inputs.

---

##  Project Objective

The goal of this project is to assist farmers in making **data-driven decisions** about what crop to grow in their region. By using historical agricultural data and machine learning, we aim to:
- Improve crop yield
- Optimize soil usage
- Support sustainable farming practices

---

##  How It Works

1.  **Input**: The user provides environmental and soil values:
   - **Nitrogen (N)**
   - **Phosphorus (P)**
   - **Potassium (K)**
   - **Humidity**
   - **Temperature**

2.  **Processing**:
   - The system pre-processes and analyzes the inputs
   - Uses a **trained Random Forest model** to evaluate the best crop match

3.  **Output**: Returns the **recommended crop** for those conditions

---

##  Technologies Used

- **Python**
- **Pandas, NumPy** – for data manipulation
- **Scikit-learn** – for training the Random Forest model
- **Matplotlib / Seaborn** – for data visualization (optional)
- **Streamlit / Flask** *(optional)* – for building a simple web interface

---

##  Dataset Overview

The dataset includes:
- Nutrient content (N, P, K)
- Weather conditions (temperature, humidity)
- Recommended crop labels

> You can use datasets like the one from Kaggle:  
> [Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)


