
13-02-2026 12:20

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1]  408[^2] se refere à situação na qual ==a requisição[^3] não foi processada pelo servidor no tempo designado para o fazer==.

Caso o usuário tenha uma requisição externa na linha de execução, esta deve ser repetida. Caso a conexão entre cliente e servidor não mais seja válida, um nova conexão será utilizada.

### Relevância

O envio desse status para o cliente quando necessário é crucial para indicar com mais precisão o erro cometido e facilitar o processo de correção para o reenvio da requisição e recebimento da informação desejada.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Requests]]

[[IETF Status Code 408]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]