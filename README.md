# Breast Cancer Prediction
This project utilizes machine learning techniques to predict breast cancer diagnoses as either malignant or benign. It includes data preprocessing, model training, evaluation, and deployment through a Flask web application

## 🔍 Features

- Logistic Regression, KNN, SVM, Decision Tree
- Trained on CSV data
- Deployed with Flask
- Simple UI for input and prediction

## 📁 Folder Structure
.
├── app.py
├── model.pkl
├── data.csv
├── templates/
│ └── index.html
├── static/
│ └── style.css
├── requirements.txt
└── breast cancer prediction.ipynb



## 🛠️ How to Run

1. Clone the repo:
```bash
git clone https://github.com/Ayushijaiswal24/Breast-cancer-prediction.git
cd Breast-cancer-prediction

Create virtual environment:

bash
Copy code
python -m venv venv
venv\Scripts\activate  # Windows
# or
source venv/bin/activate  # Mac/Linux
Install requirements:

bash
Copy code
pip install -r requirements.txt
Run the app:

bash
Copy code
python app.py
Then visit http://localhost:5000 in your browser.

📜 License
MIT License

yaml
Copy code

4. Save it

---

### ✅ Step 2: Push the README to GitHub (if done locally)

In terminal/Git Bash inside the project folder:

```bash
git add README.md
git commit -m "Add README"
git push origin main  # or use 'master' if that's your branch name