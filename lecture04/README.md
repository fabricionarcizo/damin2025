# Lecture #04 (Data Preprocessing)

This folder contains the supporting material used during Lecture #04 of the Data Mining KSD course (Autumn 2025) **on 16 September 2025**.

## Overview

This lecture covers comprehensive data preprocessing techniques essential for data mining projects. All examples are provided as interactive Jupyter Notebooks with detailed explanations, code implementations, and visualizations.

## Content Structure

### Core Data Preprocessing Notebooks

#### 1. **Missing Data Handling** (`ex01_handling_missing_data.ipynb`)

- **Learning Objectives**: Understanding different types of missing data and appropriate handling strategies
- **Techniques Covered**:
  - Deletion methods (listwise and pairwise)
  - Mean/median/mode imputation
  - K-Nearest Neighbors (KNN) imputation
  - Advanced imputation strategies
- **Key Tools**: pandas, scikit-learn SimpleImputer, KNNImputer
- **Practical Applications**: Real-world missing data scenarios and decision frameworks

#### 2. **Dealing with Noisy Data** (`ex02_dealing_noisy_data.ipynb`)

- **Learning Objectives**: Identifying and reducing noise in datasets
- **Techniques Covered**:
  - Binning and smoothing techniques
  - Regression-based noise reduction
  - Outlier detection as noise identification
  - Statistical smoothing methods
- **Key Tools**: NumPy statistical functions, pandas grouping, custom smoothing algorithms
- **Practical Applications**: Signal processing, sensor data cleaning, survey response cleaning

#### 3. **Detecting Outliers** (`ex03_detecting_outliers.ipynb`)

- **Learning Objectives**: Systematic outlier identification and treatment strategies
- **Techniques Covered**:
  - Z-score method for statistical outliers
  - Interquartile Range (IQR) method
  - Outlier removal vs. transformation approaches
  - Multivariate outlier detection
- **Key Tools**: SciPy statistics, custom outlier detection functions
- **Practical Applications**: Fraud detection, quality control, data validation

#### 4. **Data Integration** (`ex04_data_integration.ipynb`)

- **Learning Objectives**: Combining data from multiple sources effectively
- **Techniques Covered**:
  - CSV and XML data integration
  - Schema alignment and mapping
  - Handling different data formats
  - Data fusion strategies
- **Key Tools**: pandas merge/join operations, XML parsing, data transformation
- **Practical Applications**: Multi-source analytics, data warehouse construction

#### 5. **Normalization and Standardization** (`ex05_normalization_standardization.ipynb`)

- **Learning Objectives**: Understanding when and how to scale data appropriately
- **Techniques Covered**:
  - Min-Max normalization (scaling to [0,1])
  - Z-score standardization (mean=0, std=1)
  - Robust scaling techniques
  - When to use each method
- **Key Tools**: scikit-learn MinMaxScaler, StandardScaler, RobustScaler
- **Practical Applications**: Machine learning preprocessing, feature engineering

#### 6. **Aggregation and Discretization** (`ex06_aggregation_discretization.ipynb`)

- **Learning Objectives**: Data summarization and categorical conversion techniques
- **Techniques Covered**:
  - Statistical aggregation methods
  - Equal-width and equal-frequency binning
  - Custom discretization strategies
  - Handling continuous-to-categorical conversion
- **Key Tools**: pandas groupby operations, custom binning functions, NumPy statistical methods
- **Practical Applications**: Data summarization, categorical analysis, dimension reduction

#### 7. **Categorical Encoding** (`ex07_one_hot_label_enconding.ipynb`)

- **Learning Objectives**: Converting categorical variables for machine learning algorithms
- **Techniques Covered**:
  - One-Hot Encoding for nominal variables
  - Label Encoding for ordinal variables
  - Decision framework for encoding choice
  - Handling high-cardinality categories
- **Key Tools**: scikit-learn OneHotEncoder, LabelEncoder, pandas get_dummies
- **Practical Applications**: Machine learning preprocessing, categorical data analysis

### Advanced Sampling Techniques

#### 8. **Simple Random Sampling** (`ex08_simple_random_sampling.ipynb`)

- **Learning Objectives**: Foundation of probability sampling methods
- **Techniques Covered**:
  - Sampling with and without replacement
  - Sample size determination
  - Quality assessment of random samples
  - Bootstrap sampling concepts
- **Key Tools**: pandas sample(), NumPy random functions
- **Practical Applications**: Statistical inference, train-test splits, data exploration

#### 9. **Stratified Sampling** (`ex09_stratified_sampling.ipynb`)

- **Learning Objectives**: Ensuring representative samples from heterogeneous populations
- **Techniques Covered**:
  - Proportional stratified sampling
  - Equal allocation sampling
  - Optimal allocation (Neyman allocation)
  - Strata definition and validation
- **Key Tools**: scikit-learn train_test_split with stratification
- **Practical Applications**: Survey research, machine learning with imbalanced data, market research

#### 10. **Systematic Sampling** (`ex10_systematic_sampling.ipynb`)

- **Learning Objectives**: Efficient sampling for ordered populations
- **Techniques Covered**:
  - Systematic sampling with random start
  - Circular systematic sampling
  - Trend-aware sampling strategies
  - Periodicity bias detection
- **Key Tools**: Custom systematic sampling functions, statistical validation methods
- **Practical Applications**: Quality control, time series sampling, audit procedures

## Educational Features

All notebooks include:

- 📚 **Clear Learning Objectives** for each topic
- 🔍 **Step-by-step Explanations** with theoretical background
- 💻 **Hands-on Code Examples** with detailed comments
- 📊 **Interactive Visualizations** using matplotlib and custom plotting functions
- 📈 **Statistical Analysis** and validation methods
- 🎯 **Real-world Applications** and use case scenarios
- ✅ **Best Practices** and implementation guidelines
- ⚠️ **Common Pitfalls** and how to avoid them
- 📝 **Comprehensive Summaries** with key takeaways

## Technical Requirements

- **Python 3.x** with data science libraries
- **Core Libraries**: pandas, NumPy, matplotlib, scikit-learn, SciPy
- **Development Environment**: Jupyter Notebook or VS Code with notebook support
- **Data Files**: Sample datasets included in `data/` folder (managed with DVC)

## Additional Resources

### Folders

- **`data/`**: Sample datasets used in the notebooks (DVC managed)
- **`exercises/`**: Additional practice exercises and supplementary materials

### Files

- **`data.dvc`**: Data Version Control file for dataset management
- **`exercises.dvc`**: DVC file for exercise materials
- **`.gitignore`**: Git ignore patterns for the lecture folder

## Learning Path

**Recommended sequence for maximum learning effectiveness:**

1. **Foundation** (Ex 1-3): Start with data quality issues

   - Missing data handling → Noise reduction → Outlier detection

2. **Integration & Transformation** (Ex 4-7): Data preparation techniques

   - Data integration → Scaling methods → Aggregation → Encoding

3. **Sampling Methods** (Ex 8-10): Statistical sampling approaches
   - Random sampling → Stratified sampling → Systematic sampling

Each notebook builds upon concepts from previous ones, creating a comprehensive understanding of the data preprocessing pipeline essential for successful data mining projects.

## Usage Instructions

1. **Setup Environment**: Ensure all required Python libraries are installed
2. **Launch Notebooks**: Open notebooks in Jupyter or VS Code
3. **Follow Sequence**: Work through notebooks in the recommended order
4. **Practice**: Use provided exercises to reinforce learning
5. **Experiment**: Modify code examples with your own data

This comprehensive collection provides both theoretical understanding and practical skills for effective data preprocessing in real-world data mining applications.
