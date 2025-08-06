### Engenharia de Dados

---
## Módulo 0: Introdução Epistemológica e Fundamentos Históricos

**Objetivo Geral:**
Compreender os fundamentos epistemológicos, históricos e matemáticos que estruturam a Engenharia de Dados como campo disciplinar e técnico. Este módulo oferece a base crítica para avaliação das práticas e tecnologias sob uma perspectiva histórica, filosófica e científica.

**Requisitos prévios:**

* Leitura acadêmica em filosofia da ciência
* Noções de teoria da informação, lógica e álgebra
* Conhecimento básico em estruturas de dados

---

## 1. Marcos Históricos e Fundadores da Engenharia de Dados

### 1.1. Comunicação e Informação

* Shannon, C. E. (1948). *A Mathematical Theory of Communication*. Bell System Technical Journal.

  > Obra fundadora da teoria da informação. 

* Cover, T. M.; Thomas, J. A. (2006). *Elements of Information Theory*, 2nd ed. Wiley-Interscience.

  > Referência moderna e consolidada. Para atualização, incluir:

* **Verdu, S. (2021).** *Information Theory: Fifty Years Later*. IEEE Press.

  > Atualização crítica do impacto da teoria da informação no século XXI.

---

### 1.2. Cibernética e Sistemas

* Wiener, N. (1948). *Cybernetics: Or Control and Communication in the Animal and the Machine*. MIT Press.

  > Clássico fundacional, complementar com:

* **Pickering, A. (2010).** *The Cybernetic Brain: Sketches of Another Future*. University of Chicago Press.

  > Estudo histórico-filosófico atualizado sobre a cibernética como matriz da computação contemporânea.

---

### 1.3. Modelos de Dados e Organização da Informação

* Codd, E. F. (1970). *A Relational Model of Data for Large Shared Data Banks*. Communications of the ACM.

  > Fundamental para o surgimento dos SGBDs relacionais.

* Abadi, D. J.; Boncz, P.; Harizopoulos, S. (2013). *The Design and Implementation of Modern Column-Oriented Database Systems*. Foundations and Trends in Databases.

  > Para articulação moderna da teoria relacional no contexto analítico atual.

---

## 2. Epistemologia das Ciências Computacionais

### 2.1. Paradigmas e Filosofia da Ciência

* Kuhn, T. S. (1962). *The Structure of Scientific Revolutions*. University of Chicago Press.

  > Obra seminal. Complementar com:

* **Bird, A. (2022).** *Kuhn*. Routledge.
* Popper, K. (1963). *Conjectures and Refutations*. Routledge.
* Feyerabend, P. (1975). *Against Method*. Verso Books.
* **Floridi, L. (2019).** *The Logic of Information: A Theory of Philosophy as Conceptual Design*. Oxford University Press.
---

## 3. Bases Matemáticas e Formais da Engenharia de Dados

### 3.1. Teoria da Informação e Probabilidade

* Cover, T. M.; Thomas, J. A. (2006). *Elements of Information Theory*.
* **MacKay, D. J. C. (2003).** *Information Theory, Inference, and Learning Algorithms*. Cambridge University Press.
---

### 3.2. Teoria dos Grafos e Modelos Causais

* Bollobás, B. (1998). *Modern Graph Theory*. Springer.

  > Complementar com:

* **Gross, J. L.; Yellen, J. (2022).** *Graph Theory and Its Applications*, 3rd ed. Chapman & Hall.
* Pearl, J. (2009). *Causality: Models, Reasoning, and Inference*. Cambridge University Press.
* **Peters, J.; Janzing, D.; Schölkopf, B. (2017).** *Elements of Causal Inference: Foundations and Learning Algorithms*. MIT Press.


---

## 4. Práticas Avançadas — Projetos e Aplicações

### Projeto 1: Implementação do Modelo Relacional Clássico

**Objetivo**: Implementar um interpretador simplificado de álgebra relacional com operadores formais e execução básica de queries.

