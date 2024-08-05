Explanation of the Code

Import Libraries: Import the pandas library for data manipulation.

Load Dataset: Load the train.csv file into a DataFrame.

Handle Missing Values:

Check for missing values.

Fill missing values in the Age column with the median.

Fill missing values in the Embarked column with the mode.

Drop the Cabin column due to a high number of missing values.

Handle Categorical Data:

Convert the Sex column to numerical values.

Convert the Embarked column to numerical values.

Drop Unnecessary Columns: Drop columns that are not useful for prediction (Name, Ticket, PassengerId).
