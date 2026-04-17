FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="Tina"

# set environment variables to initialize the database
ENV MYSQL_ROOT_PASSWORD="vprodbpass"
ENV MYSQL_DATABASE="accounts"

# copy db.sql file to  inside of the container. This dumpfile will be used to create our database
ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql