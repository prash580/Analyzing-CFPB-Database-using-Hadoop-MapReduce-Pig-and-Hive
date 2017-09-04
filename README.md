# Analyzing-CFPB-Database-using-Hadoop-MapReduce-Pig-and-Hive
The Project utilizes Hadoop to store the Consumer Financial Protection Bureau's Consumer complaint database. The link to the database is: https://www.consumerfinance.gov/data-research/consumer-complaints/

- The data was initially cleaned to remove the unwanted punctuations and missing values using R.
- Cleaned data was then loaded into MySQL Database.
- Using sqoop the data from MySQL database was copied into Hadoop Distributed File System which was set up as single node cluster.
- First part of analysis was done using Java MapReduce run on Eclipse IDE. 
- Next, the data was imported into Derby Database and HiveQL,PigLatin languages were used to query the data.
- The Outputs were visualized using Tableau and Microsoft Excel.
