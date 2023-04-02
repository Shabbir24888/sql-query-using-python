# sql-query-using-python
Operation performed on sql workbench and pycharm
The code reads data from the Excel file into a pandas DataFrame using pd.read_excel(). It then gets the list of column names using df.columns, and constructs the INSERT query by iterating over the columns and appending them to the INSERT statement. 
Loop statement for automatic generation of labels of columns and create a new table in MySQL Workbench and insert data from a pandas DataFrame. For simplicity, we assume that all columns in the DataFrame are of type VARCHAR(255). You may need to modify this depending on the actual data types of your columns.
Note that you will need to modify the yourhost, yourusername, yourpassword, yourdatabase, yourfile.xlsx, and the column names/types in the code to match your specific situation.
