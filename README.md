# Set-up-Wordpress
Set up Wordpress with Docker-Compose

### Environment
- ubuntu 20.04
- mysql:8.0
- wordpress:6.1.0-php7.4-fpm
- nginx:1.15.12-alpine

### Create .env file
```
MYSQL_ROOT_PASSWORD=your_root_password
MYSQL_USER=your_wordpress_database_user
MYSQL_PASSWORD=your_wordpress_database_password
```

### Execute docker-compose.yml
```
docker-compose up -d
```

### shutdown
```
docker-compose down
```
