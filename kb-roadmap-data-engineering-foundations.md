### Engenharia de Dados

---

## **Módulo 0 – Introdução Epistemológica e Fundamentos Históricos**

### **Objetivo:** Compreender os marcos epistemológicos, históricos e teóricos que estruturam a Engenharia de Dados como campo.

### **Estudos:**
- Artigos clássicos e históricos:
  - Shannon, Claude. "A Mathematical Theory of Communication" (1948).
  - Codd, E. F. "A Relational Model of Data for Large Shared Data Banks" (1970).
  - Wiener, Norbert. *Cybernetics: Or Control and Communication in the Animal and the Machine* (1948).
- Epistemologia:
  - Kuhn, Thomas. *The Structure of Scientific Revolutions*. University of Chicago Press, 1962.
  - Popper, Karl. *Conjectures and Refutations*. Routledge, 1963.
  - Feyerabend, Paul. *Against Method*. Verso Books, 1975.
- História das bases matemáticas:
  - Cover, Thomas M., and Joy A. Thomas. *Elements of Information Theory*. Wiley-Interscience, 2006.
  - Bollobás, Béla. *Modern Graph Theory*. Springer, 1998.
  - Pearl, Judea. *Causality: Models, Reasoning, and Inference*. Cambridge University Press, 2009.

### **Práticas Avançadas:**
- Implementação do modelo relacional original proposto por Codd.
- Análise comparada entre os paradigmas relacionais, NoSQL e orientado a grafos, com visualização epistemológica.

---

## **Módulo 1 – Modelagem de Dados, Arquiteturas e Paradigmas**

### **Objetivo:** Dominar os modelos conceituais, lógicos e físicos de dados e as transformações históricas das arquiteturas.

### **Estudos:**
- Modelagem ER (Chen, Peter Pin-Shan. "The entity-relationship model—toward a unified view of data." ACM Transactions on Database Systems, 1976).
- Borgida, Alexander; Batory, Don et al. "Ontology-Based Data Access and Integration."
- Lenzerini, Maurizio. "Data integration: A theoretical perspective." PODS 2002. 
- Teoria da Normalização (Codd, Boyce, Date).
- Libkin, Leonid. "Incomplete Information in Relational Databases." Morgan & Claypool, 2014.
- Arenas, Marcelo; Libkin, Leonid. "An Information-Theoretic Approach to Normal Forms for Relational and Document Databases." PODS 2018.
- Fowler, Martin. Evolutionary Database Design (martinfowler.com, 2003).
- Ambler, Scott W. "Refactoring Databases." Addison-Wesley, 2006.
- Abiteboul, Serge et al. Foundations of Databases (1995).
- Libkin, Leonid. "Elements of Finite Model Theory." Springer, 2004.
- Modelos multidimensionais e Data Warehousing:
  - Inmon, W. H. *Building the Data Warehouse*. Wiley, 1996.
  - Kimball, Ralph et al. *The Data Warehouse Toolkit*. Wiley, 1996.
- Lógica de banco de dados:
  - Ullman, Jeffrey D. *Principles of Database and Knowledge-Base Systems*. Computer Science Press, 1988.
  - Suciu, Dan et al. "Probabilistic Databases." Morgan & Claypool, 2011.
  - Libkin, Leonid. "Certain Answers as Objects and Knowledge." PODS 2020.

### **Práticas Avançadas:**
- Criação de data warehouse relacional e dimensional com transformação ETL completa.
- Comparação empírica entre desempenho OLAP vs OLTP.
- Modelagem conceitual com ferramentas formais (Ex: UML, ORM).

---

## **Módulo 2 – Bancos de Dados: Tecnologias, Teorias e Implementações**

### **Objetivo:** Estudar as teorias e tecnologias de persistência e recuperação de dados.

### **Estudos:**
- Bancos relacionais e NoSQL.
- Teorema CAP (Brewer, Eric. "CAP twelve years later: How the "rules" have changed". IEEE Computer, 2012).
- Teoria de consistência eventual:
  - Vogels, Werner. "Eventually consistent." Communications of the ACM, 2009.
- Artigos:
  - Stonebraker, Michael et al. "The End of an Architectural Era". VLDB, 2007.
  - Abadi, Daniel J. "Consistency tradeoffs in modern distributed database system design." IEEE Computer, 2012.

### **Práticas Avançadas:**
- Implementação de consistência eventual com Redis/Cassandra.
- Benchmark entre bancos SQL e NoSQL para diferentes workloads.
- Simulação de teorema CAP em ambientes distribuídos.

---

## **Módulo 3 – Engenharia de Dados em Larga Escala: Pipelines e Arquiteturas**

### **Objetivo:** Construir arquiteturas robustas para ingestão, transformação e análise de dados em larga escala.

### **Estudos:**
- Arquiteturas Lambda (Marz), Kappa (Kreps), Delta Lake.
- Frameworks: Apache Spark (Zaharia et al., 2016), Beam, Flink.
- Apache Flink: Stream and Batch Processing in a Single Engine (IEEE Data Eng. Bull., 2015).
- Artigos:
  - Marz, Nathan. *Big Data: Principles and best practices of scalable real-time data systems*.
  - Zaharia, Matei et al. "Apache Spark: a unified engine for big data processing." Communications of the ACM, 2016.
  - Akidau, Tyler et al. "The dataflow model: A practical approach to balancing correctness, latency, and cost in massive-scale, unbounded, out-of-order data processing." VLDB, 2015.

### **Práticas Avançadas:**
- Pipeline híbrido com Airflow + Spark (ETL batch e stream).
- Implementação de arquitetura Lambda com processamento em tempo real.
- Gerenciamento de estado com Flink.
- Pipeline com Exactly-Once Semantics usando Flink + Kafka.
- Gerenciamento de metadados em escala com Apache Iceberg.

