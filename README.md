# LiQi-Task
This Project takes data from 2 files - 
1) Google Sheets - It depicts current financial transactions for a company in a tabular format.
2) An XML file - It depicts previous financial transactions by the company.

The code first analyses the Google Sheets' data by converting it into Pandas dataframe. Cleaning of the data is done accordingly. 
Later, data from the XML file is extracted and converted into a Pandas dataframe. This dataframe is flattened to an extent where
all the relevant columns depict the financial transactions. Finally, this data is analysed to create a Balance Sheet and Income Statement.
