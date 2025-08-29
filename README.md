-->Heart Disease Detector

This project is a Machine Learning–based Heart Disease Prediction System that uses patient health data to predict the likelihood of heart disease. The model is trained on a dataset with various clinical attributes such as age, blood pressure, cholesterol, chest pain type, and more.

📌 Features:
Predicts presence of heart disease (binary/multi-class target).
Uses features like Age, Blood Pressure, Cholesterol, Chest Pain Type, ECG results, etc.
Implements data preprocessing, feature selection, and model training.
Can be extended into a web app or API for real-world usage.

📂 Dataset
The dataset contains the following columns:

Age → Patient’s age
TRestBPS → Resting blood pressure
CHOL → Serum cholesterol
FBS → Fasting blood sugar (> 120 mg/dl)
RestECG → Resting electrocardiographic results
ThalCH → Thalassemia test result
ExANG → Exercise induced angina (1 = yes, 0 = no)
Old B → ST depression induced by exercise
Slope → Slope of the peak exercise ST segment
CA → Number of major vessels colored by fluoroscopy
Thal → Thalassemia status
Sex Male, Sex Female → Gender of patient
CP asymptomatic, CP atypical angina, CP non-anginal, CP typical angina → Chest pain type (encoded)
Target → Heart disease diagnosis (0 = No disease, 1–4 = Disease present)

⚙️ Tech Stack

Python 🐍
NumPy, Pandas → Data handling
Matplotlib, Seaborn → Data visualization
Scikit-learn → Model building & evaluation
Google Colab → Development & analysis

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/heart-disease-detector.git
cd heart-disease-detector

Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:

jupyter notebook

Open the notebook and execute cells step by step.

📊 Model Training & Accuracy

Data preprocessing: handled missing values, encoding, scaling.
Algorithms tested: Logistic Regression, Decision Trees, Random Forest, SVM.
Final model: update with your best-performing model & accuracy.

👨‍💻 Author Ishan Mishra 💼 LinkedIn - https://www.linkedin.com/in/vanshika-chauhan-1ba100279/ 📧 Email: rv.chauhan322@gmail.com

🤝 Contribution

Pull requests are welcome! If you find a bug or want to add a new feature, feel free to fork this repo and submit a PR.