* Linguagens: **Python**, **Haskell**
* Conceitos envolvidos: Relacional clássico, álgebra relacional, normalização
* Ferramentas: SQLite (para comparação), Pandas (como backend de execução)

### Projeto 2: Análise Comparativa de Paradigmas de Dados

**Objetivo**: Desenvolver uma análise epistemológica e técnica entre bancos relacionais, documentais e grafos, com ênfase em implicações lógicas e modelos de representação.

* Tecnologias: **PostgreSQL**, **MongoDB**, **Neo4j**
* Metodologia: Mapear a tradução de conceitos relacionais em documentais e grafos, avaliando implicações ontológicas e computacionais.

### Projeto 3: Modelagem de Causalidade com Dados Reais

**Objetivo**: Aplicar modelos causais sobre dados reais para inferência e explicação.

* Ferramentas: **DoWhy**, **CausalNex**, **Python**
* Dados: Dados públicos de saúde, educação ou economia (Kaggle, DataSUS, IBGE)
* Resultados: Representações causais, comparação entre correlação e causalidade, uso de grafos direcionais acíclicos (DAGs).

### Projeto 4: Análise da História Computacional com Ferramentas de Text Mining

**Objetivo**: Aplicar mineração de texto para mapear as principais correntes epistemológicas e tecnológicas na história da engenharia de dados.

* Ferramentas: **NLTK**, **spaCy**, **Scikit-Learn**, **Gensim**
* Corpus: Artigos históricos (ACM Digital Library, JSTOR)
* Produtos: Mapas semânticos, clustering de escolas de pensamento, análise temporal de conceitos técnicos.

---
## Módulo 1: Modelagem de Dados, Arquiteturas e Paradigmas

**Objetivo Geral**:
Desenvolver conhecimento profundo nos modelos conceituais, lógicos e físicos de dados, na teoria da normalização, integração de dados e arquiteturas de dados, com base em fundamentos formais e nas práticas mais recentes da indústria.

**Requisitos prévios**:

* Lógica de primeira ordem
* Álgebra relacional
* Sistemas gerenciadores de banco de dados (SGBDs) relacionais e não-relacionais
* Conhecimentos introdutórios em engenharia de software

---

## 1. Modelagem Conceitual e Lógica de Dados

### 1.1. Modelo Entidade-Relacionamento (ER)

* Chen, P. P. S. (1976). *The Entity-Relationship Model: Toward a Unified View of Data*. ACM TODS, 1(1), 9–36.

### 1.2. Ontologias e Lógicas Descritivas para Modelagem

* Calvanese, D. et al. (2020). *Ontology-Based Data Management*. Synthesis Lectures on Data Management, Morgan & Claypool.
* Borgida, A. et al. (2021). *Conceptual Modeling with Description Logics: Foundations and Applications*. Springer.

---

## 2. Teoria Relacional e Normalização

### 2.1. Fundamentos

* Codd, E. F. (1970). *A Relational Model of Data for Large Shared Data Banks*. Communications of the ACM, 13(6), 377–387.

### 2.2. Abordagens Modernas à Normalização

* Arenas, M.; Libkin, L.; Vrgoc, D. (2021). *Relational and Document Normal Forms Based on Information Theory*. ACM PODS.
* Libkin, L. (2021). *Foundations of Data Exchange and Integration*. Morgan & Claypool.

---

## 3. Incompletude, Certas Respostas e Modelagem com Incerteza

### 3.1. Informação Incompleta

* Libkin, L. (2014). *Incomplete Information in Relational Databases*. Morgan & Claypool.
* Libkin, L.; Savenkov, V. (2022). *Certain Answers for SQL with Nulls*. ACM Transactions on Database Systems.

### 3.2. Bancos de Dados Probabilísticos

* Suciu, D.; Olteanu, D.; Ré, C.; Koch, C. (2011). *Probabilistic Databases*. Morgan & Claypool.
* Olteanu, D.; Huang, Z. (2020–2023). *Recent Advances in Probabilistic Data Management*. VLDB Proceedings (vários artigos).

