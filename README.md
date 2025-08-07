# ⚡ IBM_INTERNSHIP: Power System Fault Detection and Classification using Machine Learning

This project was completed as part of the **IBM SkillsBuild / Edunet Internship Program** under **Problem Statement No. 41**.  
It focuses on leveraging machine learning to classify different types of faults in a power distribution system using voltage and current phasor data.

---

## 📌 Problem Statement

Design a machine learning model to detect and classify faults in a power distribution system.

### The model must classify:
- 🔹 Line-to-Ground (LG)
- 🔹 Line-to-Line (LL)
- 🔹 Three-Phase (LLL)
- 🔹 Others (LLG, LLLG)
  
The objective is to enable **rapid and accurate fault identification** to ensure **grid stability and reliability**.

---

## 💡 Proposed Solution

We used **IBM Watson Studio's AutoAI** to automate:
- ML pipeline creation  
- Training  
- Evaluation  

The best-performing model was a **Random Forest Classifier**, selected based on cross-validation accuracy.

---

## ⚙️ System Approach

### ✅ Requirements
- IBM Cloud (Lite Tier)
- IBM Watson Studio / AutoAI
- Kaggle dataset

### 🛠️ Tools & Libraries
- Python
- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`, `seaborn`

---

## 🧠 ML Model Overview

- **Data Source:** Power System Faults Dataset (Kaggle)
- **Target Feature:** Fault Type (multi-class)
- **Model:** Random Forest (via IBM AutoAI)
- **Accuracy:** ~40.9% (cross-validation)
- **Evaluation:** Confusion Matrix, AutoAI Leaderboard

---

## 🚀 Deployment

The model was trained and evaluated within **IBM Watson Studio**.  
It is suitable for deployment as a **REST API** or integration into **real-time grid monitoring systems**.

---

## 📊 Result Highlights

- AutoAI generated **9 optimized pipelines**
- Best pipeline achieved **~40.9% accuracy**
- Automated:
  - Feature engineering
  - Hyperparameter tuning

---

## 🔭 Future Scope

- Integrate real-time phasor data (PMUs, SCADA)
- Use larger and more diverse datasets
- Apply advanced models (e.g., LSTM, Transformers)
- Deploy on edge devices or cloud dashboards

---

## 🔐 API Key Usage (Security Best Practice)

> ⚠️ **DO NOT hardcode your IBM API Key in the notebook.**

Instead, use secure input as shown below:

```python
import getpass
api_key = getpass.getpass("Please enter your api key (press enter): ")

🧪 How to Run the Notebook
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Regulus2627/IBM_INTERNSHIP.git
cd IBM_INTERNSHIP
Open ML_IBM Nimisha.ipynb in Jupyter or VS Code.

When prompted, enter your IBM Cloud API key securely.

Run all cells in sequence.


🎓 Certifications
As part of this internship, the following IBM SkillsBuild certifications were completed:

✅ IBM Getting Started with AI

✅ IBM Introduction to Machine Learning

✅ IBM Journey to Cloud

