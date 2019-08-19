# Installs mysql server
# Creates a volume
# Expose mysql port 3306

FROM ubuntu

MAINTAINER Kevin

RUN apt-get update
RUN apt-get -y install mysql-server-5.7

VOLUME ["/var/lib/mysql"]

EXPOSE 3306
