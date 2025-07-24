# 🛍️ Ecommerce Sales & Profit Prediction Dashboard

A web-based analytics application built with **Flask**, **Plotly**, and **Power BI** that allows users to:

- 🔮 Predict sales revenue and profitability for ecommerce orders.
- 📊 Visualize sales performance using interactive charts.
- 📂 Launch a Power BI dashboard directly from the web interface.

---

## 🚀 Features

- 🔐 Login authentication (`admin` / `admin`)
- 🧠 Sales prediction using Random Forest Regression
- 💹 Profit classification using XGBoost + SMOTE
- 📉 Dynamic Plotly charts (bar, pie, line) with filters
- 📊 Power BI integration to open `.pbix` files locally

---

## 📁 Project Structure

📦 project/
├── app1.py # Full Flask application
├── Ecommerce_data.csv # Input data
├── Ecommerce.pbix # Power BI dashboard file
├── models/ # Trained ML models
│ ├── sales.pkl
│ ├── profit_model2.pkl
│ └── label_encoders2.pkl
├── templates/ # HTML templates
│ ├── home.html
│ ├── predict.html
│ ├── chart_filter.html
│ ├── index.html
│ └── dashboard.html
├── t1.py / test.py # Model training scripts
└── train_models.py # Basic model training

yaml
Copy
Edit

---

## 💻 Installation

1. **Clone the repository**

```bash
git clone https://github.com/ChennarapuJyothika/your-repo-name.git
cd your-repo-name
Install dependencies

bash
Copy
Edit
pip install flask pandas numpy scikit-learn plotly xgboost imbalanced-learn
Run the app

bash
Copy
Edit
python app1.py
Access in browser

Open http://127.0.0.1:5000

Login:

pgsql
Copy
Edit
Username: admin  
Password: admin
📈 Power BI Integration
Make sure Power BI is installed at:

mathematica
Copy
Edit
C:\Program Files\Microsoft Power BI Desktop\bin\PBIDesktop.exe
Click the "Open Power BI" button in the app to launch Ecommerce.pbix.

🧑‍💻 Author
Chennarapu Jyothika
GitHub: ChennarapuJyothika

 
