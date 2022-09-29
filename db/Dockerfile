FROM mysql:5.7.25
LABEL "project"="Vprofile"
LABEL "Author"="Najmul Haq"

ENV MYSQL_ROOT_PASSWORD="vprodbass"
ENV MYSQL_DATABASE="acounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
