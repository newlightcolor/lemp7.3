FROM mysql/mysql-server:8.0

ENV MYSQL_DATABASE=lemp \
  MYSQL_USER=hoge \
  MYSQL_PASSWORD=hoge \
  MYSQL_ROOT_PASSWORD=root \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chmod 644 /etc/my.cnf