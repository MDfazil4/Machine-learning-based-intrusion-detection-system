# **Machine Learning-Based Intrusion Detection System (IDS)**

## **Project Overview**

This project is a Machine Learning-based Intrusion Detection System (IDS) designed to detect potential security threats in network traffic using Long Short-Term Memory (LSTM) neural networks. The system employs LSTM for time-series-based anomaly detection, capturing patterns in network traffic data over time. Additionally, SHAP (SHapley Additive exPlanations) is used to interpret the model’s predictions and provide insights into which features contribute to the detection of intrusions.

---

## **Features**

- **Time-Series Anomaly Detection:** Uses LSTM neural networks to detect anomalies in network traffic over time.
- **Interpretability with SHAP:** Provides detailed feature importance and interpretability for each model prediction.
- **Improved Accuracy:** Achieved a detection accuracy of over 95%.
- **Reduced False Positives:** Successfully reduced false positives by 20% compared to traditional methods.
- **Real-Time Threat Detection:** Efficiently monitors and flags malicious activity in network traffic.

---

## **Technologies Used**

- **Programming Language:** Python
- **Libraries & Frameworks:**
  - **TensorFlow/Keras:** For implementing LSTM neural networks.
  - **Scikit-Learn:** For preprocessing and additional machine learning tasks.
  - **SHAP:** For interpretability and model explanation.
  - **Pandas/Numpy:** For data manipulation and analysis.
  - **Wireshark:** For network traffic data collection and analysis.

---

## **Project Setup**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-repo/intrusion-detection-system.git
   cd intrusion-detection-system
   ```

2. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Dataset:**
   - Download the network traffic dataset (e.g., from CICIDS, KDD99) and place it in the `/data` directory.

4. **Run the model:**

   ```bash
   python train_lstm_model.py
   ```

---

## **Usage**

- **SHAP Interpretability:**
  The `Lstn_SHAP.py` script performs SHAP analysis on the trained model, providing insights into which features most influence model predictions.

---

## **Achievements**

- Achieved a detection accuracy of over **95%**.
- Reduced false positives by **20%** compared to traditional methods.
- Implemented SHAP for feature importance and improved model interpretability.
