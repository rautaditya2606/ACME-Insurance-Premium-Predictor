# ACME Medical Insurance Cost Prediction

## 📊 Project Overview

This project analyzes medical insurance costs using machine learning techniques to predict healthcare expenses based on various demographic and health factors. The analysis includes exploratory data analysis (EDA) and implements linear regression models to predict insurance charges.

## 🎯 Project Goals

- Analyze factors affecting medical insurance costs
- Build predictive models for insurance charges
- Understand the relationship between demographic factors and healthcare expenses
- Provide insights for insurance cost optimization

## 📁 Project Structure

```
ACME/
├── acme.ipynb          # Main Jupyter notebook with analysis and models
├── expenses.csv         # Medical insurance dataset
└── README.md           # This file
```

## 📈 Dataset Overview

The `expenses.csv` dataset contains 1,338 records with the following features:

| Feature | Type | Description |
|---------|------|-------------|
| `age` | Integer | Age of the insured person |
| `sex` | String | Gender (male/female) |
| `bmi` | Float | Body Mass Index |
| `children` | Integer | Number of dependents/children |
| `smoker` | String | Smoking status (yes/no) |
| `region` | String | Geographic region (northeast/southeast/southwest/northwest) |
| `charges` | Float | Annual medical insurance charges (target variable) |

## 🔍 Key Analysis Features

### Exploratory Data Analysis (EDA)
- **Age Distribution**: Analysis of age patterns and their impact on costs
- **BMI Analysis**: Body Mass Index distribution and correlation with charges
- **Smoking Impact**: Comparative analysis of costs between smokers and non-smokers
- **Regional Analysis**: Cost variations across different geographic regions
- **Gender-based Analysis**: Cost differences between males and females

### Data Visualizations
- Interactive histograms with marginal box plots using Plotly
- Distribution analysis for all key variables
- Correlation analysis between features and target variable

### Machine Learning Models
- **Linear Regression**: Primary model for cost prediction
- **Feature Engineering**: Multi-variable analysis combining age, BMI, and other factors
- **Model Evaluation**: RMSE (Root Mean Square Error) for model performance assessment

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib & Seaborn**: Static visualizations
- **Plotly**: Interactive visualizations
- **Scikit-learn**: Machine learning models (LinearRegression)
- **Jupyter Notebook**: Interactive development environment

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab

### Installation
1. Clone or download this repository
2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter
```

### Running the Analysis
1. Open `acme.ipynb` in Jupyter Notebook
2. Run all cells to execute the complete analysis
3. The notebook includes:
   - Data loading and preprocessing
   - Exploratory data analysis
   - Visualization creation
   - Model training and evaluation

## 📊 Key Findings

### Cost Factors
- **Smoking Status**: Most significant factor affecting insurance costs
- **Age**: Positive correlation with medical charges
- **BMI**: Higher BMI generally leads to higher costs
- **Region**: Geographic variations in healthcare costs
- **Children**: Number of dependents impacts cost calculations

### Model Performance
- Linear regression models trained on various feature combinations
- RMSE evaluation for model accuracy
- Feature importance analysis

## 🔧 Model Usage

The trained models can predict insurance costs based on:
- Individual demographic information
- Health indicators (BMI, smoking status)
- Geographic location
- Family size (number of children)

## 📝 Future Enhancements

- Implement more advanced ML algorithms (Random Forest, XGBoost)
- Add feature scaling and normalization
- Cross-validation for better model evaluation
- Web application for real-time predictions
- API development for integration with other systems

## 🤝 Contributing

Feel free to contribute to this project by:
- Improving the analysis methodology
- Adding new visualizations
- Enhancing model performance
- Suggesting additional features

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: This project is part of the Machine Learning curriculum and demonstrates practical application of data science concepts in healthcare cost analysis. 