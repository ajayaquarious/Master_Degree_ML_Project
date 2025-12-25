# 🎓 Masters Decision Support System (ML + Streamlit)

A Machine Learning–based Decision Support System that helps determine whether a student/professional should pursue a Master’s degree based on **GATE score** and **current salary**.  
The project uses a **Random Forest Classifier** with an interactive **Streamlit web interface**.

---

## 🚀 Features

- Interactive Streamlit UI
- Machine Learning–based prediction
- Random Forest Classifier
- Real-time prediction using user inputs
- Dataset visualization (bar chart, histogram, pie chart)
- Clean and modular project structure

---

## 🧠 Machine Learning Details

- **Algorithm Used:** Random Forest Classifier  
- **Input Features:**
  - GATE Score (Poor / Average / Good)
  - Current Salary (INR)
- **Target Variable:**
  - Should_Do_Masters (Yes / No)
- **Preprocessing:**
  - Label encoding
  - Train-test split
- **Model Training:** Cached using Streamlit for performance

---

## 🖥️ Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas
- Matplotlib

---

## 📁 Dataset

The dataset (`dataset.csv`) contains:
- GATE score categories
- Salary values
- Decision label indicating whether pursuing a Master’s degree is recommended
