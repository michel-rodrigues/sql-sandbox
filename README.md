# sql-sandbox

docker-compose up --build -d

docker-compose down

docker-compose exec postgresql /bin/bash

psql -U postgres

exibir bancos de dados
$ \l

conectar num banco
$ \c sql_sandbox

exibir tabelas
$ \d

acessar o shell dentro do psql
$ \!

executar um comando no shell dentro do psql
$ \! <command>


pg_restore -U postgres -d <database_name> <database_restore_path>.tar
