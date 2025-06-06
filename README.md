# Customer Churn Prediction using ANN

This project predicts customer churn using an **Artificial Neural Network (ANN)** built with TensorFlow and Keras. It helps telecom companies identify customers likely to leave their services, enabling proactive retention strategies.

## 📌 Features

- Pretrained ANN model trained on a cleaned Telco Customer Churn dataset
- Streamlit-powered interactive web app
- Predicts customer churn probability based on input features
- Fully deployable and open-source

---

## 🧠 Tech Stack

- **Python 3.10**
- **TensorFlow / Keras** for ANN
- **Pandas / NumPy** for data handling
- **Streamlit** for UI deployment
- **scikit-learn** for preprocessing and evaluation

---

## 📂 Project Structure

```
Customer-Churn-Prediction-using-ANN/
│
├── churn_model.h5              # Trained ANN model
├── customer_data.csv           # Dataset used for training
├── app.py                      # Streamlit app script
├── requirements.txt            # Python dependencies
├── runtime.txt                 # Python version for Streamlit Cloud
└── README.md                   # Project documentation
```

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/devsaini889/Customer-Churn-Prediction-using-ANN.git
cd Customer-Churn-Prediction-using-ANN
```

### 2. Create and Activate Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit App

```bash
streamlit run app.py
```

---

## 🧪 Sample Inputs

To test the model, fill in details like:

- Tenure
- Monthly Charges
- Contract Type
- Payment Method
- Internet Service

The model will predict the likelihood of customer churn based on these features.

---

## 🧠 About the Model

- The model is an **Artificial Neural Network** with:
  - Input Layer matching features
  - Two hidden layers with ReLU activation
  - Output layer with sigmoid activation
- Trained using **Binary Crossentropy loss** and **Adam optimizer**

---

## 🌐 Live Demo

Check out the live version of the project hosted on Streamlit Cloud:

🔗 [Customer Churn Prediction Web App](https://customer-churn-prediction-using-ann-lr8ur23wuhg4hdce9qjwbq.streamlit.app/)

---



## 📬 Contact

Made with ❤️ by **Dev Saini**  
📫 [LinkedIn](www.linkedin.com/in/ds0752607)
