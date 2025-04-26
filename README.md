# Task_2
Exploratory Data Analysis (EDA) on the cleaned Titanic dataset to identify patterns, correlations, and survival trends using Python.
# Exploratory Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on a **cleaned version** of the Titanic dataset, prepared during Task 1.  
The goal is to understand the dataset deeply through **statistical summaries**, **visualizations**, and **pattern recognition**, preparing it for future machine learning tasks.

---

## Project Structure

| File Name                  | Description                                   |
|-----------------------------|-----------------------------------------------|
| `Titanic_Cleaned_EDA.ipynb` | Jupyter Notebook containing the full EDA workflow |
| `cleaned_titanic_data.csv`  | Preprocessed and cleaned Titanic dataset |
| `README.md`                 | Project overview, objectives, and instructions |

---

## Dataset Information

- **Original Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)
- **Description**: The Titanic dataset provides details of passengers aboard the Titanic, such as age, sex, ticket class, fare paid, and survival status.
- **Preprocessing Applied**:
  - Missing values handled
  - Standardization of numerical features (`Age`, `Fare`)
  - Categorical encoding (`Sex`, `Embarked`)
  - Removal of irrelevant or highly missing features (e.g., `Cabin`)

---

## Project Objectives

- Generate descriptive statistics (mean, median, std, min, max)
- Visualize distributions of key features using histograms and boxplots
- Analyze feature relationships using correlation heatmaps and pairplots
- Understand survival patterns across gender and passenger class
- Identify trends, anomalies, and patterns useful for modeling
- Build logical inferences based on observations

---

## EDA Workflow

### Step 1: Import Libraries
- Imported `pandas`, `seaborn`, and `matplotlib` for data manipulation and visualization.

### Step 2: Load Cleaned Dataset
- Loaded the already preprocessed Titanic dataset (`cleaned_titanic_data.csv`).

### Step 3: Generate Summary Statistics
- Used `describe()` to compute:
  - Mean, median, standard deviation, minimum, maximum, and percentiles for numerical features.

### Step 4: Visualize Distributions
- Plotted histograms of:
  - **Age** (standardized values)
  - **Fare** (standardized values)
- Visualized boxplots to detect outliers.

### Step 5: Correlation Analysis
- Created a **correlation heatmap** to observe relationships between:
  - `Age`, `Fare`, `Pclass`, `Survived`, etc.
- Plotted pairplots (scatter matrix) colored by survival status.

### Step 6: Category-Based Analysis
- Plotted **barplots** showing:
  - Survival rates by gender (`Sex_male`: 0=Female, 1=Male)
  - Survival rates by passenger class (`Pclass`)

### Step 7: Observations and Inferences
- Summarized findings from the visualizations into clear, concise points.

---

## 📈 Key Findings

- **Gender Impact**: Females had much higher survival rates than males.
- **Passenger Class**: 1st class passengers had the best survival chances compared to 2nd and 3rd classes.
- **Fare Relationship**: Higher fares were associated with higher survival probability.
- **Age Distribution**: Slight skewness detected; younger passengers had relatively higher survival.

---

## Tools & Libraries Used

- **Python 3**
- **Pandas** – for data manipulation
- **Matplotlib** – for static plotting
- **Seaborn** – for attractive statistical plots

---

## How to Run the Notebook

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/titanic-cleaned-eda.git
   cd titanic-cleaned-eda
   ```

2. **Open the notebook** `Titanic_Cleaned_EDA.ipynb` using:
   - Jupyter Notebook
   - Google Colab
   - VS Code with Jupyter extension

3. **Run all cells** to view visualizations and analysis.

---

## Internship Context

- **Program**: AI & ML Internship
- **Task**: Task 2 - Exploratory Data Analysis
- **Objective**: Gain practical experience in understanding and preparing real-world datasets for machine learning.


---

## Important Notes

- No additional cleaning was done in this task, as the dataset was already processed in Task 1.
- Focused purely on exploratory analysis and pattern discovery.

---

##  Acknowledgements

- Titanic dataset sourced from Kaggle
- Visualizations inspired by best practices in data science

---

# Happy Exploring! ✨

---
