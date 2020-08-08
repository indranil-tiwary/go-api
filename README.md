# Golang API Practice

To run `go run main.go`

- Create DB `go_api_db` in postgres
- Example `.env` file:
```
# Postgres Live
API_SECRET=98hbun98h #Used when creating a JWT. It can be anything
DB_HOST=127.0.0.1
DB_DRIVER=postgres
DB_USER=postgres
DB_PASSWORD=password
DB_NAME=go_api_db
DB_PORT=5432 #Default postgres port

# Postgres Test
TestApiSecret=98hbun98h
TestDbHost=127.0.0.1
TestDbDriver=postgres
TestDbUser=postgres
TestDbPassword=password
TestDbName=go_api_test
TestDbPort=5432
```