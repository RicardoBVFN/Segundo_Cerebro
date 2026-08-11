
28-08-2025 15:47

Tags: [[Desenvolvimento]]; [[Tratamento de Dados]]
Status: #jovial 


### Definição

Um banco de dados[^1]  em grafos é um banco de dados noSQL[^2] no qual dados são armazenados em esquemas de relacionamento representados por grafos. Nós representam as ocorrências (instâncias), arestas representam os relacionamentos entre estas entidades e propriedades (properties) armazenam os dados adicionais relacionados tanto a entidades quanto a relacionamentos.

### Relevância

Por sua natureza distribuída, consultas em bancos com muitos relacionamentos são bem mais vantajosas do que se estas fossem feitas em um modelo SQL[^3]. Enquanto em um modelo de grafo basta seguir as conexões pelos "matches" da consulta, em um modelo relacional haveria a necessidade de relacionar todas as linhas com todas as colunas para se obter o join final.

Pensados para agir em uma única máquina, esta categoria possui algumas semelhanças com bancos SQL. No caso do Nos4j, seus nós oferecem suporte para ACID. De forma geral suportam transações, oferecendo consistência nestas, a exemplo do Neo4J que realiza todas as suas operações por meio de transações.




### Referências:

[^1]: [[Introdução à Banco de Dados]]

[^2]: [[Banco de Dados noSQL]]

[^3]: [[Banco de Dados SQL]]

[[Bancos de dados de grafos]]
