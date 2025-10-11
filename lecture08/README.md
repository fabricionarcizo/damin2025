# Lecture #08 (Regression Analysis)

This folder contains the supporting material used during Lecture #08 of the Data Mining KSD course (Autumn 2025) **on 21 October 2025**.

## Overview

This lecture covers comprehensive regression analysis techniques essential for predictive modeling and statistical inference in data mining. All examples are provided as interactive Jupyter Notebooks with detailed explanations, mathematical foundations, code implementations, and visualizations demonstrating both simple and advanced regression methodologies.

## Content Structure

### Fundamental Regression Techniques

#### 1. **Simple Linear Regression** (`ex01_simple_linear_regression.ipynb`)

- **Learning Objectives**: Understanding the foundation of linear regression with one predictor variable
- **Techniques Covered**:
  - Simple linear regression implementation
  - Train-test split methodology
  - Residual analysis and visualization
  - Model evaluation with RMSE
  - Feature correlation analysis
- **Key Tools**: scikit-learn LinearRegression, matplotlib visualization, pandas data manipulation
- **Practical Applications**: Predictive modeling with single features, understanding linear relationships, Breast Cancer Wisconsin dataset analysis

#### 2. **County-Level Data Analysis** (`ex02_county_complete.ipynb`)

- **Learning Objectives**: Comprehensive statistical analysis and regression modeling with real-world data
- **Techniques Covered**:
  - Data distribution analysis (histograms, violin plots)
  - Scatter plot analysis for relationship exploration
  - Linear regression with inferential statistics
  - Confidence interval calculation
  - Hypothesis testing (t-tests, p-values)
  - Standard error estimation
- **Key Tools**: seaborn for advanced visualization, scipy.stats for statistical inference, pandas for data manipulation
- **Practical Applications**: Socioeconomic data analysis, policy research, understanding education-poverty relationships

#### 3. **Multiple Linear Regression** (`ex03_multiple_linear_regression.ipynb`)

- **Learning Objectives**: Extending regression to multiple predictor variables
- **Techniques Covered**:
  - Multiple linear regression with multiple features
  - Feature selection based on correlation
  - Data standardization techniques
  - 3D visualization of regression planes
  - Residual analysis in multiple dimensions
- **Key Tools**: scikit-learn StandardScaler, 3D plotting with matplotlib, correlation analysis
- **Practical Applications**: Complex predictive modeling, Diabetes progression prediction, multi-factor analysis

#### 4. **Professor Evaluations Analysis** (`ex04_teachers_evaluations.ipynb`)

- **Learning Objectives**: Advanced regression modeling with categorical and continuous variables
- **Techniques Covered**:
  - Handling overlapping data points
  - Jitter application for visualization
  - Simple and multiple linear regression
  - Categorical variable encoding (Label Encoding)
  - Multiple regression with mixed variable types
  - Confidence intervals with statsmodels
  - Coefficient visualization and interpretation
- **Key Tools**: seaborn scatter plots, LabelEncoder, statsmodels OLS, error bar visualization
- **Practical Applications**: Educational research, performance prediction, understanding multi-factor influences

### Advanced Regression Methods

#### 5. **Polynomial Regression** (`ex05_polynomial_regression.ipynb`)

- **Learning Objectives**: Modeling non-linear relationships with polynomial features
- **Techniques Covered**:
  - Polynomial feature transformation
  - Multiple degree comparison (2nd to 5th degree)
  - Model evaluation with MAE and R²
  - Overfitting detection and analysis
  - Prediction with polynomial models
- **Key Tools**: scikit-learn PolynomialFeatures, model comparison visualization
- **Practical Applications**: Non-linear relationship modeling, housing price prediction, curve fitting

#### 6. **Correlation Analysis** (`ex06_correlation_analysis.ipynb`)

- **Learning Objectives**: Understanding different correlation measures and their applications
- **Techniques Covered**:
  - Pearson correlation (linear relationships)
  - Spearman correlation (monotonic relationships)
  - Kendall's Tau (ordinal variables with ties)
  - Correlation interpretation and selection
  - Pair plot visualization techniques
