### MySql good Practices

docker run --name dataring-mysql -v dataring-mysql:/var/lib/mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=mysql789 -d mysql:5.7
netstat -aon|findstr "3306"

CREATE USER 'druser'@'localhost' IDENTIFIED BY 'mysql123';
