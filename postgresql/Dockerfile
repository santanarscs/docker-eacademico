FROM postgres:9.6

ADD scripts/activiti.postgres.create.engine.sql /docker-entrypoint-initdb.d/
ADD scripts/activiti.postgres.create.history.sql /docker-entrypoint-initdb.d/
ADD scripts/activiti.postgres.create.identity.sql /docker-entrypoint-initdb.d/

MAINTAINER raphaelstn@gmail.com
