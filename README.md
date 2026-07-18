Project Overview
The primary focus of this repository is exploring core data science and statistical concepts natively in R.

Featured Implementation: Gaussian Mixture Model (GMM)
This repository includes a native R implementation of a Gaussian Mixture Model (GMM) optimized using the Expectation-Maximization (EM) algorithm. The script generates a synthetic 2D dataset with two distinct clusters, initializes the model parameters, and runs the EM steps iteratively to track convergence.

Synthetic Data Generation: Generates 20,000 data points split evenly across two distinct normal distributions.
Custom Multivariate Gaussian PDF: Computes probability densities natively without external dependencies.
Expectation-Maximization Loop: Manually implements both the E-step (responsibility calculation) and M-step (parameter updates).
Convergence Tracking: Calculates and records log-likelihood across iterations to track EM behavior.
Visualization: Automatically exports plots showing the final clustered data and log-likelihood convergence.
data-r

Welcome to the data-r repository! This project contains native R implementations and scripts for data analysis, statistical modeling, and machine learning algorithms.

**Project Overview**
The primary focus of this repository is exploring core data science and statistical concepts natively in R.

**Featured Implementation: Gaussian Mixture Model (GMM)**
This repository includes a native R implementation of a Gaussian Mixture Model (GMM) optimized using the Expectation-Maximization (EM) algorithm. The script generates a synthetic 2D dataset with two distinct clusters, initializes the model parameters, and runs the EM steps iteratively to track convergence.

**Synthetic Data Generatio****n**: Generates 20,000 data points split evenly across two distinct normal distributions. Custom Multivariate Gaussian PDF: Computes probability densities natively without external dependencies. Expectation-Maximization Loop: Manually implements both the E-step (responsibility calculation) and M-step (parameter updates). Convergence Tracking: Calculates and records log-likelihood across iterations to track EM behavior. Visualization: Automatically exports plots showing the final clustered data and log-likelihood convergence.

Getting Started
Prerequisites
To run the scripts in this repository, you only need a standard installation of R. No external CRAN packages (like mclust or tidyverse) are required.


<img width="672" height="669" alt="data 1" src="https://github.com/user-attachments/assets/852a4e64-ce31-47da-aa92-f677930a0bd0" />
<img width="671" height="667" alt="data 2" src="https://github.com/user-attachments/assets/9de71317-47bf-4810-8bc9-cd52b87e192a" />
<img width="673" height="667" alt="data 3" src="https://github.com/user-attachments/assets/fd4091f7-dd19-4534-a7bb-e94b367c5f1d" />


Execution
Run the main script in your R console or via your terminal:

source("gmm.R")





 Prerequisites
To run the scripts in this repository, you only need a standard installation of **R**. No external CRAN packages (like `mclust` or `tidyverse`) are required.




**Author**
Student Name:  Kirithik balan S

Course: BCA

Project: Week 1 – Gaussian Mixture Model using EM Algorithm

Language: R (Base R)
