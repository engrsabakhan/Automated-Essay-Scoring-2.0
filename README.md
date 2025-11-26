<b>📝 Automated Essay Scoring (AES) – Kaggle Project</div</b>
<b>Automated Essay Scoring (AES) is an intelligent system designed to evaluate written essays using machine learning and deep learning techniques. This project focuses on developing a reliable scoring model using the Kaggle AES dataset, applying modern NLP preprocessing, feature engineering, and state-of-the-art neural architectures.
The goal is to create a scoring pipeline that performs consistently, reduces human bias, and delivers accurate, fast, and scalable evaluations of student writing.</b>
***
📚 Table of Contents

📖 Overview

📁 Repository Structure

🎯 Objectives

🚀 Features

🛠️ Installation

📊 Usage

🧹 Data Preprocessing

🧠 Models Used

📈 Evaluation

📂 Dataset

📚 References

📝 License

✨ Author

📖 Overview

Automated Essay Scoring (AES) is transforming the way learning assessments are conducted by improving the speed, consistency, and fairness of scoring. Manual grading is slow and labor-intensive, especially in areas with limited educational resources. AES applies machine learning and NLP techniques to automate the scoring process.

This project provides a comparative study of multiple AES models trained on one of the largest publicly accessible essay datasets aligned with modern educational standards.

Model Performance Summary
Model	Cohen’s Kappa
Linear Regression	0.6540
XGBoost	0.7100
LightGBM (LGBM)	0.7210
LSTM	0.7710
BERT	0.7806

Deep learning models — especially LSTM and BERT — significantly outperform traditional machine learning methods in prediction accuracy and reproducibility.

The goal of this work is to propose a publicly available AES system that improves teacher workflow efficiency and provides students with fast, objective feedback.

📁 Repository Structure
├── Dataset
│   ├── train.csv
│   ├── test.csv
│
├── Notebook
│   ├── AES_model.ipynb
│   ├── AES_inference.py
│
├── References
│   ├── research_paper.pdf
│
├── .gitignore
├── LICENSE
├── README.md
├── requirements.txt

🎯 Objectives

Automate essay scoring using ML and NLP

Compare traditional and deep learning approaches

Extract linguistic & semantic features

Build train-ready and inference-ready scripts

Improve feedback speed for students

🚀 Features

✔ Full AES pipeline (preprocessing → training → prediction)
✔ Multiple model comparisons
✔ Deep learning support (LSTM, BERT)
✔ Clean notebook + Python script
✔ Requirements.txt for easy setup
✔ MIT licensed

🛠️ Installation
1️⃣ Clone the repository
git clone https://github.com/YourUsername/Automated-Essay-Scoring.git
cd Automated-Essay-Scoring

2️⃣ Install dependencies
pip install -r requirements.txt

📊 Usage
Run Jupyter Notebook
jupyter notebook


Open file:
Notebook/AES_model.ipynb

Run Python Inference Script
python Notebook/AES_inference.py

🧹 Data Preprocessing

The pipeline includes:

Lowercasing

Punctuation removal

Stopword removal

Lemmatization

Tokenization

Word & sentence statistics

Readability metrics

TF-IDF feature extraction

🧠 Models Used
Model Type	Description
Linear Regression	Baseline scoring model
RandomForest / XGBoost / LGBM	Strong for tabular + text stats
LSTM	Sequential deep learning model
BERT	Transformer-based, best semantic understanding
📈 Evaluation

Primary Metric:

<div align="center">⭐ Quadratic Weighted Kappa (QWK)</div>

Used in Kaggle AES competitions to measure agreement between model predictions and human graders.

📂 Dataset

Dataset contains:

Essay text

Essay set ID

Human-graded score

You must download the dataset from Kaggle:
👉 Kaggle → Automated Essay Scoring Dataset

📚 References

Kaggle AES Competition

NLP Educational Research

Included Research PDF in /References/

📝 License

This project is licensed under the MIT License.
See the LICENSE file.
