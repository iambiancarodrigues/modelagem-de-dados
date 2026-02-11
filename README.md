# 📑 Meus Estudos: Modelagem de Dados (MER e Dimensional)

Este repositório serve como meu guia pessoal de referência e repositório de anotações sobre **Modelagem de Dados**. O objetivo aqui é documentar a teoria e a prática para estruturar dados de forma eficiente, desde bancos transacionais até ambientes analíticos.

---

## 🎯 Foco do Aprendizado

- **Sistemas OLTP:** Modelagem Entidade-Relacionamento (MER), Normalização e integridade de dados.
- **Sistemas OLAP:** Modelagem Dimensional, técnicas de Kimball, otimização de consultas e Data Warehousing.

---

## 📚 Fontes de Estudo, Referências e Ferramentas

### 📖 Livros
#### [The Data Warehouse Toolkit (3rd Edition)](https://chandan-choudhury.github.io/Data-Engineering/Books/The%20Data%20Warehouse%20Toolkit.pdf)
Escrito por Ralph Kimball e Margy Ross, este livro é a base fundamental para quem trabalha com Business Intelligence e Data Engineering. Ele introduz a **Modelagem Dimensional**, priorizando a performance de consulta e a clareza para o usuário final.

**Tópicos Essenciais abordados na obra:**
* **Tabelas Fato e Dimensão:** A distinção clara entre eventos (fatos) e o contexto que os cerca (dimensões).
* **Arquitetura Bus:** Criação de dimensões conformadas para integrar diferentes processos de negócio.
* **Star Schema vs. Snowflake:** Quando priorizar a simplicidade da "estrela" ou a normalização do "floco de neve".
* **Slowly Changing Dimensions (SCD):** Estratégias (Tipos 0-7) para lidar com atributos que mudam ao longo do tempo.
* **Granularidade:** A importância de definir o nível mais atômico de um fato antes da modelagem.

### 🎓 Cursos
#### [UDEMY] [Modelagem de Dados - MER e Modelo Dimensional (DW)](https://www.udemy.com/course/modelagem_de_dados/)
**Tópicos explorados:**
* Modelo de Entidade e Relacionamento.
* Cardinalidade.
* Modelos Conceitual, Lógico e Físico.
* Normalização (1FN, 2FN, 3FN).
* Modelo Dimensional.
* Star Schema e Snowflake.
* Diferenças do MER e Modelo Dimensional.

### 🖥️ Ferramentas
#### [draw.io](https://app.diagrams.net/)
* Ferramenta versátil para criação de diagramas conceituais e lógicos (MER). Ideal para visualizar fluxos e a estrutura inicial dos dados.
#### [dbdiagram.io](https://dbdiagram.io/)
* Ferramenta focada em modelagem física. Permite gerar diagramas de entidade-relacionamento rapidamente através de código, facilitando a visualização de chaves e relacionamentos.

