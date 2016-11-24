FROM mysql:5.6

# Contents of /docker-entrypoint-initdb.d are run on mysqld startup
ADD  docker-entrypoint-initdb.d/ /docker-entrypoint-initdb.d/

# Database Environment Variables
ENV MYSQL_DATABASE=docker
ENV MYSQL_USER=sarp
ENV MYSQL_PASSWORD=password
