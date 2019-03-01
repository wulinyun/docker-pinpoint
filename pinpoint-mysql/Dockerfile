FROM mysql:5.7

ADD CreateTableStatement-mysql.sql /docker-entrypoint-initdb.d
ADD SpringBatchJobRepositorySchema-mysql.sql /docker-entrypoint-initdb.d

RUN chmod -R 775 /docker-entrypoint-initdb.d