

# Heart Disease Classification

This repository contains code for analyzing and modeling a heart disease dataset. The code is written in Python and utilizes PySpark for distributed computing.

## Getting Started

To get started with the code, follow the instructions below:

### Prerequisites

- Python 3.x
- `pip` package manager

### Installation

1. Clone this repository to your local machine or download the code files as a ZIP archive.

2. Open a terminal or command prompt and navigate to the project directory.

3. Install the required dependencies by running the following command:

   ```
   !pip3 install pyspark==3.1.2
   !pip install findspark
   ```

### Dataset

1. Download the heart disease dataset (CSV format) from [here](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset/download?datasetVersionNumber=2) and save it in the project directory.

2. Rename the dataset file to `heart.csv`.

### Running the Code

1. Open the code file, such as `heart_disease_analysis.py`, in a Python editor or Jupyter Notebook.

2. In the code file, locate the section where the dataset is loaded:

   ```python
   # Load the dataset using pd.read_csv
   df = pd.read_csv('heart.csv')
   ```

   If you saved the dataset file with a different name or in a different location, modify the file path accordingly.

3. Run the code file and observe the output in the editor or notebook interface.

   Note: Depending on the size of the dataset and your machine's resources, running the code may take some time.

4. The code includes various data analysis and visualization steps. You can modify or comment out specific sections of the code to focus on the analysis aspects that interest you.

### Output

- The code generates various plots and outputs, such as histograms, countplots, box plots, correlation heatmaps, and scatter plots, to help visualize and understand the heart disease dataset.

- Additionally, the code performs data preprocessing, such as handling missing values, detecting outliers, scaling features, and training a logistic regression model for classification.

- The code also calculates evaluation metrics, such as accuracy, for the trained model on a test dataset.

## Conclusion

By running the provided code, you can explore and analyze the heart disease dataset using PySpark. Feel free to modify the code and experiment with different analysis techniques to gain insights from the data.
