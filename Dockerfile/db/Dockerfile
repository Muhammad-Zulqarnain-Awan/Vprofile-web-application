FROM mysql:5.7.25
LABEL maintainer='Zulqarnain <muhammad.zulqarnain1001@gmail.com>'
LABEL project='VProfileProject'

ENV MYSQL_ROOT_PASSWORD=1234
ENV MYSQL_DATABASE = 'accounts'

ADD ./db_backup.sql docker-entrypoint-initdb/db_backup.sql