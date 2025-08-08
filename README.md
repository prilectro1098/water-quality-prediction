# 💧 Water Quality Prediction App

A Streamlit web app to **predict pollutant levels** in water bodies based on the year and station ID using a trained regression model.

---

## 🧠 About the Project

This machine learning app allows users to input the **year** and **station ID**, and it predicts the levels of key water pollutants such as:

- O₂ (Dissolved Oxygen)
- NO₃ (Nitrate)
- NO₂ (Nitrite)
- SO₄ (Sulfate)
- PO₄ (Phosphate)
- CL (Chloride)

It uses a multi-output regression model trained on historical water quality datasets, aiming to help researchers, students, or authorities with environmental monitoring.

---

## 🖼️ Demo Screenshot

*(Insert a screenshot here if you have one)*

---

## 📦 Features

- 🔢 Predict pollutant concentrations with just year and station ID
- 📊 Outputs concentrations of six key pollutants
- ⚡ Powered by a compressed regression model for speed
- 🌐 Runs in-browser using Streamlit

---

## 🧰 Technologies Used

- Python 3
- Streamlit
- pandas, numpy
- scikit-learn (model creation - assumed)
- joblib (for model handling)

---

## 📁 Project Structure

WaterQuality-Predictor/
├── app.py # Streamlit frontend
├── compress_model.py # Script to compress trained model
├── pollution_model.pkl # Trained model (not uploaded here)
├── pollution_model_compressed.pkl # (optional compressed model output)
├── model_columns.pkl # Column structure used by the model
├── requirement.txt # Python dependencies
└── README.md

yaml
Copy
Edit

---

## ▶️ How to Run the App

### 🧑‍💻 1. Clone the Repo

```bash
git clone https://github.com/yourusername/WaterQuality-Predictor.git
cd WaterQuality-Predictor
📦 2. Install Requirements
bash
Copy
Edit
pip install -r requirement.txt
🚀 3. Run the Streamlit App
bash
Copy
Edit
streamlit run app.py
The app will open in your default browser at http://localhost:8501.

📋 Input Format
Field	Type	Example
Year	Integer	2025
Station ID	String	1, ST34, etc.

⚙️ Model Details
Multi-output regression model (assumed linear/regressor ensemble)

Trained to predict pollutant concentrations for various water stations

Uses one-hot encoding on station ID

Model files required:

pollution_model.pkl

model_columns.pkl

📜 License
This project is licensed under the MIT License.

🙋‍♂️ Author
Pritam Saha
Water Quality Predictor – Machine Learning Internship Project
Year: 2025

🌟 Star this repo
If this project helped you, consider giving it a ⭐ on GitHub!

yaml
Copy
Edit

---
