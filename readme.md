# Awesome Knowledge Graph [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Knowledge Graph related learning materials, databases, tools and other resources

## Contents

* [Infrastructure](#infrastructure)
  * [Graph Databases](#graph-databases)
  * [Triple Stores](#triple-stores) 
  * [Graph Computing Frameworks](#graph-computing-frameworks)
  * [Languages](#languages)
  * [Managed Hosting Services](#managed-hosting-services)
* [Knowledge Graph Content](#knowledge-graph-content)
  * [General](#general)
  * [Semantic Network](#semantic-network)
  * [Academic](#academic)
* [Learning Materials](#learning-materials)
  * [Official Documentations](#official-documentations)
  * [Community Effort](#community-effort)


## Infrastructure

### Graph Databases

* [AgensGraph](https://bitnine.net/agensgraph-2/) - multi-model graph database with SQL and Cypher support
* [ArangoDB](https://www.arangodb.com/) - highly available Multi-Model NoSQL database
* [Blazegraph](https://github.com/blazegraph/database) - GPU accelerated graph database
* [Cayley](https://github.com/cayleygraph/cayley) - open source database written in Go
* [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/graph-introduction) - cloud-based multi-model database with support for TinkerPop3
* [Dgraph](https://dgraph.io) - Fast, Transactional, Distributed Graph Database (open source, written in Go)
* [DSE Graph](https://www.datastax.com/products/datastax-enterprise-graph) - Graph layer on top of DataStax Enterprise (Cassandra, SolR, Spark)
* [Grakn.AI](https://grakn.ai/) - a distributed hyper-relational database for knowledge-oriented systems, i.e. a distributed knowledge base
* [Graphd](https://github.com/google/graphd) - the Metaweb/Freebase Graph Repository
* [JanusGraph](http://janusgraph.org) - an open-source, distributed graph database with pluggable storage and indexing backends
* [Memgraph](https://memgraph.com/) - High Performance, In-Memory, Transactional Graph Database
* [Neo4j](http://tinkerpop.apache.org/docs/currentg/#neo4j-gremlin) - OLTP graph database
* [Sparksee](http://www.sparsity-technologies.com/#sparksee) - makes space and performance compatible with a small footprint and a fast analysis of large networks
* [Stardog](http://stardog.com/) - RDF graph database with OLTP and OLAP support
* [OrientDB](http://orientdb.com/orientdb/) - Distributed Multi-Model NoSQL Database with a Graph Database Engine

### Triple Stores

* [AllegroGraph](https://franz.com/agraph/allegrograph/) - high-performance, persistent graph database that scales to billions of quads
* [Apache Jena](https://jena.apache.org/) - open source Java framework for building Semantic Web and Linked Data applications
* [Eclipse RDF4J](http://rdf4j.org/) - (formerly known as Sesame) is an open source Java framework for processing RDF data. This includes parsing, storing, inferencing and querying of/over such data. It offers an easy-to-use API that can be connected to all leading RDF storage solutions. It allows you to connect with SPARQL endpoints and create applications that leverage the power of linked data and Semantic Web.
* [GraphDB](http://graphdb.ontotext.com/graphdb/) - enterprise ready Semantic Graph Database, compliant with W3C Standards
* [Virtuoso](https://virtuoso.openlinksw.com/) - a "Data Junction Box" that drives enterprise and individual agility by deriving a Semantic Web of Linked Data from existing data silos
* [Hoply](https://github.com/amirouche/hoply/) - explore bigger than RAM relational data in the comfort of Python.

### Graph Computing Frameworks

* [Apache Giraph](https://giraph.apache.org/) - an iterative graph processing system built for high scalability
* [Apache TinkerPop](https://tinkerpop.apache.org/) - a graph computing framework for both graph databases (OLTP) and graph analytic systems (OLAP)
* [Apache Spark - GraphX](https://spark.apache.org/graphx/) - Apache Spark's API for graphs and graph-parallel computation

### Languages

* [Cypher](http://www.opencypher.org/)
* [Gremlin](https://tinkerpop.apache.org/gremlin.html)
* [SPARQL](https://en.wikipedia.org/wiki/SPARQL)

### Managed Hosting Services

* [CosmosDB @ Microsoft](https://docs.microsoft.com/en-us/azure/cosmos-db/graph-introduction)
* [JanusGraph @ IBM Compose](https://www.compose.com/databases/janusgraph)
* [JanusGraph @ Google Cloud Platform](https://cloud.google.com/solutions/running-janusgraph-with-bigtable) - JanusGraph on Google Kubernetes Engine backed by Google Cloud Bigtable
* [JanusGraph @ Amazon Web Services Labs](https://github.com/awslabs/dynamodb-janusgraph-storage-backend) - The Amazon DynamoDB Storage Backend for JanusGraph
* [Neo4j @ Graphene](https://www.graphenedb.com/)
* [Neo4j @ Graph Story](https://www.graphstory.com/) - End-to-end Graph Database hosting for Community and Enterprise Neo4j with expert help for development
* [Neptune @ Amazon Web Services](https://aws.amazon.com/neptune/) - a fast, reliable, fully-managed graph database service that makes it easy to build and run applications that work with highly connected datasets
* [Graph Engine Service @ Huawei Cloud](https://www.huaweicloud.com/en-us/product/ges.html) - Fully-managed, distributed, at-scale graph query and analysis service that provides a visualized interactive analytics platform.

## Knowledge Graph Content

### General

* [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) - Wikidata is a free, collaborative, multilingual, secondary database, collecting structured data to provide support for Wikipedia, Wikimedia Commons, the other wikis of the Wikimedia movement, and to anyone in the world.
* [Google Knowledge Graph](https://developers.google.com/knowledge-graph/) - Google’s Knowledge Graph has millions of entries that describe real-world entities like people, places, and things.
* [DBpedia](https://wiki.dbpedia.org/) - DBpedia is a crowd-sourced community effort to extract structured content from the information created in various Wikimedia projects.
* [XLore](https://xlore.org/) - A large-scale English-Chinese bilingual knowledge graph by structuring and integrating Chinese Wikipedia, English Wikipedia, French Wikipedia, and Baidu Baike. 

### Semantic Network

* [ConceptNet](http://conceptnet.io/) - ConceptNet is a freely-available semantic network, designed to help computers understand the meanings of words that people use.
* [Microsoft Concept Graph](https://concept.research.microsoft.com/) - For Short Text Understanding
* [OpenHowNet](https://openhownet.thunlp.org) - An Open Sememe-based Lexical Knowledge Base

### Academic

* [AMiner](https://www.aminer.cn/) - Aminer aims to provide comprehensive search and mining services for researcher social networks.
* [Microsoft Academic](https://academic.microsoft.com/) - Microsoft Academic (MA) employs advances in machine learning, semantic inference and knowledge discovery to help you explore scholarly information in more powerful ways than ever before.

## Learning Materials

### Official Documentations
* [Cypher](https://neo4j.com/developer/cypher-query-language/) - reference documentation
* [Gremlin](http://tinkerpop.apache.org/docs/current/reference/#traversal) - reference documentation

### Community Effort
* [Graph Book](https://github.com/krlawrence/graph) - TinkerPop3 centric book written by [Kelvin R. Lawrence](https://twitter.com/gfxman)
* [SQL2Gremlin](http://sql2gremlin.com/) - transition from SQL to Gremlin by [Daniel Kuppitz](https://twitter.com/dkuppitz)
* [The Gremlin Compendium](http://www.doanduyhai.com/blog/?p=13460) - minimum survival kit for any Gremlin user, 10 blog post series by [Doan DuyHai](https://twitter.com/doanduyhai)

## Conferences

* [Graph Connect](http://graphconnect.com/) - powered by Neo4j
* [Graph Day](http://graphday.com/) - an Independent Graph Conference from the Data Day folks


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.  
Some of the content were copied from other awesome lists:  

* [awesome-graph](https://github.com/jbmusso/awesome-graph) - Graph, the infrastructure for Knowledge Graph
* [awesome-knowledge-graph](https://github.com/husthuke/awesome-knowledge-graph) - Knowledge graph related materials but all in Chinese




## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Sitao Z. has waived all copyright and
related or neighboring rights to this work.