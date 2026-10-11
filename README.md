# Radar Signal Classification & Pattern Recognition
An end-to-end workflow for analyzing radar signal returns from the ionosphere to determine whether targeted atmospheric structures are present. The project benchmarks multiple statistical classifiers, performs clustering analysis to discover natural groupings, and evaluates model sensitivity across multiple data splits. Both supervised and unsupervised techniques are implemented. 


### Key Components

* **Exploratory Data Analysis:** Distribution assessment, outlier visualization, and feature correlations.
* **Data Preprocessing:** Min-Max scaling into `[0, 1]` and handling multiclass/binary target labels.
* **Supervised Learning:** Classification using linear, quadratic, and probabilistic decision boundaries.
* **Unsupervised Learning:** Centroid-based clustering (with Elbow & Silhouette analysis) and hierarchical dendrograms.
* **Model Validation:** Benchmarking performance across 70/30, 80/20, and 90/10 train/test splits.


### Dataset

* **Source:** Johns Hopkins University Ionosphere Dataset
* **Instances:** 351 observations
* **Attributes:** 34 continuous pulse-pair radar features (`A01` to `A34`)
* **Target:** Binary class (`g` for "good" returns, `b` for "bad" returns)
* **Missing Values:** None
