# Attention with Recurrent Neural Networks (RNNs)

## Overview
This project explores the integration of an **attention mechanism** into a **Recurrent Neural Network (RNN)** to improve time series forecasting performance and interpretability. The lab is framed around a real-world renewable energy use case: predicting wind turbine power output based on historical wind data.

Traditional RNNs often struggle with long-term dependencies and sudden changes in temporal patterns. By incorporating attention, the model can dynamically focus on the most relevant time steps in an input sequence, leading to more accurate predictions and greater insight into model behavior.

---

## Problem Context
Accurate forecasting of wind turbine power output is critical for:
- Optimizing energy production
- Scheduling maintenance
- Managing grid integration

In this lab, an attention-enhanced RNN is used to better capture significant fluctuations and long-term temporal dependencies in wind data, improving both predictive performance and interpretability for technical and non-technical stakeholders.

---

## Lab Workflow
The lab is completed in **Jupyter Lab** and follows these steps:

1. **Set Up the Environment**
2. **Prepare the Data**
3. **Create Sequences for RNN Input**
4. **Split the Data into Training and Test Sets**
5. **Build an RNN Model with a Custom Attention Layer**
6. **Train the Model**
7. **Evaluate and Visualize the Results**

---

## Key Concepts
- Recurrent Neural Networks (RNNs / LSTMs)
- Attention Mechanisms
- Sequence Modeling
- Time Series Forecasting
- Model Interpretability
- TensorFlow / Keras Functional API

---

## Results
Model performance is evaluated using metrics such as:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Visualizations include:
- Actual vs. predicted power output
- Attention weight distributions across time steps

---

## Tools & Libraries
- Python
- NumPy
- pandas
- TensorFlow / Keras
- scikit-learn
- Matplotlib
- Jupyter Lab

---

## Author
Andrew Marasco  

