MySql 5.6 Docker Image
=========================

Building the Container
---------------------
    $ git clone https://github.com/buraksarp/docker.git
    $ cd docker/mysql-5.6
    $ docker build -t sarp/mysql .

Running the Container
---------------------
To run this container:

    $ docker run --name mysql-5.6 -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -d sarp/mysql


