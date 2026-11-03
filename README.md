## Hi there 👋

I'm Andrés, a database developer who has been building query planners and runtime engines since 2010. I've spent most of that time deep inside Neo4j and Vitess, and these days I'm building [Neki](https://neki.dev/), where I lead the design of the query planner.

### Blogs and Papers
- I share my thoughts on my [blog](https://systay.github.io/)
- I've also contributed to academic papers, check them out [here](https://scholar.google.com/citations?user=ZA9AZq4AAAAJ&hl=en).

### Key Projects
- *Neki Query Planner*: Designing the planner for Neki, PlanetScale's sharded Postgres. [neki.dev](https://neki.dev/)
- *Grouping & Aggregation Across Shards in Vitess*: Brought in the Local Aggregation algorithm (inspired by [this paper](https://dl.acm.org/doi/abs/10.1145/376284.375748)) to optimize shard-level aggregations across joins. [Learn more](https://planetscale.com/blog/grouping-and-aggregations-on-vitess)
- *New Query Optimizer for Vitess*: Led the work on a [new optimizer](https://github.com/vitessio/vitess/issues/7280) based on the GOO paper, adapted for Vitess's sharded architecture.
- *MySQL Compatibility for Vitess*: Helped make Vitess behave more like MySQL, which meant overhauling both the planner and the runtime.
- *PlanetScale's Boost Caching System*: Designed the planner for a caching approach that turns the plan tree into a plan DAG, so operators can be reused multiple times.
- *Creation of Cypher*: Oversaw the specification and standardization of Neo4j's query language, now the go-to for countless developers. [Cypher Spec](https://github.com/opencypher/openCypher)
- *Neo4j's Cypher Query Planner*: Designed and wrote most of the original Cypher planner, applying relational optimization ideas to graph queries.
- *Morsel Runtime in Neo4j*: Worked on the early version of Morsel, boosting query performance in Neo4j.
- *Compiled Runtime for Neo4j*: Part of the original team that made Cypher queries faster by compiling them to bytecode.