---

## 4. Integração de Dados e Acesso Ontológico

### 4.1. Perspectiva Teórica

* Lenzerini, M. (2002). *Data Integration: A Theoretical Perspective*. ACM PODS.

### 4.2. Práticas Ontológicas Modernas

* Calvanese, D. et al. (2020). *Ontology-Based Data Management*. Synthesis Lectures on Data Management.

---

## 5. Design de Esquemas, Evolução e Refatoração

### 5.1. Refatoração Tradicional

* Ambler, S.; Sadalage, P. (2006). *Refactoring Databases: Evolutionary Database Design*. Addison-Wesley.

### 5.2. Práticas Ágeis e DevOps

* Fowler, M.; Sadalage, P. (2023). *Refactoring Databases*, 2nd Edition. Addison-Wesley.
* Li, Y. et al. (2021). *Continuous Schema Evolution in Cloud-native Databases*. VLDB Proceedings.

---

## 6. Modelos Multidimensionais e Arquiteturas Analíticas

### 6.1. Data Warehousing Clássico

* Kimball, R.; Ross, M. (2013). *The Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling*. 3rd ed., Wiley.
* Golfarelli, M. (2023). *Data Warehouse Design: Modern Principles and Methodologies*. Springer.

### 6.2. Lakehouses e Arquiteturas Híbridas

* Databricks (2020). *The Databricks Lakehouse Platform*. Whitepaper, atualizado em 2023.
* Abadi, D. J.; Boncz, P. A.; Harizopoulos, S. (2013). *The Design and Implementation of Modern Column-Oriented Database Systems*. Now Publishers.

---

## 7. Fundamentos Formais e Lógica para Bancos de Dados

* Libkin, L. (2004). *Elements of Finite Model Theory*. Springer.
* Libkin, L. (2016). *Logical Foundations of Data Exchange and Integration*. ACM SIGMOD Record.

---

## 8. Práticas Avançadas — Projetos e Aplicações

### Projeto 1: Modelagem e Integração Ontológica com OBDA

**Objetivo**: Desenvolver um sistema que unifique diferentes fontes de dados relacionais por meio de uma ontologia formal.

* Tecnologias: **OWL**, **Protégé**, **Ontop**, **PostgreSQL**
* Tópicos: OBDA, SPARQL, descrição lógica
* Resultado esperado: Implementação funcional de integração semântica com consultas federadas.

### Projeto 2: Refatoração de Esquema em Ambiente DevOps

**Objetivo**: Criar um pipeline de refatoração de esquemas com versionamento e rollback automático.

* Tecnologias: **Liquibase**, **Flyway**, **Docker**, **CI/CD com GitHub Actions**
* Tópicos: Schema evolution, versionamento, rollback, refatoração incremental
* Resultado esperado: Pipeline funcional com múltiplas versões de schema e testes automatizados.

### Projeto 3: Análise Multidimensional e Lakehouse Analytics

**Objetivo**: Implementar uma arquitetura híbrida (Data Warehouse + Lakehouse) para análise de grandes volumes de dados.

* Tecnologias: **Apache Spark**, **Delta Lake**, **dbt**, **Databricks**
* Tópicos: OLAP, pipelines ELT, arquitetura moderna de dados
* Resultado esperado: Infraestrutura analítica escalável com dados estruturados e semiestruturados.

### Projeto 4: Consulta e Transformação sobre Dados Incompletos

**Objetivo**: Explorar estratégias para obtenção de "certain answers" sobre bancos de dados com informação parcial ou nula.

* Tecnologias: **PostgreSQL**, **NullLogic DSL**, **Z3 SMT Solver**
* Tópicos: Respostas certas, incompletude, SQL com nulls
* Resultado esperado: Mecanismo de inferência lógico sobre base relacional parcial com justificativas formais.

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



