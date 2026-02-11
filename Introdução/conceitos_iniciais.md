# 📑 Conceitos Iniciais

## 📚 O que são Banco de Dados?
Um banco de dados é uma coleção organizada de informações, ou dados, estruturados, normalmente armazenados eletronicamente em um sistema de computador. Ele é gerenciado por um Sistema Gerenciador de Banco de Dados (**SGBD**), que permite a criação, consulta, atualização e administração dos dados de forma eficiente. [(Oracle - What is Database?)](https://www.oracle.com/br/database/what-is-database/)

## 📚 Banco de Dados Relacionais (SQL)
Baseados no modelo relacional, esses bancos organizam os dados em **tabelas** com linhas e colunas. Eles utilizam a linguagem **SQL** (*Structured Query Language*) para manipular os dados e dependem de um esquema fixo (*schema*). São ideais para manter a consistência e integridade dos dados através de relacionamentos e chaves (primárias e estrangeiras).
* **Exemplos:** PostgreSQL, MySQL, SQL Server e Oracle.

## 📚 Banco de Dados Não-Relacionais (NoSQL)
Projetados para modelos de dados específicos (documentos, chave-valor, grafos ou colunas), os bancos NoSQL oferecem esquemas flexíveis e facilidade de escala horizontal. São amplamente utilizados para grandes volumes de dados, dados não estruturados ou aplicações que exigem baixa latência e alta disponibilidade.
* **Exemplos:** MongoDB (Documento), Redis (Chave-Valor), Cassandra (Colunas) e Neo4j (Grafos).

## 📚 ACID
É o conjunto de propriedades que garante a confiabilidade das transações em um banco de dados relacional:
* **Atomicity (Atomicidade):** A transação ocorre por inteiro ou não ocorre nada ("tudo ou nada").
* **Consistency (Consistência):** A transação leva o banco de um estado válido a outro estado válido, respeitando todas as regras e restrições.
* **Isolation (Isolamento):** Transações simultâneas não interferem umas nas outras.
* **Durability (Durabilidade):** Uma vez confirmada (*commit*), a transação permanece salva, mesmo em caso de falha no sistema.

## 📚 BASE
É o modelo de consistência frequentemente adotado por bancos NoSQL, priorizando a disponibilidade em vez da consistência imediata:
* **Basically Available (Basicamente Disponível):** O sistema garante a disponibilidade, mesmo que partes dele falhem.
* **Soft State (Estado Suave):** O estado do sistema pode mudar ao longo do tempo, mesmo sem entrada de dados, devido à consistência eventual.
* **Eventual Consistency (Consistência Eventual):** O sistema eventualmente se tornará consistente, garantindo que todos os nós recebam a última atualização após um período de tempo.