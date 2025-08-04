# IBM_INTERNSHIP
# ⚡ Power System Fault Detection and Classification using Machine Learning

This project was completed as part of the **IBM SkillsBuild/Edunet Internship Program**.  
It addresses **Problem Statement No. 41**, focusing on the use of **machine learning** for classifying different types of faults in a power distribution system based on voltage and current phasor data.

---

## 📌 Problem Statement

Design a machine learning model to detect and classify different types of faults in a power distribution system.  
The model should distinguish between normal operating conditions and various fault conditions such as:
- Line-to-Ground (LG)
- Line-to-Line (LL)
- Three-Phase (LLL)
- Others (LLG, LLLG)

The objective is to enable **rapid and accurate fault identification** to ensure **grid stability and reliability**.

---

## 💡 Proposed Solution

We used **IBM Watson Studio's AutoAI** to automate the machine learning pipeline creation, training, and evaluation.  
The best-performing model was a **Random Forest Classifier**, selected based on cross-validation accuracy.

---

## ⚙️ System Approach

### Requirements
- IBM Cloud (Lite Tier)
- IBM Watson Studio / AutoAI
- Kaggle dataset

### Tools & Libraries
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn

---

## 🧠 ML Model Overview

- **Data Source**: Power System Faults Dataset (Kaggle)
- **Target Feature**: Fault Type (multi-class)
- **Model**: Random Forest (via IBM AutoAI)
- **Accuracy**: ~40.9% (cross-validation)
- **Evaluation**: Confusion Matrix, Pipeline Leaderboard

---

## 🚀 Deployment

The model was trained and evaluated within IBM Watson Studio.  
The system is suitable for deployment as a REST API or integration into real-time grid monitoring systems.

---

## 📊 Result Highlights

- AutoAI tested 9 model pipelines with different optimizations
- Best pipeline achieved ~40.9% accuracy
- Feature engineering and hyperparameter tuning were automated

---

## 🔭 Future Scope

- Integrate real-time phasor data (PMUs, SCADA)
- Use larger, more diverse datasets
- Apply advanced models like LSTM or transformers
- Deploy using edge computing or cloud-based dashboards

---

## 🎓 Certifications

As part of this internship, I completed the following:
- IBM Getting Started with AI
- IBM Introduction to Machine Learning
- IBM Journey to Cloud

---

## 👩‍💻 Author

**Nimisha Ramesh Thoppil**  
Electronics and Computer Science Engineering  
Pillai College of Engineering  
GitHub: [Regulus2627](https://github.com/Regulus2627)

---

⭐ *If you found this helpful, feel free to star this repo or connect with me!*
