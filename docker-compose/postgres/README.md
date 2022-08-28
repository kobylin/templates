# Postgres Container


## How to run

1. `docker-compose up`
2. `sudo chown -R 5050:5050 admin-data`


```
Warning: pgAdmin runs as the pgadmin user (UID: 5050) in the pgadmin group (GID: 5050) in the container. You must ensure that all files are readable, and where necessary (e.g. the working/session directory) writeable for this user on the host machine. For example:

sudo chown -R 5050:5050 admin-data
```