# docker_environement
Provide an environment with PHP7,  MariaDB and Apache

## Code Example

To use this project, it's simple just hit this command

```
docker-compose up -d
```

This commande run 3 containers :

- 1 container for Apache and your file on port 80, 443 with ip 127.0.0.1
- 1 container for mariaDB on port 3306 with ip 127.0.0.1
- 1 container for phpmyadmin on port 8080 with ip 127.0.0.1