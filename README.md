## Hi there 👋

I’m Andrés, a database developer with over a decade of hands-on experience building query planners and runtime engines. My work revolves around Neo4j and Vitess, and you’ll find most of my contributions right here on GitHub.

### What I’m Focusing On:
 - Building Neki. https://planetscale.com/blog/announcing-neki

### Blogs and Papers:
- I share my thoughts on my [blog](http://systay.github.io/)
- I’ve also contributed to academic papers—check them out [here](https://scholar.google.com/citations?user=ZA9AZq4AAAAJ&hl=en&citsig=AMD79opH4qlRfuM1_GJiZiiZ4PJ1BKviWQ).

### Key Projects:
 - *Grouping & Aggregation Across Shards in Vitess*: Brought in the Local Aggregation algorithm (inspired by [this paper](https://dl.acm.org/doi/abs/10.1145/376284.375748)) to optimize shard-level aggregations across joins. [Learn more](https://planetscale.com/blog/grouping-and-aggregations-on-vitess)
 - *New Query Optimizer for Vitess*: Leading the charge on a [new optimizer](https://github.com/vitessio/vitess/issues/7280) based on the GOO paper, adapted for Vitess’s sharded architecture.
 - *MySQL Compatibility for Vitess*: Helped enhance Vitess so it behaves more like MySQL, which involved overhauls to both the planner and runtime.
 - *Neo4j’s Cypher Query Planner*: Designed and wrote most of the inaugural Cypher planner, applying relational optimization concepts to graph queries.
 - *Creation of Cypher*: Oversaw the specification and standardization of Neo4j’s query language, now the go-to for countless developers. [Cypher Spec](https://github.com/opencypher/openCypher)
 - *Morsel Runtime in Neo4j*: Worked on the early version of Morsel, boosting query performance in Neo4j.
 - *Compiled Runtime for Neo4j*: Part of the original development team, helping Cypher queries run faster by compiling them to bytecode.
 - *PlanetScale’s Boost Caching System*: Designed the planner for a caching approach that transforms the plan tree into a plan DAG, allowing operators to be reused multiple times.

### Achievements
- #3 contributor to [Vitess](https://github.com/vitessio/vitess/graphs/contributors) and #5 contributor to [Neo4j](https://github.com/neo4j/neo4j/graphs/contributors)—both major open-source database systems
- My contributions have helped these projects scale to thousands of users daily, improving performance and reliability in mission-critical deployments.
- Author of influential blog posts and academic papers
