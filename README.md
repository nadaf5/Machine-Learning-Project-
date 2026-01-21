# Machine-Learning-Project
<div dir="ltr">

# Mental Health in Tech Survey – Machine Learning Analysis
Mental Health in Tech Survey – Machine Learning Analysis

# Project Overview
- Purpose:
  Analyze mental health trends among professionals in the technology sector
  and study the factors that influence seeking mental health treatment.
- Approach:
  Apply both supervised and unsupervised machine learning techniques to
  extract insights and build predictive models.
- Outcome:
  Compare different models to identify the most effective methods for this dataset.

Dataset
- Source:
  Kaggle – Mental Health in Tech Survey.
- Size:
  1,259 survey responses collected from tech professionals.
- Target Variable:
  treatment (Yes / No), indicating whether the respondent sought mental health treatment.
- Feature Types:
  Combination of demographic, workplace, and mental health-related attributes.

Data Preprocessing
- Data Cleaning:
  Removed duplicate records and handled missing values in key columns.
- Feature Encoding:
  Converted categorical variables into numerical form using One-Hot Encoding
  and Label Encoding.
- Feature Scaling:
  Standardized numerical features using StandardScaler to ensure fair model training.
- Feature Selection:
  Selected meaningful features to improve learning and reduce noise.

Supervised Learning Models
- Logistic Regression:
  A linear classification model used as a baseline for prediction.
- Random Forest Classifier:
  An ensemble tree-based model capable of capturing non-linear relationships.

Evaluation Metrics
- Accuracy:
  Measures overall correctness of predictions.
- Precision:
  Measures how many predicted positives were actually correct.
- Recall:
  Measures how many actual positives were correctly identified.
- F1-score:
  Harmonic mean of precision and recall.

Supervised Learning Results
- Logistic Regression:
  Achieved approximately 76% accuracy, performing well on linearly separable patterns.
- Random Forest:
  Achieved approximately 79% accuracy with a higher F1-score.
- Interpretation:
  Random Forest outperformed Logistic Regression, indicating non-linear feature interactions.

Unsupervised Learning Models
- K-Means Clustering:
  Groups participants based on similarity using distance-based clustering.
- Hierarchical Clustering:
  Builds a hierarchy of clusters and reveals deeper data structure.

Evaluation Metric
- Silhouette Score:
  Measures how well data points fit within their assigned clusters.

Unsupervised Learning Results
- K-Means:
  Silhouette score of approximately 0.32, indicating moderate cluster separation.
- Hierarchical Clustering:
  Silhouette score of approximately 0.35, showing better-defined clusters.
- Interpretation:
  Hierarchical clustering captured participant relationships more effectively.

Visualization
- Distribution Plots:
  Used to analyze feature distributions and detect outliers.
- Performance Comparison:
  Bar charts comparing supervised model metrics.
- Clustering Visuals:
  Elbow plots, dendrograms, and PCA-based cluster visualizations.

Key Insights
- Mental health treatment decisions are influenced by multiple interacting factors.
- Tree-based ensemble models handle complex survey data better than linear models.
- Hierarchical clustering provides more meaningful participant groupings.

Conclusion
- Random Forest is the most effective supervised learning model for this dataset.
- Hierarchical Clustering provides stronger unsupervised insights.
- Combining both approaches results in a deeper understanding of the data.

Future Work
- Model Optimization:
  Apply hyperparameter tuning to improve performance.
- Data Imbalance:
  Address class imbalance using resampling techniques.
- Advanced Models:
  Experiment with Gradient Boosting and XGBoost.
- Text Analysis:
  Perform NLP analysis on the survey comments section.

Files
- MLProject.ipynb:
  Complete notebook containing analysis, models, and visualizations.
- Images/:
  Stored figures and plots generated during the project.
- README.md:
  Project documentation.

