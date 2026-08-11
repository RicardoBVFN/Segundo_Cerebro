
30-01-2026 18:22

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 405[^2] indica que ==o método presente na requisição[^3], a pesar de ser conhecido pela origem, não é suportado pelo servidor de destino==. Na response[^4] do status 405 o servidor deve enviar uma lista de métodos suportado pelo mesmo para o cliente.

### Relevância

O envio desse status para o cliente quando necessário é crucial para indicar com mais precisão o erro cometido e facilitar o processo de correção para o reenvio da requisição.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Requests]]

[^4]: [[Responses]]

[[IETF Status Code 405]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]