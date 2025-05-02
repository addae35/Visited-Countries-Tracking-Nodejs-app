FROM postgres:17.4

LABEL "Project"="Travel-Tracker"
LABEL "Author"="Emmanuel Owusu-Addai"

ENV POSTGRES_USER="postgres"
ENV POSTGRES_DB="world"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql
