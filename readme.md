# Awesome Knowledge Graph [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Knowledge Graph related learning materials, databases, tools and other resources

## Contents

* [Infrastructure](#infrastructure)
  * [Graph Databases](#graph-databases)
  * [Triple Stores](#triple-stores) 
  * [Graph Computing Frameworks](#graph-computing-frameworks)
  * [Graph Visualization](#graph-visualization)
  * [Graph Construction](#graph-construction)
  * [Languages](#languages)
  * [Managed Hosting Services](#managed-hosting-services)
* [Knowledge Engineering](#knowledge-engineering)
  * [Knowledge Fusion](#knowledge-fusion)
* [Knowledge Graph Dataset](#knowledge-graph-dataset)
  * [General](#general)
  * [Semantic Network](#semantic-network)
  * [Academic](#academic)
* [Learning Materials](#learning-materials)
  * [Official Documentations](#official-documentations)
  * [Community Effort](#community-effort)

## Infrastructure

### Graph Databases

* [AgensGraph](https://bitnine.net/agensgraph/) - multi-model graph database with SQL and Cypher support based on PostgreSQL
* [ArangoDB](https://www.arangodb.com/) - highly available Multi-Model NoSQL database
* [Atomic-Server](https://crates.io/crates/atomic-server/) - open-source type-safe graph database server with GUI, written in rust. Supports [Atomic Data](docs.atomicdata.dev/), JSON & RDF.
* [Blazegraph](https://github.com/blazegraph/database) - GPU accelerated graph database
* [Cayley](https://github.com/cayleygraph/cayley) - open source database written in Go
* [CosmosDB](https://docs.microsoft.com/en-us/azure/cosmos-db/graph-introduction) - cloud-based multi-model database with support for TinkerPop3
* [Dgraph](https://dgraph.io) - Fast, Transactional, Distributed Graph Database (open source, written in Go)
* [DSE Graph](https://www.datastax.com/products/datastax-enterprise-graph) - Graph layer on top of DataStax Enterprise (Cassandra, SolR, Spark)
* [TypeDB](https://vaticle.com/) - a database with a rich and logical type system. 
* [Graphd](https://github.com/google/graphd) - the Metaweb/Freebase Graph Repository
* [JanusGraph](http://janusgraph.org) - an open-source, distributed graph database with pluggable storage and indexing backends
* [Memgraph](https://memgraph.com/) - High Performance, In-Memory, Transactional Graph Database
* [Neo4j](http://tinkerpop.apache.org/docs/currentg/#neo4j-gremlin) - OLTP graph database
* [Sparksee](http://www.sparsity-technologies.com/#sparksee) - makes space and performance compatible with a small footprint and a fast analysis of large networks
* [Stardog](http://stardog.com/) - RDF graph database with OLTP and OLAP support
* [OrientDB](http://orientdb.com/orientdb/) - Distributed Multi-Model NoSQL Database with a Graph Database Engine
* [TigerGraph](https://www.tigergraph.com) - a complete, distributed, parallel graph computing platform for enterprise, supporting web-scale data analytics in real-time. 
* [Nebula Graph](https://nebula-graph.io/) - A truly distributed, linear scalable, lightning-fast graph database, using SQL-like query language. 
* [HugeGraph](https://github.com/hugegraph/hugegraph) - An open source TinkerPop 3 compliant OLTP Graph Database with pluggable storage bakcend which is similar to JanusGraph. It also supports OLAP through Spark GraphX. 
* [Diffbot](https://diffbot.com/products/knowledge-graph) - One of three Western entities to crawl a majority of the web. Largest commercially available knowledge graph. 
* [Weaver](https://www.weaverhq.com/) - A graph database built on top of Postgres, which allows you to query the dataset in both SQL and graph query languages including SQL, SPARQL, and GraphQL.
* [Kuzu](https://kuzudb.com/) - A highly scalable, extremely fast, and very easy-to-use embeddable graph database.
* [CogDB](https://cogdb.io/) - A Micro Graph Database for Python Applications.
* [TuGraph](https://www.tugraph.org/) - Graph database behinde Alipay. It has achieved the top-ranking performance in LDBC-SNB, a globally recognised benchmark test, surpassing competing solutions.


### Triple Stores

* [AllegroGraph](https://franz.com/agraph/allegrograph/) - high-performance, persistent graph database that scales to billions of quads
* [Apache Jena](https://jena.apache.org/) - open source Java framework for building Semantic Web and Linked Data applications
* [Copernic](https://git.sr.ht/~amirouche/copernic) - Data, and its history, via change requests at scale
* [Eclipse RDF4J](http://rdf4j.org/) - (formerly known as Sesame) is an open source Java framework for processing RDF data. This includes parsing, storing, inferencing and querying of/over such data. It offers an easy-to-use API that can be connected to all leading RDF storage solutions. It allows you to connect with SPARQL endpoints and create applications that leverage the power of linked data and Semantic Web.
* [GraphDB](http://graphdb.ontotext.com/graphdb/) - enterprise ready Semantic Graph Database, compliant with W3C Standards
* [Virtuoso](https://virtuoso.openlinksw.com/) - a "Data Junction Box" that drives enterprise and individual agility by deriving a Semantic Web of Linked Data from existing data silos
* [Apache Marmotta](https://marmotta.apache.org/) - (retired Apache project) an open platform for linked data.
* [Oxigraph](https://github.com/oxigraph/oxigraph) - a light wight triple store written in Rust.

### Graph Computing Frameworks

* [Apache Giraph](https://giraph.apache.org/) - an iterative graph processing system built for high scalability
* [Apache TinkerPop](https://tinkerpop.apache.org/) - a graph computing framework for both graph databases (OLTP) and graph analytic systems (OLAP)
* [Apache Spark - GraphX](https://spark.apache.org/graphx/) - Apache Spark's API for graphs and graph-parallel computation
* [Tencent Plato](https://github.com/tencent/plato) - a fast distributed graph computation and machine learning framework used by WeChat. 
* [Gradoop](https://github.com/dbs-leipzig/gradoop) - a distributed graph analytics framework based on Apache Flink

### Graph Visualization

* [AntV G6](https://github.com/antvis/g6) - Simple, easy and complete high performance graph visualization engine written in JavaScript, from Ant Financial
* [Graphistry](https://github.com/graphistry/pygraphistry) - An end-to-end GPU visual graph analytics engine (Nvidia RAPIDS.ai / Apache Arrow) with interfaces including JS/React, Python (Jupyter/StreamLit), REST, rich no-code/low-code UIs for various databases, and self + cloud hosting, from Graphistry.
* [Gephi](https://gephi.org/) - Graph visualization platform software runs on Windows, Mac and Linux.
* [KeyLines & ReGraph](https://cambridge-intelligence.com/) - Graph visualization tookits for JavaScript and React developer from Cambridge Intelligence.
* [Linkurious](https://linkurio.us) - Linkurious is an enterprise ready on-premises graph visualization and analysis platform.
* [Cytoscape](https://cytoscape.org/) - Open source graph visualization platform software runs on Windows, Mac and Linux.
* [Cytoscape.js](https://js.cytoscape.org/) - Graph visualization tookit for JavaScript.
* [Sigma.js](https://www.sigmajs.org/) - JavaScript library aimed at visualizing larger graphs. 

### Graph Construction

* [Morph-KGC](https://github.com/morph-kgc/morph-kgc/) - Knowledge graph generation system with RML mappings.
* [Termboard](https://termboard.com/) - A very simple graphical editor to create Terms and Relations. It can use ChatGPT, Google Bard or any other chatbot. Ideal for beginners wanting to make and share quick sketches.

### Languages

* [Cypher](http://www.opencypher.org/)
* [Gremlin](https://tinkerpop.apache.org/gremlin.html)
* [SPARQL](https://en.wikipedia.org/wiki/SPARQL)
* [GraphQL+-](https://docs.dgraph.io/query-language/) - The query language of Dgraph, which is based on Facebook's GraphQL
* [GQL](https://gql.today/) - An initiative to create a standard query language for property graph database, just like SQL for relational database. 

### Managed Hosting Services

* [CosmosDB @ Microsoft](https://docs.microsoft.com/en-us/azure/cosmos-db/graph-introduction) - Azure Cosmos DB is Microsoft's globally distributed, multi-model (Key-value, Document, Column, Graph) database service.  
* [JanusGraph @ IBM Compose](https://www.compose.com/databases/janusgraph)
* [JanusGraph @ Google Cloud Platform](https://cloud.google.com/solutions/running-janusgraph-with-bigtable) - JanusGraph on Google Kubernetes Engine backed by Google Cloud Bigtable
* [JanusGraph @ Amazon Web Services Labs](https://github.com/awslabs/dynamodb-janusgraph-storage-backend) - The Amazon DynamoDB Storage Backend for JanusGraph
* [Neo4j @ Graphene](https://www.graphenedb.com/)
* [Neo4j @ Graph Story](https://www.graphstory.com/) - End-to-end Graph Database hosting for Community and Enterprise Neo4j with expert help for development
* [Neptune @ Amazon Web Services](https://aws.amazon.com/neptune/) - a fast, reliable, fully-managed graph database service that makes it easy to build and run applications that work with highly connected datasets
* [Graph Engine Service @ Huawei Cloud](https://www.huaweicloud.com/en-us/product/ges.html) - Fully-managed, distributed, at-scale graph query and analysis service that provides a visualized interactive analytics platform.
* [Graph Database (beta) @ Aliyun (Alibaba Cloud)](https://www.aliyun.com/product/gdb) - highly reliable and available property graph database that supports ACID and TinkerPop Gremlin query language. 
* [Tencent Knowledge Graph @ Tencent Cloud](https://cloud.tencent.com/product/tkg) - One stop platform for Graph database, computing and visualization. Currently available in beta test and only in Chinese. 
* [WoordLift](https://wordlift.io/) - Easy-to-use SEO-focused Graph Database hosting for web and e-commerce websites running on Apache Marmotta. 
* [Baidu Knowledge Graph @ Baidu AI Platform](https://ai.baidu.com/solution/kgaas) - One-stop AI platform to build knowledge graph and its applications. 
* [Graphistry](https://github.com/graphistry/pygraphistry) - Cloud accounts for Graphistry end-to-end GPU-accelerated visual graph analytics projects

## Knowledge Engineering

* [YAGA-NAGA](https://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/) - Harvesting, Searching, and Ranking Knowledge from the Web

### Knowledge Fusion

* [Dedupe](https://github.com/dedupeio/dedupe) - dedupe is a python library that uses machine learning to perform fuzzy matching, deduplication and entity resolution quickly on structured data.
* [LIMES](https://github.com/dice-group/LIMES) - Link Discovery Framework for Metric Spaces.

## Knowledge Graph Dataset

### General

* [BabelNet](https://babelnet.org/) - Both a **multilingual encyclopedic dictionary**, with lexicographic and encyclopedic coverage of terms, and a **semantic network** which connects concepts and named entities in a very large network of semantic relations, made up of about 16 million entries, called Babel synsets. Each Babel synset represents a given meaning and contains all the synonyms which express that meaning in a range of different languages.
* [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) - Wikidata is a free, collaborative, multilingual, secondary database, collecting structured data to provide support for Wikipedia, Wikimedia Commons, the other wikis of the Wikimedia movement, and to anyone in the world.
* [Google Knowledge Graph](https://developers.google.com/knowledge-graph/) - Google’s Knowledge Graph has millions of entries that describe real-world entities like people, places, and things.
* [Freebase](https://developers.google.com/freebase/) - Large scale knowledge base originally stated by Metaweb. Later aquired by Google and used in [Google Knowledge Graph](https://blog.google/products/search/introducing-knowledge-graph-things-not/).
* [DBpedia](https://wiki.dbpedia.org/) - DBpedia is a crowd-sourced community effort to extract structured content from the information created in various Wikimedia projects.
* [XLore](https://xlore.org/) - A large-scale English-Chinese bilingual knowledge graph by structuring and integrating Chinese Wikipedia, English Wikipedia, French Wikipedia, and Baidu Baike. 
* [The GDELT Project](https://www.gdeltproject.org/) - The GDELT Project monitors the world's broadcast, print, and web news from nearly every corner of every country in over 100 languages and identifies the people, locations, organizations, themes, sources, emotions, counts, quotes, images and events driving our global society  every second of every day, creating a free open platform for computing on the entire world.
* [YAGO](http://yago-knowledge.org/) - A huge semantic knowledge base, derived from [Wikipedia](http://en.wikipedia.org/),  [WordNet](http://wordnet.princeton.edu/) and [GeoNames](http://www.geonames.org/). Currently, YAGO has knowledge of more than 10 million entities (like persons, organizations, cities, etc.) and contains more than 120 million facts about these entities. The source code of YAGO is in this Github [repo](https://github.com/yago-naga/yago3). 
* [Zhishi.me](http://zhishi.me/) - Knowledge Graph data extracted from the largest Chinese encyclopedias,  [Baidu Baike](https://baike.baidu.com/), [Hudong Baike](https://www.baike.com/) and [Chinese Wikipedia](https://zh.wikipedia.org/).
* [NELL](http://rtw.ml.cmu.edu/rtw/) - Never-Ending Language Learner, read the web and extract facts from text found in web pages continuously and improve itself.
* [Golden Protocol](https://golden.xyz/) - A decentralized canonical knowledge graph. It is open, transparent, consensus, bounty enabled and built in the age of Web 3.

### Semantic Network

* [ConceptNet](http://conceptnet.io/) - ConceptNet is a freely-available semantic network, designed to help computers understand the meanings of words that people use.
* [Microsoft Concept Graph](https://concept.research.microsoft.com/) - For Short Text Understanding
* [OpenHowNet](https://openhownet.thunlp.org) - An Open Sememe-based Lexical Knowledge Base in Chinese.
* [WordNet](http://wordnet.princeton.edu/) - A free large lexical database of English from Princeton University.

### Academic & Research

* [AMiner](https://www.aminer.cn/) - Aminer aims to provide comprehensive search and mining services for researcher social networks.
* [Microsoft Academic](https://academic.microsoft.com/) - Microsoft Academic (MA) employs advances in machine learning, semantic inference and knowledge discovery to help you explore scholarly information in more powerful ways than ever before.
* [AceMap](https://www.acemap.info/) - Academic search engine based on knowledge graph which includes entities like paper, author, institution and etc. 
* [Semantic Scholar](https://www.semanticscholar.org/) - A free, AI-powered research tool for scientific literature. Collaborating with academic publishers to build a trustworthy and authoritative scientific knowledge graph.

### Other Domain

* [Lynx](https://lynx-project.eu/) - an ecosystem of smart cloud services to better manage compliance, based on a Legal Knowledge Graph (LKG) which integrates and links heterogeneous compliance data sources including legislation, case law, standards and other private contracts.
* [ResearchSpace](https://researchspace.org/) - A culture heritage knowledge graph from the British Museum. 
* [Unified Medical Language System (UMLS)](https://www.nlm.nih.gov/research/umls/index.html) - The UMLS integrates and distributes key terminology, classification and coding standards, and associated resources to promote creation of more effective and interoperable biomedical information systems and services, including electronic health records.
* [DrugBank](https://go.drugbank.com/) - Knowledge base for drug interactions, pharmacology, chemical structures, targets, metabolism, and more. 
* [STRING](https://string-db.org/) - A database of known and predicted protein-protein interactions.

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
* [Connected Data London](https://connected-data.london/) - Connected Data London brings together 160+ Artificial Intelligence, Semantic Technology, Linked Data and Graph Database innovators, thought leaders and practitioners annually in one great conference. The conference has expanded its themes and tracks, from its roots as the primary conference for Knowledge Graphs, Linked Data and Semantics to include related Graph Database and AI / Machine Learning technologies and practical use cases.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.  
Some of the content were copied from other awesome lists:  

* [awesome-graph](https://github.com/jbmusso/awesome-graph) - Graph, the infrastructure for Knowledge Graph
* [awesome-knowledge-graph](https://github.com/husthuke/awesome-knowledge-graph) - Knowledge graph related materials but all in Chinese

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Sitao Z. has waived all copyright and related or neighboring rights to this work.
