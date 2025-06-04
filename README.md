# Prodigy_Task_2
# 🚢 Titanic Survival Data Analysis & Visualization

This project is part of a data analytics task focused on analyzing the Titanic dataset to understand survival patterns based on passenger demographics and characteristics. It uses data cleaning, transformation, and visualizations to uncover meaningful insights.

## 🎯 Task Objective

Analyze the Titanic dataset (`train.csv`) to:
- Handle missing data
- Perform basic feature transformations
- Visualize survival distribution by various factors (Sex, Age, Class, etc.)
- Generate a correlation heatmap and pair plots

## 📁 Dataset

- **Source:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)
- **Files Used:** `train.csv`

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn

## ⚙️ Key Steps Performed

1. **Data Cleaning**
   - Filled missing values for `Age` and `Embarked`
   - Dropped `Cabin` due to excessive null values

2. **Feature Transformation**
   - Converted categorical variables like `Sex` and `Embarked` into numeric format for analysis

3. **Visualization**
   - Correlation heatmap of numerical features
   - Survival count bar plots
   - Survival comparison across `Sex`, `Pclass`
   - Histogram for Age distribution
   - Pairplot for multivariate analysis

## 📊 Sample Visuals

- **Survival by Gender**
- **Survival by Class**
- **Age Distribution**
- **Correlation Heatmap**
- **Pairplot of Key Variables**

*(Screenshots or saved graphs can be added here)*

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic-visualization.git
   cd titanic-visualization
Install the required packages:
pip install pandas matplotlib seaborn
Place the train.csv file in the project directory.

Run the Python script:
python titanic_analysis.py
