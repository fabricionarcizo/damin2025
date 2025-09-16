# Lecture #05 (Data Exploration and Visualization)

This folder contains the supporting material used during Lecture #05 of the Data Mining KSD course (Autumn 2025) **on 23 September 2025**.

## Overview

This lecture covers comprehensive data exploration and visualization techniques essential for understanding and analyzing datasets. All examples are provided as interactive Jupyter Notebooks with detailed explanations, code implementations, and visualizations using matplotlib, seaborn, and advanced plotting libraries.

## Content Structure

### Core Data Exploration Notebooks

#### 1. **Data Types and Structure** (`ex01_data_types.ipynb`)

- **Learning Objectives**: Understanding different data types and their characteristics
- **Techniques Covered**:
  - Binary data (two possible values)
  - Nominal data (categorical without order)
  - Ordinal data (categorical with meaningful order)
  - Interval data (continuous with no true zero)
  - Ratio data (continuous with true zero point)
- **Key Tools**: pandas DataFrames, custom table rendering with matplotlib
- **Practical Applications**: Data structure analysis, type-appropriate processing decisions

#### 2. **Descriptive Statistics Visualization** (`ex02_descriptive_statistics.ipynb`)

- **Learning Objectives**: Calculating and visualizing central tendency measures
- **Techniques Covered**:
  - Mean, median, mode, and midrange calculations
  - Distribution fitting with Gaussian models
  - Skewness analysis (symmetric, positive, negative)
  - Multi-modal distribution handling
- **Key Tools**: NumPy statistics, SciPy, lmfit Gaussian models, custom plotting functions
- **Practical Applications**: Statistical summaries, distribution analysis, data quality assessment

#### 3. **Normal Distribution and Percentiles** (`ex03_normal_percentile.ipynb`)

- **Learning Objectives**: Understanding z-scores and percentile relationships
- **Techniques Covered**:
  - Standard normal distribution visualization
  - Z-score to percentile conversion
  - Dual-axis plotting techniques
  - Bell curve analysis and interpretation
- **Key Tools**: SciPy statistics, matplotlib dual-axis plots, custom tick formatting
- **Practical Applications**: Statistical testing, data standardization, outlier detection

#### 4. **Pearson Correlation Analysis** (`ex04_pearson_correlation_coefficient.ipynb`)

- **Learning Objectives**: Measuring and interpreting linear relationships between variables
- **Techniques Covered**:
  - Pearson correlation coefficient calculation
  - Correlation matrix generation and visualization
  - Scatter plot analysis with trend lines
  - Statistical significance testing
- **Key Tools**: pandas correlation functions, seaborn heatmaps, matplotlib scatter plots
- **Practical Applications**: Feature selection, relationship discovery, multicollinearity detection

#### 5. **Automated Data Profiling** (`ex05_ydata_profiling.ipynb`)

- **Learning Objectives**: Generating comprehensive automated data analysis reports
- **Techniques Covered**:
  - YData Profiling library implementation
  - HTML report generation
  - Automated statistical summaries
  - Missing value and data quality analysis
- **Key Tools**: ydata_profiling ProfileReport, automated visualization generation
- **Practical Applications**: Quick dataset overview, initial data assessment, stakeholder reporting

#### 6. **Distance Metrics and Similarity** (`ex06_distance_metrics.ipynb`)

- **Learning Objectives**: Understanding different distance measures for data comparison
- **Techniques Covered**:
  - Euclidean distance calculations
  - Manhattan distance implementation
  - Cosine similarity analysis
  - Distance matrix visualization
- **Key Tools**: SciPy spatial distance functions, custom distance implementations
- **Practical Applications**: Clustering algorithms, similarity search, recommendation systems

### Advanced Visualization Techniques

#### 7. **Basic Visualization Portfolio** (`ex07_basic_visualization.ipynb`)

- **Learning Objectives**: Creating comprehensive visualization suites
- **Techniques Covered**:
  - Multiple chart types (bar, line, pie, scatter, histogram, heatmap, box plot)
  - Complex subplot layouts using gridspec
  - Professional styling and color schemes
  - Appropriate chart selection for data types
