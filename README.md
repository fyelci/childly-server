# Childly Server

[//]: # (head-end)

* [NodeJS](https://github.com/nodejs/node)
* [Express](https://github.com/expressjs/express)
* [PostgreSQL](https://github.com/postgres/postgres)
* [GraphQL](https://github.com/graphql/graphql-js)
* [Typescript](https://github.com/microsoft/TypeScript)
* [Apollo-Server](https://github.com/apollographql/apollo-server)
* [GraphQL Code Generator](https://github.com/dotansimha/graphql-code-generator)
* [GraphQL Modules](https://github.com/urigo/graphql-modules)
* [Jest](https://github.com/facebook/jest)

## Running locally

Clone the project.


> if you want to use together with the [React Client](https://github.com/fyelci/childly-web), 

Install dependencies:
```
$ yarn
```

Run the the codegen to generate Typescript types from GraphQL:
```
$ yarn codegen
```

Install PostgreSQL and initialize a database by following the instructions 

* With docker - PosgreSQL
```
docker run -d --name childly-postgres -e POSTGRES_DB=childly -e POSTGRES_USER=testuser -e POSTGRES_PASSWORD=testpassword --rm -p5432:5432 postgres
```

Run tests to make sure everything is ok:
```
$ yarn test
```

Start the server:
```
$ yarn start
```
