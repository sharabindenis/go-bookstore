docker run --detach --name=test --env="MYSQL_ROOT_PASSWORD=password" --publish 6603:3306 mysql

mysql -u root -p
//enter your localhost password