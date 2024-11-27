# Academic_FDA

ntoxication Detection using Accelerometer and TAC (Transdermal Alcohol Concentration) Data
Table of Contents
Overview
Data Loading
Data Preprocessing
Applied permutation entropy and complexity
Pattern Analysis
Modeling
Evaluation
Insights and Future Directions
Overview
This project focuses on the detection of intoxication using accelerometer and TAC data collected from participants during bar crawls. The dataset was sourced from the UCI Machine Learning Repository. To understand the data and techniques, the research paper "Sobriety Tracker: Detecting Heavy Drinking Episodes during Complex, Naturalistic Drinking Events" served as a primary reference.

Data Loading
Utilized Python libraries to load and preprocess the dataset.
Conducted initial exploratory data analysis to understand the structure and characteristics of the data.
Ensured data integrity and compatibility for further analysis.
Data Preprocessing
Converted accelerometer data from milliseconds to seconds for consistency.
Addressed discrepancies in sampling frequency between accelerometer and TAC data.
Segmented data based on TAC values for further analysis.
Applied permutation entropy and complexity
Applied permutation entropy and complexity analysis to detect patterns or randomness in the time series data.
These methods were employed to extract valuable insights into the dynamics of intoxication-related signals captured by the accelerometer and TAC data.
Modeling
Employed Random Forest classification to predict intoxication status based on accelerometer data.
Utilized machine learning algorithms to classify participants as drunk or sober, leveraging both accelerometer and TAC data.
Evaluation
Assessed model performance metrics such as accuracy, precision, recall, and F1-score to evaluate the effectiveness of the classification approach.
Identified limitations and challenges in accurately detecting intoxication solely based on accelerometer data.
Insights and Future Directions
Extracted insights from the analysis, including the challenges of classifying intoxication based solely on accelerometer data.
Proposed future research directions, such as refining classification algorithms for improved accuracy.
