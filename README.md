# ETL-pipeline
Implementing an ETL pipeline using psycopg2 and postgres. 
Data from an online music streaming application was residing in json files in local directories an there was no way to analyze it in its current form. 
Using ETL techniques, data was migrated into tables in Postgres using the Python's psycopg2 package. There was one fact table created and 4 dimension tables for the analytics team to analyze data conveniently.
