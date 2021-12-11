---
author: Claudio Belo Rodrigues Junior
email: claudiobelorjr@gmail.com
---
# metabase-mysql

[README (Portuguese Brazilian)](./docs/readme-pt-br.md)

---

Este repositório tem como objetivo ser um passo inicial para a estruturação de um ambiente do [Metabase](https://www.metabase.com/) com um banco de dados [MySQL](https://www.mysql.com/).

## Serviços

Para a estruturação do ambiente serão utilizados o docker do [metabase](https://hub.docker.com/r/metabase/metabase) e o [mysql](https://hub.docker.com/_/mysql) com o auxilio da ferramenta [docker compose](https://docs.docker.com/compose/).

Esses serviços serão estão organizados no arquivo [docker-compose.yml](docker-compose.yml).

## Variáveis de Ambiente

As variavéis de ambiente podem ser encontradas na pasta [config](./config) e estão.

Metabase:

- MB_DB_TYPE: Tipo de banco de dados.
- MB_DB_HOST: Nome do host do banco de dados.
- MB_DB_PORT: Porta para conexão com o banco de dados.
- MB_DB_USER: Usuário do banco de dados.
- MB_DB_PASS: Senha do banco de dados.
- MB_DB_DBNAME: Nome do banco de dados para conexão.
- MB_ENCRYPTION_SECRET_KEY: Chave para armazenamento de dados sensíveis.

MySQL:

- MYSQL_ROOT_PASSWORD: Senha do usuário root.
- MYSQL_DATABASE: Banco de dados padrão.
- MYSQL_USER: Usuário do banco de dados.
- MYSQL_PASSWORD: Senha do banco de dados.
