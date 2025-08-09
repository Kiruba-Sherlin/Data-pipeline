# Data-pipeline

COMPANY: CODTECH IT SOLUTIONS

NAME: KIRUBA SHERLIN. A

INTERN ID: CT04DH2074

DOMAIN: DATA SCIENCE

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION:

Program Description:

This Python script implements a basic ETL (Extract, Transform, Load) workflow for the Iris dataset, a classic dataset in machine learning.
It performs the following steps:

1) Extract:

     i) Loads the Iris dataset using scikit-learn’s load_iris() function.

     ii) Converts the data into a pandas DataFrame for easier manipulation.

     iii) Adds a readable target column (species) by mapping numeric labels to class names.

2) Transform:

     i) Scales the numerical features using StandardScaler to ensure all features have a mean of 0 and standard deviation of 1                  (important for many ML algorithms).

     ii)Encodes categorical target labels into numeric values using LabelEncoder.

3) Load:

     i) Saves the processed data as a CSV file (iris_cleaned.csv) into a data/processed directory.

     ii) Creates the directory if it does not exist using os.makedirs().

Tools & Technologies Used:

i) Python -	Core programming language for the script.

ii) pandas	- Data manipulation and analysis — used to create DataFrames, combine features, and save CSV files.

iii) scikit-learn (sklearn)	- Machine learning toolkit — used to load the Iris dataset, scale features, and encode categorical labels.

iv) StandardScaler	- From sklearn.preprocessing, used to standardize features for better ML performance.

v) LabelEncoder	- From sklearn.preprocessing, used to convert categorical class labels into integers.

vi) os (Python standard library) -	Used to handle file system operations like creating directories.

Workflow Summary:

Extract: Read the Iris dataset → Convert into DataFrame.

Transform: Standardize numeric features → Encode categorical labels.

Load: Save the cleaned dataset into a structured directory for further use.

Output:

<img width="782" height="258" alt="Image" src="https://github.com/user-attachments/assets/761d54ff-392f-4ecb-9510-029e01436780" />
<img width="794" height="249" alt="Image" src="https://github.com/user-attachments/assets/7aff3b1a-931d-4b82-bf62-2f6816a7e498" />
