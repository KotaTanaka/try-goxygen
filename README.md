# try-goxygen

Generate by **[Goxygen](https://github.com/Shpota/goxygen)**
- *Frontend: React*
- *Backend: Go*
- *DB: MongoDB*

## Environment

* [Go](https://golang.org/)
* [Node.js](https://nodejs.org/)
* [Docker](https://www.docker.com/), [Docker Compose](https://docs.docker.com/compose/)

## Getting Started

Install

```
$ git clone git@github.com:KotaTanaka/try-goxygen.git
$ cd try-goxygen
```

Start Mongo DB - http://localhost:27017

```
$ docker-compose -f docker-compose-dev.yml up
```

Start Server - http://localhost:8080

```
$ cd server
$ go run server.go
```

Start Client - http://localhost:3000

```
$ cd webapp
$ yarn
$ yarn start
```

**Start in production mode** - http://localhost:8080


```
$ docker-compose up
```
