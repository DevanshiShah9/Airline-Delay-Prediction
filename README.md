# Airline Delay Prediction

## Goal

Implemented to expand knowledge in parallelization for Big Data using PySpark, this project aimed to predict airline delays in California, Florida, Virginia, and New York. It involved employing Big Data Analytics and predictive modeling techniques for efficient delay assessment.

## Tech Stack

### Languages & Libraries
- Python, Numpy, Pandas, Scikit-Learn, Jupyter Notebook, PandasUDF, PySpark

### Models Used
- Logistic Regression, Random Forest, Support Vector Machines

## Dataset

Utilized data sourced from the Bureau of Transportation Statistics for California, New York, Florida, and Virginia airports. The dataset was processed and curated for meaningful analysis, comprising approximately one million rows with 20% marked as delayed based on time threshold.

## Project

- Utilized PySpark and Pandas UDF to process and prepare a large dataset for predictive modeling.
- The project involved feature selection, data cleaning, and handling categorical variables.
- Employed Random Forest, Logistic Regression, and Support Vector Machines for classification.
- Metric evaluation included precision, recall, and AUC-ROC scores.
- Parallelization reduced computation time by 50% for 1 million rows, achieving recall of 0.69 and precision of 0.98 with Random Forest.

### Learning and Improvements
- Navigating PandasUDF proved challenging but rewarding once implemented.
- Future steps involve deeper data analysis, feature correlations, and refining algorithmic solutions for improved predictions. 
