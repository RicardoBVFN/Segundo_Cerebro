
24-02-2026 17:12

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 412[^2] se refere ao erro ocorrido quando ==um ou mais requisitos enviados no request header[^3] de sua requisição[^4] falham durante o processamento da mesma==.

Este status permite que o usuário aplique novos requisitos tendo como referência o status atual do recurso, prevenindo que este seja processado pelo cliente em um estado indesejado.

### Relevância

O envio desse status para o cliente quando necessário é crucial para indicar com mais precisão o erro cometido e facilitar o processo de correção para o reenvio da requisição.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Request Headers]]

[^4]: [[Requests]]

[[IETF Status Code 412]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]