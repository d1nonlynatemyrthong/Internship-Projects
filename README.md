The raw customer dataset (customer.csv) was imported into Jupyter Notebook, and a new notebook titled new_task.ipynb was created for the task. Using the Pandas library (imported as pd), the dataset was loaded with the read_csv() function.

Key steps performed in the notebook include:

Initial data inspection using functions like .info() and .shape to understand the structure.

Column names were cleaned and renamed for consistency.

Missing and duplicate values were identified and removed.

Data types were corrected where necessary (e.g., converting Age to integer).

Standardized categorical fields such as Gender and Country.

Converted the Joindate column to a proper datetime format.

The cleaned dataset was saved as customer_cleaned.csv.
