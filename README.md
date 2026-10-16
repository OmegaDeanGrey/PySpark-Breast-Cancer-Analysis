# Breast Cancer Analysis with PySpark and Python

This project uses PySpark and Pandas to explore the Breast Cancer Wisconsin Diagnostic dataset. The lab focuses on loading and preparing data, examining diagnosis categories, calculating summary statistics, and visualizing class distributions.

## Dataset

The dataset contains 569 records with diagnostic measurements and classifications of benign (B) or malignant (M).

An extra empty column was removed during preprocessing, leaving 32 columns for analysis.

## Tools

- Python
- PySpark
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Analysis

The notebook covers:

- Creating and verifying a Spark session
- Loading CSV data with PySpark
- Converting a Spark DataFrame to Pandas
- Inspecting the dataset structure and data types
- Counting benign and malignant diagnoses
- Visualizing diagnosis relative frequencies
- Calculating feature statistics and ratios
- Closing the Spark session after processing

## Key Results

- Total records: 569
- Benign diagnoses: 357
- Malignant diagnoses: 212
- Malignant relative frequency: 37.26%
- Radius mean of the 50th record: 13.49
- Absolute difference between selected feature extremes: 0.0086
- Product of rounded benign feature means: 16990.71552
- Average malignant radius-to-perimeter ratio: 0.15

## Running the Notebook

Install the required Python packages:

```bash
python3 -m pip install pyspark pandas numpy matplotlib pyarrow jupyter
```

Open `CGLabC4M3.ipynb` in Jupyter or VS Code and run the cells in order. A compatible Java installation is required for PySpark.

Keep `breast_cancer.csv` in the same directory as the notebook.

## Notes

The notebook follows the provided CodeGrade instructions where they differ from the Canvas rubric. The analysis is exploratory and does not train or evaluate a predictive diagnostic model.