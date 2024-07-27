# Using an Extract, Transform, Load (ETL) process to clean up crowdfunding campaign data

This project require a fair amount of data cleaning and prep.  

First I worked on the crowdfunding spreadsheet  
-Imported as a pandas dataframe.  
-Split 'category & sub-category' column into two separate columns.  
-Created variables to store lists of the category and subcategory names.  
-Created category and subcategory ids and paired them with the variables in the last step.  
-Used those pairs to create category and subcategory csv files and exported.  

Campaign data  
-Made a new dataframe using the crowdfunding info.  
-Renamed columns, changed data types, formatted data as needed.  
-Merged with category and subcategory files.  
-Removed unwanted columns to simplify.  
-Created csv file and exported.  

Contacts list  
-Used pandas to import contact info.  
-Contact id, name, and email were all in a single cell so I split them into separate columns.  
-Split the name into two columns with first name and last name.  
-Reordered columns.  
-Created csv file and exported.  

