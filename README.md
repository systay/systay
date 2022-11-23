### Hi there 👋

I'm Andrés, and I am a database developer. I've spent the last ten years writing query planners and runtime engines for Neo4j and Vitess. Most of that work is available here on github.

I'm currently working on making Vitess emulate MySQL better.

Here is some stuff I wrote:
http://systay.github.io/

Here are some projects I worked on that I think are extra cool:
   * [Planning grouping and aggregation](https://github.com/vitessio/vitess/pull/9643) across shards was interesting. I was able to use the Local Aggregation algorith in the paper [Orthogonal Optimization of Subqueries and Aggregation](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.563.8492&rep=rep1&type=pdf), by Cesar A. Galindo-Legaria and Milind M. Joshi from Microsoft Corp. to split aggregation across two sides of a join. I wrote a [blog post](https://planetscale.com/blog/grouping-and-aggregations-on-vitess) about it. 

   * I've been writing a [new query optimiser](https://github.com/vitessio/vitess/issues/7280) for Vitess. It is an implementation of the GOO paper, adapted to the kind of sharded plans we use in Vitess.
   
   * The MySQL compatability project at [Vitess](https://github.com/vitessio/vitess/). The project was about making Vitess emulating MySQL in more situations, and lead to rewriting a lot of the planner and runtime components of the query handler in Vitess.

   * The [planner](https://github.com/neo4j/neo4j/tree/4.2/community/cypher/cypher-planner/src/main/scala/org/neo4j/cypher/internal/compiler/planner/logical) that Neo4j uses to plan Cypher queries. It's an implementation of a very interesting [paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.43.4235&rep=rep1&type=pdf) for how to do relational query optimization that we adapted to be used for graph queries.
   
   * Specifying a database query language. When I created Cypher, Neo4j's query language, it started as a 20% project that I worked on on Fridays and weekends, but it quickly grew to be the main interface for Neo4j. Today it's used by thousands of developers, and there are [multiple](https://www.amazon.com/dp/B089DSXN3Q) [books](https://www.amazon.com/dp/B00KCHOXZE) [written](https://www.amazon.com/dp/B083ND9B27) about it. First leading the work of [specifying the language](https://github.com/opencypher/openCypher) and then being part of the push to standardize it with ANSI was a great learning experience and something I'm proud of.
   
   * The Morsel runtime in Neo4j. I was part of the inception of this project, but left before it made it into production. It's an implementation of this [paper](http://cs.brown.edu/~kayhan/papers/morsel_cp.pdf), and enables a single query to run on multiple threads, or a single thread to switch between multiple running queries.

   * The [compiled runtime](https://github.com/neo4j/neo4j/tree/3.2/enterprise/cypher/cypher-compiled-runtime-3.2/src/main/scala/org/neo4j/cypher/internal/compiled_runtime/v3_2) used by Neo4j. Again, it's the implementation of a [paper](https://w6113.github.io/files/papers/p539-neumann.pdf). It allows Cypher queries to be compiled to bytecode to run faster. This is another project that I was part of during it's start, but I left before it was done-done-done.

This is <a rel="me" href="https://fosstodon.org/@systay">me</a> on on Mastodon!
