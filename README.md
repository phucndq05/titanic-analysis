# Titanic Survival Analysis

This project is a classic exploratory data analysis (EDA) of the Titanic dataset. The main goal is to explore passenger data to understand the key factors that influenced survival rates during the disaster.

## 📊 Dataset

The dataset used in this analysis is the `train.csv` file from the [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data) competition on Kaggle.

It contains information about individual passengers, such as their age, gender, passenger class, and whether they survived.

## 💡 Key Findings

This analysis revealed several key factors correlated with survival:

1.  **Gender Impact:** Female passengers had a significantly higher survival rate than male passengers, highlighting the "women and children first" protocol.
2.  **Socio-Economic Status:** Passengers in First Class (`Pclass 1`) had the highest chance of survival, while those in Third Class had the lowest.
3.  **Age Factor:** The age distribution analysis shows that young children had a higher survival rate compared to other age groups.

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:**
  - Pandas & NumPy
  - Matplotlib & Seaborn
- **Environment:** Jupyter Notebook (run in VS Code)

## 🚀 Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/phucndq05/titanic-analysis.git](https://github.com/phucndq05/titanic-analysis.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd titanic-analysis
    ```
3.  **Create and activate a virtual environment (Recommended):**
    ```bash
    python3 -m venv .venv
    source .venv/bin/activate
    ```
4.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
5.  **Launch the Jupyter Notebook:**
    ```bash
    jupyter notebook analysis.ipynb
    ```

## 📁 Project Structure
```
titanic-analysis/
├── data/
│   └── train.csv
├── analysis.ipynb
├── requirements.txt
└── README.md
```