
30-01-2026 17:37

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 401[^2] indica que a requisição[^3] não foi processada pois ==suas credenciais foram invalidadas, seja por ausência ou por não correspondência==. O servidor que emitir um 401 deve emitir ao menos um campo de verificação válido para o recurso requisitado.

### Relevância

O envio desse status para o cliente quando necessário é crucial para indicar com mais precisão o erro cometido e facilitar o processo de correção para o reenvio da requisição. É muito aplicado a senários de login, cadastramento, dentre outros.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Requests]]

[[IETF Status Code 401]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]