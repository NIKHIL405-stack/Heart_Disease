[README.md](https://github.com/user-attachments/files/23930562/README.md)

# ❤️ Heart Disease Prediction Using Machine Learning


A brief description of what this project does and who it's for

This project predicts the likelihood of heart disease in a person based on medical attributes.
It uses a Machine Learning model (Scikit-Learn) and a Flask web application for real-time predictions.

📌 Features

Heart disease prediction using ML

Clean dataset (heart.csv)

Model training inside Project.ipynb

Saved model (heart_disease.pkl)

Web interface using Flask

Simple and user-friendly HTML form

🧠 Machine Learning Details

Algorithm Used: Logistic Regression (or replace with your model)

Steps Included:

Data preprocessing

Train–test split

Model training

Hyperparameter tuning

Accuracy evaluation

Saving model with pickle

The full workflow is inside Project.ipynb.

📂 Project Structure
Heart_Disease/
│── app.py                 # Flask backend  
│── model.py               # ML model training code  
│── Project.ipynb          # Notebook with analysis  
│── heart.csv              # Dataset  
│── heart_disease.pkl      # Saved ML model  
│── templates/
│      └── index.html      # Frontend form  
│── static/
│      └── style.css       # Stylesheet  
│── requirements.txt       # Dependencies  
└── README.md              # Documentation  

🚀 Running the Project
1. Clone the repo
git clone https://github.com/NIKHIL405-stack/Heart_Disease.git
cd Heart_Disease

2. Install dependencies
pip install -r requirements.txt

3. Run the Flask app
python app.py

4. Open the app
http://127.0.0.1:5000/

🧪 Input Fields

The model takes the following inputs:

Age

Sex

Chest Pain Type (cp)

Resting Blood Pressure (trestbps)

Cholesterol (chol)

Fasting Blood Sugar (fbs)

Rest ECG (restecg)

Maximum Heart Rate (thalach)

Exercise Induced Angina (exang)

ST depression (oldpeak)

Slope

CA

Thal

📊 Output

The web app shows:

✔️ The person is likely to have heart disease
or
✔️ The person is NOT likely to have heart disease

🛡️ Disclaimer

This project is for academic and educational purposes only.
It is not a medical diagnostic tool.

📧 Developer

Nikhil Aditya Nagvanshi
B.Tech CSE – KIIT University## Color Reference

| Color             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Example Color | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) #0a192f |
| Example Color | ![#f8f8f8](https://via.placeholder.com/10/f8f8f8?text=+) #f8f8f8 |
| Example Color | ![#00b48a](https://via.placeholder.com/10/00b48a?text=+) #00b48a |
| Example Color | ![#00d1a0](https://via.placeholder.com/10/00b48a?text=+) #00d1a0 |


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Deployment

To deploy this project run

```bash
  npm run deploy
```


## Appendix

Any additional information goes here

