# Menjalankan program
go run main.go

## Postgres
https://github.com/golang-migrate/migrate/blob/master/database/postgres/TUTORIAL.md

migrate -database "{urldatabase}" -path db/migrations up
migrate -database "{urldatabase}" -path db/migrations down

