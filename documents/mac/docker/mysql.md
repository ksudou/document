# mysqlイメージを使ってみる
```
$ docker pull mysql
$ docker run --name mysql -e MYSQL_ROOT_PASSWORD=mysql -d -p 3306:3306 mysql
$ docker ps
$ docker stop <CONTAINER ID>
$ docker rm <CONTAINER ID>
```
