# Awesome Graph Universe 🌐

Welcome to **Awesome Graph Universe**, a curated list of resources, tools, libraries, and applications for working with graphs and networks. This repository covers everything from **Graph Databases** and **Knowledge Graphs** to **Graph Analytics**, **Graph Computing**, and beyond.

Graphs and networks are essential in fields like data science, knowledge representation, machine learning, and computational biology. Our goal is to provide a comprehensive resource that helps researchers, developers, and enthusiasts explore and utilize graph-based technologies.

Feel free to contribute by submitting pull requests! 🚀

## Table of Contents

<ul>
  <li><a href="#graph-databases">Graph Databases</a></li>
  <li><a href="#graph-engines">Graph Engines</a></li>
  <li><a href="#knowledge-graphs">Knowledge Graphs</a></li>
  <li><a href="#graph-etl">Graph ETL</a></li>
  <li><a href="#graph-data-science-and-analytics">Graph Data Science and Analytics</a></li>
  <li><a href="#graph-computing">Graph Computing</a></li>
  <li><a href="#graph-visualization">Graph Visualization</a></li>
  <li><a href="#graphrag-infrastructure">GraphRAG Infrastructure</a></li>
  <li><a href="#graph-stream-processors">Graph Stream Processors</a></li>
</ul>

---

## Graph Databases

Graph databases are designed to store, manage, and query graph-structured data. They come in two main categories: **Property Graphs** and **Triple Stores**. Below are some key tools and their respective languages.

### Property Graph Databases

Property graphs allow nodes and edges to have associated properties, making them useful for more detailed graph representations.