- **Key Tools**: scipy.stats correlation functions, seaborn PairGrid, advanced plotting
- **Practical Applications**: Feature selection, relationship discovery, understanding data dependencies, restaurant tipping analysis

#### 7. **Regularization Techniques** (`ex07_regularization_techniques.ipynb`)

- **Learning Objectives**: Preventing overfitting with regularization methods
- **Techniques Covered**:
  - Ridge Regression (L2 regularization)
  - Lasso Regression (L1 regularization)
  - Polynomial regression comparison
  - Regularization parameter tuning
  - Model comparison and evaluation
- **Key Tools**: scikit-learn Ridge and Lasso, model comparison, performance metrics
- **Practical Applications**: High-dimensional data modeling, feature selection, overfitting prevention, medical data analysis

## Educational Features

All notebooks include:

- 📚 **Clear Learning Objectives** for each regression technique
- 🔍 **Step-by-step Explanations** with mathematical foundations and statistical theory
- 💻 **Hands-on Code Examples** with detailed comments and best practices
- 📊 **Interactive Visualizations** using matplotlib, seaborn, and 3D plotting
- 📈 **Statistical Analysis** including hypothesis testing, confidence intervals, and inference
- 🎯 **Real-world Applications** with authentic datasets and practical use cases
- ✅ **Best Practices** for model selection, validation, and interpretation
- ⚠️ **Common Pitfalls** including overfitting, underfitting, and multicollinearity
- 📝 **Comprehensive Summaries** with key metrics (RMSE, R², MAE, TSS, SSE)
- 🔧 **Model Evaluation** and performance comparison techniques

## Technical Requirements

- **Python 3.x** with statistical and machine learning libraries
- **Core Libraries**: pandas, NumPy, matplotlib, seaborn
- **Statistical Analysis**: scipy, statsmodels
- **Machine Learning**: scikit-learn (LinearRegression, Ridge, Lasso, PolynomialFeatures, StandardScaler)
- **Development Environment**: Jupyter Notebook or VS Code with notebook support
- **Data Files**: CSV datasets included in `data/` folder (managed with DVC)

## Additional Resources

### Folders

- **`data/`**: Real-world datasets for regression analysis (DVC managed)
  - `county_complete.csv`: County-level socioeconomic data
  - `evals.csv`: Professor evaluation and beauty dataset
  - `simple_windsor.csv`: Housing data for polynomial regression
  - `portfolio_data.csv`: Financial data for additional analysis

### Files

- **`data.dvc`**: Data Version Control file for dataset management
- **`.gitignore`**: Git ignore patterns for the lecture folder

## Learning Path

**Recommended sequence for maximum learning effectiveness:**

1. **Foundation** (Ex 1-2): Build regression fundamentals

   - Simple linear regression → Statistical inference and confidence intervals

2. **Multiple Variables** (Ex 3-4): Extend to multiple predictors

   - Multiple linear regression → Mixed variable types and categorical encoding

3. **Advanced Techniques** (Ex 5-7): Handle complex scenarios
   - Polynomial regression → Correlation analysis → Regularization methods

Each notebook progressively builds upon previous concepts, creating a comprehensive understanding of regression analysis from basic linear models to advanced regularization techniques essential for professional data mining applications.

## Usage Instructions

1. **Setup Environment**: Install required Python libraries and statistical packages
2. **Launch Notebooks**: Open notebooks in Jupyter or VS Code
3. **Follow Sequence**: Work through notebooks in the recommended order
4. **Understand Theory**: Pay attention to statistical concepts and mathematical foundations
5. **Practice**: Apply techniques to your own datasets and modify parameters
6. **Interpret Results**: Focus on understanding coefficients, p-values, and confidence intervals

This comprehensive collection bridges theoretical statistical concepts with practical implementation skills, preparing students for real-world regression analysis challenges in data mining and predictive modeling applications.
