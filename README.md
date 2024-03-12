
**README.md**

# Temperature Anomaly Prediction Project

This project utilizes machine learning techniques to forecast temperature anomalies based on historical climate data. Two distinct modeling approaches are implemented:

**Models**

1. **Feedforward Neural Network (FNN):** 
   * Employs a dense feedforward architecture to learn complex patterns within time-series temperature data.
   * Leverages MinMaxScaler for data normalization.

2. **Recurrent Neural Network (RNN):**
   * Specifically utilizes a SimpleRNN architecture for handling the sequential nature of temperature data.
   * Employs time-series datasets for effective model training.

**Workflow**

* **Data Preparation:**
   * Loads temperature data from CSV files (`data.csv`, `data-2.csv`).
   * Preprocesses data, including index setting and normalization.
   * Partitions data into training and testing sets (RNN model).

* **Model Development:**
   * Constructs FNN model with appropriate layers and activation functions.
   * Builds an RNN (SimpleRNN) model for time-series analysis.

* **Training:**
   * Trains both FNN and RNN models on the prepared datasets.
   * Validates the RNN model during the training process.

* **Forecasting:**
   * Generates temperature anomaly predictions for specified future periods.
   * Iteratively updates time-series sequences for multi-step RNN predictions.

* **Visualization:**
   * Plots actual vs. predicted temperature anomalies for evaluation.

**Dependencies**

* Python 3
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* Keras
* TensorFlow

**Usage**

1. Install required packages: `pip install numpy pandas matplotlib scikit-learn keras tensorflow`
2. Adjust data filepaths within the code as needed.
3. Execute the Python script.

**Customization**

* Experiment with model hyperparameters (e.g., layers, neurons, sequence length).
* Explore different RNN architectures (e.g., LSTM, GRU).
* Modify the forecasting horizon.

**Disclaimer**

This project serves as an educational tool for exploring temperature anomaly prediction. Results may vary, and further refinement could enhance prediction accuracy.

Let me know if you'd like any additional adjustments or have specific aspects you want to emphasize! 

# Note: This project is a starting point; explore different configurations for improved results.
