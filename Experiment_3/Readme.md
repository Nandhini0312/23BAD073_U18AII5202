Multivariate Visualization of Healthcare Data
Objective

The objective of this experiment is to identify and analyze relationships among multiple health-related variables using multivariate visualization techniques.

Scenario

A hospital analytics team examines patient health records to understand the relationships between Age, Body Mass Index (BMI), Glucose Level, and Blood Pressure. These insights support early disease prediction and data-driven healthcare decision-making.

Dataset Description

The dataset consists of patient health records containing key attributes such as:

Age

BMI

Glucose_Level

Blood_Pressure

An additional categorical variable, Age_Group, is derived from the Age attribute to enable grouped visual analysis.

Tools and Libraries Used

R Programming Language

GGally Package – used for generating scatter plot matrices and multivariate visualizations

Methodology

A scatter plot matrix is generated to visualize pairwise relationships among Age, BMI, Glucose Level, and Blood Pressure.

Age-based grouping is applied, and color encoding is used to distinguish different age categories within the visualization.

A correlation matrix is computed to quantitatively assess the strength and direction of relationships among the selected health indicators.

Outputs

Scatter plot matrix illustrating multivariate relationships

Color-encoded scatter plot matrix based on age groups

Correlation matrix summarizing relationships among health variables

Observations

A strong positive correlation is observed between BMI and Glucose Level.

Age shows a moderate positive correlation with Blood Pressure.

Higher age groups tend to exhibit elevated health risk indicators.

Conclusion

Multivariate visualization techniques effectively reveal hidden relationships within healthcare data. The integration of scatter plot matrices, color encoding, and correlation analysis enhances interpretability and supports predictive healthcare analytics and early disease detection.
