

13-08-2026 15:59

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #jovial 

### Definição

O verbo HTTP[^1] PUT define uma requisição que, necessariamente, ==deve criar ou alterar o estado de um elemento no servidor alvo com base na representação do mesmo anexada o request message body==[^2]. o retorno esperado para uma requisição do tipo GET[^3] tendo como alvo o recurso afetado deve conter a exata mesma representação retornada em uma response[^4] acompanhada de um status code[^5] 200[^6].

### Considerações importantes

Diferentemente do que acontece numa requisição[^7] POST[^8], ao enviar uma requisição PUT ocorre uma ==comunicação direta com a infraestrutura interna do servidor==. Na prática, a requisição ==acessa diretamente o local do recurso dentro do servidor== e daí processa suas informações.

### Relevância

Por ser idempotent[^9], é preterível utilizar PUT em situações nas quais ==manter a integridade da informação deve ser uma prioridade==. Como exemplo, é possível citar situações de conexão instável, onde a requisição frequentemente sofre um reenvio, e transações financeiras.


### Referências:

[^1]: [[Verbos HTTP]]

[^2]: [[Request Message Body]]

[^3]: [[GET (Verbo HTTP)]]

[^4]: [[Responses]]

[^5]: [[HTTP Status Codes]]

[^6]: [[Status Code 200 (OK)]]

[^7]: [[Requests]]

[^8]: [[POST (Verbo HTTP)]]

[^9]: [[Idempotent]]

[[IETF PUT (Verbo HTTP)]]

[[POSTvsPUT.pdf]]

[[0208 Os Verbos HTTP e o REST]]