---

## **Módulo 4 – Transmissão e Processamento de Fluxos: Kafka, Event Sourcing e além**

### **Objetivo:** Dominar as arquiteturas de eventos e transmissão contínua.

### **Estudos:**
- Apache Kafka (Kreps, Neha Narkhede).
- Event Sourcing (Fowler), CQRS (Young).
- Change Data Capture (Debezium, Maxwell).
- Artigos:
  - Kleppmann, Martin. *Designing Data-Intensive Applications*. O'Reilly, 2017.
  - Fowler, Martin. *Event Sourcing* (martinfowler.com).
  - Young, Greg. "CQRS and Event Sourcing" (2010).
  - Kafka: A Distributed Messaging System (Netflix Tech Blog, 2011).
  - *Out-of-Order Processing*: Akidau et al. (VLDB, 2013).

### **Práticas Avançadas:**
- Criação de pipeline com Kafka + Debezium + PostgreSQL (CDC).
- Implementação de Event Sourcing completo com materialização de leitura.
- Análise da latência de ponta a ponta em arquitetura baseada em eventos.
- CDC com Debezium + Avro Schema Registry + Quarkus.
- Simulação de falhas em sistemas event-driven (Chaos Engineering com Gremlin).

---

## **Módulo 5 – DataOps, Observabilidade e Governança de Dados**

### **Objetivo:** Aprender práticas modernas de governança, qualidade e ciclo de vida do dado.

### **Estudos:**
- DataOps: Luhn, D. *DataOps Manifesto*.
- Observabilidade e lineage: OpenLineage, Great Expectations.
- Governança: DAMA-DMBOK (Data Management Body of Knowledge).
- Artigos:
  - Monte Carlo, *Data Observability Fundamentals*.
  - DataKitchen, *The DataOps Cookbook*.
  - Data Observability: The Missing Piece (Monte Carlo, 2021).
  - Marquez: A Metadata Management System (Airbnb Eng. Blog, 2020).
  - Great Expectations: Pipeline Testing (Open Source, 2020).

### **Práticas Avançadas:**
- Integração de testes de dados em pipelines CI/CD.
- Implementação de observabilidade em tempo real com Superset + DataHub.
- Catálogo automatizado com OpenMetadata.
- - CI/CD para dados com dbt + Great Expectations + Dagster.
- Análise de lineage com OpenLineage + Spark Listener.

---

## **Módulo 6 – Inteligência Artificial, Semântica e Interoperabilidade dos Dados**

### **Objetivo:** Integrar modelos de IA à engenharia de dados e explorar modelos semânticos.

### **Estudos:**
- Ontologias, RDF, OWL, Web Semântica:
  - Berners-Lee, Tim. *The Semantic Web*. Scientific American, 2001.
  - Gruber, Thomas R. "A translation approach to portable ontology specifications." Knowledge Acquisition, 1993.
- Knowledge Graphs: Google, DBpedia, YAGO.
- Enterprise Knowledge Graphs: Hogan, A. et al. (ACM CSUR, 2021).
- Neo4j: Graph Algorithms (O’Reilly, 2019).
- Integração de ML com dados: Feature Store, MLflow.
- Feature Stores for ML: Feast Framework (Gojek, 2020).

### **Práticas Avançadas:**
- Construção de um grafo de conhecimento com integração semântica RDF.
- Deploy de pipeline de machine learning com dados em tempo real.
- Análise semântica de entidades em base heterogênea.
- Construção de Grafo de Conhecimento com RDFox + Ontop.
- Feature Engineering em tempo real com Tecton + Flink.


---

## **Módulo 7 – Fronteiras e Tendências Avançadas da Engenharia de Dados**

### **Objetivo:** Explorar a fronteira do conhecimento e o estado da arte em pesquisa e mercado.

### **Estudos:**
- Data Mesh:
  - Dehghani, Zhamak. *Data Mesh: Delivering Data-Driven Value at Scale*. O'Reilly, 2022.
  - Dehghani, Zhamak. Data Mesh Principles (2022).
  - Uber’s Databook: Metadata Management at Scale (2021).
- Privacidade Diferencial:
  - Dwork, Cynthia. "Differential Privacy." ICALP, 2006.
  - Dwork, Cynthia. The Algorithmic Foundations of Differential Privacy (2014).
  - *Zero-Knowledge Proofs*: zk-SNARKs in Big Data (Zcash, 2016).
- Blockchain e integridade:
  - Wood, Gavin. *Ethereum: A Secure Decentralised Generalised Transaction Ledger*. 2014.
- Web3 e armazenamento descentralizado (IPFS, Filecoin).
- Federated Learning (McMahan et al., Google, 2017).

### **Práticas Avançadas:**
- Criação de produto de dados em arquitetura Data Mesh.
- Aplicação de técnicas de privacidade diferencial em dados sensíveis.
- Pipeline com armazenamento distribuído e verificação via blockchain (Ex: IPFS + Hyperledger).
- Treinamento federado de modelo com dados privados descentralizados.
- Implementação de Data Product com Open Data Mesh (Kafka + Airflow + S3).
- Anonimização via Privacidade Diferencial (Google’s PipelineDP).

## Tendências de Pesquisa (2023+)
- Database Theory:
  - Formal Verification of Database Systems (CIDR, 2023).
- AI-Native Databases:
  - PGML: Machine Learning in PostgreSQL (SIGMOD, 2022).
- Quantum Data Engineering:
  - Quantum Algorithms for Database Search (IBM Research, 2023).



