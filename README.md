# Assignment5
Explanation of the contents of the python code:-
•	Imports the necessary libraries: numpy, pandas, sqlalchemy, and pymysql.
•	Reads in a CSV file "youtube_dataset.csv" using pandas and creates a dataframe called "df_youtube".
•	Displays the first 5 rows of the dataframe using the "head()" method.
•	Displays the row and column size of the dataframe using the "shape" attribute.
•	Displays detailed information about the dataframe using the "info()" method.
•	Creates a new dataframe called "df_first_1000_rows" containing the first 1000 rows of "df_youtube".
•	Defines a function called "distribution()" that takes in a dataframe and a column name as input and returns a new dataframe containing the distribution of values in the specified column.
•	Calls the "distribution()" function on the "df_first_1000_rows" dataframe and the column "channeltype" to create a new dataframe called "df_dist" containing the distribution of values in the "channeltype" column.
•	Writes the first 1000 rows of the "df_youtube" dataframe to a CSV file called "youtube_top_1000.csv".
•	Creates a connection to a MySQL database using the "create_engine()" method from the SQLAlchemy library.
•	Writes the first 1000 rows of the "df_youtube" dataframe to a MySQL table called "top_1000_channels" using the "to_sql()" method.
•	Writes the first 10 rows of the "df_youtube" dataframe to a MySQL table called "df_10" using the "to_sql()" method with specified column datatypes.
Overall, this Python code reads in a dataset from a CSV file, creates a dataframe, performs some data exploration and analysis, and writes the data to both a CSV file and a MySQL database.
