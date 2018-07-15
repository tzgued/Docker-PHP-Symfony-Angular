FROM mysql:5.7


RUN ["apt-get", "update"]
RUN ["apt-get", "install", "-y", "vim"]

RUN   echo "default_authentication_plugin= mysql_native_password" >> /etc/mysql/my.cnf

RUN start mysql

EXPOSE 3306


