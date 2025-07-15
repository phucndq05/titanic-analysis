# Titanic Survival Analysis

This project is a classic exploratory data analysis (EDA) of the Titanic dataset. The main goal is to explore the data and find factors that seemed to have an impact on the survival rate of the passengers.

## 📊 Dataset

The dataset used in this analysis is the `train.csv` file from the [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data) competition on Kaggle.

It contains information about individual passengers, such as their age, gender, passenger class, and whether they survived the disaster.

## 🚀 Technologies Used

- **Language:** Python
- **Libraries:**
  - Pandas (for data manipulation)
  - Matplotlib & Seaborn (for data visualization)
- **Environment:** Jupyter Notebook (run in VS Code)

## 💡 Key Findings

The analysis reveals a few key factors correlated with survival:

1.  **Gender:** Female passengers had a significantly higher survival rate compared to male passengers.
2.  **Passenger Class:** Passengers in the First Class (Pclass 1) had the highest survival rate, while passengers in the Third Class (Pclass 3) had the lowest. This suggests a strong correlation between socio-economic status and survival.

## 🛠️ How to Run

1.  Clone this repository:
    ```bash
    git clone [https://github.com/phucndq05/titanic-analysis.git](https://github.com/phucndq05/titanic-analysis.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd titanic-analysis
    ```
3.  Install the required libraries:
    ```bash
    pip3 install pandas matplotlib seaborn jupyter
    ```
4.  Open and run the `analysis.ipynb` notebook in VS Code or any Jupyter environment.