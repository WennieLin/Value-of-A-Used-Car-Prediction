# Value-of-A-Used-Car-Prediction# 🚗 Used Car Price Prediction using GRA + PSO + BPNN

This project focuses on predicting the selling price of used cars using machine learning, specifically an optimized neural network model enhanced with Grey Relational Analysis (GRA) and Particle Swarm Optimization (PSO).

---

## 📌 Objective

To help used car dealerships:
- Accurately estimate used car values
- Improve inventory selection
- Optimize pricing strategies

---

## 📊 Dataset Overview

The dataset includes features such as:
- `new_price`: Original new car price
- `displacement`: Engine size
- `mileage`: Total kilometers driven
- `gearbox`: Transmission type
- `fuel_consumption`: Combined fuel usage
- `license_date`: Registration date
- Other car dimensions and specs

---

## 🔧 Modeling Pipeline

### 1. **Feature Selection: Grey Relational Analysis (GRA)**
- GRA is used to rank feature importance relative to car price.
- Top features (e.g., `new_price`, `displacement`, `mileage`) are selected.

### 2. **Data Preprocessing**
- Features normalized using Min-Max Scaling to the range [0, 1].

### 3. **Model Construction: Backpropagation Neural Network (BPNN)**
- Neural network implemented using TensorFlow/Keras
- Trained with MSE loss and Adam optimizer

### 4. **Optimization: Particle Swarm Optimization (PSO)**
- PSO optimizes the initial weights and biases of the BPNN
- Enhances convergence and prediction accuracy

### 5. **Final Model: GRA + PSO + BPNN**
- Combines feature selection and optimization into a highly accurate predictive model

---

## 📈 Model Performance

| Model              | MAPE (%) | MAE   | R² Score |
|-------------------|----------|-------|----------|
| Standard BPNN     | 5.92     | 0.782 | 0.927    |
| PSO-BPNN          | 4.38     | 0.593 | 0.962    |
| GRA + PSO + BPNN  | **3.93** | **0.475** | **0.984** |

---

## ✅ Business Use Case

Used car dealerships can use this model to:
- Determine the fair market price of used cars
- Choose which vehicles to acquire based on resale value
- Reduce risk of overpricing or undervaluing inventory

---

## 📂 Files

- `UsedCarPricePrediction.ipynb`: Main Colab notebook with code and explanations
- `README.md`: Project documentation

---

## ▶️ How to Run

1. Open the [Google Colab Notebook](https://colab.research.google.com/drive/1nSOMeTzHDzdJNENPrj3I39vFCPLUge-4#scrollTo=inSPzPKvLqZe)
2. Run cells in order to:
   - Load and preprocess data
   - Perform GRA feature selection
   - Train and evaluate models
   - Visualize results

---

## 📬 Contact

For business inquiries, model integration, or support:
**Email:** nasa.wen0209@gmail.com
**Author:** Wennie Lin

---

