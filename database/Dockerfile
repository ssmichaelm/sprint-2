FROM mysql

# The "docker-entrypoint.sh" file will run any files *.sql in this directory when built
# alinedb.sql is the SQL schema for the database
ADD alinedb.sql /docker-entrypoint-initdb.d

# Environment variables will be set in the YAML file
# ENV ...

# Default MySQL port
EXPOSE 3306