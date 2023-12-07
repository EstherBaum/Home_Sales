# Home_Sales
## Overview

1. This program imports the needed package, Installs Spark and Java, and set the Environment Variables. 

2. A spark session is created and a csv is read in from the AWS S3 bucket. 

3. A temporary veiw is created and several SQL queries are performed on teh dataframe. 

4. The temporary table home_sales is cached and a query is performed. 

5. the data is formatted into parquet and partitioned. 

6. The parquet formatted data is read and a temporary table is created. 

7. A query is performed on the table. 

8. The temporary table is uncached. 
