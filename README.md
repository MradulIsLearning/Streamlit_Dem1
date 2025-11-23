# Streamlit_Dem1
🍄 Mushroom Classification Web App

A Streamlit-based interactive machine learning web app that predicts whether a mushroom is edible or poisonous based on its features.
Users can choose between different machine learning models, tune hyperparameters, and visualize key evaluation metrics.

🚀 Features

✔ Load and preprocess Mushroom dataset (UCI ML Repo)
✔ Select a classifier:

Support Vector Machine (SVM)

Logistic Regression

Random Forest

✔ Hyperparameter tuning using sidebar UI
✔ Performance metrics:

Accuracy, Precision, Recall

Confusion Matrix

ROC Curve

Precision–Recall Curve

✔ Option to view raw dataset
✔ Real-time UI powered by Streamlit

🧠 Tech Stack
Component	Technology
Frontend UI	Streamlit
Machine Learning	Scikit-Learn
Data Handling	Pandas, NumPy
Visualization	Matplotlib
📂 Dataset

The dataset used is:

Mushroom Data Set — UCI Machine Learning Repository
Features describe mushroom characteristics and classify them as edible or poisonous.

🔗 Dataset info:
https://archive.ics.uci.edu/ml/datasets/Mushroom

⚠️ Make sure you update the CSV file path inside the code:

data = pd.read_csv("data/mushrooms.csv")

▶️ Run Locally
1️⃣ Clone the repository
[[git clone https://github.com/yourusername/mushroom-classification-app.git](https://github.com/MradulIsLearning/Streamlit_Dem1.git)]
cd mushroom-classification-app

2️⃣ Install required libraries
pip install -r requirements.txt

3️⃣ Run the app
streamlit run app.py
Then open the URL shown in the terminal (usually http://localhost:8501).

🛠 Requirements

Example requirements.txt:

streamlit
pandas
numpy
scikit-learn
matplotlib

✨ Future Enhancements

📌 Add more models (XGBoost, Neural Networks)
📌 Deploy on Streamlit Cloud / HuggingFace Spaces
📌 Enhance dataset visualization
📌 Add model explainability (SHAP/LIME)

👨‍💻 Author

Your Name
B.Tech in Artificial Intelligence & Data Science
📧 your-mradulbhartiya111@gmail.com

🔗 LinkedIn: <www.linkedin.com/in/mradul-bhartiya-292a5729a>
