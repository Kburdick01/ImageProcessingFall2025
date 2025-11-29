Applied Data Mining - Fall 2025

This repository contains implementations and automated report generation scripts for the Applied Data Mining course at Manhattan College, Department of Electrical and Computer Engineering.
Repository Overview

This collection represents a systematic exploration of fundamental data mining techniques through practical implementation and analysis. Each project includes automated report generation that produces IEEE-formatted documentation with comprehensive methodology descriptions, experimental results, and visualizations.
Project Structure
Project 2: Clustering Analysis

Topic: Comparative Study of Clustering Algorithms

Implementation and analysis of three fundamental clustering paradigms:

    K-Means Clustering: Partition-based centroid optimization for well-separated Gaussian clusters
    Hierarchical Clustering: Agglomerative clustering with Ward linkage and dendrogram visualization
    DBSCAN: Density-based spatial clustering for non-convex cluster identification and outlier detection

Key Focus: Algorithm comparison across different data geometries, computational complexity trade-offs, and practical applicability assessment.
Project 3: Time Series Analysis and Forecasting

Topic: Temporal Pattern Recognition and Prediction

Comprehensive time series decomposition and forecasting using:

    Seasonal decomposition (trend, seasonal, residual components)
    ARIMA modeling for autoregressive forecasting
    Exponential smoothing for trend and seasonal predictions
    Autocorrelation and partial autocorrelation analysis

Key Focus: Understanding temporal dependencies, model selection criteria, and forecast accuracy evaluation.
Project 4: Classification Algorithms

Topic: Supervised Learning Methods Comparison

Evaluation of classification techniques for labeled datasets with performance metric analysis.
Project 5: Advanced Clustering - Mean Shift

Topic: Non-Parametric Density-Based Clustering

Implementation of mean shift algorithm for automatic cluster discovery without predefined cluster counts.
Project 6: Dimensionality Reduction - PCA

Topic: Principal Component Analysis

Eigenvalue decomposition for feature space transformation, variance retention analysis, and high-dimensional data visualization.

Key Focus: Explained variance ratios, principal component interpretation, and dimensionality reduction trade-offs.
Project 7: Outlier Detection

Topic: Anomaly Identification Methods

Statistical and algorithmic approaches to outlier detection in multivariate datasets.
Technical Implementation
Dependencies

    Core Libraries: NumPy, Pandas, SciPy
    Machine Learning: scikit-learn, statsmodels
    Visualization: Matplotlib
    Report Generation: python-docx

Report Generation System

Each project includes a standalone report generation script that:

    Implements the data mining algorithm(s)
    Generates synthetic or processes real datasets
    Produces publication-quality visualizations
    Creates IEEE-formatted technical reports in DOCX format

Batch Generation: Use generate_all_reports.py to generate all project reports sequentially with error handling and summary statistics.
Usage

Generate individual project report:

python3 generate_project2_report.py

Generate all reports:

python3 generate_all_reports.py

Repository Contents
Documentation

    Assignment specifications (PDF format)
    Generated technical reports (IEEE format)
    Visualization outputs (high-resolution PNG)

Source Code

    Individual report generation scripts (generate_project[2-7]_report.py)
    Unified report generator (generate_all_reports.py)

Academic Context

Institution: Manhattan College
Department: Electrical and Computer Engineering
Course: Applied Data Mining
Format: IEEE-style technical reporting with experimental validation
Implementation Notes

All implementations prioritize:

    Reproducibility: Fixed random seeds for consistent results
    Documentation: Comprehensive inline comments and docstrings
    Visualization: Clear, publication-ready figures with appropriate annotations
    Academic Rigor: Proper citation of foundational algorithms and methodologies

Report Structure

Each generated report follows IEEE conference paper format:

    Abstract
    Introduction with literature context
    Problem definition and research questions
    Applied methodology with mathematical formulations
    Results with quantitative metrics
    Discussion of strengths, weaknesses, and applications
    Conclusion with future work recommendations
    References to foundational papers

Future Extensions

Potential areas for expansion:

    Ensemble clustering methods
    Deep learning-based time series forecasting
    Real-world dataset applications
    Hyperparameter optimization frameworks
    Cross-validation and statistical significance testing

Note: This repository serves as a comprehensive reference for fundamental data mining techniques with emphasis on rigorous experimental methodology and clear technical communication.
