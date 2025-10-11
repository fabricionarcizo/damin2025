# Lecture #10 (Clustering: Advanced Techniques)

This folder contains the supporting material used during Lecture #10 of the Data Mining KSD course (Autumn 2025) **on 04 November 2025**.

## Overview

This lecture covers advanced clustering techniques that go beyond traditional partitioning methods. All examples are provided as interactive Jupyter Notebooks with detailed explanations, code implementations, and visualizations demonstrating density-based clustering, probabilistic models, and neural network-based approaches.

## Content Structure

### Advanced Clustering Algorithms

#### 1. **DBSCAN Clustering** (`ex01_dbscan_clustering.ipynb`)

- **Learning Objectives**: Understanding density-based spatial clustering and comparing it with K-Means
- **Techniques Covered**:
  - K-Means clustering on anisotropic data
  - DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
  - Feature standardization for density-based methods
  - Handling arbitrary-shaped clusters
  - Noise point detection and outlier identification
  - Comparison of centroid-based vs. density-based clustering
- **Key Tools**: scikit-learn DBSCAN and KMeans, StandardScaler, pandas, matplotlib
- **Practical Applications**: Spatial data analysis, anomaly detection, cluster discovery without predefined k

#### 2. **1D Gaussian Mixture Model** (`ex02_1d_gaussian_mixture_model.ipynb`)

- **Learning Objectives**: Implementing Gaussian Mixture Models from scratch using the Expectation-Maximization algorithm
- **Techniques Covered**:
  - Kernel Density Estimation (KDE) for data distribution analysis
  - Peak detection and data splitting
  - Multivariate normal distribution generation
  - Probability Density Function (PDF) visualization
  - Expectation-Maximization (EM) algorithm implementation
  - E-Step: Computing responsibility weights
  - M-Step: Updating means, variances, and mixing coefficients
  - Convergence detection and iteration control
  - Random initialization strategies
  - Statistical parameter estimation
- **Key Tools**: NumPy for statistical computing, scipy for distributions and signal processing, seaborn for KDE visualization, matplotlib
- **Practical Applications**: Statistical modeling, distribution fitting, probabilistic clustering, mixture model estimation

#### 3. **2D Gaussian Mixture Model** (`ex03_2d_gaussian_mixture_model.ipynb`)

- **Learning Objectives**: Applying Gaussian Mixture Models to 2D data using scikit-learn
- **Techniques Covered**:
  - GMM clustering on anisotropically distributed data
  - Multivariate Gaussian component fitting
  - Soft clustering with probability assignments
  - Kernel Density Estimation visualization in 2D
  - Cluster overlap and uncertainty representation
  - Comparison with hard clustering methods
- **Key Tools**: scikit-learn GaussianMixture, seaborn KDE plots, pandas, matplotlib
- **Practical Applications**: Image segmentation, pattern recognition, soft cluster assignment, probabilistic data modeling

#### 4. **Self-Organizing Maps (SOM)** (`ex04_self_organizing_maps.ipynb`)

- **Learning Objectives**: Understanding neural network-based clustering with topology preservation
- **Techniques Covered**:
  - Self-Organizing Map architecture and training
  - Competitive learning for unsupervised clustering
  - Topology-preserving dimensionality reduction
  - Grid-based neural network structure (2D lattice)
  - Weight vector adaptation
  - Neighborhood function and learning rate decay
  - Visualization of SOM grid connections
  - Multi-center blob data clustering
- **Key Tools**: sklearn_som.som SOM implementation, custom grid plotting functions, matplotlib
- **Practical Applications**: Data visualization, dimensionality reduction, feature mapping, exploratory data analysis

## Educational Features

All notebooks include:

- 📚 **Clear Learning Objectives** for each advanced clustering technique
- 🔍 **Step-by-step Explanations** with mathematical foundations
- 💻 **Hands-on Code Examples** with extensive comments
- 📊 **Interactive Visualizations** showing algorithm behavior
- 📈 **Algorithm Comparisons** (K-Means vs DBSCAN, Hard vs Soft clustering)
- 🎯 **Real-world Applications** and practical use cases
- ✅ **Best Practices** for algorithm selection and parameter tuning
- ⚠️ **Implementation Details** for complex algorithms (EM algorithm)
- 📝 **Comprehensive Documentation** with helper functions
- 🎨 **Custom Color Schemes** for enhanced visualization clarity
- 🔬 **Mathematical Foundations** (probability theory, statistical modeling)

## Technical Requirements

- **Python 3.x** with data science libraries
- **Core Libraries**: NumPy, pandas, matplotlib, seaborn, scikit-learn, scipy
- **Specialized Libraries**:
  - sklearn_som (for Self-Organizing Maps)
  - scipy.stats (for statistical distributions)
  - scipy.signal (for peak detection)
- **Development Environment**: Jupyter Notebook or VS Code with notebook support
- **Data Files**: Sample datasets and blob generation configurations (managed with DVC)

## Additional Resources

### Folders

- **`data/`**: Sample datasets and configuration files (DVC managed)

### Files

- **`data.dvc`**: Data Version Control file for dataset management
- **`.gitignore`**: Git ignore patterns for the lecture folder

## Learning Path

**Recommended sequence for maximum learning effectiveness:**

1. **Density-Based Clustering** (Ex 1): Understand alternatives to partitioning methods

   - DBSCAN fundamentals → Comparison with K-Means → Handling arbitrary shapes

2. **Probabilistic Clustering** (Ex 2-3): Explore statistical approaches

   - 1D GMM from scratch → EM algorithm → 2D GMM with scikit-learn

3. **Neural Network Clustering** (Ex 4): Advanced topology-preserving methods
   - Self-Organizing Maps → Competitive learning → Dimensionality reduction

Each notebook progressively introduces more sophisticated clustering concepts, from density-based methods through probabilistic models to neural network approaches, providing a comprehensive understanding of advanced clustering techniques beyond basic K-Means.

## Usage Instructions

1. **Setup Environment**: Ensure all required Python libraries are installed (NumPy, pandas, scikit-learn, scipy, seaborn, sklearn_som)
2. **Launch Notebooks**: Open notebooks in Jupyter or VS Code
3. **Follow Sequence**: Work through notebooks in the recommended order
4. **Run Examples**: Execute code cells to see algorithms in action
5. **Experiment**: Modify parameters (eps, n_components, grid sizes, learning rates) to understand their impact
6. **Observe Convergence**: Watch the EM algorithm and SOM training processes evolve

## Key Concepts Covered

### Density-Based Clustering

- **DBSCAN**: Finds clusters of arbitrary shape based on density connectivity
- **Core Points**: Points with sufficient neighbors within epsilon radius
- **Border Points**: Non-core points within epsilon of core points
- **Noise Points**: Points that don't belong to any cluster

### Probabilistic Clustering

- **Gaussian Mixture Models**: Soft clustering with probability distributions
- **EM Algorithm**: Iterative optimization for parameter estimation
- **E-Step**: Calculate posterior probabilities (responsibilities)
- **M-Step**: Update model parameters (means, variances, mixing coefficients)
- **Convergence**: Monitoring parameter changes for algorithm termination

### Neural Network Clustering

- **Self-Organizing Maps**: Competitive learning with topology preservation
- **Weight Adaptation**: Adjusting neuron weights based on input similarity
- **Neighborhood Function**: Updating nearby neurons in the grid
- **Topology Preservation**: Maintaining spatial relationships in lower dimensions

This comprehensive collection provides both theoretical understanding and practical implementation skills for advanced clustering algorithms used in real-world data mining applications, including anomaly detection, probabilistic modeling, and topology-preserving dimensionality reduction.