- **Key Tools**: matplotlib gridspec, seaborn styling, pandas plotting functions
- **Practical Applications**: Dashboard creation, report generation, presentation graphics

#### 8. **Interactive Visualization** (`ex08_interactive_visualization.ipynb`)

- **Learning Objectives**: Building dynamic and interactive data visualizations
- **Techniques Covered**:
  - Plotly interactive charts
  - Dynamic filtering and selection
  - Hover information and tooltips
  - Web-ready visualization formats
- **Key Tools**: Plotly Express, interactive plotting libraries
- **Practical Applications**: Web dashboards, exploratory data analysis, user interfaces

#### 9. **Advanced Visualization Techniques** (`ex09_advanced_visualization.ipynb`)

- **Learning Objectives**: Implementing sophisticated visualization methods
- **Techniques Covered**:
  - Complex multi-dimensional visualizations
  - Advanced statistical plots
  - Custom visualization functions
  - High-quality publication graphics
- **Key Tools**: Advanced matplotlib techniques, custom plotting functions
- **Practical Applications**: Research publications, advanced analytics, complex data storytelling

## Educational Features

All notebooks include:

- 📚 **Clear Learning Objectives** for each visualization technique
- 🔍 **Step-by-step Explanations** with theoretical background
- 💻 **Hands-on Code Examples** with detailed comments
- 📊 **Interactive Visualizations** using matplotlib, seaborn, and plotly
- 📈 **Statistical Analysis** and interpretation methods
- 🎯 **Real-world Applications** and use case scenarios
- ✅ **Best Practices** for effective data visualization
- ⚠️ **Common Pitfalls** and how to avoid them
- 📝 **Comprehensive Summaries** with key takeaways

## Technical Requirements

- **Python 3.x** with data visualization libraries
- **Core Libraries**: pandas, NumPy, matplotlib, seaborn, plotly, ydata_profiling
- **Statistical Libraries**: SciPy, lmfit for advanced statistical modeling
- **Development Environment**: Jupyter Notebook or VS Code with notebook support
- **Data Files**: Sample datasets included in `data/` folder (managed with DVC)

## Additional Resources

### Folders

- **`data/`**: Sample datasets and visualization themes (DVC managed)
  - `sample_data_100.csv`: Small dataset for quick examples
  - `sample_data_1000.csv`: Larger dataset for comprehensive analysis
  - `themes/`: Custom matplotlib style sheets (rose-pine theme)
- **`exercises/`**: Practice datasets and supplementary materials
  - `starwars.csv`: Character dataset for advanced exercises
- **`challenges/`**: Advanced challenges and research papers

### Files

- **`data.dvc`**: Data Version Control file for dataset management
- **`exercises.dvc`**: DVC file for exercise materials
- **`challenges.dvc`**: DVC file for challenge datasets and papers
- **`iris_dataset_report.html`**: Sample automated profiling report
- **`.gitignore`**: Git ignore patterns for the lecture folder

## Learning Path

**Recommended sequence for maximum learning effectiveness:**

1. **Foundation** (Ex 1-3): Core data understanding and statistics

   - Data types → Descriptive statistics → Normal distributions

2. **Correlation & Profiling** (Ex 4-6): Relationship analysis and automation

   - Correlation analysis → Automated profiling → Distance metrics

3. **Visualization Mastery** (Ex 7-9): Comprehensive visualization skills
   - Basic charts → Interactive plots → Advanced techniques

Each notebook builds upon concepts from previous ones, creating a comprehensive understanding of data exploration and visualization essential for effective data mining and analysis.

## Usage Instructions

1. **Setup Environment**: Ensure all required Python libraries are installed
2. **Launch Notebooks**: Open notebooks in Jupyter or VS Code
3. **Follow Sequence**: Work through notebooks in the recommended order
4. **Practice**: Use provided datasets to reinforce learning
5. **Experiment**: Modify visualizations with your own data
6. **Generate Reports**: Create automated profiling reports for new datasets

This comprehensive collection provides both theoretical understanding and practical skills for effective data exploration and visualization in real-world data science applications.
