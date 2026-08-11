
30-01-2026 18:03

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 404[^2] indica que ==o servidor falhou em localizar o recurso requisitado[^3] pelo cliente de acordo com as informações enviadas pelo mesmo==.

Esse status não indica se a falta de representação do recuso é temporário ou permanente. ==Caso o servidor saiba que o recurso requisitado definitivamente não possui representação um status code 410[^4] é mais indicado==.

### Relevância

O envio desse status para o cliente quando necessário é crucial para indicar com mais precisão o erro cometido e facilitar o processo de correção para o reenvio da requisição.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Requests]]

[^4]: [[Status Code 410 (Gone)]]

[[IETF Status Code 404]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]