- [Amazon Neptune](https://aws.amazon.com/neptune/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A managed graph database service that supports both RDF graphs (Triple Store) and property graphs.
- [ArangoDB](https://www.arangodb.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - Multi-model database supporting graphs, documents, and key-value pairs.
- [Data Graphs](https://datagraphs.com) ![Status](https://img.shields.io/badge/status-active-brightgreen) - Ultra-fast graph database SaaS platform, easy to use, with openCypher.
- [Gremlin Server/TinkerGraph](https://tinkerpop.apache.org/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - Apache TinkerPop is an open source graph computing framework for graph database and graph analytics systems.  As part of that offering TinkerGraph is a reference implementation of an OLTP graph database that provides an in-memory graph engine.
- [JanusGraph](https://janusgraph.org/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - A scalable, distributed property graph database optimized for querying massive graphs.
- [KuzuDB](https://kuzudb.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) - A highly scalable, extremely fast, easy-to-use embeddedable graph database.
- [Memgraph](https://memgraph.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - Open-source in-memory graph database, tuned for dynamic analytics environments.
- [Neo4j](https://neo4j.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - A leading native graph database with high-performance queries for large datasets.
- [OrientDB](https://orientdb.com/) ![Status](https://img.shields.io/badge/status-inactive-red) ![Language](https://img.shields.io/badge/language-Java-orange) - A multi-model database supporting graphs and documents.
- [TigerGraph](https://www.tigergraph.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A fast, scalable graph database for enterprise applications and analytics.

### Triple Stores (RDF Databases)

Triple stores are designed to store and query RDF (Resource Description Framework) data, which represents information in triples: subject-predicate-object.

- [Amazon Neptune](https://aws.amazon.com/neptune/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A managed graph database service that supports both RDF graphs (Triple Store) and property graphs.
- [Blazegraph](https://blazegraph.com/) ![Status](https://img.shields.io/badge/status-inactive-red) ![Language](https://img.shields.io/badge/language-Java-orange) - A high-performance triple store used for RDF data.
- [GraphDB](https://www.ontotext.com/products/graphdb/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - An RDF database that helps create and query linked data.
- [Ontop VKG](https://ontop-vkg.org/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - The open source Virtual Knowledge Graph engine is used in several commercial products, open source projects and research projects for providing a SPARQL endpoint on top of relational sources and materializing relational data sources as RDF files.
- [Stardog](https://www.stardog.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - An enterprise knowledge graph platform, fully compliant with RDF and SPARQL.

---

## Graph Engines

Graph engines are optimized systems for performing queries, computations, and analytics on large graph datasets, leveraging both hardware and software efficiencies.

- [AnzoGraph](https://www.cambridgesemantics.com/product/anzograph) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A massively parallel, in-memory graph database engine for advanced analytics.
- [Apache TinkerPop](https://tinkerpop.apache.org/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - Apache TinkerPop is an open source graph computing framework for graph database and graph analytics systems. 
- [Dgraph](https://dgraph.io/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Go-blue) - A fast, distributed graph database system designed for real-time query execution.
- [GFQL](https://pygraphistry.readthedocs.io/en/0.34.8/gfql/about.html) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) ![Language](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white) - An easy-to-use open-source graph query language with dataframe-native columnar processing, optional GPU acceleration, and part of the pygraphistry/arrow/nvidia ecosystem.
- [GunDB](https://gun.eco/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-JavaScript-yellow) - A decentralized graph database engine designed for distributed systems.
- [KuzuDB](https://kuzudb.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) - A highly scalable, extremely fast, easy-to-use embeddedable graph database.
- [Memgraph](https://memgraph.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - Open-source in-memory graph database, tuned for dynamic analytics environments.
- [PuppyGraph](https://www.puppygraph.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) - Seamlessly query one or multiple data stores as a unified graph model.
- [TigerGraph](https://www.tigergraph.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A real-time graph analytics platform that supports massive datasets and deep link analytics.

---

## Knowledge Graphs

Knowledge graphs connect data points into a rich semantic web of entities and relationships. They are often used in AI applications, search engines, and data integration platforms.

- [DBpedia](https://wiki.dbpedia.org/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-PHP-blueviolet) - A project aimed at extracting structured content from Wikipedia.
- [Google Knowledge Graph](https://developers.google.com/knowledge-graph) ![Status](https://img.shields.io/badge/status-active-brightgreen) - Powering Google's search engine with structured knowledge representation.
- [Louie.AI, AI KG](https://www.louie.ai/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) ![Language](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white) Real-time self-adjusting AI graph intelligence tier for popular scalable vector-capable databases with native support for scalable ingestion, targeting, analysis, and triggering.
- [Wikidata](https://www.wikidata.org/wiki/Wikidata:Main_Page) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-JavaScript-yellow) - A free and open knowledge graph that can be queried and used in various applications.
- [YAGO](https://yago-knowledge.org/) ![Status](https://img.shields.io/badge/status-inactive-red) ![Language](https://img.shields.io/badge/language-Java-orange) - A huge semantic knowledge base derived from Wikipedia, WordNet, and GeoNames.

---

## Graph ETL

Knowledge Graph ETL (Extract, Transform, Load) refers to the process of extracting data from various sources, transforming it into a structured format suitable for a knowledge graph, and then loading it into a graph database.

- [Graph.Build](https://graph.build/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - Graph.Build is a no-code platform dedicated to managing Ontologies, LPG schemas, and ETL workflows using source data to graph model production.

- [Ontopic Studio](https://ontopic.ai/en/ontopic-studio/) ![Status](https://img.shields.io/badge/status-active-brightgreen) - Ontopic Studio enables the rapid creation of Knowledge Graphs from any relational data source, supporting both graph virtualization and ETL workflows. 

- [Nodestream](https://nodestream-proj.github.io/docs/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) - Nodestream is a declarative framework for building, maintaining, and analyzing graph data.

- [TrustGraph](https://github.com/trustgraph-ai/trustgraph) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) - Bulk ingestion of PDFs, TXT, or MD files built directly to RDF graphs with mapped vector embeddings.


---

## Graph Data Science and Analytics

Graph data science focuses on analyzing the structure and patterns in graphs to solve complex problems in domains like recommendation systems, fraud detection, and social network analysis.

- [Amazon Neptune Analytics](https://aws.amazon.com/neptune/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - Neptune Analytics is a memory-optimized graph database engine for analytics an graph algorithms.
- [Data Graphs](https://datagraphs.com) ![Status](https://img.shields.io/badge/status-active-brightgreen) - Stunning graph data visualizations and domain modelling tools.
- [GraphTool](https://graph-tool.skewed.de/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) - An efficient Python module for manipulation and statistical analysis of graphs.
- [GraphX (Apache Spark)](https://spark.apache.org/graphx/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Scala-blue) - A component of Apache Spark for graph-parallel computation.
- [GraphFrames](https://graphframes.github.io/graphframes/docs/_site/user-guide.html#connected-components) - GraphFrames is a package for Apache Spark which provides DataFrame-based Graphs in Scala, Java, and Python. Features includes motif finding and a Pregel engine.
- [MAGE](https://memgraph.com/docs/advanced-algorithms) - Memgraph Advanced Graph Extensions is an open-source graph algorithms library written in C++, Python and Rust.
- [Neo4j Graph Data Science](https://neo4j.com/product/graph-data-science/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Java-orange) - A comprehensive library for graph algorithms and machine learning models.
- [NetworkX](https://networkx.github.io/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) - A Python library for creating, manipulating, and studying complex networks.
- [PyGraphistry[AI]](https://github.com/graphistry/pygraphistry) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) ![Language](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white) - Open source library & platform to leverage the power of graph visualization, analytics, ML, & AI, including with native GPU acceleration.
- [TigerGraph Graph Studio](https://www.tigergraph.com/products/graph-analytics/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - Powerful tools for exploring and analyzing graph data.


---

## Graph Computing

Graph computing refers to the infrastructure and platforms that handle large-scale graph processing, often distributed across multiple machines for speed and scalability.

- [Apache Giraph](http://giraph.apache.org/) ![Status](https://img.shields.io/badge/status-inactive-red) ![Language](https://img.shields.io/badge/language-Java-orange) - A scalable graph processing system used by Facebook for social graph analysis.
- [GFQL](https://pygraphistry.readthedocs.io/en/0.34.8/gfql/about.html) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) ![Language](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white) - An easy-to-use open-source graph query language with dataframe-native columnar processing, optional GPU acceleration, and part of the pygraphistry/arrow/nvidia ecosystem.
- [GraphFrames (Apache Spark)](https://graphframes.github.io/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Scala-blue) - Combines the benefits of GraphX and DataFrames for scalable graph processing.
- [GraphLab](https://turi.com/products/create/docs/graphlab.html) ![Status](https://img.shields.io/badge/status-inactive-red) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - A high-performance, graph-based computation engine for machine learning applications.
- [Pregel](https://research.google/pubs/pub36726/) ![Status](https://img.shields.io/badge/status-na-lightgrey) ![Language](https://img.shields.io/badge/language-C%2B%2B-blue) - Google's graph processing model, inspired by Bulk Synchronous Parallel (BSP) systems.
- [PyGraphistry[AI]](https://github.com/graphistry/pygraphistry) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) ![Language](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white) - Open source library & platform for data scientists and developers to leverage the power of graph visualization, analytics, ML, & AI, including with native GPU acceleration.
- [thatDot Streaming Graph](https://docs.thatdot.com/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Scala-blue) - Built on top of [Quine](https://quine.io/), Streaming Graph is a high-performance stream processor designed for real-time, massively parallel, graph data processing and analytics, capable of ingesting millions of events per second.

---

## Graph Visualization

Graph visualization tools can be used to visualize and interact with graphs, in a way that helps detect patterns in the data. Some are primarily meant for ![Purpose](https://img.shields.io/badge/purpose-networkAnalysis-orange), that is for global pattern identification. Other have functionalities for ![Purpose](https://img.shields.io/badge/purpose-localAnalysis-orange), that is to identify pattern in the local context of nodes. 
Some tools are meant to ![Purpose](https://img.shields.io/badge/purpose-drawGraphs-orange) or for ![Purpose](https://img.shields.io/badge/purpose-graphDataStructuring-orange) . 

### Apps
- [Gephi](https://gephi.org/) ![Purpose](https://img.shields.io/badge/purpose-networkAnalysis-orange)  visualization and exploration software for all kinds of graphs and networks. Gephi is open-source and free.
- [GraphAware Hume](https://graphaware.com/products/hume/) ![Purpose](https://img.shields.io/badge/purpose-localAnalysis-orange) Connected Data Analytics Platform.
- [Graph Notebook](https://github.com/aws/graph-notebook) ![Purpose](https://img.shields.io/badge/purpose-localAnalysis-orange) The graph notebook provides an easy way to interact with graph databases using Jupyter notebooks. Using this open-source Python package, you can connect to any graph database that supports the Apache TinkerPop, openCypher or the RDF SPARQL graph models. 
 ![Techno](https://img.shields.io/badge/techno-AmazonNeptune-green) ![Techno](https://img.shields.io/badge/techno-ApacheTinkerPop-green) ![Techno](https://img.shields.io/badge/techno-RDF-green) ![Techno](https://img.shields.io/badge/techno-openCypher-green)  ![Techno](https://img.shields.io/badge/techno-Neo4j-green)
- [Graphistry Hub, Graphistry Enterprise](https://www.graphistry.com/get-started) ![Purpose](https://img.shields.io/badge/purpose-localAnalysis-orange)  ![Language](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white) ![WebGL](https://img.shields.io/badge/WebGL-990000?logo=webgl&logoColor=white)
 Visual investigation platform for graphs of all scales, including free GPU tier and many integrations
 
  ![Techno](https://img.shields.io/badge/techno-Neo4j-green) ![Techno](https://img.shields.io/badge/techno-AmazonNeptune-green) ![Techno](https://img.shields.io/badge/techno-Graphistry-green)  ![Techno](https://img.shields.io/badge/techno-GraphFrames-green)  ![Techno](https://img.shields.io/badge/techno-GFQL-green)  ![Techno](https://img.shields.io/badge/techno-SQL-green).
- [G.V()](https://gdotv.com) - A Graph Database Client compatible with Apache TinkerPop enabled graph databases that enables users to write and run Gremlin queries against their database, and visualize the results using various formats (graph visualization, JSON, tables, etc). It's also comes with query debugging/profiling features, and graph data exploration and editing features.
- [Kineviz, GraphXR](https://www.kineviz.com/graphxr) ![Purpose](https://img.shields.io/badge/purpose-networkAnalysis-orange)  Exploring connected data in an immersive browser-based platform.
- [Kineviz, GraphXR,Neo4j GraphApp](https://graphxr.kineviz.com/projects) ![Purpose](https://img.shields.io/badge/purpose-networkAnalysis-orange)
- [Kineviz, SightXR](https://www.kineviz.com/sightxr) ![Purpose](https://img.shields.io/badge/purpose-networkAnalysis-orange) Navigate unstructured data with visual knowledge maps and GenAI.
- [Linkurious Enterprise](https://resources.linkurious.com/lke-free-trial) ![Purpose](https://img.shields.io/badge/purpose-localAnalysis-orange) For interactive visual exploration of local graph patterns. Contextual decision intelligence solutions
- [Louie.AI](https://www.louie.ai/) ![Purpose](https://img.shields.io/badge/purpose-localAnalysis-orange) ![WebGL](https://img.shields.io/badge/WebGL-990000?logo=webgl&logoColor=white) Interactive genAI-native notebooks and dashboards with native integration for Python, Graphistry, and many databases
![Techno](https://img.shields.io/badge/techno-Neo4j-green) ![Techno](https://img.shields.io/badge/techno-AmazonNeptune-green)  ![Techno](https://img.shields.io/badge/techno-Graphistry-green) ![Techno](https://img.shields.io/badge/techno-GraphFrames-green) ![Techno](https://img.shields.io/badge/techno-GFQL-green)  ![Techno](https://img.shields.io/badge/techno-SQL-green).
- [metaphacts](https://metaphacts.com/) metaphacts offers a flexible, open platform for describing and querying graph data and for visualizing and interacting with knowledge graphs.
- [Neo4j Bloom](https://neo4j.com/product/bloom/) ![Purpose](https://img.shields.io/badge/purpose-localAnalysis-orange) ![Techno](https://img.shields.io/badge/techno-Neo4j-green) Explore and freely interact with Neo4j’s graph data platform with no coding required.
- [NeoDash](https://neo4j.com/labs/neodash/) ![Purpose](https://img.shields.io/badge/purpose-localAnalysis-orange)  Build dashboards (tables, maps, graph visualization,...) from data in a ![Techno](https://img.shields.io/badge/techno-Neo4j-green) db.
- [SemSpect](https://www.semspect.de/) ![Purpose](https://img.shields.io/badge/purpose-localAnalysis-orange) No-code graph exploration. ![Techno](https://img.shields.io/badge/techno-Neo4j-green) **RDF**
- [TheBrain](http://www.thebrain.com/) ![Purpose](https://img.shields.io/badge/purpose-graphDataStructuring-orange) Organizing notes and documents in a graph structure, with creation of visual representation of relations with the mouse.
- [WebVOWL](https://service.tib.eu/webvowl/)  **RDF** Ontologies visualization
- [yWork, yEd Desktop](https://www.yworks.com/products/yed/download) ![Purpose](https://img.shields.io/badge/purpose-drawGraphs-orange) Easily draw graphs for illustration, with icons on nodes, styling of labels and relations.
- [yWork, yEd Live](https://www.yworks.com/yed-live/index.html) ![Purpose](https://img.shields.io/badge/purpose-drawGraphs-orange) Display graphs with styling for nodes, relationships and apply several automatic layout algorithm and export to pdf , png, graphML.
- [yWorks, Data Explorer for Neo4j](https://www.yworks.com/neo4j-explorer/) ![Purpose](https://img.shields.io/badge/purpose-drawGraphs-orange) Extract nodes from a ![Techno](https://img.shields.io/badge/techno-Neo4j-green) db and display them by applying templates based on node labels. Resulting graph can be sent to yWork, yEd Live to further adjust the display.

### Libraries

Various ![Language](https://img.shields.io/badge/language-Javascript-blue) and ![Language](https://img.shields.io/badge/language-Python-blue) libraries allow to display large networks.

- [Cytoscape](https://js.cytoscape.org/) ![Language](https://img.shields.io/badge/language-Javascript-blue)
- [EasyGraph](https://easy-graph.github.io/index.html) ![Language](https://img.shields.io/badge/language-Python-blue)
- [GraphistryJS](https://github.com/graphistry/graphistry-js) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-JavaScript-blue) ![Language](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white)  ![WebGL](https://img.shields.io/badge/WebGL-990000?logo=webgl&logoColor=white) Open-source HTML, Node, React, vanilla JS library for quickly visualizing large-scale graph data in Graphistry, including with native GPU acceleration.
- [iGraph](https://igraph.org/python/) ![Language](https://img.shields.io/badge/language-Python-blue)
- [Linkurious, Ogma](https://resources.linkurious.com/ogma) ![Language](https://img.shields.io/badge/language-Javascript-blue)
- [NetworkX](https://networkx.org/) ![Language](https://img.shields.io/badge/language-Python-blue)
- [Orb](https://github.com/memgraph/orb) - Open-source graph visualization library. ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-TypeScript-blue)
- [PyGraphistry](https://github.com/graphistry/pygraphistry) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) ![Language](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white)  ![WebGL](https://img.shields.io/badge/WebGL-990000?logo=webgl&logoColor=white) - Open-source library & platform for quickly visualizing large-scale graph data, including with native CPU & GPU acceleration, and native support for most Python notebook and dashboard environments and leading graph packages.
- [Sigma.js](https://www.sigmajs.org/) ![Language](https://img.shields.io/badge/language-Javascript-blue)
- [yWorks, yFiles for HTML](https://www.yworks.com/yfiles-overview?yfiles.com) Diagramming SDK to precisely display and interect with different shapes of graphs. 
- [yWorks, yFiles for Jupyter](https://www.yworks.com/products/yfiles-graphs-for-jupyter) ![Language](https://img.shields.io/badge/language-Python-blue) interactive graph visualization widget for Jupyter Notebooks and Google Colab supporting Python Objects, Pandas Dataframes, NetworkX graphs [Neo4j graphs explorer](https://github.com/yWorks/yfiles-jupyter-graphs-for-neo4j/)

---

## GraphRAG Infrastructure

GraphRAG refers to using knowledge graphs for the basis of RAG (Retrieval-Augmented Generation) to improve the accuracy of Generative AI responses.

- [GraphRAG](https://github.com/microsoft/graphrag) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) - Microsoft's open source project to deploy a GraphRAG solution
- [Louie.AI, AI KG](https://www.louie.ai/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) ![Language](https://img.shields.io/badge/CUDA-76B900?logo=nvidia&logoColor=white) Real-time self-adjusting AI graph intelligence tier for popular scalable vector databases with native support for scalable ingestion, targeting, analysis, and triggering.
- [TrustGraph](https://github.com/trustgraph-ai/trustgraph) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Python-blue) - Full AI Engine with Native GraphRAG for Agent Development.

---

## Graph Stream Processors

Graph stream processors enable real-time graph computations within event-stream processing systems. They integrate seamlessly into ETL pipelines or event streams, allowing graph operations to be performed on incoming data streams. These tools consume events, apply graph-based transformations or analyses, and emit processed events, facilitating dynamic graph processing as data flows through the system.

- [Quine](https://quine.io/) ![Status](https://img.shields.io/badge/status-active-brightgreen) ![Language](https://img.shields.io/badge/language-Scala-blue) - Quine allows developers to combine multiple event streams into a single graph, query for complex event relationships to identify high value patterns, and take an action in real time.

---

## Contributing

Contributions are welcome! If you know of any valuable graph-related resources, tools, or libraries that should be included, feel free to submit a pull request or open an issue.

Please follow the [contribution guidelines](CONTRIBUTING.md) to maintain the quality and consistency of Awesome Graph Universe.

---

## License

[![CC0](https://img.shields.io/badge/license-CC0-blue.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This repository is licensed under CC0 1.0 Universal, which means you can freely use and contribute to this project.

---

Happy Graphing! 😊

---

Inspired by the work of [Jean-Baptiste Musso](https://github.com/jbmusso/awesome-graph) - which is currently inactive.
