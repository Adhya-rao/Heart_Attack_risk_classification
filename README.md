# ❤️ Heart Attack Risk Classification App

A simple and interactive **Machine Learning web application** built using *Streamlit* to predict the **risk of heart attack** based on medical and lifestyle inputs.

---

## 📌 Project Overview
This project classifies whether a person is at **high risk or low risk of a heart attack** using a trained **Support Vector Machine (SVM)** model.

Users provide health-related details, and the model predicts the risk instantly.

---

## 🚀 Live Demo
👉 https://heartattackriskclassification-jbycugwrgx7mangykdne5f.streamlit.app/

---

## 🧠 Technologies Used
* Python  
* Streamlit  
* Scikit-learn  
* Pandas  
* NumPy  
* Seaborn  
* Pickle  

---

## 📂 Features
* User-friendly interface  
* Real-time prediction  
* Handles both numerical and categorical inputs  
* Encodes categorical variables  
* Scales numerical features  
* Instant risk classification (High / Low)  

---

## 📊 Input Parameters
* **Age** → Age of the person  
* **RestingBP** → Resting Blood Pressure  
* **Cholesterol** → Cholesterol level  
* **FastingBS** → Fasting Blood Sugar (0 or 1)  
* **MaxHR** → Maximum Heart Rate achieved  
* **Oldpeak** → ST depression value  
* **Gender** → Male / Female  
* **ChestPainType** → ATA / NAP / ASY / TA  
* **RestingECG** → Normal / ST / LVH  
* **ExerciseAngina** → Yes / No  
* **ST_Slope** → Up / Flat / Down  

---

## ⚙️ How It Works
* User inputs health data  
* Data preprocessing:
  * Encoding categorical variables (gender, chest pain, ECG, etc.)  
  * Scaling numerical features using StandardScaler  
* Model predicts class (0 or 1)  
* Output:
  * **1 → High Risk ⚠️**  
  * **0 → Low Risk 😊**  

---

## 🛠️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone <your-repo-link>
cd <your-project-folder>
```

### 2️⃣ Create Virtual Environment (Windows PowerShell)
```powershell
python -m venv myenv
myenv\Scripts\activate
```

### 3️⃣ Install Dependencies
```bash
pip install streamlit scikit-learn pandas seaborn numpy
```

### 4️⃣ Run Application
```bash
streamlit run app.py
```

---

## 📁 Project Structure
```
├── app.py              # Main Streamlit app
├── svm_model.pkl      # Trained SVM model
├── README.md          # Documentation
```

---

## 🔮 Model Details
* Algorithm Used: Support Vector Machine (SVM)  
* Model loaded using Pickle  
* Classification output:
  * 1 → High Risk  
  * 0 → Low Risk  

---

## 📌 Sample Prediction Flow
* Input: Age = 45, Cholesterol = 240, Smoker = Yes  
* Model processes features  
* Output: High Risk ⚠️  

---

## ⚠️ Notes
* Ensure `svm_model.pkl` is present in the project directory  
* Avoid refitting scaler during prediction in production  
* Predictions depend on training data quality  

---

## 💡 Future Improvements
* Add probability score for risk  
* Improve UI design  
* Deploy using Docker  
* Add more health parameters  
* Display model accuracy and metrics  

---

## 👨‍💻 Author
* Developed as a Machine Learning project  

---

## ⭐ If you like this project
* Give it a star ⭐  
* Share with others 🚀  
