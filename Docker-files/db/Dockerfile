FROM mysql:8.0.33
LABEL "Project"="Vprofile"
LABEL "Author"="naveen"

ENV MYSQL_ROOT_PASSWORD="vprodpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backupfile docker-entrypoint-initdb.d/db_backupfile.sql