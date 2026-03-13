# 🧬 Breast Cancer Prediction 

A deep learning-based **binary classification model** built with **PyTorch** to predict whether a tumor is **benign or malignant**. The model uses an Artificial Neural Network (ANN) trained on medical data to assist in early detection of breast cancer.

---

# 📌 Project Overview

Breast cancer is one of the most common cancers worldwide. Early detection plays a critical role in improving survival rates.

This project implements a **deep learning model using PyTorch** to classify tumors based on diagnostic features. The model learns patterns from medical data and predicts whether a tumor is **benign (non-cancerous)** or **malignant (cancerous)**.

---

# 🚀 Key Features

* Binary classification for tumor prediction
* Implemented using **PyTorch deep learning framework**
* Lightweight ANN architecture for efficient training
* Performance evaluation using multiple metrics
* Visualization of model performance

---

# 🧠 Model Architecture

The model is a **fully connected Artificial Neural Network (ANN)** consisting of:

* **Input Layer** – accepts diagnostic tumor features
* **Hidden Layer 1** – fully connected with **ReLU activation**
* **Hidden Layer 2** – fully connected with **ReLU activation**
* **Output Layer** – single neuron with **Sigmoid activation** for binary classification

---

# ⚙️ Training Details

* **Framework:** PyTorch
* **Optimizer:** Adam
* **Loss Function:** Binary Cross Entropy Loss
* **Activation Functions:** ReLU (hidden layers), Sigmoid (output layer)

The model was trained and tuned to achieve **high prediction accuracy while minimizing false positives**.

---

# 📊 Model Performance

* **Test Accuracy:** 96%
* **Evaluation Metrics Used:**

  * Accuracy
  * Confusion Matrix
  * ROC Curve
  * F1 Score

Model thresholds were optimized to **improve the F1 score and reduce false positive predictions**.

---

# 📈 Visualizations

The project includes visual analysis of model performance:

* Accuracy plots during training
* Confusion matrix heatmaps
* ROC curve analysis

These visualizations help evaluate how well the model distinguishes between benign and malignant tumors.

---

# 🛠️ Technologies Used

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

# 📂 Project Structure

```
Breast-Cancer-Prediction
│
├── dataset/
│   └── breast_cancer_data.csv
│
├── models/
│   └── cancer_model.pth
│
├── train_model.py
├── evaluation.py
├── visualization.py
├── requirements.txt
└── README.md
```

---

# ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/yourusername/breast-cancer-prediction.git
```

### 2️⃣ Navigate to the Project Directory

```
cd breast-cancer-prediction
```

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Run the Training Script

```
python train_model.py
```

---

# 📊 Applications

* Medical decision support systems
* Early cancer detection tools
* Healthcare data analysis
* Machine learning in medical diagnostics

---

# 🔮 Future Improvements

* Use larger medical datasets for improved generalization
* Implement deep neural networks with more layers
* Deploy the model as a web application
* Integrate explainable AI techniques for interpretability

---

# 📜 License

This project is licensed under the **MIT License**.
