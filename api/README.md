## Kroom Api

[GraphQL](https://graphql.org) server written with [akka-http](https://github.com/akka/akka-http), [circe](https://github.com/circe/circe) and [sangria](https://github.com/sangria-graphql/sangria).

After starting the server with

```bash
sbt run
``` 

you can run queries interactively using [graphql-playground](https://github.com/prisma/graphql-playground) by opening [http://localhost:8080](http://localhost:8080) in a browser or query the `/graphql` endpoint directly. The HTTP endpoint follows [GraphQL best practices for handling the HTTP requests](http://graphql.org/learn/serving-over-http/#http-methods-headers-and-body).

# Dependencies

- Java 8+
- Sbt

```cmd
brew install sbt
```

# mailhog

- Docker

````cmd
docker run -p 8025:8025 -p 1025:1025 mailhog/mailhog
````

# test

- Vegeta

```cmd
brew update && brew install vegeta
```

# Note

Subscription: Need parameter Query
