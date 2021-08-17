# Unit and integration testing

Step by step from this post:
<https://medium.com/@victorsteven/understanding-unit-and-integrationtesting-in-golang-ba60becb778d>

A really good idea for start with unit and integration testing

Please change your database connection in `.env` file

That file is used for integration tests and running the app

Run all tests with coverage

```bash
go test ./... --cover
```

Run application in localhost

```bash
go run main.go
```

Build your application and run it

```bash
go build main.go
./main
```
