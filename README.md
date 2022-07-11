# users_data_pipeline
A data pipeline using shell script, for extracting the data from users data file and transform it and store in the postgres sql table

# Note - Please follow this order
Please go throught the "prerequisites_exercises" notebook to get familiar with the commands used in the "pipe_users_data"

# Start the PostgreSQL database.
--> start_postgres
# Create database
--> CREATE DATABASE test
# Connect to database
--> \c test
# Create table
--> create table users(username varchar(50),userid int,homedirectory varchar(100));

# The data extracted and transformed will be stored in "users" table



