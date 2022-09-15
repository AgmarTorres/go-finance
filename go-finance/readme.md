Golang Migrate: https://github.com/golang-migrate/migrate
Golang Migrate CMD para instalação: https://github.com/golang-migrate/migrate/tree/master/cmd/migrate
Código fonte do projeto no Github: https://github.com/GustavoNoronha0/gofinance-backend


----------------

docker run --name postgres -e POSTGRES_PASSWORD=postgres -d postgres:14-alpine

docker exec -it postgres psql -U postgres

\q

pgadmin

name= postgres14

connection

  host name = localhost

  ssl disabled

  username

    postgres

    password 

Migration

[https://www.geeksforgeeks.org/how-to-install-golang-migrate-on-ubuntu/](https://www.geeksforgeeks.org/how-to-install-golang-migrate-on-ubuntu/)

sudo apt-get install migrate

migrate create -ext sql -dir db/migration -seq initial_tables
