# Odoo Docker

![image](https://github.com/Antony-M1/docker-odoo/assets/96291963/4fa3ec3b-4e2b-446a-8034-f186b7a5752e)

Its a `odoo docker` setup to run the odoo in the docker container

For starting run this command
```
docker compose up -d
```

For Stop
```
docker compose down
```

### DB Connection
Default user: `odoo`, password: `odoo`

Run this commadn check the odoo DB
```
docker exec -it -u odoo <CONTAINER_NAME> psql
```
example
```
docker exec -it -u odoo db psql
```
