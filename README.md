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

<h1><a id="user-content-mailhog" class="anchor" aria-hidden="true" href="#mailhog"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>mailhog</h1>
