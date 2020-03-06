# Data Dumping
This is a list of few scripts of mine used in data dumping.

File / Repository Name and Description                                             | File Link   
--------------------------------------------------------------------- | ----------
<code>dump_SQL_table.sh</code> A template for dumping a table from one MySQL database to another MySQL database. The copy is done in chunks and therefore the script can be used also for huge tables. | <sub>https://github.com/BerniHacker/Linux/blob/master/dump_SQL_table.sh</sub>
<code>SQL_to_CSV.py</code> This script queries the full content of a defined table of a defined MySQL database (with defined credentials) and stores the result of the query temporarily into a pandas dataframe. The content of the dataframe is then dumped into a file with a defined name. The script allows handling "large data". Both the SQL query and the dump into the CSV file are performed in chunks according to pre-defined paramater values. | <sub>https://github.com/BerniHacker/Python/blob/master/SQL_to_CSV.py</sub>
<code>ETL_Pipeline</code> The scope of this project is to build an ETL pipeline to extract data from a disk where CSV files are loaded daily. The purpose of the pipeline is to store the content of those files into a repository for further processing, together with some aggregate data. Cloud Computing is used for the repository (AWS EC2 instances and RDS instances). | <sub>https://github.com/BerniHacker/ETL_Pipeline</sub>

Go back to the main CV page: https://github.com/BerniHacker/CV/blob/master/README.md
