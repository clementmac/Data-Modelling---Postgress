Introduction:
Sparkify is a music streaming app. The analytics team is particularly interested in understanding what songs users are listening to. Currently, their data resides in a directory of JSON logs on user activity on the app, as well as a directory with JSON metadata on the songs in their app. However, this cannot provid an easy way to query the data.

The goal:
The purpose of this project is to create a Postgres database and ETL pipeline to optimize queries to help Sparkify's analytics team.

So, we have created a database in a simple star schema format and loaded the data into the tables 
using an ETL pipeline.

Steps to be followed :

1. Open the create_and_ETL.ipynb.

2. Restart the kernel just in case.

3. Run the create_tables script first. [Output = 'Success']

4. Run the etl.py command in the same notebook file.

5. Finally, open test.ipynb and run each cell to see if the data has been loaded properly.

6. DO NOT FORGET TO restart kernel if scripts have to be run again.

(the star schema can be viewed in the Star_Schema.JPG file)