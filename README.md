# Predicting Plant Growth Using Nonlinear Regression

## 📌 Overview  
This project models plant growth as a **nonlinear function** of environmental factors including:
- **Temperature** (°C)  
- **Light Intensity** (lux)  
- **Photoperiod** (hours per day)

A synthetic dataset is generated using a nonlinear equation that combines a **Gaussian-like response to temperature** and **saturating functions** for light intensity and photoperiod. The model is implemented using **MLPRegressor** (a type of feedforward neural network) from `scikit-learn`.

---

## 🤖 Model Details  
- **Algorithm**: MLPRegressor (Multi-layer Perceptron for regression)  
- **Activation Function**: ReLU  
- **Hidden Layer Size**: 1 layer with 50 neurons  
- **Training**: Gradient descent with the Adam optimizer  
- **Loss Function**: Mean Squared Error (MSE)

---

## 📈 Evaluation  
The model is evaluated using:  
- **Mean Squared Error (MSE)**  
- **R² Score**  
- **Actual vs Predicted Scatter Plot**  
- **Error Distribution Histogram**

---

## 📊 3D Visualization  
The project includes interactive 3D surface plots that show the predicted `Plant_Growth` as a function of:
1. **Temperature & Light Intensity** (with Photoperiod fixed)  
2. **Temperature & Photoperiod** (with Light Intensity fixed)  
3. **Light Intensity & Photoperiod** (with Temperature fixed)

These plots help to visualize the **nonlinear interactions** between environmental variables and plant response.

---

## 🚀 Future Ideas  
- Apply real-world datasets from plant biology or agriculture  
- Add interaction terms or higher complexity (e.g., deep neural networks)  
- Deploy as an interactive web app with Streamlit or Dash  
