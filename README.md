# Iris Flower Classification

This repository contains my implementation of the **Iris Flower Classification Project**, completed as part of my **AI & ML Internship at CODEXINTERN**.  
The goal is to predict the species of an Iris flower — *Setosa*, *Versicolor*, or *Virginica* — using sepal and petal measurements.


---

## 🔍 Exploratory Data Analysis (EDA)

Performed detailed EDA including:

- Dataset overview (`head`, `tail`, `info`)  
- Scatterplots between features:  
  - Sepal Length vs Sepal Width  
  - Petal Length vs Petal Width  
  - Sepal Length vs Petal Length  
  - Sepal Width vs Petal Width  
- Key Insights:  
  - Petal features are the most important for classification.  
  - Setosa is distinctly separable, while Versicolor and Virginica overlap slightly.  

---

## Models Implemented

Three supervised learning models were trained, evaluated, and compared:

| Model                  | Accuracy |
|-------------------------|----------|
| K-Nearest Neighbors (k=3) | 1.0 (100%) |
| Logistic Regression     | 1.0 (100%) |
| Decision Tree           | 1.0 (100%) |

- All models achieved **perfect classification** on the test set.  
- This confirms that the **Iris dataset is highly separable** with standard ML models.  

---

## Evaluation

Each model was evaluated using:

- **Accuracy**  
- **Confusion Matrix (heatmap with Seaborn)**  
- **Classification Report (Precision, Recall, F1-score)**

## ⚙️ Installation & Usage

### Clone the repository and set up the environment:

## ⚙️ Installation & Usage

### 1. Clone the repository and set up the environment
```bash
git clone https://github.com/varma1221/Iris-Flower-Classification.git
cd Iris-Flower-Classification

# Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt




