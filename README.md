# PTB-XL Dataset Analysis Using Unsupervised Learning Algorithms

## Project Overview

This project involves the analysis of the PTB-XL dataset, a large-scale ECG dataset, using unsupervised learning techniques. The primary goal was to identify patterns and clusters in ECG data without the use of labeled data (i.e., no supervised learning methods were applied).

## Dataset Description

The PTB-XL dataset is a well-known electrocardiography (ECG) dataset that contains clinical ECG recordings along with metadata and diagnostic labels. For this project, the focus was on the raw ECG signals without leveraging the diagnostic labels for training.

1. Dataset source: https://physionet.org/content/ptb-xl/1.0.3/

2. Size: Over 21,000 clinical 12-lead ECG recordings

3. Sampling Frequency: 500Hz

Metadata includes age, gender, and diagnostic information (not used for supervised learning here)

# Objective

1. dentify patterns and clusters in ECG data.

2. Detect potential abnormalities or similarities between ECG samples.

3. Explore the underlying structure of the data using clustering algorithms.

# Techniques and Algorithms Used

1. This project solely utilized unsupervised learning algorithms for data exploration and pattern recognition, including:

2. K-Means Clustering

3. DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

4. Hierarchical Clustering

# Key Steps Involved

## Data Preprocessing:

1. Extraction and cleaning of ECG signal data from the PTB-XL dataset.

2. Normalization and standardization of ECG features.

3. Handling missing values and data inconsistencies.

## Feature Engineering:

1. Time-domain and frequency-domain feature extraction.

2. Dimensionality reduction (e.g., PCA) to visualize and simplify data.

## Clustering:

1. Application of K-Means, DBSCAN, and Hierarchical Clustering.

2. Evaluation and visualization of clusters.

## Analysis:

1. Interpretation of clusters based on ECG waveforms.

2. Insights into potential subgroups in the dataset.

# Tools and Technologies

1. Python

2. NumPy, Pandas

3. Matplotlib, Seaborn

4. SciPy, Scikit-learn

5. Jupyter Notebook

# Results & Insights

1. Clustered ECG signals into distinct groups based on waveform characteristics.

2. Observed potential patterns suggesting the presence of abnormal heart rhythms in certain clusters.

3. Demonstrated the applicability of unsupervised learning in the medical signal processing domain.

# Challenges Faced

1. Handling high-dimensional ECG signal data.

2. Noise and variability in ECG waveforms.

3. Selecting appropriate features for clustering.

# Future Scope

1. Exploration of advanced clustering techniques.

2. Incorporating time-series analysis methods.

3. Combining unsupervised and semi-supervised learning for better diagnostic insights.


# How to Run the Project

1. Clone the repository:

   git clone https://github.com/Muskanyada/PTB_XL_Internship_projec.git

2. Navigate to the project directory:

   cd ptb-xl-unsupervised-learning

3. Install dependencies:

   pip install -r requirements.txt

4. Open Jupyter Notebook:

  jupyter notebook

Run the notebooks in the notebooks/ directory.

# References

1. PTB-XL Dataset: https://physionet.org/content/ptb-xl/1.0.3/

2. Unsupervised Learning Algorithms: https://scikit-learn.org/stable/unsupervised_learning.html

# License

This project is licensed under the MIT License.

