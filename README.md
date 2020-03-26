# MusicRoom-Api

kroom-graphql-api Developped by Cyrill Epalle https://github.com/cepalle/kroom-graphql-api

<a href="https://graphql.org" rel="nofollow">GraphQL</a> server written with <a href="https://github.com/akka/akka-http">akka-http</a>, <a href="https://github.com/akka/akka-http">akka-http</a> and <a href="https://github.com/sangria-graphql/sangria">sangria</a>.

After starting the server with

<pre>sbt run</pre>

<p>you can run queries interactively using <a href="https://github.com/prisma/graphql-playground">graphql-playground</a> by opening <a href="http://localhost:8080" rel="nofollow">http://localhost:8080</a> in a browser or query the <code>/graphql</code> endpoint directly. The HTTP endpoint follows <a href="http://graphql.org/learn/serving-over-http/#http-methods-headers-and-body" rel="nofollow">GraphQL best practices for handling the HTTP requests</a>.</p>


# Dependencies

<li>Java 8+</li>

<li>Sbt</li>

<pre>brew install sbt</pre>

# mailhog

<pre>Docker</pre>

docker run -p 8025:8025 -p 1025:1025 mailhog/mailhog

# test

<li>Vegeta</li>

<pre>brew update && brew install vegeta</pre>
