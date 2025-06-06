
# Machine Learning Evaluation App 📊

A Streamlit-based web interface to upload your dataset and test multiple classification and regression models with live evaluation metrics and plots.

---

## Features

- Upload CSV/XLSX datasets directly from the UI
- Auto-detects task type: classification or regression
- Built-in models:
  - **Classification**: Logistic Regression, Random Forest, Decision Tree, K-Nearest Neighbors
  - **Regression**: Linear Regression, Random Forest, Decision Tree
- Adjustable parameters: test/train split, number of trees, neighbors (K), etc.
- Metrics and plots:
  - Classification: Accuracy, Confusion Matrix Heatmap
  - Regression: Mean Squared Error, R² Score, Predicted vs Actual scatter plot
- Interactive web interface powered by Streamlit

---

## Installation

```bash
git clone https://github.com/<your-username>/ml-showcase.git
cd ml-evaluation-app

# Optional: create and activate a virtual environment
python -m venv .venv
# Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
````

---

## requirements.txt

```text
streamlit>=1.30
pandas>=1.0
scikit-learn>=1.0
seaborn>=0.10
matplotlib>=3.0
```

---

## Run the App

```bash
streamlit run ML.py
```

After launching, a local URL will appear in the terminal (usually [http://localhost:8501](http://localhost:8501)). Open it in your browser to start using the app.

---

## Folder Structure

```text
.
├── ML.py              # Main Streamlit app script
├── requirements.txt    # Dependency list
└── README.md           # Project documentation
```


