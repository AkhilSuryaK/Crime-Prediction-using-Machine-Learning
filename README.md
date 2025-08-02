# 🚨 Crime Rate Prediction - Unlock Safety: Reduce Crime Rate Together

An intelligent machine learning application that predicts crime rates across **19 Indian metropolitan cities**. Built to assist **law enforcement agencies** in analyzing trends and optimizing their resource allocation for a safer tomorrow.

> 🔗 Live Demo: _Coming Soon_  
> 👨‍💻 Developed by [Kolipaka Akhil Surya](https://www.linkedin.com/in/akhilsurya/)

---

## 🧠 About the Application

This project leverages historical crime data to forecast future crime rates, helping stakeholders anticipate patterns and proactively address potential issues. Data is manually curated from **NCRB reports (2014–2021)** for Indian metros.

It supports **prediction of 10 crime categories** using **Random Forest Regression**, achieving an impressive **93.20% accuracy**.

---

## 📊 Crime Categories

- Murder  
- Kidnapping  
- Crime Against Women  
- Crime Against Children  
- Crime Committed by Juveniles  
- Crime Against Senior Citizens  
- Crime Against SC  
- Crime Against ST  
- Economic Offences  
- Cyber Crimes  

---

## ✨ Features

- 📌 Predicts crime rates for **10 categories**
- 🏙️ Supports **19 Indian metropolitan cities**
- 📅 Based on **2014–2021** NCRB data
- 🌳 Uses **Random Forest Regression**
- ✅ Achieves **93.20% model accuracy**

---

## 🔧 Tech Stack

- **Backend:** Python, Flask
- **ML Model:** Scikit-learn (Random Forest Regression)
- **Frontend:** HTML, CSS, Bootstrap, Jinja2
- **Visualization:** Matplotlib / Seaborn (if applicable)

---

## 📁 Project Structure



Crime-Rate-Prediction/

├── templates/ # HTML Templates (index.html, result.html, etc.)

├── static/ # CSS/JS assets (optional)

├── app.py # Flask application

├── crp.ipynb # Jupyter Notebook with model building

├── model.pkl # Trained ML model

├── requirements.txt # Project dependencies

└── README.md # Project documentation

---

## 🛠️ Installation

```bash
# Clone the repository
git clone https://github.com/AkhilSuryaK/Crime-Prediction-using-Machine-Learning.git

# Navigate into the project
cd Crime-Rate-Prediction

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py

🚀 Usage
Launch the app using python app.py.

Open your browser and visit http://127.0.0.1:5000/.

Select:

✅ A City

✅ A Crime Category

✅ A Future Year

Click Predict.

Get the forecasted crime rate instantly!

🤝 Contributing
Contributions are welcome!
Follow these steps to contribute:

# Fork the repository
# Create a new feature branch
git checkout -b feature-name

# Make your changes and commit
git commit -m "Added new feature"

# Push and create a Pull Request
git push origin feature-name

Please follow clean code practices and test before submitting PRs.

📬 Contact
GitHub: @AkhilSuryaK
LinkedIn: Akhil Surya Kolipaka

📃 License
This project is licensed under the MIT License.

---

Let me know when you're ready for the next one—I'll keep them consistent and clean!
