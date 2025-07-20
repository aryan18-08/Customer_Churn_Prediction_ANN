# Customer Churn Prediction using ANN (TensorFlow & Keras)

This project focuses on predicting whether a customer will churn (leave the service) using the Telco Customer Churn dataset. The model is built using an Artificial Neural Network (ANN) in TensorFlow/Keras.

🛠️ Tech Stack
- Python
- TensorFlow / Keras
- Pandas & NumPy
- Scikit-learn (for preprocessing)
- Matplotlib, Seaborn (for visualization)
- Google Colab (for development)

🧠 Model Architecture
- Input Features: Based on dataset after encoding (e.g., 27 features)
- Hidden Layers:
  - Layer 1: 64 neurons, ReLU
  - Dropout: 30%
  - Layer 2: 32 neurons, ReLU
  - Dropout: 20%
  - Layer 3: 16 neurons, ReLU
- Output Layer: 1 neuron with Sigmoid activation
- Loss Function: Binary Crossentropy
- Optimizer: Adam


🔍 Model Performance
- Accuracy: ~78%
- Precision (Churn class): 65%
- Recall (Churn class): 48%
- F1 Score: 55%
- Also includes a confusion matrix and classification report

⚠️ Note: The dataset is slightly imbalanced, which affects recall. Techniques like SMOTE or class weights can help further improve performance.

📁 Contents
- Customer_Churn_ANN.ipynb: The main Jupyter Notebook with all preprocessing, model training, evaluation, and visualization
- README.md: Overview and notes about the project
- 
🚀 Future Improvements
- Experiment with SMOTE or cost-sensitive learning to boost recall on churn class
- Try deploying the model as a simple web app using Streamlit

