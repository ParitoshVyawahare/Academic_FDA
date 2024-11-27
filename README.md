# Intoxication Detection using Accelerometer and TAC Data

This project focuses on detecting intoxication using accelerometer and TAC (Transdermal Alcohol Concentration) data collected from participants during bar crawls. The dataset was sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php), and the research paper [*Sobriety Tracker: Detecting Heavy Drinking Episodes during Complex, Naturalistic Drinking Events*](https://doi.org/10.xxxx/xxxx) served as a primary reference.

---

## Table of Contents
- [Overview](#overview)
- [Data Loading](#data-loading)
- [Data Preprocessing](#data-preprocessing)
- [Applied Permutation Entropy and Complexity](#applied-permutation-entropy-and-complexity)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Insights and Future Directions](#insights-and-future-directions)

---

## Overview

The goal of this project is to predict intoxication levels using time series data from accelerometers and TAC sensors. We explored machine learning methods to classify participants as sober or intoxicated and analyzed patterns in the data using entropy and complexity measures.

---

## Data Loading

- Utilized Python libraries to load and preprocess the dataset.
- Conducted exploratory data analysis (EDA) to understand the structure and characteristics of the data.
- Ensured data integrity and compatibility for further analysis.

---

## Data Preprocessing

- Converted accelerometer timestamps from milliseconds to seconds for consistency.
- Addressed discrepancies in sampling frequencies between accelerometer and TAC data.
- Segmented the dataset based on TAC values to facilitate detailed analysis.

---

## Applied Permutation Entropy and Complexity

- Applied **permutation entropy** and **complexity analysis** to the time series data.
- These methods revealed patterns and levels of randomness in the dynamics of intoxication-related signals.

---

## Pattern Analysis and Modeling

### Modeling
- Implemented a **Random Forest Classifier** to predict intoxication levels using accelerometer data.
- Combined accelerometer and TAC data for enhanced machine learning classification.

### Evaluation
- Assessed model performance using:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-score**
- Analyzed challenges in detecting intoxication based solely on accelerometer data.

---

## Insights and Future Directions

### Key Insights
- Challenges in accurately classifying intoxication based solely on accelerometer data were identified.
- Combined accelerometer and TAC data significantly improved classification performance.

### Future Directions
- Refine classification algorithms for better accuracy.
- Explore deep learning approaches for analyzing time series data.
- Collect additional data to improve model generalization across diverse participants and scenarios.

---

## References
1. [Sobriety Tracker: Detecting Heavy Drinking Episodes during Complex, Naturalistic Drinking Events](https://doi.org/10.xxxx/xxxx)
2. [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or contributions, please contact [Your Name](mailto:your.email@example.com).
