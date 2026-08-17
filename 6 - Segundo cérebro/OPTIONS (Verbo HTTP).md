
17-08-2026 11:22

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #jovial 

### Definição

O verbo HTTP[^1] OPTIONS define uma requisição[^2] cujo objetivo é ==informar as opções de conexão disponíveis para a propagação de uma requisição==. O remetente de uma requisição OPTIONS deve ser um ==intermediário em um túnel de conexão==[^3] entre dois ou mias endpoints.

### Relevância

Este verbo é fundamental pois, juntamente com o CONNECT[^4], viabiliza toda a comunicação via protocolo HTTP[^5]. É por meio da resposta a esta requisição que o servidor pode ==definir o caminho mais otimizado para a propagação da requisição e formação do túnel==.


### Referências:

[^1]: [[Verbos HTTP]]

[^2]: [[Requests]]

[^3]: [[Túnel de Conexão]]

[^4]: [[CONNECT (Verbo HTTP)]]

[^5]: [[Protocolo HTTP]]
