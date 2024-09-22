# Clustering Learners' Job Profiles - Scaler Case Study
![image](https://github.com/user-attachments/assets/ce188046-6b10-453d-b93e-8b38a8134b95)

## Project Overview
    This project is aimed at profiling learners from Scaler's database to identify patterns and similarities based on their job profiles, companies, and other features. The project involves applying unsupervised learning techniques like K-Means and Hierarchical clustering after dimensionality reduction using PCA. The main objective is to cluster learners with similar characteristics, which can provide insights into top-performing employees and help Scaler in guiding their learners toward the best companies and positions.

## Dataset Description
    The dataset contains information about learners' job profiles, current companies, and salary data, among other features.

## Key Features:
    Company: Current employer of the learner
    Orgyear: Year when the learner joined the organization
    CTC: Current CTC (Cost to Company)
    Job Position: Learner's role within the company
    CTC Updated Year: The year when the CTC was last updated
    File: scaler_kmeans.csv
## Objectives

### Exploratory Data Analysis (EDA):

    Examine the dataset structure and characteristics.
    Analyze the unique emails, missing values, and duplicates.
    Feature engineering by adding new features like 'Years of Experience' and preparing data for clustering.
### Manual Clustering:

    Group learners based on their company, job position, and years of experience.
    Create summary statistics for CTC based on company and job position.
    Generate flags for learners earning more/less than average based on their experience and position.
### Unsupervised Clustering:

    Use frequency encoding for categorical features (company, job_position).
    Apply Principal Component Analysis (PCA) for dimensionality reduction.
    Perform clustering using K-Means and Hierarchical clustering methods.
### Tools and Libraries
    Pandas: Data manipulation and preprocessing
    Scikit-Learn: Machine learning algorithms (K-Means, PCA, Hierarchical Clustering)
    Matplotlib & Seaborn: Data visualization
    Numpy: Numerical computations
    Regex: For cleaning special characters in data
