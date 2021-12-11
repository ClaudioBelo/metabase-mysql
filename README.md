---
author: Claudio Belo Rodrigues Junior
email: claudiobelorjr@gmail.com
---
# metabase-mysql

[README (pt-br)](./docs/readme-pt-br.md)

---

Repository to start an environment with [Metabase](https://www.metabase.com/) and [MySQL](https://www.mysql.com/).

## Serviços

for the environment it will be necessary to use the [Metabase](https://hub.docker.com/r/metabase/metabase) and [MySql](https://hub.docker.com/_/mysql) docker with the help of [docker compose](https://docs.docker.com/compose/).


These services are organized in the [docker-compose.yml](docker-compose.yml).

## Environment Variables

Environment variables can be found in the folder [config](./config).

[Metabase Environment](https://www.metabase.com/docs/latest/operations-guide/environment-variables.html):

- MB_DB_TYPE: Database type
- MB_DB_HOST: Database host name.
- MB_DB_PORT: Database port.
- MB_DB_USER: Database user.
- MB_DB_PASS: Database password.
- MB_DB_DBNAME: Database name.
- MB_ENCRYPTION_SECRET_KEY: Key for storing sensitive data.

[MySql](https://hub.docker.com/_/mysql):

- MYSQL_ROOT_PASSWORD: Password for root user.
- MYSQL_DATABASE: Database name.
- MYSQL_USER: Database user.
- MYSQL_PASSWORD: Database password.
