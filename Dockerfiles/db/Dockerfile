FROM mysql:5.7.25
LABEL "Project"="Aurora"
LABEL "Author"="Anil"
ENV MYSQL_ROOT_PASSWORD='vprodbpass'
ENV MYSQL_DATABASE='accounts'
COPY db_backup.sql /docker-entrypoint-initdb.d/db_backup.sql
