# PTB-XL Dataset Analysis Using Unsupervised Learning Algorithms

Project Overview

This project involves the analysis of the PTB-XL dataset, a large-scale ECG dataset, using unsupervised learning techniques. The primary goal was to identify patterns and clusters in ECG data without the use of labeled data (i.e., no supervised learning methods were applied).

Dataset Description

The PTB-XL dataset is a well-known electrocardiography (ECG) dataset that contains clinical ECG recordings along with metadata and diagnostic labels. For this project, the focus was on the raw ECG signals without leveraging the diagnostic labels for training.

Dataset source: https://physionet.org/content/ptb-xl/1.0.3/

Size: Over 21,000 clinical 12-lead ECG recordings

Sampling Frequency: 500Hz

Metadata includes age, gender, and diagnostic information (not used for supervised learning here)

Objective

Identify patterns and clusters in ECG data.

Detect potential abnormalities or similarities between ECG samples.

Explore the underlying structure of the data using clustering algorithms.

Techniques and Algorithms Used

This project solely utilized unsupervised learning algorithms for data exploration and pattern recognition, including:

K-Means Clustering

DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

Hierarchical Clustering

Key Steps Involved

Data Preprocessing:

Extraction and cleaning of ECG signal data from the PTB-XL dataset.

Normalization and standardization of ECG features.

Handling missing values and data inconsistencies.

Feature Engineering:

Time-domain and frequency-domain feature extraction.

Dimensionality reduction (e.g., PCA) to visualize and simplify data.

Clustering:

Application of K-Means, DBSCAN, and Hierarchical Clustering.

Evaluation and visualization of clusters.

Analysis:

Interpretation of clusters based on ECG waveforms.

Insights into potential subgroups in the dataset.

Tools and Technologies

Python

NumPy, Pandas

Matplotlib, Seaborn

SciPy, Scikit-learn

Jupyter Notebook

Results & Insights

Clustered ECG signals into distinct groups based on waveform characteristics.

Observed potential patterns suggesting the presence of abnormal heart rhythms in certain clusters.

Demonstrated the applicability of unsupervised learning in the medical signal processing domain.

Challenges Faced

Handling high-dimensional ECG signal data.

Noise and variability in ECG waveforms.

Selecting appropriate features for clustering.

Future Scope

Exploration of advanced clustering techniques.

Incorporating time-series analysis methods.

Combining unsupervised and semi-supervised learning for better diagnostic insights.


How to Run the Project

Clone the repository:

git clone https://github.com/your-username/ptb-xl-unsupervised-learning.git

Navigate to the project directory:

cd ptb-xl-unsupervised-learning

Install dependencies:

pip install -r requirements.txt

Open Jupyter Notebook:

jupyter notebook

Run the notebooks in the notebooks/ directory.

References

PTB-XL Dataset: https://physionet.org/content/ptb-xl/1.0.3/

Unsupervised Learning Algorithms: https://scikit-learn.org/stable/unsupervised_learning.html

License

This project is licensed under the MIT License.

