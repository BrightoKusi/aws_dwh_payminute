# aws_dwh_payminute
Building a cloud data warehouse with AWS for Payminute company

# Introduction
1. PayMinute is a Fintech Company with over 5000 active users located in Nigeria and Kenya. They currently have Data Analysts whose daily tasks is to deliver analysed data to the department heads and board members weekly.
The analysts have since began to experience delayed data retrieval and need for multiple-checks on data accuracy as their daily transactions grew. After much complain, the business has decided to adopt the services of a Big Data Engineer


#  Tools and dependancies
1. Python
2. Pandas
3. Psycopg2
4. Boto3
5. s3fs
6. configparser
7. redshift-connector
8. sqlalchemy

# Work Done
1. Dataset loaded in postgresql.
2. Data warehouse designed based on data analysts requirements using a star schema design.
3. Data lake(s3 bucket) created and data loaded.
4. Amazon redshift created and raw data loaded from data lake into DEV schema.
5. Staging schema created based on transformed tables.
6. Data finally loaded to staging schema for use.
