# mysql 설치
## docker run --name mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=1234 -d mysql --character-set-server=utf8mb4 --collation-server=utf8mb4_unicode_ci

# mysql 브릿지 연결 및 설치
## docker run --network docker-elk_elk --name mysql -p 3306:3306 -e MYSQL_ROOT_PASSWORD=1234 -d mysql --character-set-server=utf8mb4 --collation-server=utf8mb4_unicode_ci
