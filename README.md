# MedX AI – AI-Powered Medical Diagnosis System

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/svk091/medx-ai)  
[![Live Demo](https://img.shields.io/badge/Live-Demo-green?logo=streamlit)](https://medxai.streamlit.app/)

**MedX AI** is an AI-powered medical diagnosis system that leverages **Scikit-learn, Pandas, and Streamlit** to provide predictive healthcare insights. The project aims to assist medical professionals in analyzing patient data and predicting possible conditions using machine learning models.

---

## Features

- Machine Learning-based medical diagnosis using **Scikit-learn**
- Interactive web-based interface built with **Streamlit**
- Real-time predictions using trained models
- Supports detection of **Diabetes, Heart Disease, Parkinson's, Lung Cancer, and Hypothyroidism**

---

## Demo

🔗 **Live Demo**: [MedX AI](https://medxai.streamlit.app/)

## 🛠️ Tech Stack

| Technology             | Purpose                                      |
| ---------------------- | -------------------------------------------- |
| **Python**             | Core programming language                    |
| **Pandas**             | Data preprocessing and manipulation          |
| **Scikit-learn**       | Machine learning model training              |
| **Streamlit**          | Web-based UI for easy interaction            |
| **Matplotlib/Seaborn** | Data visualization                           |
| **Statsmodels**        | Statistical modeling and regression analysis |

---

## Machine Learning Models Used

| Model                            | Purpose                                                                  |
| -------------------------------- | ------------------------------------------------------------------------ |
| **Logistic Regression**          | Used for binary classification tasks like predicting diseases            |
| **Support Vector Machine (SVM)** | Used for classification tasks to separate medical conditions effectively |
| **StandardScaler**               | Used for feature scaling and normalization                               |
| **Statsmodels API**              | Used for statistical modeling and analysis                               |

---

## ⚙️ Installation & Setup

### **1️⃣ Clone the Repository**

```bash
git clone https://github.com/svk091/medx-ai.git
cd medx-ai
```

### **2️⃣ Create & Activate Virtual Environment (Optional but Recommended)**

```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### **3️⃣ Install Dependencies**

```bash
pip install -r requirements.txt
```

### **4️⃣ Run the Application**

```bash
streamlit run app.py
```

Now, open the **localhost URL** displayed in the terminal to access the app!

## 📂 Project Structure

```
medx-ai/
│── models/                     # Saved trained models
│── data/                       # Dataset files (if applicable)
│── app.py                      # Model training script
│── requirements.txt             # Dependencies
│── README.md                    # Documentation
│── .gitignore                   # Ignored files
```
