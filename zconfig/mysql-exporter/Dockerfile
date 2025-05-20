FROM prom/mysqld-exporter:latest
ADD .my.cnf /home/

ENTRYPOINT  [ "/bin/mysqld_exporter", "--config.my-cnf=/home/.my.cnf" ]