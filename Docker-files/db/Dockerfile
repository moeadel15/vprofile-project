FROM mysql:8.0.33
LABEL "project"="First one"
LABEL "Author"="Mohamed"

ENV MYSQL_ROOT_PASSWORD="PASSWORD1"
ENV MYSQL_DATABASE="accounts"

COPY db_backup.sql docker-entrypoint-initdb.d/db_backup.sql